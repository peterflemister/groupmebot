GroupMe Java API
==
The unofficial GroupMe API for Java


Example usage:
--
```java
Bot bot = new Bot("your bot id here");
bot.sendTextMessage("Test message");
bot.sendImage("Check out this image", "http://www.wtt.com/Pictures/WTT_logo_color_Jan2010.gif");
bot.sendLocation("Home", 38.8977, -77.0366, "The White House");
```
To obtain a bot with an ID use [this form](https://dev.groupme.com/bots/new). After creation use the bot id as a parameter when you create your bot object.
Here are some other useful links:
- [GroupMe docs](https://dev.groupme.com/docs/v3)
- [Request response codes](http://www.w3.org/Protocols/rfc2616/rfc2616-sec10.html) can be used to determine debug messages (you will know them when you see them)
- [Intro to GroupMe bots without this api](https://dev.groupme.com/tutorials/bots) not java related


To Do
--
Feel free to add any of these by first forking this repository, create a branch with a name relevant to your addition then create a pull request describing your addition.
- Create a Bot Registrator
- Add a Bot.class method to change the bot name
- Perform message sending work on a seperate thread to prevent blocking
- Add some ability to listen for messages that are sent in the bots group
- Add the ability for the above on a seperate thread
- Anything else you can think of...

Contact
--
If you have any questions about using the API or contributing to it contact me on skype with the username wreed12345 or by emailing me at wreed58@gmail.com