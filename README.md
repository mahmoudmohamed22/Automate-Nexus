# Automate-Nexus with Ansible

This repository contains Ansible playbooks, roles, and configurations to automate the installation of Nexus, a repository manager, using Ansible.

## Directory Structure
The repository follows the standard Ansible role directory structure. The main files and directories are as follows:
![image](https://github.com/mahmoudmohamed22/Automate-Nexus/assets/47304558/3cb3d825-28c5-4903-af90-d0d2a327bf96)

## Prerequisites

Before running the Ansible playbooks, ensure that you have the following:

- Ansible installed on your local machine.
- Access to the target host where Nexus will be installed.
- SSH access to the target host with appropriate permissions.



## Getting Started

To get started with the installation, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/mahmoudmohamed22/Automate-Nexus.git
   ```

2. Navigate to the repository directory:
```
cd Automate-Nexus
```
3. Using Dynamic Inventory to get public hosts in specific region .

4. Run the playbook to install Nexus:
```
ansible-playbook playbook.yml
```
5.Access Nexus by navigating to http://<nexus-host>:8081 in your web browser.


## install nexus with ansible 

![Screenshot from 2023-06-17 22-36-50](https://github.com/mahmoudmohamed22/Automate-Nexus/assets/47304558/881b11f6-0880-46dc-b40c-7c277ed4ac21)

#### check nexus availibility with handler 
![Screenshot from 2023-06-17 22-36-34](https://github.com/mahmoudmohamed22/Automate-Nexus/assets/47304558/aeb9bc3b-e24c-4667-91a8-ffbe695eda49)


## Automate Nexus Deployment 

![Screenshot from 2023-06-17 21-50-34](https://github.com/mahmoudmohamed22/Automate-Nexus/assets/47304558/b4984c35-47ae-427d-8052-4f085c93cadf)


## Contributing
Contributions to this repository are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.
