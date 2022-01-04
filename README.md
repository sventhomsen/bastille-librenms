# bastille-librenms
A [Bastille](https://bastillebsd.org/) template for running [LibreNMS](https://librenms.org) in a FreeBSD jail 

This template creates a working installation of LibreNMS with a clean database.

I've created this Bastillefile mostly as an alternative documentation of my setup at home. 

There also is a [port of librenms](https://www.freshports.org/net-mgmt/librenms), which you could or should also try first. 

## Usage

    bastille bootstrap https://github.com/sventhomsen/bastille-librenms
    bastille create librenms 13.0-RELEASE 192.168.1.1 em0
    bastille template librenms sventhomsen/bastille-librenms

After a while, you should be able to point your browser to the ip adress (192.168.1.1 in this example) and finish the installation.

![First launch](/librenms-launch.png)
![Databse Setup](/librenms-database.png)
![Create Admin User](/librenms-admin.png)
![First login](/librenms-login.png)


