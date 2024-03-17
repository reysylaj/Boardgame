I have created the pipeline for this project of Boardgame with the guide of DevOps Shack, https://www.youtube.com/watch?v=NnkUGzaqqOc.

# Corporate DevOps Project - Phase 1: Infrastructure Setup

## Introduction
This repository contains documentation and scripts for Phase 1 of the Corporate DevOps project. In this phase, the focus is on setting up the necessary infrastructure to support Corporate DevOps practices.

## Table of Contents
- [Project Overview](#project-overview)
- [Infrastructure Setup](#infrastructure-setup)
- [Instructions](#instructions)

## Project Overview
Phase One of the project involves the following key tasks:
1. Creating a secure and isolated network environment.
2. Deploying a Kubernetes cluster or similar container orchestration platform.
3. Setting up virtual machines within the network environment.
4. Installing and configuring essential servers and tools such as SonarQube, Nexus, and Jenkins.
5. Deploying monitoring tools for application health and performance monitoring.

## Infrastructure Setup
In this phase, the following steps were executed:
1. **AWS Setup**:
   - Accessing the AWS account and creating the necessary resources including VPCs, Security Groups, Key Pair, and Instances.
2. **Instance Configuration**:
   - Instances were launched and configured with necessary dependencies. The instances include:
     - Master
     - Slave 1
     - Slave 2
     - Nexus
     - Jenkins
     - SonarQube
3. **Kubernetes Cluster**:
   - Kubernetes cluster was installed on each instance (Master, Slave 1, and Slave 2) to facilitate container orchestration.
4. **Server Setup**:
   - Nexus, Jenkins, and SonarQube instances were configured with Docker installed and necessary configurations applied.

## Instructions
To replicate the setup performed in Phase 1, follow these steps:
1. **AWS Setup**:
   - Access your AWS account.
   - Create VPCs, Security Groups, Key Pair, and Instances as per the project requirements.
2. **Instance Configuration**:
   - Launch instances and configure them according to the provided specifications.
   - Connect to instances using MOBAXTERM or similar software.
3. **Kubernetes Cluster**:
   - Install Kubernetes on each session (Master, Slave 1, and Slave 2) by executing the provided script.
4. **Server Setup**:
   - Create additional instances for Nexus, Jenkins, and SonarQube.
   - Connect to these instances and install Docker.
   - Configure Nexus, Jenkins, and SonarQube as needed.

# Corporate DevOps Project - Phase 2: Source Code Management with Git

## Introduction
This repository contains documentation and instructions for Phase 2 of the Corporate DevOps project. In this phase, the focus is on managing the source code of applications using Git repositories.

## Table of Contents
- [Project Overview](#project-overview)
- [Source Code Management](#source-code-management)
- [Instructions](#instructions)

## Project Overview
Phase Two of the project involves the following key activities:
1. Creating private Git repositories for storing source code securely.
2. Pushing source code to the repositories for version control and collaboration.
3. Configuring access controls to ensure visibility only to authorized personnel.

## Source Code Management
In this phase, the following steps were executed:
1. **Git Repository Setup**:
   - A new empty repository was created in private mode using Gitbash or a similar tool.
2. **Cloning Existing Repository**:
   - The existing repository at [https://github.com/jaiswaladi246/Boardgame.git](https://github.com/jaiswaladi246/Boardgame.git) was cloned to the local environment using Gitbash.
3. **Authentication with GitHub Token**:
   - Authentication with GitHub was established using a token to ensure secure access to the repository.
4. **Pushing Source Code**:
   - All files from the local repository were added using `git add .` and then pushed to the new private repository using `git push`.

## Instructions
To replicate the setup performed in Phase 2, follow these steps:
1. **Git Repository Setup**:
   - Create a new empty repository in private mode on GitHub or a similar platform.
2. **Cloning Existing Repository**:
   - Clone the existing repository from [https://github.com/jaiswaladi246/Boardgame.git](https://github.com/jaiswaladi246/Boardgame.git) to your local environment using Gitbash:
     ```
     git clone https://github.com/jaiswaladi246/Boardgame.git
     ```
3. **Authentication with GitHub Token**:
   - Generate a personal access token on GitHub with appropriate permissions.
   - Authenticate with GitHub using the generated token:
     ```
     git config --global credential.helper store
     ```
4. **Pushing Source Code**:
   - Add all files from the local repository:
     ```
     git add .
     ```
   - Commit changes:
     ```
     git commit -m "Initial commit"
     ```
   - Push the code to the new private repository:
     ```
     git push origin master
     ```

# Corporate DevOps Project - Phase 3: Continuous Integration and Continuous Deployment (CI/CD)

## Introduction
This repository contains documentation and instructions for Phase 3 of the Corporate DevOps project. In this phase, the focus is on implementing CI/CD pipelines for automating the software delivery process.

## Table of Contents
- [Project Overview](#project-overview)
- [CI/CD Implementation](#cicd-implementation)
- [Instructions](#instructions)

## Project Overview
Phase Three of the project involves the following key activities:
1. Setting up CI/CD pipelines for automated testing and deployment.
2. Following best practices and implementing security measures in CI/CD pipelines.
3. Configuring email notifications for pipeline status updates.
4. Automating deployment processes after successful pipeline executions.
5. Conducting security scanning of the infrastructure to identify vulnerabilities.

## CI/CD Implementation
In this phase, the following steps were executed:
1. **Jenkins Setup**:
   - Connect to Jenkins and install all available plugins including Jdk, Jenkins, SonarQube, and Docker.
   - Configure Jenkins by providing necessary credentials and settings.
2. **Pipeline Configuration**:
   - Start a new pipeline and choose "Definition: Pipeline Script".
   - Write the code for the pipeline, defining the stages for automated testing, deployment, and security scanning.
3. **Email Notifications**:
   - Configure email notifications in Jenkins to receive updates on pipeline status.
4. **Automation and Security**:
   - Automate deployment processes to trigger after successful pipeline executions.
   - Implement security measures within the CI/CD pipeline to ensure safe software delivery.

## Instructions
To replicate the setup performed in Phase 3, follow these steps:
1. **Jenkins Setup**:
   - Access Jenkins and install necessary plugins.
   - Configure Jenkins with appropriate credentials and settings.
2. **Pipeline Configuration**:
   - Create a new pipeline and select "Definition: Pipeline Script".
   - Write the pipeline code according to your project requirements.
3. **Email Notifications**:
   - Configure email notifications in Jenkins for receiving pipeline status updates.
4. **Automation and Security**:
   - Automate deployment processes within the pipeline.
   - Implement security measures to ensure safe software delivery.

# Corporate DevOps Project - Phase 4: Monitoring

## Introduction
This repository contains documentation and instructions for Phase 4 of the Corporate DevOps project. In this phase, the focus is on monitoring the deployed applications to ensure optimal performance and reliability.

## Table of Contents
- [Project Overview](#project-overview)
- [Monitoring Implementation](#monitoring-implementation)
- [Instructions](#instructions)

## Project Overview
Phase Four of the project involves the following key activities:
1. Monitoring system-level metrics such as CPU and RAM usage.
2. Monitoring website-level metrics such as traffic and performance.
3. Using monitoring tools to identify potential issues and optimize user experience.

## Monitoring Implementation
In this phase, the following steps were executed:
1. **Creating a Monitoring Virtual Machine**:
   - A new virtual machine named "monitor" was created to host monitoring tools such as Prometheus and Grafana.
2. **Installation of Monitoring Tools**:
   - Prometheus, Grafana, and Blackbox Exporter were installed on the monitoring virtual machine to facilitate monitoring of system and website-level metrics.
3. **Configuration of Prometheus and Grafana**:
   - Prometheus and Grafana were configured to collect and visualize metrics from various sources including system-level metrics from Node Exporter and website-level metrics from Blackbox Exporter.
4. **Creation of Dashboards**:
   - Dashboards were created in Grafana to visualize the collected metrics. Separate dashboards were created for system-level monitoring and website monitoring.

## Instructions
To replicate the setup performed in Phase 4, follow these steps:
1. **Create Monitoring Virtual Machine**:
   - Create a new virtual machine (e.g., "monitor") to host monitoring tools.
2. **Install Monitoring Tools**:
   - Install Prometheus, Grafana, and Blackbox Exporter on the monitoring virtual machine.
3. **Configure Prometheus and Grafana**:
   - Configure Prometheus to scrape metrics from the desired targets, and configure Grafana to visualize the collected metrics.
4. **Create Dashboards**:
   - Create dashboards in Grafana to monitor system-level metrics using Node Exporter and website-level metrics using Blackbox Exporter.

