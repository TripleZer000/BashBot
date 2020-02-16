# BashBot
-------------------------------------------------------------------------------------------------------------------------------
This Irc Bash Bot is a stripped down code of Megatron. Megatron is my bot that is on EvilCorp in #lobby. https://triplezer0.hugoslop.repl.co/mega.html
This Bot requires u to have a passworded nick.
The bot.sh is setup to ssl port 6697. YAY!
# Configuring
simply edit bot.properties
# Running
1. Open on the file directory in which u put the files.
2. chmod +x bot.sh
3. ./bot.sh
# making your own commands
The basic lines for the bot to read a msg and respond to it is below.
```
	*"example"*)
	 echo "PRIVMSG $channel :this is the output" >> $input
	;;
```
In IRC using this comman is shown belown
<NICK> example
<BashBot> this is the output
To make your own u can edit the word "example" and "this is the ouput".
To make another one of this simply copy and paste right after that and edit it
(DO NOT - go outsite of the ############## lines)
# Saver.sh
Don't worry about this unless u wish for your bot to auto reconnect if any issues. Example: if your wifi cuts out a lot.
saver.sh is an alternative to running bot.sh (only use one or the other)
1. chmod +x saver.sh
2. make sure bot saver.sh and bot.sh are chmod +x
3. Just run saver.sh and not bot.sh with command ./saver.sh
