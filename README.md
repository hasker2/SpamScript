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
