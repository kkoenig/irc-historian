irc-historian
=============
A simple IRC bot that records chat history and plays it back to users.
installation
============

With [npm](http://github.com/isaacs/npm), do:

    npm install irc-historian -g
 
or clone this project on github:

    git clone http://github.com/kkoenig/irc-historian.git
    
commands
========
update
------
Gets all the chat messages that occurred while the current user was not present in the given channel.
    
    /message historian update <channel>
    
get
---
Gets the last n chat messages
  
    /message historian get <channel> <n>
    
    
