
Project Title: Low-Cost Teaching Vehicle Model  
Group Number: Project Group 19  
Group Members: Shangkai Ji, Hongru Liu, Mo Zhou, Peiwen Sun
Version: v1

# 1. Project Overview
A summary of all of section 1 and 2 from [Engineering Specification v0](Engineering%20Specification%20v0.md)
## 1.1 Problem Statement

## 1.2 Project Scope

| **#** | **Scope Decision** | **Model** |
| ----- | ------------------ | --------- |
|       |                    |           |

# 2. Detailed Requirements
Functions, objectives, and constraints of the project

### Demonstration

| Name | Description | Target | Reason | Evidence at concept stage |
| ---- | ----------- | ------ | ------ | ------------------------- |
|      |             |        |        |                           |
|      |             |        |        |                           |
|      |             |        |        |                           |
|      |             |        |        |                           |
|      |             |        |        |                           |

### Operation and modularity

| Name             | Description                                                                                  | Target                                                         | Reason                                                                                             | Evidence at concept stage                                 |
| ---------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | --------------------------------------------------------- |
| Lab Usability    | Must enable four students run the cars, change the vehicle conditions, and make comparisons. | Total test cycle ≤ 30 min (Setup 15m + Test 15m)               | Fits within a standard 3-hour lab session, ensuring students have time for data analysis.          | Draft Lab Procedure, Accessibility review                 |
| Modular Assembly | Must allow the all sub assemblies/components to be removed and replaced                      | One student swaps one module in ≤ 5 min with ≤ 1 standard tool | Enables rapid iteration during the lab.                                                            | CAD motion simulation                                     |
| Robustness       | Must drive every connected wheel (OUTPUT) in every allowed configuration.                    | 100% success rate across all defined configurations            | Remove any module and it still works, ensuring robustness and modularity of the drivetrain design. | Configuration matrix with a power-path check for each row |

| Name | Description | Target | Reason | Evidence at concept stage |
| ---- | ----------- | ------ | ------ | ------------------------- |
|      |             |        |        |                           |
|      |             |        |        |                           |
|      |             |        |        |                           |

### Input, size and steering

| Name          | Description                                                                                                                                                              | Target                                      | Reason                                                                       | Evidence at concept stage                                                         |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------- | ---------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| Input Drive   | The system must be driven by a realistic manual or motor input.                                                                                                          | Input torque ≤ 2.5 N·m                      | Ensures operational safety and accessibility for all students                | Required torque and speed calculation compared with the chosen input's capability |
| Tabletop fit  | The system must operate within a standard lab tabletop area                                                                                                              | 500×250mm                                   | Tabletop use; ensures the equipment  fits standard lab benches.              | Dimensioned overall CAD envelope                                                  |
| Storage Size  | The system should be able to be conveniently stored in standard laboratory cabinets.                                                                                     | 500×250×200mm                               | Ensures the equipment can be stored in lab cabinets when not in use.         | Dimensioned overall CAD envelope                                                  |
| Turn Geometry | The system must demonstrate travelling on a curved path where (i) wheels on the same axle and (ii) front/rear axles travel different distances, with repeatable results. | Centreline turn radius ≤ 800 mm; repeatable | Provides the necessary kinematic conditions to observe differential behavior | Turn-geometry sketch with each wheel's path radius                                |

### Safety, cost and lifecycle

| Name | Description | Target | Reason | Evidence at concept stage |
| ---- | ----------- | ------ | ------ | ------------------------- |
|      |             |        |        |                           |
|      |             |        |        |                           |
|      |             |        |        |                           |
|      |             |        |        |                           |
|      |             |        |        |                           |

# 3. Project Management & Iteration
_This section addresses the Agile/Scrum requirements._
- **Product Backlog:** A GitHub board has been established containing all tasks.
- **Sprint Planning:** 1-2 week sprints, each producing a tangible engineering deliverable (e.g., CAD model, BOM, test report).
- **Role Assignments:**

| Key Roles        | Assigned Person                              | Main Responsibilities                                                                                                                                                                                                                                                             |
| ---------------- | -------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Designed Owner   | Shangkai Ji                                  | Defines what needs to be created and sets the priority list for the project. While this can be done collaboratively (especially when defining your project’s scope), be sure that one person has final authority/responsibility and maintains consistency throughout the project. |
| CAD Design Owner | Mo Zhou                                      | Controls and edits master geometry and skeleton CAD parts. Assigns specific parts for members to work in to avoid reference conflicts. Ensure CAD files merge with no issues.                                                                                                     |
| Scrum Master     | Hongru Liu                                   | Helps the team follow the framework (leads the “ceremonies” below), ensures scrum rules are followed, and clears away any roadblocks.                                                                                                                                             |
| Developer        | Shangkai Ji, Hongru Liu, Mo Zhou, Peiwen Sun | The cross-functional team members who do the actual hands-on work to build the product.                                                                                                                                                                                           |
| Meeting Recorder | Shangkai Ji                                  | Record every meeting content and update on Github. Show our working process                                                                                                                                                                                                       |

**Iteration Record:** The Engineering Specification will be updated after each Sprint Review, documenting the reasons for design changes.
