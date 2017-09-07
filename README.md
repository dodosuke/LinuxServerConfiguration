# LinuxServerConfiguration
This is the information about how to setup linux Server on AWS Lightsail.

## Server Setting
* IP address:   http://54.92.57.121/
* SSH port:     2200
* URL:          http://54.92.57.121/catalog/

## Summary of software installed and configuration changes made
1. Set up Ubuntu server on AWS Lightsail
2. Added a new user "grader" and gave sudo permission
3. Set up ssh-key using a local computer (Macbook)
4. Added public key to the server
5. Set up a firewall in the server and in the AWS Lightsail to only allow incoming connections with SSH-key
6. Configured local timezone to UTC
7. Installed Apache2, mod_wsgi, and PostgreSQL applications
8. Created a database with limited access permissions
9. Installed Git
10. Downloaded the project from Github (https://github.com/dodosuke/ItemCatalog.git)
11. Installed libraries, such as flask, sqlalchemy, psycopg2, oauth2client, httplib2, requests
12. Made and configure the WSGI file (http://flask.pocoo.org/docs/0.10/deploying/mod_wsgi/)
13. Changed the path of databases in python codes
14. Executed a python file (addSampleDataToDB.py) to insert data in to the DB
15. Executed a python file (controllers.py) to launch the app
