There are still a number of questions I need to answer first.

So we will have to go with smaller projects then, before reaching the end goal.


- How to manage coreos and its deployments.

 	- should I control the services online with fabric? 
	- is it something jenkins and the api can easily do?
	- to build the basic infra then, i will need only to create an EC2 instance with CoreOS stable in there, plus an ELB in front (optional), plus route53, plus (in the future) permanent storrage


- how should i handle permanent storage? 
	- having extra ELB disks in the EC2 instance? not multi az
	- having S3 buckets? doesn t support some operations, and is very bad for some uses. not a real filesystem.
	- having a fixed instance with NFS? seems rubish and not HA.

