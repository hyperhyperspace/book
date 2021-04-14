# Why?

The set of standards and the software stack that power the Internet are a monumental success.

Global connectivity is now taken for granted - to the point that the technical challenge of interconnecting hugely many independent, incompatible networks seems distant and completely solved.

This has not always been the case. In 1992 -as the popularity of the Internet was exploding- early Internet pioneer David C. Clark identified a number of issues that threatened its development: a range of prescient concerns including cyberterrorism, the network demands of new technologies like on-line video and games, the role businesses would have in the provision of the service, and many others. Most of these issues were addressed by improvements, refinements and additions to the Internet Protocols in the years since, and would not be considered impediments today.

There is one line of reasoning, however, that feels uncannily relevant. As stated in RFC1958: _Architectural Principles of the Internet_, the goal of the Internet is __connectivity__. In some applications, like a telephone call being routed through the net, connectivity is really all there is to it. But Clark correctly predicts that providing __information__ is the network's ultimate purpose. He says:

> The network as an Information Mesh. An old goal, not yet achieved.

Clark praises recent developments like the World Wide Web (!) and Gopher, but also remarks the need for _information objects_ to be known to the protocols that power the net. 


> Develop a new protocol reference model for application
> level relay networks. Make it work.


> Infrastructure must know about information objects.


. Yet, seen through the eyes of the IETF staff Clark was addressing in 1992, these services fell short of the __Information Mesh__ concept Clark was envisaging. The design of these application level data protocols diverged significantly from the principles that were used in the wildy successful transport and internet layers of the Interent, that emphasized the concept of __end to end intelligence__:

> The intelligence is end to end rather than hidden in the network.

Internet Protocols intelligence is end to end. They designed the protocols attempting to avoid having intelligence hidden in the network. 

Again following RFC1958, the design of the Internet Protocols attempts to put __intelligence in the ends of the connection__, instad of hidden in the network. 



early Internet pioneer David Clark addressed the Internet Egnineering Task Force.




RFC1958, _Architectural Principles of the Internet_, June 1996

> The goal is __connectivity__.\
> The tool is the __Internet Protocol__.\
> The __intelligence is end to end__ rather than hidden in the network.



