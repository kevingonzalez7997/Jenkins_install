# Jenkins Installation Script
### Kevin Gonzalez
This Bash script simplifies the installation process for Jenkins on your Linux system. Jenkins is a popular automation server used for Continuous Integration and Continuous Deployment (CI/CD).

## How to Use

1. Run the script on your Linux machine.
2. The script will perform the following actions:

   - Update the package repository to ensure you have the latest package information.
   - Install the Java Runtime Environment (JRE) required for Jenkins.
   - Add the necessary repositories for Jenkins.
   - Update the system again to fetch information from the newly added Jenkins repository.
   - Install Jenkins on your system.
   - Start the Jenkins service.

Now, you can access Jenkins through your web browser by navigating to `http://host:8080`. Follow the on-screen instructions to complete the setup.

## Requirements

- A Linux-based system (Debian/Ubuntu in this script)
- Superuser privileges (sudo)
