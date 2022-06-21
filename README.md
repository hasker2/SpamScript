# SpamScript
Spamming script for telegram. You can use it to promote your service/channel/web-site. Free.\
It's open source so you can edit it as you wish
# Installing PC (Windows)
Firstly install [Python 3+](https://www.python.org/downloads/) and [Git](https://git-scm.com/downloads)\
*You should install pyrogram and termcolor*

	pip install pyrogram termcolor

*Then clone this repository*

	git clone https://github.com/hasker2/SpamScript.git
# Inctalling on termux

	apt-get update
*Downloading python*

	apt-get install git python
*Downloading pyrogram and termcolor*

	pip install pyrogram termcolor
*Cloning repository*

	git clone https://github.com/hasker2/SpamScript.git

[Then open it](https://github.com/hasker2/SpamScript/blob/main/README.md#opening)
# Opening
[Update](https://github.com/hasker2/SpamScript/blob/main/README.md#updating) srcipt before opening

	cd SpamScript
	python main.py

*[How to use](https://github.com/hasker2/SpamScript/blob/main/README.md#commands)*
# Updating
### After update your texts and ids will disapeare

	cd SpamScript
	
*Then write 'git pull'*
	
	git pull
# First settings
Firstly you should be member of channel where you want to spam\
Then use command /newchannel and after space enter id of this channel e.g.\
/newchannel -12345678910
## How to get channel id?
You should use [t.me/getmyid_bot](t.me/getmyid_bot) or something else.\
Just forward any message from your channel to [t.me/getmyid_bot](t.me/getmyid_bot) and get channel id (it starts at -)\
![Id of my test channel whick I created. It should start with dash (-)](https://github.com/hasker2/SpamScript/blob/main/screens/%D0%97%D0%BD%D1%96%D0%BC%D0%BE%D0%BA%20%D0%B5%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202022-06-20%20154640.png)
Then you should add you text(s)
Use command "/newtext Your text" to add your text.You can add more than one. If you add more than one programm will choose random of them. If you don't add any text, programm will spam with default one - Hello!👈 Click on my logo
# Commands
## Channel commands
/newchannel -12345678910\
Add new channel id *(into channelids.db)*

/clearchannels\
Clear all channel ids

/removechannel -12345678910\
Remove channel by id

## Text commands
/newtext HELLO - example.com👈
Add new spam text (Program chooses random one from texts which you added)

/cleartexts\
Clears all your texts (if you wont add any text script will post default one - Hello!👈 Click on my logo, but if you add anything it wont be use)
## Script commands
/quit - closing script without session exit (alternative to Ctrl + C in console)
# Then
Then it checks every posts in your channels. Sometimes it may print error in console because admin posted post without comments, or chat has some time limits, but bot script wont stop, it will just standart telegram API error. Even if script somehow stops just relaunch it using [this commands](https://github.com/hasker2/SpamScript#opening), all your texts and chat ids saved in databases
