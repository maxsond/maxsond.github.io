---
layout: page
title: System Administration with Godot
permalink: /sysadmin/
---

*Users want applications and systems they can customize.*

*One user’s customization is another user’s gratuitous change. - [Steve Simmons](http://www-personal.umich.edu/~scs/TechWriting/)*

# Introduction
Lately I started a DigitalOcean droplet with no former experience being solely responsible for every element of
administrating a system. This was a bit like having a first child, having had no former experience being responsible for a child,
in that immediately there were pressing needs that I became responsible for.

This became clear the day after I started the server and looked at the Nginx logs to debug some intended feature,
to be greeted by several lines in the logs from inquisitive strangers probing the server for weaknesses.

It turns out there's quite a lot to set up on a fresh system and although there are plenty of tutorials, the user
experience for a fresh ignorant system administrator gives them no insight into what glaring issues their system may have, 
which is a big problem if we want a world where anyone can set up their own server so we can put the power of the internet 
back into the hands of the users.

To that end, I'm building a modular graphical user interface for general system administration, and I'm doing it in Godot.

# Why Godot?
It's an experiment in GUI development in a game engine. This connects to a parallel mental thread that computers
are at the point that we can fulfill the original promise of [Croquet](https://www.youtube.com/watch?v=cXGLOiZUZ2U):
an internet of virtual objects and environments rather than documents. People are mentally adapted for thinking in spatial terms. We use 2D web forms as a proxy because
we had to in the early days of the internet, but we don't live in that time any more. 

The other reason for Godot specifically is that, linking back to Croquet (and Smalltalk, which it derived from), there
is ongoing work in enabling Godot development in Smalltalk: [GodotTalk](https://gitlab.com/chandler.justin.s/godot-talk-VM)

Therefore, by building our GUI environments in Godot, we merge the best of Smalltalk with the best of
Godot. Common users don't need to be familiar with Smalltalk to develop assets and features in this virtual environment,
but those who have followed the path of Croquet (like [OpenCobalt](http://www.opencobalt.net/)) can benefit as well.