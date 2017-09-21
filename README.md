# linux-project

i. The IP address and SSH port so your server can be accessed by the reviewer.
ip address: 54.187.0.171
ssh port: 2200

ii. Server url: http://54.187.0.171

iii. 
Software installed: git, mod-wsgi, apache2, pip, httplib2, SQLAlchemy, flask, psycopg2, libpq-dev, virtualenv, postgresql, python requests, oath2

Configuration changes made: 

     Configured UFW to deny all incoming except port 2200/tcp, 123/udp, 80/tcp.
     
     Configured a user named grader with sudo permissions
     
     Configured localtimezone to UTC
     Configured a catalog directory and git cloned in my item catalog project
     Configured the project to work on the lightsail environment with mod-wsgi
     Configured a virtual host conf file in /etc/apache2/sites-available
     Configured apache to use flask with a .wsgi file(/catalog/catalog.wsgi)
     
iv.Non-udacity non-documentation sources:
  https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
  https://realpython.com/blog/python/kickstarting-flask-on-ubuntu-setup-and-deployment/
  https://www.enigmeta.com/blog/starting-flask/
