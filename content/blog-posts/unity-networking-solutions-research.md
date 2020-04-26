+++
author = "Clément"
date = 2020-04-26T19:00:00Z
draft = true
hero = "/images/UnityNetworkResearch_T-1.png"
title = "Unity networking solutions research"
type = "blog"

+++
# Why?

I often limit my game ideas to singleplayer or local coop because of the complexity that a multiplayer game induces, and because I'm not comfortable with setting up such a project.

My goals with this research and a first prototype would be:

* Find a stack that is easy to set up (from project generation to deploying it online)
* If possible open-source libraries to help the community by finding bugs and writing documentation

# Technologies/Librairies

**Socket.io**

In the past, I've used socket.io technology to create multiplayer JS games. It was easy to use and to deploy but it seems that this is not popular in the C# world because existing libraries don't have a lot of support.

**Unity new multiplayer stack**

UNet has been deprecated and replaced by a new multiplayer technology linked to the DOTs stack. This is going to be the future, but right now it's still super early and the API is not stable enough even for a personal project that would take a few months to achieve.

**DarkRift 2**

Great library with an active community. I've used it at work for a mobile multiplayer game, I didn't do the core implementation so I'm not aware of how hard it is. For all the features that I had to implement their plugin architecture made it super easy.

**LiteNetLibe**

This is the networking solution that I use at work on our new multiplayer mobile project. Not much to say because I didn't use it directly yet.

**ENet**

Still an unknown library for me, I just discovered it through the Entitas documentation.

# The prototype

I want to build a project to try one of those libraries, it's going to be a card game known as _La ratatouille_ or _Le barbu_ in France.

I'll be using the Entitas ECS framework because we started using it at work and I'm in love with ECS way of coding. The Unity DOTs stack is not well documented enough for the moment, using it would require a steep learning curve that I keep for another experiment project.

References

[https://github.com/sschmid/Entitas-CSharp](https://github.com/sschmid/Entitas-CSharp "https://github.com/sschmid/Entitas-CSharp")

[https://darkriftnetworking.com/darkrift2](https://darkriftnetworking.com/darkrift2 "https://darkriftnetworking.com/darkrift2")

[https://github.com/RevenantX/LiteNetLib](https://github.com/RevenantX/LiteNetLib "https://github.com/RevenantX/LiteNetLib")

[https://github.com/nxrighthere/ENet-CSharp](https://github.com/nxrighthere/ENet-CSharp "https://github.com/nxrighthere/ENet-CSharp")

[https://github.com/LestaAllmaron/EmbeddedFPSExample](https://github.com/LestaAllmaron/EmbeddedFPSExample "https://github.com/LestaAllmaron/EmbeddedFPSExample")

[https://github.com/RevenantX/NetGameExample](https://github.com/RevenantX/NetGameExample "https://github.com/RevenantX/NetGameExample")

[https://github.com/RomanZhu/Entitas-Sync-Framework](https://github.com/RomanZhu/Entitas-Sync-Framework "https://github.com/RomanZhu/Entitas-Sync-Framework")