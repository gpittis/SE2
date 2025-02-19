# Software Engineering 2 Project 2024-25

<p align=center>
<img src="https://issel.ee.auth.gr/wp-content/uploads/2021/06/logo.png" height=100px width:auto />
  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
<img src="https://cdn4.iconfinder.com/data/icons/logos-3/600/React.js_logo-512.png" height=100px width:auto />
  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
<img src="https://github.com/user-attachments/assets/723a41b1-ea2f-4980-bac0-a76522c758ea" height=90px width:auto />
</p>

## Overview

This repository contains materials related to assignments of the Software Engineering 2 course of ECE, Aristotle University of Thessaloniki.

>Course professor: [Andreas Symeonidis](https://people.auth.gr/symeonid/).

> Made with valuable help from the [ISSEL](https://issel.ee.auth.gr/) team.

## Cyclopt platform

Code optimization, bug fixing and statistics extraction for code quality is done using the Cyclopt tool. The tool, as well as info on the company can be found at [cyclopt.com](https://www.cyclopt.com/).

<!---
The rating of this repository can be found below and is automatically updated.

<a href="http://cyclopt.com" >
  <img src="https://server.cyclopt.services/api/badges/6727801f6970cf34939e0f6e" alt="cyclopt rating" height=70px width:auto/>
</a>
--->

## Deliverable 1
- Utilization of existing Swagger files from the Software Engineering 1 course
- API description transformation into a real server using SwaggerHub or Swagger Editor
- Upload of generated code to a new GitHub repository
- Creation of separate branches for each team member in the GitHub repository for collaboration
- Creation of a project on the Cyclopt platform and importing the existing features of the system
- Inclusion of future tasks required for project implementation
- Task point assignment based on difficulty (1 point = 1 person-hour)
- Application of the point system to estimate task completion time
- The project follows an agile methodology
- The Cyclopt board is updated throughout the semester, with bi-weekly assessments

## Deliverable 2
- CI/CD Implementation
- Testing strategy implementation
  - Backend Testing (Unit Tests)
    - The unit tests are located in the test folder
    - Use of the c8, ava, and got libraries.
  - Frontend Testing (Acceptance Tests)
    - The acceptance tests are located in the cypress/e2e folder
    - Use of the cypress library
- Deploy to Render
- Testing Coverage
  - Unit tests must cover at least 90% of code
 
## Deliverable 3
- Evaluation of code quality using the Cyclopt platform and tools across all active branches
- We improved the following metrics:
  - Maintainability Ιndex
  - Comment Density
- We reduced the following metrics:
  - Unused Variables
  - Security Issues
- The project quality is **A** !!

## The rest of the team

- [Thanasis Tsarnadelis](https://github.com/tsarnadelis)
- [Alexandros Fotiadis](https://github.com/afotiadis)
- [Anastasis Gourdomichalis](https://github.com/anasgourd)

**Origin of this repo:** [Tsarnadelis](https://github.com/tsarnadelis/SoftwareEngineering2Projects)

## Swagger generated server

This server was generated by the [swagger-codegen](https://github.com/swagger-api/swagger-codegen) project, by using the [OpenAPI-Spec](https://github.com/OAI/OpenAPI-Specification).

## Running the server
To run the server, run:

```
npm start
```

To view the Swagger UI interface:

```
open http://localhost:8080/docs
```

