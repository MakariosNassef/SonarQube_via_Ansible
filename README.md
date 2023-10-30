# CLEAN CODE EVERYWHERE, FOR EVERYONE ✨

## Introduction
This Ansible playbook automates the installation of SonarQube on a Debian/Ubuntu-based system. It ensures clean code quality for all! 🧹

![1_rn-sO9oWLn9lYO7jkVO6og](https://github.com/MakariosNassef/SonarQube_via_Ansible/assets/28235504/444c376f-7791-4f32-91fd-cf246254ca91)


## Prerequisites
Before diving into the world of clean code, make sure you have the following:

- ✅ Ansible installed on your control machine.
- 🚀 SSH access to the target server.
- ⚙️ The playbook is configured with the necessary variables (e.g., `sonarqube_version`, `psql_sonar_username`, `psql_sonar_password`, etc.).

## Usage
Get ready to unleash the power of clean code with these simple steps:

1. 📥 Clone this repository or download the playbook to your local machine.

2. 🛠️ Update the playbook variables:
   - Open the playbook file (e.g., `vars/main.yml`) and set the required variables according to your setup. Pay attention to variables such as `sonarqube_version`, `psql_sonar_username`, `sonar_web_port`, etc.

3. 🚀 Run the playbook using the following command:

   ```bash
   ansible-playbook -i inventory.ym sonarqube-install.yml
   ```


1. 🎉 The playbook will execute all the tasks, including downloading SonarQube, configuring PostgreSQL, Nginx, and setting up SonarQube as a service.

2. 🌐 Once the playbook completes, you should have SonarQube up and running. Access the SonarQube web interface by opening a web browser and navigating to http://your-server-ip:sonar_web_port.


🎉 The playbook will execute all the tasks, including downloading SonarQube, configuring PostgreSQL, Nginx, and setting up SonarQube as a service.

🌐 Once the playbook completes, you should have SonarQube up and running. Access the SonarQube web interface by opening a web browser and navigating to http://your-server-ip:sonar_web_port.

Important Notes
Clean code is essential, and here are some reminders to keep your codebase sparkling:

🧽 Ensure that the server where you are installing SonarQube meets the system requirements for SonarQube.

🔐 Make sure to secure your SonarQube instance properly, including setting up firewalls, authentication, and access control.

💾 Backup any data or configurations before running this playbook, especially if you are installing SonarQube on a production system.

📚 For more information about SonarQube, please refer to the official SonarQube documentation.

Author
Clean Code Advocate: Makarios Nassef 🧼 

- E-mail: [makarios059@gmail.com](mailto:makarios059@gmail.com)
- LinkedIn: [https://www.linkedin.com/in/makarios-nassef/](https://www.linkedin.com/in/makarios-nassef/)
