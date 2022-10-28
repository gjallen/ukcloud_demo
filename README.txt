Ansible deployment to automate the tasks set out below --

Interview demo task:

3 RedHat virtual machines:

- Virtual Machine 1 Install RH8 (Dev account), install MariaDB
- Virtual machine 2 Install RH8 (Dev account), install Docker and a website which uses the database
- Virtual Machine 3 Install RH8 (Dev account), install HA Proxy to access the website from the HOST Machine

- Use Ansible to automate the application install
- Use Ansible to automate the RH8 Machine maintenance
- Use Git for all the code
- Be able to demonstrate a change to the website in code and automation update the website