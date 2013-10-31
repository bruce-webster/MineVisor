MineVisor
=========

Minevisor

MineVisor is an open source project which attempts to provide an 
automated online solution to manageing minecraft servers. It sits on top 
of the minecraft server application and communicates with it via stdio. 
The intention is to have a server capable of remotely controlling the 
minecraft application via a web interface. The application should also 
be able to log data from minecraft into a database for fault analysis 
and other purposes.

There are some issues with this kind of program, of course one being the 
interface with the sub process. However it makes it easy for upgrades 
and doesn't care whether the user is running a vanilla server or a 
custon server such as FTB. However it should be noted that only vanilla 
commands will initially be supported.

The current state of the project is:

Web server: partially complete, needs to be more extensable in terms of 
pages.
Logger: Mostly complete in terms of how I invisage it. Suggestions are 
more than welcome
Control element and interfaces: this needs work to implement most of the 
commands, only some are implemented.

The program can currently start and stop a server from a web interface. 
It can also display a log of the servers STD Error output.

I'd like to get to the point where the log data can be selected on the 
webserver. I would also like all the commands implemented
