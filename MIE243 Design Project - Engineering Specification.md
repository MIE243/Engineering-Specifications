
Project Title: Low-Cost Teaching Vehicle Model  
Group Number: Project Group 19  
Group Members: Shangkai Ji, Hongru Liu, Mo Zhou, Peiwen Sun
Version: v0

# 1. Project Overview - Liu

Existing teaching platforms for vehicle drivetrains are typically narrowly targeted, expensive, and can't directly demonstrate the mechanism principles. This makes it difficult for universities to provide affordable, hands-on lab experiences that cover a broad range of drivetrains. There is a need for a low-cost, modular vehicle model for teaching that students and instructors can use for labs and demonstrations. 

# 2. Context - Shangkai Ji

(SECTION INTRODUCTION SHOULD COVER THIS) 

Examined which channels (such as commercial education product websites, GrabCAD, Thingiverse, YouTube DIY projects, publicly available materials from university laboratories).

Selection criteria (price range, functional scope, target users, manufacturability).

## 2.1 Scope - Mo

What drivetrain design we are doing specifically

1. 4x4 (4-wheel) drive, 

2. Transfer Case, 

3. Differentials. 

Differentials, transfer cases, and CVTs  → discuss together ??  add together ??

## 2.2 Service Environment, Interest Holders, Production - Liu

Who and where is the model used. How is it built and how many are built? 

### 2.2.3 Service Environment
The platform is intended for use for undergraduate teaching labs, especially for mechanical engineering design and drivetrain-related courses. Due to its relatively large size, the platform should be placed on the laboratory floor, and is used by student groups of 2–4 during a 1–3 hour lab session. 

The operating environment is an indoor laboratory. Outdoor, high-temperature, high-humidity, and high-vibration conditions are not expected. The noise level must remain low enough for normal conversation during lab sessions. 
### 2.2.4 Interest Holders
The platform is used by students, instructors, teaching assistants, and the university. Their needs and expectations are summarized below.

| Interest Holders    | Needs/Expectations                                           |
| ------------------- | ------------------------------------------------------------ |
| Students            | hands-on interaction, clear instructions, observable results |
| Instructors         | Reliable, easy to explain                                    |
| Teaching Assistants | Easy setup, robust, safe                                     |
| University          | Low cost, durable, low maintenance, storable                 |
### 2.2.5 Production
This platform is suitable for small-scale production (10 to 100 pieces), which can be manufactured by university technicians themselves. The production should be able to manufactured by rapid prototyping methods (3D printing, laser cutting). The use of injection molding, custom castings, special materials, and complex electronic components should be avoided. 

## 2.3 Existing Designs - Mo

The table below explores six existing designs, ranging from physical to non-physical, and from full-size cutaway models to toys.

