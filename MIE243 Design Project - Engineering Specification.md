
Project Title: Low-Cost Teaching Vehicle Model  
Group Number: Project Group 19  
Group Members: Shangkai Ji, Hongru Liu, Mo Zhou  
Version: v0

# 1. Project Overview & Design Goals - Liu

The aim of this project is to develop an advanced conceptual design for a low-cost vehicle model for teaching. The intent of a vehicle model is to provide a platform that students can use for labs, and which instructors can use for demonstrations and other course activities. 

Ideally, we would like you to develop one platform that enables teaching for as many use-cases as possible. Specifically, this teaching/lab platform would focus on vehicle drivetrains and related mechanical components. 

[Insert problem statement here]

# 2. Context - Shangkai Ji

(SECTION INTRODUCTION SHOULD COVER THIS) 

Examined which channels (such as commercial education product websites, GrabCAD, Thingiverse, YouTube DIY projects, publicly available materials from university laboratories).

Selection criteria (price range, functional scope, target users, manufacturability).

## 2.1 Scope - Mo

This project covers a tabletop, physically working model of a four-wheel-drive (4x4) driveline that includes a transfer case and three differentials (center, front, and rear). 
**In scope**
1. **Input:** The driveline must be able to be driven from the transfer case input (representing the engine), either manually or by motor, so power flows through the transfer case and differentials as in a real vehicle. 
2. **Transfer case:** selectable 2H / 4H / 4L modes, with a high/low range reduction. The transfer case must demonstrate both full-time and part-time 4WD behaviour.
3. **Front and rear axles:** each with a differential that can be locked and unlocked.
4. **Driveshafts:** front and rear driveshafts linking the transfer case to both axles.
5. **Wheels:** four wheels that students can turn, hold or let spin freely to demonstrate varying traction conditions.
6. **Steering:** steerable front wheels, so a real turn shows why each wheel needs a different speed.

**Planned Demonstrations**
The model should demonstrate all wheels turning at the same speed while driving straight and different inner and outer wheel speeds when turning (through the differentials). The model should also be able to show what happens with the differential when traction on one wheel is significantly higher than another, and how locking the differential changes this. 

The model should also be able to demonstrate switching between 2WD and 4WD as well as varying wheel speeds in High vs Low range with the transfer case, and the higher wheel torque in Low range. The model should also be able to show the effects of center differential on front vs rear axle speeds. 

**Out of scope**
- Engine, clutch and a multi-speed gearbox. 
- Suspension and axle articulation, a vehicle brake system (devices for adding resistance to individual wheels for demonstrations are not excluded), and electronic traction or torque control.
- Carrying real vehicle loads. 

**Future modules**
- A CVT, or another input-stage module, can be mounted upstream of the transfer case. The input interface will be designed so it can be added later without redesigning the rest of the driveline.
- A road-simulation base (e.g. motor-driven rollers under each wheel) to reproduce turning and traction conditions automatically.

## 2.2 Service Environment, Interest Holders, Production - Liu

Who and where is the model used. How is it built and how many are built? 

## 2.3 Existing Designs - Mo

List commercially available products.

| Products                                                                                                                                                | Price | Size | Key Features                                                                             | Strength | Weakness | Points that can be learned from |
| ------------------------------------------------------------------------------------------------------------------------------------------------------- | ----- | ---- | ---------------------------------------------------------------------------------------- | -------- | -------- | ------------------------------- |
| Video Animations [Ultimate Drivetrain Guide: FWD vs RWD vs AWD vs 4x4 – Everything You Need to Know.](https://youtu.be/-cTJqNWwmf0?si=bc4jpFTCxsqP5ChQ) | 0     | N/A  | Very easy to understand how individual components work and how everything works together |          |          |                                 |
|                                                                                                                                                         |       |      |                                                                                          |          |          |                                 |

## 2.4 Design Goals - Shangkai Ji


# 3. Detailed Requirements

## 3.1 Function

## 3.2 Objective

## 3.3 Constraint

- Tabletop size, approx. 1/10 to 1/5 scale (to be refined during CAD sizing).


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

