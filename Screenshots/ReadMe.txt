
link to LucidCharts Infrastructure Diagram:

https://lucid.app/lucidchart/b25db5b8-2e16-4f03-a878-31926f1bf51f/edit?invitationId=inv_9ad62842-547e-4beb-aeb7-43101edc6940#


Link to LoadBalancer DNS
http://chall-WebAp-1J5Z4IJEMUFF3-921779967.us-east-1.elb.amazonaws.com


Parameters: see attached json files & screenshots

Resources: See attached yaml files

Outputs: See attached yaml files and screenshot. I used the !Join function to concatenate the "http://" prefix to the loadbalancer DNS Name

Working Test: go to http://chall-WebAp-1J5Z4IJEMUFF3-921779967.us-east-1.elb.amazonaws.com

LoadBalancer: see yaml files for Target group, health check conditions and Listener/Listener rule. 

Auto-scaling: t3.small with 10 gb of RAM specified.

Due to time constraints, i didn't get around to setting up the bastion hosts as I outlined in the infrastructure diagram, however since the primary project objectives are fulfilled i opted to submit and continue further study and practice offline.