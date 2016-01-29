# Vagrant-config-ultimate

After several research here is my One script ultimate Vagrant Config.


This is a one script Vagrant. Easy to copy and modify for your PHP/Nodejs/Laravel project.

It includes : 

- Apache
- Latest PHP & common extensions (include mcrypt, imagick)
- Nodejs
- Grunt
- Bower
- mongo & redis (optionnal)

## How to install ?

Install [Vagrant](https://www.vagrantup.com/downloads.html) and [Virtual Box](https://www.virtualbox.org/wiki/Downloads).

Simply copy-paste install.sh or in your terminal at your project root

    curl -O https://raw.githubusercontent.com/danielsum/vagrant-config-ultimate/master/\{Vagrantfile,install.sh\}
    
    vagrant up
    
    vagrant ssh

Now you can connect to http://localhost:8080    
    
## Options

Feel free to adapt the install.sh script to your need (see install.sh for more info)

@todo : phpmyadmin access



