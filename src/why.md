# Why?

The set of standards and the software stack that power the Internet are a monumental success.

Global connectivity is now taken for granted - to the point that the technical challenge of interconnecting hugely many independent, incompatible networks seems distant and completely solved.

This has not always been the case. In 1992 -as the popularity of the Internet was exploding- early Internet pioneer David D. Clark identified a number of issues that threatened its development: a range of prescient concerns including cyberterrorism, the network demands of new technologies like on-line video and games, the role businesses would have in the provision of the service, and many others. Most of these issues were addressed by enhancements and additions to the Internet Protocols in the years since, and would not be considered impediments today.

There is one line of reasoning, however, that feels uncannily relevant. As stated in ```RFC1958```: _Architectural Principles of the Internet_, the goal of the Internet is __connectivity__. In some applications, like a telephone call being routed through the net, connectivity is really all there is to it. But Clark correctly predicts that providing __information__ is the network's ultimate purpose. He says:

> The network as an Information Mesh. An old goal, not yet achieved.

Clark praises recent developments like the World Wide Web (!) and Gopher, but also remarks the need for _information objects_ to be known to the protocols that power the net. Seen through the lens of the contemporary Internet, it is easy to see how this is still missing today. The online platforms for e-commerce, social interaction, entertainment distribution, workplace collaboration, etc. we have today are globally accessible, building upon the Internet premise of providing _connectivity_, but don't constitute an _information mesh_ in the sense Clark imagined.

The protocols we use to access the web are _presentational_ in nature, anchored first in the concept of a _document_, and later evolving (as web browsers became more powerful and versatile) into a _thin client_ through which very sophisticated platforms can be remotely operated. The inner workings of these platforms, however, remain opaque. Thus even basic concepts like identity, ownership and trust remain internal to each of these walled gardens, that have very limited interoperability with each other. This greatly complicates ownership of the digital assets created within the platforms, since they can only exist inside of each platform's systems.

Going back to ```RFC1958```, the organizing principle for the Internet protocols was

> The __intelligence is end to end__ rather than hidden in the network.

It is easy to see how information systems, as they developed into the platforms described above, have diverged from this principle, and why Clark and the Internet Engineering Task Force he was addressing considered this possibility worrisome (in 1992!).

Clark included the following idea in his list of recommendations:

> Develop a new protocol reference model for application
> level relay networks. Make it work.

Almost 30 years after this presentation, we still don't have a reference model for a general application-level protocol. On the contrary, once popular application-level protocols like ```SMTP```, ```IRC``` and ```NNTP``` are in decline or have been abandoned.

The Hyper Hyper Space is our attempt to create and implement such a model: a general protocol that can be extended to create distributed applications, where the _intelligence_ -as the IETF named it- resides in the computers and devices owned by the public that uses them, instead of being hidden in the network and out of our control. ```HHS```-based applications form an _information mesh_ in the spirit of the one described above, enabling information sharing and interoperability.

This short book attemtps to explain how this new information layer works and how to use it to create novel applications.

The Hyper Hyper Space is work in progress, and any and all contributions are heartily welcome.

