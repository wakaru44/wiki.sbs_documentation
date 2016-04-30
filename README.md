# The project 2016

This year, I want to do between jobs something that has been floating in my mind for a while.

I want to have my services in the cloud, and controlled by me. But I don't need them all the time, and I don't want to spend all that money, all that time.

So what I want is minimally sized services, under close start and stop control, from anywhere, anytime. 10 seconds work to start a service, for my, by me.

Part of this project, includes mobile apps, an api, and probably a web interface of some kind.

On top of that, using containers to ensure that is reproducible, and things like troposphere and ansible to provision the environments.

## Services that I might want:

- contact sync with owncloud

- files sync
    
    - owncloud?
    - any of the new options of distributed filesystems that use S3 or ELB for storage
    - a storage provider like infinit, dropbox , or whatever.

    
    the filesync solution is the most difficult and the most important to get right. It has to:

  - be compatible with linux, windows, and portable devices (at least access, but sync is better)
  - have some kind of agent to keep files in sync without being a fucking hasle to stay updated
  - be self-hosted, so i can do it at home, at a server in the cloud, or whenever I want.
  - ideally, i should be able to see all my files, but have locally only the ones that i want to access here. Keeping more than one copy automatically and that stuff (dropbox has the correct kind of browser integration, but is expensive and not self hosted).

- in general, owncloud provides many many services for user land.

- I want to run different kinds of APIs and programming related services. On top of that, I will want to run as well my own projects.

- having a jenkins with superpowerds would be pretty nice as a way to abstract all this tasks in a user interface without having to develop something in-house. even for prototyping at the beggining.

- a private docker repo will be very useful for this sort of things as well.

	- it will need EBS or similar based storage that is kept online
        - 

the infrastructure, will have a part that is fixed, with a part that is flexible. But both parts should be controlled equally, depending only in a minimal set (thta means, having setup the basics, we can i.e. shut down the docker registry when the platform is off.

## minimal infrastructure

to start with a minimal MVP, to trial the tech

- start with the dockerized owncloud or with the node.js api??

- the jenkins server is part of the creating of the apps and the deployment of the api.

- 


## the desired services 

- owncloud docker + fixed storage

- the api for our purposes


- 
