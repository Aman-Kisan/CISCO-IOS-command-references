## CISCO IOS commands

### Basic Configuration

|command|description|runs on|
|:-------:|:-----------:|:------|
|`SW>enable`, `Router>enable` |To move from user exec mode to privileged exec mode|Switch,Router |
|`SW>disable`, `Router>disable` |To turn off privilege mode|Switch,Router |
|`#configure terminal`|To activate the global configuration mode|Switch,Router|
|`?`| Type this in any mode the show the commands you can run from that mode|Switch,Router|
|`(config)#enable password <password>`| To set password for privileged exec mode|Switch,Router|
|`(config)#enable secret <password>`| To set password for privileged exec mode (encrypted)|Switch,Router|
|`(config)# service password-encryption`| To encrypt the passwords in the running-config| Switch, Router|
|`#show running-config`| To display config file in RAM|Switch,Router|
|`#copy running-config startup-config`,`write memory`,`write`| To save the running config to NVRAM|Switch,Router|                                                                         
|`erase startup-coinfig`| To return to the default startup-config (use with caution)|Switch,Router|
|`banner motd %Any message%`| To set the message-of-the-day banner, that shows up when user logs in|Switch,Router|      
|`no <command>`| To reverse the affect of a command| Switch,Router|
|`(config)# line console 0`| To access console port 0| Switch,Router|
|`(config) line vty 0 15#`|To access the virtual port line from port 0 to 15.| Switch| 
|`(config)# interface [interface id]`| To access the interface configuration mode|Switch,Router|
|`(config)# interface range [interface id]`| To access the interface configuration mode for a range of interfaces (e.g. 0-10, 0-24, 0/1-24, etc.)|Switch,Router|
|`#show interfaces {interface id}`|To show the status of interface or interfaces | Switch,Router|
