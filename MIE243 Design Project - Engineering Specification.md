
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
In order to understand the existing teaching schemes for automotive transmission systems and to determine the design direction for the proposed teaching model, we conducted a preliminary investigation. The investigation covered multiple information channels, including commercial teaching product websites, online CAD and 3D printing model platforms such as GrabCAD and Thingiverse, YouTube demonstrations and DIY projects, as well as relevant materials publicly released by university laboratories.

For the existing designs and teaching schemes found in the investigation, we analyzed them based on multiple screening criteria, including price range, functional scope, target users, and manufacturability. The price was used to determine whether the existing schemes were suitable as low-cost teaching platforms; the functional scope was used to analyze which transmission system components and their working principles could be demonstrated by different schemes; the target users were used to determine the application scenarios of each scheme; and manufacturability was evaluated based on the complexity of manufacturing and assembly, as well as whether commercial off-the-shelf components or 3D printed components could be used for the manufacturing. 

These investigation results provided a foundation for subsequently determining the project scope and service environment, comparing relevant existing designs, and formulating the design goals for the proposed teaching platform for automotive transmission systems.

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

List commercially available products.

| Products                                                                                                                                                | Price | Size | Key Features                                                                             | Strength | Weakness | Points that can be learned from |
| ------------------------------------------------------------------------------------------------------------------------------------------------------- | ----- | ---- | ---------------------------------------------------------------------------------------- | -------- | -------- | ------------------------------- |
| Video Animations [Ultimate Drivetrain Guide: FWD vs RWD vs AWD vs 4x4 – Everything You Need to Know.](https://youtu.be/-cTJqNWwmf0?si=bc4jpFTCxsqP5ChQ) | 0     | N/A  | Very easy to understand how individual components work and how everything works together |          |          |                                 |
|                                                                                                                                                         |       |      |                                                                                          |          |          |                                 |

## 2.4 Design Goals - Shangkai Ji

After an initial investigation, it was found that the existing automotive teaching models have some limitations. For instance, the current automotive teaching models may be expensive and have complex mechanical structures, or they may only focus on showcasing a single specific system. Additionally, if all the teaching components are enclosed or the components are too close to the real vehicle's systems, it may make it difficult for students to observe the movement of the teaching automotive components and to understand how different components interact with each other.

Therefore, our main design goal is to develop a low-cost, modular, and easily observable automotive teaching model. This model should enable students to observe how each component works and how they cooperate as part of a complete automotive system. In cases where it is feasible, the individual components should be able to be disassembled or interchanged, so that the same platform can showcase various different transmission system configurations.

Among the teaching tools, we may use 3D-printed components such as gears. This way, our team doesn't have to purchase specially customized components online to reduce manufacturing costs. At the same time, our team can adopt detachable and interchangeable transmission system modules, enabling different components or different system configurations to be installed on the same base platform for demonstration. For example, if we want to showcase Gearboxes or Transmissions, we can directly remove this part for demonstration. When we want to present the whole thing, we can simply put these components back and demonstrate the braking method. This approach is convenient for students to understand. For rotating components, we can combine purchased metal shafts, bearings, and couplings with 3D-printed components to improve the durability and reliability of the model while maintaining a low manufacturing cost.

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

