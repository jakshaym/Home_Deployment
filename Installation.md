####Installing Lamp server
 
    sudo apt-get install tasksel
    sudo  tasksel

####Select LAMP Server using space button

####Installling SSH Server

    sudo apt-get install ssh

####Configuration for JPlug
Copy data1.php file as mailed by Radio Studio to /var/www.
Datafiles shall start getting collected in that folder.

    sudo chmod 777 /var/www -R

####Installing Python Setup Tools,pip

    sudo apt-get install python-setuptools
    sudo easy_install pip

####Installing web.py for web framework task

    sudo pip install web.py

####Installing gnome-shell on Ubuntu
 
   sudo apt-get install gnome-shell

####Install python-mysql stuff
  
    sudo apt-get install python-dev libmysqlclient-dev
    sudo easy_install -U distribute
    sudo pip install MySQL-python


####Create database and table for smart_meter data collection
ON MySql promt
    
    create database smart_meter;
    use smart_meter;
    Use gist at https://gist.github.com/nipunreddevil/0030d1052bbaab08aa88/raw/6a4d566d8520ecbe85e71abc95e038ccbf0e8bd3/energy_data_table to create the table


####Installing monitoring script for JPlug data collection

####Installing Matplotlib,Numpy

    sudo pip install numpy
    sudo apt-get install g++
    sudo pip install pytz
    sudo apt-get install matplotlib
