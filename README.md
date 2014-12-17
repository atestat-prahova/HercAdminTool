HercAdminTool
=============

Hercules RO Server Admin Tool. A tool written in PHP with Codeigniter + Bootstrap allows you to administrate your RO Server easily and securely.

What is it?!

It's an Administrator tool written in PHP with a Codeigniter/Bootstrap backend. Designed to be fast and secure, it's aim is to be the "PHPMyAdmin" of Hercules hosting.

What does it do?!

Basically it suppliments your current CP, or better yet, replaces it. It allows you to control your RO server from anywhere, anytime. Fully customizable for your needs as far as permissions and features go, it allows you to edit accounts, characters, view logs, all securely and without your members having access.

What makes it so secure?!

It's designed to be standalone. Almost all the Control Panels on RO Server maintenance are member facing. They're coupled into your website. Hercules Admin Tool, or the HAT, is not designed to be member facing. It's designed to be tucked safely behind an inconsipcuous URL, and an htaccess password restriction. Your members don't know you use it, don't know where it is, leaving your RO server protected.

What are the current features?!

Right now, almost nothing. It's in its infancy, being actively developed. Check back later for more it can do.

What are the planned features?!

First off, the HAT is designed to run WITH your RO server, on the same machine. This enhances security by not having to send commands across the internet. While this may seem like a waste apache resources, you can also use lighthttpd or ngix to run it, or make apache2 run better by using less resources (you should hardly need them anyway). A full list of planned features include, but are not limited to:

* Account editing, deletion, addition
* Character editing, deletion, moving, position reset, save point reset
* Log viewing/searching
* Account pruning
* Guild management
* Item/Mob DB management (either through SQL or /db/ folder. You can edit items/mobs in a SQL form like interface and then either save them directly to your SQL database or have the CP convert them accordingly and upload directly to your server)
* Item shop management
* Server maintenance management (edit configs, stuff in /db/ folder, start/stop/update both your Herc server OR packages on the server)
* Banned account management
* Complete server logging, CP logging
* all completely controlled by a very comprehensive permissions system. Want your GM's to not be able to edit a character's zeny but edit their level? Give them that permission set. Up to 98 different permission sets available. (99 is admin and 0 is not available)

Cool! How do I install it?!

Right now, you don't. The Control panel isn't even close to ready as it currently does nothing but sit there and look pretty. I'll update when there are features worth installing for :)