| Product                                                                                                                                                                                                                                                                | Price                                      | Size                                          | Key Features                                                                                                                                                                       | Strengths                                                                                                                                                                                                                                         | Weakness                                                                                                                                                                                                                   | Points that can be learned from them                                                                                                                                                                                                                                                        | Image                                     |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------ | --------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------- |
| **A. [AutoEDU 4×4 Transmission Cutaway Trainer (AE411300M)](https://autoedu.com/product/4x4-vehicle-transmission-with-mechanical-gearbox-educational-trainer-ae411300m/)**                                                                                             | Not published                              | 2250 × 750 × 1050 mm, 230 kg                  | • Cutaway OEM 5-speed gearbox + Hi/Lo unit<br>• Front & rear self-locking hypoid differentials<br>• Driveshafts with U-joints<br>• Manual 4WD engagement                           | Complete driveline from the gearbox to both axles. Real parts show true geometry, and it's large enough for a group to gather around.                                                                                                             | Likely costly, heavy and large, so it needs a dedicated lab space. Not self-explanatory: an instructor has to explain the cut steel sections. No wheels, so the effect at the wheels (turning, wheel slip) can't be shown. | Colour-code the functional groups. Lay out the driveline so the full power path can be traced from input to wheels. Give students a manual 2WD/4WD control.                                                                                                                                 | ![[Pasted image 20260928005610.png\|150]] |
| **B. [Training Systems Australia 4WD Transfer Case with Locking Differential Cutaway (VB 11084M)](https://www.trainingsystemsaustralia.com.au/products/automotive-technologies/cutaways/transmissions-cutaways/4wd-transfer-case-with-locking-differential-cutaway/)** | Not published                              | 400 × 400 × 600 mm (H), 25 kg                 | • Cutaway transfer case with Hi/Lo reduction<br>• Lockable center differential<br>• Hand-crank operated<br>• Colour-coded parts                                                    | Sits on a benchtop, with hand cranks that let students drive the gears themselves. Also shows the center differential lock and range reduction.                                                                                           | Demonstrates only the transfer case, with no axles or wheels, so its effect on the rest of the driveline can't be seen. Heavy, and most likely expensive for what it shows.                                                | Give students a simple, safe input (hand-crank in this case). Separate gear groups with colour contrast.                                                                                                                                                                                    | ![[Pasted image 20260928005550.png\|150]] |
| **C. [LEGO Technic Land Rover Defender (42110)](https://www.lego.com/en-us/product/land-rover-defender-42110)**                                                                                                                                                        | US$199.99                                  | 420 × 200 × 220 mm; 2,573 pieces              | • AWD with 3 differentials<br>• 4-speed gearbox + Hi/Lo<br>• Steering, independent suspension                                                                                      | Low cost compared with cutaway trainers. It is modular and can be rebuilt. Real wheels show the differentials at work. Replacement parts are common.                                                                                              | The body and chassis hide much of the gearing and driveline. Plastic gears have backlash and can slip under load. No 2WD mode and no differential locks.                                                                   | Fit center, front and rear differentials in a small space with off-the-shelf gears. Use standard modular gears and axles so parts are easy to replace and reconfigure. Keep the driveline open, with no body panels.                                                                        | ![[Pasted image 20260928005442.png\|150]] |
| **D. [Traxxas TRX-4 Crawler Kit](https://traxxas.com/82216-4-trx-4-crawler-kit) (1/10 scale RC)**                                                                                                                                                                      | US$399.95                                  | 523 × 249 × 159 mm, 312 mm wheelbase, 2.91 kg | • Steel-gear transfer case<br>• Remote 2-speed Hi/Lo<br>• Remote front & rear differential locks<br>• Portal axles, full-time 4WD                                                  | Durable steel gears. Hi/Lo and differential locks work on a real rolling vehicle. Compact, with good parts support and documentation.                                                                                                             | Students can't see any motion inside the sealed gearboxes. Full-time 4WD, with no 2WD mode and no center differential. Designed for driving rather than teaching.                                                  | Operate the differential locks and Hi/Lo with cables or small servos, so they can be switched from outside the driveline. Buy off-the-shelf RC parts (driveshafts, bearings, CV joints) instead of making them. A full 4x4 driveline fits at 1/10 scale, a good minimum size for our model. | ![[Pasted image 20260928005515.png\|150]] |
| **E. Video Animations** – [Ultimate Drivetrain Guide: FWD vs RWD vs AWD vs 4x4 – Everything You Need to Know.](https://youtu.be/-cTJqNWwmf0?si=bc4jpFTCxsqP5ChQ)                                                                                                       | Free                                       | N/A                                           | • ~10-min animated video<br>• Covers FWD, RWD, AWD and 4x4<br>• Traces power flow from engine to wheels<br>• Explains transfer cases, differential locks and center differentials | Free. Very easy to understand how individual components work and how everything works together. Covers every drivetrain layout in a relatively short time (about 10 minutes).                                                                 | Not physical or interactive. Students can only watch passively under one fixed condition. Little depth on each component.                                                                                                 | Explain each component first, then show how they work together.                                                                                                                                                                                                                             | ![[Pasted image 20260928033548.png\|150]]      |
| **F. Interactive 3D Model** – [ProCalcLab](https://procalclab.com/3d-differential-simulator/), [Mozaik](https://nl.mozaweb.com/en/Extra-3D_scenes-How_does_it_work_Differential_gear-246529)                                                                           | Free (ProCalcLab)<br>Subscription (Mozaik) | N/A                                           | • Rotate, zoom, preset views<br>• Animation + narration (Mozaik)<br>• Adjustable gear teeth & speed (ProCalcLab)<br>• Straight / turn / slip / lifted-wheel modes                  | Free (ProCalcLab) or school subscription (Mozaik), and every student can use one at the same time. It can be viewed from any angle, and the inside can be seen with nothing blocking the view. The effects of changes can also be seen instantly. | Not physical. The tools found only model a single open differential, with no transfer case, center differential, locks or full 4x4 driveline. Motion is idealized and has no real loads.                                   | Straight, turning, one-wheel-slip and lifted-wheel cases should be shown with our model.                                                                                                                                                                                                    | ![[Pasted image 20260928033804.png]]      |

## 2.4 Design Goals - Shangkai Ji


# 3. Detailed Requirements

## 3.1 Function

## 3.2 Objective

## 3.3 Constraint


# 4. Project Management & Iteration

_This section addresses the Agile/Scrum requirements._
- **Product Backlog:** A Github board has been established containing all tasks.
- **Sprint Planning:** 1-2 week sprints, each producing a tangible engineering deliverable (e.g., CAD model, BOM, test report).
- **Role Assignments:**

| Key Roles        | Assigned Person                  | Main Responsibilities                                                                                                                                                                                                                                                             |
| ---------------- | -------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Designed Owner   | Shangkai Ji                      | Defines what needs to be created and sets the priority list for the project. While this can be done collaboratively (especially when defining your project’s scope), be sure that one person has final authority/responsibility and maintains consistency throughout the project. |
| CAD Design Owner | Mo Zhou                          | Controls and edits master geometry and skeleton CAD parts. Assigns specific parts for members to work in to avoid reference conflicts. Ensure CAD files merge with no issues.                                                                                                     |
| Scrum Master     | Hongru Liu                       | Helps the team follow the framework (leads the “ceremonies” below), ensures scrum rules are followed, and clears away any roadblocks.                                                                                                                                             |
| Developer        | Shangkai Ji, Hongru Liu, Mo Zhou | The cross-functional team members who do the actual hands-on work to build the product.                                                                                                                                                                                           |
| Meeting Recorder | Shangkai Ji                      | Record every meeting content and update on Github. Show our working process                                                                                                                                                                                                       |

**Iteration Record:** The Engineering Specification will be updated after each Sprint Review, documenting the reasons for design changes.

# 5. Reference

- [AutoEDU – 4×4 Transmission Cutaway Trainer AE411300M](https://autoedu.com/product/4x4-vehicle-transmission-with-mechanical-gearbox-educational-trainer-ae411300m/)
- [Training Systems Australia – 4WD Transfer Case with Locking Differential Cutaway](https://www.trainingsystemsaustralia.com.au/products/automotive-technologies/cutaways/transmissions-cutaways/4wd-transfer-case-with-locking-differential-cutaway/)
- [LEGO – Land Rover Defender 42110](https://www.lego.com/en-us/product/land-rover-defender-42110); [New Elementary review (dimensions, price)](https://www.newelementary.com/2020/02/lego-review-42110-land-rover-defender-2020.html); [Brickset (release and retirement dates)](https://brickset.com/sets/42110-1/Land-Rover-Defender)
- [Traxxas – TRX-4 Crawler Kit (82216-4)](https://traxxas.com/82216-4-trx-4-crawler-kit)
- [Mozaik Education – "How does it work? – Differential gear" 3D scene](https://nl.mozaweb.com/en/Extra-3D_scenes-How_does_it_work_Differential_gear-246529); [mozaik3D app](https://www.mozaweb.com/mozaik3D)
- [ProCalcLab – Interactive 3D Differential Simulator](https://procalclab.com/3d-differential-simulator/)
