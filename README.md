# Jenkins_Playground
Jenkins project of multistage and multiagent, along with simple and complex projects. 

# CI/CD Pipeline – Jenkins & GitHub

## Overview
This project demonstrates a complete CI/CD pipeline built using Jenkins to automate build, test, and deployment processes. The objective was to understand how code changes move from source control to deployment in a controlled and repeatable manner.

## Architecture
Developer pushes code to GitHub → Jenkins triggers pipeline → Build and validation steps → Deployment to target environment.

## Tools & Technologies
- Jenkins – Pipeline orchestration
- GitHub – Source code management
- Linux – Execution environment
- Shell scripting – Automation logic

## Pipeline Flow
1. Code is pushed to GitHub repository.
2. Jenkins detects the change via webhook or polling.
3. Pipeline executes build steps.
4. Validation steps ensure stability.
5. Application is deployed to the target environment.

## Key Learnings
- Understood CI/CD fundamentals and pipeline stages.
- Learned how Jenkins automates repetitive tasks.
- Gained hands-on experience with pipeline failures and troubleshooting.
