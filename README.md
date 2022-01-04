# bastille-librenms
A Bastille template for running librenms in a FreeBSD jail 

This template creates a working installation of LibreNMS with a clean database.

I've done it mostly as an alternative way for documenting my setup. 

There also is a port of librenms, which you could also try.

## Usage

    bastille bootstrap https://github.com/sventhomsen/bastille-librenms
    bastille create librenms 13.0-RELEASE 192.168.1.1 em0
    bastille template librenms sventhomsen/bastille-librenms

After a while, you should be able to point your browser to the ip adress (192.168.1.1 in this example) and finish the installation.

![First launch](/librenms-launch.jpg)
![Databse Setup](/librenms-database.jpg)
![Create Admin User](/librenms-admin.jpg)
![First login](/librenms-login.jpg)


