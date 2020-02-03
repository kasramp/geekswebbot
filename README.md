# geekswebbot
Create bot for your website or blog easily with GeeksWebBot (GWB).

## Description
GeeksWeb Bot is a simplified and lightweight version of [Jadibot by Jaavid](https://github.com/jaavid/jadibot/) Telegram bot. It is designed to be easy to launch on HeroKu cloud application platform. In this bot, the database portion and other complicated parts of Jadibot have been removed to make it easy to configure on cloud application platforms.

The use of this bot application is not difficult, you just need to copy/paste the content to your HeroKu application and commit the code, however, before that you are required to set your website/blog RSS feed as well as access token. In order to do so, just change the following values in index.php file,

	$client = new Zelenin\Telegram\Bot\Api('AccessToken');
	$url = 'Your website RSS feed';

## Usage 
The working version of this bot program is deployed for [Geeky Hacker](https://geekyhacker.com) on HeroKu. Click on  [telegram.me/GeeksWebBot](https://telegram.me/GeeksWebBot) link to start interaction with the bot.

List of available commands for this bot are,
	
- ````/help```` Shows list of available commands
- ````/email```` Gets email address of the blog owner
- ````/latest```` Displays the latest of the blog

## Dependencies
The program works out the box so smoothly and all necessary dependencies have been already added to the project.
You just need to run it in your server. It is highly recommended to run "composer update" command before deploying your application in order to update all dependencies

## Screenshot
<p align="center">
<img src="https://user-images.githubusercontent.com/4501120/47316095-958e8400-d646-11e8-88ed-217ad4b05826.png" alt="Drawing" height="300" width="400"/>
</p>

## Useful resources

If you do not know how to setup a telegram bot, I recommend you to have a look on the following link:

[https://geekyhacker.com/2015/10/04/how-to-create-telegram-bot-with-php-and-host-in-heroku/](https://geekyhacker.com/2015/10/04/how-to-create-telegram-bot-with-php-and-host-in-heroku/)

## Contact
* kasra@madadipouya.com

## License
GeeksWeb Bot (GWB) is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License version 3
as published by the Free Software Foundation.

GeeksWeb Bot (GWB) is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.  <http://www.gnu.org/licenses/>

Author(s):

© 2015-2020 Kasra Madadipouya <kasra@madadipouya.com>
