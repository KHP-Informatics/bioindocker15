Security
--------

No control of the Infrastructures
- root access to machines
- want K8S, Docker etc.



- Running on Multiuser environments
A)  Stage 1 on usernamespaces. 
https://github.com/docker/docker/pull/12648/files#r41048220 


TODOs
-----

This has wide implications and various parties are interested in how this will work and what the implications of any limitations are when using the user namespaces.

It is quite a while before Docker v1.10 is made available. It would therefore be nice to see if the experimental candidate for user namespaces working, this will likely need someone to build this branch and perhaps report back?
