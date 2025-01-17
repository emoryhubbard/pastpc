# PastPC, a Classic LAMP

PastPC is a fictional website, an Airbnb for renting out older PCs and unused computers remotely:

![Image of PastPC home page](PastPCHomePageCropped.png)

This project is designed to show how PHP apps:
- Can be made through the popular LAMP stack--Linux, Apache, MySQL/MariaDB, PHP
- Run for local development, and with some modification, how they can be self-hosted

Resources for self-hosting and cloud deployment:
- How to self-host and perform cloud deployment: https://github.com/emoryhubbard/way-of-the-server
- Script file (a bot) for running Terraform and acquiring Oracle compute instances mentioned in the above tutorial: https://github.com/emoryhubbard/remote-docker-script

## Implementation Details

Instead of using Linux directly, it is run inside of a Docker container.

Could-hosting a MySQL/MariaDB app is also possible, but will require the use of persistent containers available for free for only a temporary trial period.

For indefinite free cloud-hosting and further modernization, I recommend refactoring a new LAMP that uses MySQL/MariaDB to instead use PostgreSQL (if you still like to use SQL), or MongoDB (if you don't mind moving away from SQL), both of which can be deployed for free separately and connected to your PHP app.

## Why Non-Fictional?

It was created for the way-of-the-server tutorial site, which is the first online tutorial that teaches how to self-host PHP apps, all the way from the beginning to the end. This is relevant for training web developers in PHP and MySQL, even when there aren't any free cloud-hosting options for the MySQL component. I also recommend learning PostgreSQL and MongoDB as mentioned above.

Possible use cases for a non-fictional version of PastPC:
- Passive income through unused devices
- Running legacy software without emulators
- Inexpensive DIY hosting
- Cryptomining
- Inexpensive remote desktops

Drawing users with these interests would allow a non-fictional version of the app to be monetized through various means, such as ad revenue or a percentage of each transaction over the platform.

