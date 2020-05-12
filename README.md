# Full stack web developer udacity nanodegree - Linux server
i. The IP address and SSH port so your server can be accessed by the reviewer.<br>
```
host : 134.122.90.168
port : 2200
```

ii. The complete URL to your hosted web application.
[web app]: http://irenaapp.de/home

iii. A summary of software you installed and configuration changes made.
- Installed apache2 and created wsgi file for the app.
- Modififed the configurations for apache2 to acceptincoming connections.
- Installed postgres as database and updated connection url
- Flask,sql alchmey libraries are installed using pip3.
- Updated Google api console with the new domain names and ip address to accept the OAUTH

iv. Softwares/DNS
- pgAdmin,postgresql
- apache2
- Godaddy (Domain registraion for irenaapp.de)

v. A list of any third-party resources you made use of to complete this project.
- Followed this url for installing postgres which ialso helped in understanding the necessity of disabling remote ports of database in production systems https://medium.com/@omerkarabacak/how-to-setup-postgresql-on-ubuntu-16-04-12facbf98c9
- Read about SSH private and public key from https://www.digitalocean.com/community/tutorials/how-to-set-up-ssh-keys--2 and understood there importance in secure connections
