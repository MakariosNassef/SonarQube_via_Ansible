# Ansible Playbook for Installing SonarQube

## Introduction

This Ansible playbook automates the installation of SonarQube on a Debian/Ubuntu-based system. It covers the installation of required packages, PostgreSQL setup, Java installation, SonarQube download and configuration, Nginx configuration, and setting up SonarQube as a service.

## Prerequisites

Before running this playbook, make sure you have:

- Ansible installed on your control machine.
- SSH access to the target server with sudo privileges.
- The playbook is configured with the necessary variables (e.g., `sonarqube_version`, `psql_sonar_username`, `psql_sonar_password`, etc.).

## Usage

1. Clone this repository or download the playbook to your local machine.

2. Update the playbook variables:
   - Open the playbook file (e.g., `sonarqube-install.yml`) and set the required variables according to your setup. Pay attention to variables such as `sonarqube_version`, `psql_sonar_username`, and `sonar_web_port`.

3. Run the playbook using the following command:
   ```bash
   ansible-playbook  -i inventory.ym sonarqube-install.yml

1. The playbook will execute all the tasks, including downloading SonarQube, configuring PostgreSQL, Nginx, and setting up SonarQube as a service.

2. Once the playbook completes, you should have SonarQube up and running. Access the SonarQube web interface by opening a web browser and navigating to http://your-server-ip:sonar_web_port.

## Important Notes

- Ensure that the server where you are installing SonarQube meets the system requirements for SonarQube.

- Make sure to secure your SonarQube instance properly, including setting up firewalls, authentication, and access control.

- Backup any data or configurations before running this playbook, especially if you are installing SonarQube on a production system.

- For more information about SonarQube, please refer to the [official SonarQube documentation](https://docs.sonarqube.org/).



## Author

**Makarios Nassef**  
DevOps Engineer

- Mobile: +20 1206330662 | +20 1099893484
- E-mail: [makarios059@gmail.com](mailto:makarios059@gmail.com)
- LinkedIn: [https://www.linkedin.com/in/makarios-nassef/](https://www.linkedin.com/in/makarios-nassef/)
- Address: Cairo, Egypt
