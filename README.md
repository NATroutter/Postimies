![banner](https://cdn.nat.gg/img/Postimies_banner.png)

<div align="center">
<h1 style="margin: 0px;font-weight: 700;font-family:-apple-system,BlinkMacSystemFont,Segoe UI,Helvetica,Arial,sans-serif,Apple Color Emoji,Segoe UI Emoji">Postimies</h1>

![GitHub](https://img.shields.io/github/license/NATroutter/PostiMies?style=for-the-badge)
![Jenkins](https://img.shields.io/jenkins/build?jobUrl=https%3A%2F%2Fhub.nat.gs%2Fjenkins%2Fjob%2FPostimies%2F&style=for-the-badge)

Postimies is a simple discord bot that will track your  
post packages and notify your package get get updated

</div>

## Features

1. Configurable
2. Simple
3. Self Hosted
4. Automaticly remove packages when they are arrived
5. Tracking your packages day and night non stop
6. reveive update messages when your package status changes

## Installation
### Debian/ubuntu

1. Download newest release from [jenkins](https://hub.nat.gs/jenkins/job/Postimies/lastBuild/)
2. make new folder to some directory where you want to keep the bot and  
   drop downloaded jar file to that directory
3. create new start file ``start.sh``
4. insert this into start file ``java -jar Postimies-<version>.jar`` and replace <version>   
   with correct version number then close the file
5. Give file permissions to be executed ```chmod 755 ./start.sh ./Postimies-<version>.jar```   
   remember to replace <version> with correct version number then close the file
6. Run start script with ``./start.sh``
7. when console has closed open ```config.json``` file which is generated to  
   same folder where ``Postimies.jar`` is located
8. login or register new account in [trackingmore.com](https://www.trackingmore.com/)
9. Acquire trackingmore apikey from your account settings [here](https://my.trackingmore.com/get_apikey.php?lang=en)
10. Create new bot in discord developer portal [here](https://discord.com/developers/applications)
11. add bot to your discord server and make sure that server members  
    can send you private messages!
12. add trackingmore and discord bot token to ```config.json```
13. add your discord user id and name to whitelist
14. start the bot again with ``./start.sh`` bot should send status online message   
    to your private messages!
15. You are Finished

### Windows

1. Download newest release from [jenkins](https://hub.nat.gs/jenkins/job/Postimies/lastBuild/)
2. make new folder to some directory where you want to keep the bot and  
   drop downloaded jar file to that directory
3. create new start file ``start.bat``
4. insert this into start file ``java -jar Postimies-<version>.jar`` and replace <version>   
   with correct version number then close the file
5. Run start script with ``./start.bat``
6. when console has closed open ```config.json``` file which is generated to  
   same folder where ``Postimies.jar`` is located
7. login or register new account in [trackingmore.com](https://www.trackingmore.com/)
8. Acquire trackingmore apikey from your account settings [here](https://my.trackingmore.com/get_apikey.php?lang=en)
9. Create new bot in discord developer portal [here](https://discord.com/developers/applications)
10. add bot to your discord server and make sure that server members  
    can send you private messages!
11. add trackingmore and discord bot token to ```config.json```
12. add your discord user id and name to whitelist
13. start the bot again with ``./start.bat`` bot should send status online message   
    to your private messages!
14. You are Finished
