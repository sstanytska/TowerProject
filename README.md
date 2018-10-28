******Fail2ban Service******

fail2ban.yaml 

This playbook installs and configures Fail2ban service on Amazon-Linux and CentOS7 
The requerement to install fail2ban service is epel-release repository
1. It install epel-release on CentOS7 
2. It install epel-release on Amazon-Linux
3. Install Fail2ban service on Amazon-Linux and CentOS7 
4. Enables Fail2ban Service
5. Create configuration file on CentOS7
6. Configures Fail2ban Service on CentOS7
7. Configures Fail2ban Service on Amazon-Linux
8. Restarts Fail2ban service on Amazon-Linux
9. Restarts Fail2ban service on CentOS7


**FAIL2BAN Configuration"
The configuration:
1. Allows 3 retry
2. Allows 2 minutes to login
3. If faild to login, bans for 1 hour
4. Ignores company's CIDR block


*****Create file 5GB*****

This playbook create 5Glogfile in projects.
You can pull it for some project
and create your template and use it. 




***atop_installation.yml**

This playbook installs on Centos/RedHat. 
Atop is not available on Ubuntu. 
It is safe to run the playbook

****5Glogfile.yml***
I was able to create the playbook, and I created a project under my name "Roman's Project". Within this project you have atop-installation.yml file. Use it to install on Centos/Redhat Systems.
Unfortunately atop is not available for Ubuntu. Please let me know if you have any questions. For more instructions please read README file.
