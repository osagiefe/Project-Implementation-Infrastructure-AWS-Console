# install the apache2 web server
#!/bin/bash
sudo apt-get update
sudo apt-get install apache2 -y
sudo systemctl start apache2
sudo systemctl enable apache2
sudo systemctl status apache2


# install the nginx web server
#!/bin/bash
sudo apt-get update
sudo apt-get install nginx -y
sudo systemctl start nginx
sudo systemctl enable nginx
sudo systemctl status nginx
sudo apt-get install git -y

# Check to see if Apache2 is installed
$whereis apache2

# Grant permission to apache2
chmod 777 apache2
# Run apache2 script
./apache2

