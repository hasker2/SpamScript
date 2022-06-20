# SpamScript
Spamming script for telegram. You can use it to promote your service/channel/web-site. Free.
# Installing PC (Windows)
[Python](https://www.python.org/downloads/) 3+ required\
[Git](https://git-scm.com/downloads) required\
*You should install pyrogram*

	pip install pyrogram

*Then clone this repository*

	git clone https://github.com/hasker2/SpamScript.git
# Opening
[Update](https://github.com/hasker2/SpamScript/blob/main/README.md#updating) srcipt before opening

	python SpamScript/main.py

*[How to use](https://github.com/hasker2/SpamScript/blob/main/README.md#commands)*
# Updating

	cd SpamScript
	
*Then write 'git pull'*
	
	git pull
# First settings
Firstly you should be member of channel where you want to spam\
Then use command /newchannel and after space enter channel id e.g.\
/newchannel -12345678910\
## How to get channel id?
You should use t.me/getmyid_bot ar something else.\
Just forward any message from your channel to t.me/getmyid_bot and get channel id (it starts at -)\
! [Id of my test channel whick I created. It should start with dash (-)(https://raw.githubusercontent.com/hasker2/SpamScript/main/screens/%D0%97%D0%BD%D1%96%D0%BC%D0%BE%D0%BA%20%D0%B5%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202022-06-20%20154640.png)
# Commands
## Channel commands
/newchannel -12345678910\
Add new channel id *(into channelids.db)*

/clearchannels -12345678910\
Clear all channel ids

/removechannel -12345678910\
Remove channel by id

## Text commands
/newtext HELLO - example.com👈
Add new spam text (Program chooses random one from list)

/cleartexts
Clear all texts (it can't be empty so there are always be default text - Hello!👈 Click on my logo)
