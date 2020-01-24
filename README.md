# Linux Server Configuration:
Its the online copy of the project "Item Catalog" on linux server(Ubuntu).

# Information:
1. Public IP: 3.8.237.195
2. SSH port: 2200
3. Login as "grader" with: ssh grader@3.8.237.195 -p 2200 -i ~/.ssh/project
4. Application url: http://3.8.237.195.xip.io/

# How to login as grader?
To login you need to use the ssh-key which i added in the "Notes to Reviewer" 
you need to use command line and type:
`ssh grader@3.8.237.195 -p 2200 -i ~/.ssh/project`

# Downloaded application list:
finger
apache2
libapache2-mod-wsgi
git
python-pip
httplib2
requests
oauth2client
sqlalchemy
Flask-SQLAlchemy
flask-seasurf
postgresql
postgresql-contrib

# Configurations made:
Configure the Uncomplicated Firewall only allow incoming connections for SSH (port 2200), HTTP (port 80), and NTP (port 123).
Configure the local timezone to UTC

# third-party resources used to complete this project:
Apache documentation
Flask documentation mod_wsgi (Apache)

