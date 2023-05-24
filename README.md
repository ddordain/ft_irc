# IRC
This repository contains the code for a basic Internet Relay Chat (IRC) server implemented in C++98. This project provides a simple, robust solution for real-time chat functionality over the internet.

Fully compatible with IRSSI client. 

## Features
- Communication over TCP/IP protocol
- Support for basic IRC commands
- Concurrent handling of multiple client connections
- Thread-safe message handling
- Efficient network traffic management

## How To Use It 

Download the repository
```bash
git clone https://github.com/ddordain/ft_irc.git 
```

Navigate into the repository
```bash
cd ft_irc
```

Compile the files
```bash
Make
```

Run the server
```bash
./ft_irc <port> <password>
```


In a new terminal, you can launch IRSSI. You can also launch the script called irssi in the repo to generate two terminals, with gg and dd as name chosen, assuming the password you set earlier for the server is "pw".

With irssi, you can connect to the :with with
```bash
/connect localhost <port> <pw> <nickname>
```

Among all the available command, the server implements AWAY, DIE, INVITE, JOIN, KICK, KILL, MODE, MOTD, NAMES, NICK, NOTICE, OPER, PART, PASS, PING, PRIVMSG, QUIT, TOPIC, USER, WHOIS.

For more information on these commands, refer to the IRC protocol documentation.
