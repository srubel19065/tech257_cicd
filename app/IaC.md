# Infrastructure as Code

## What is it?
Concept of infrastrcuture being managed by code and and software dev tools rather than manual processes. 
- Declare a programming language when defining the infrastructure and tools with use this code to automatically manage and configure the infrastructure
 
## Why should we use it?
1. Consistency & Reliability
   - As it is defined by code, we can keep the environment consistent each time and can reproduce the same thing each time
2. Automation
   - Automate the provision and managing of tasks, less human error and speeds up/ make it more efficient
3. Scalability
   - automated resources means can scale up and down based on demand
4. Version Control & Collaboration
   - Can use Git for Version Ctrl and teams can collaborate with code changes

## When to use it?
1. New project
   - set good foundation with concistency from the beginning
2. Scalability
   - can provision based on demand and scale looking at traffic
3. DevOps Practices
   - Fits with DevOps principles by automating software delivery process, provisioning and promotes collaboration
  
## Where to use it?
1. Cloud 
   - AWS, Azure, GCP 
2. Data centers
   - onsite data centers can use IaC to automate processes
3. Containerised environments 
   - Docker and Kubernetes have underlying infrastructure that needs to be managed and IaC can be used

## Tools
1. Terraform
   - open source tool allow to define and manage using declarative config language
2. AWS Cloud Formation
3. ARM Templates
4. Ansible
   - automation tool using YAML-based playbooks to define tasks and config

## Ansible
1. Open source automation tool
2. Config management, provisioning, app deployment, orchestration
3. Written in Python and YAML for congif files
4. Agentless architecture - connects to manages systems with SSH or WinRM
5. Powerful and Flexible