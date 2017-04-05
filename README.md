# Sensu
## Howto, install, tests and more about Sensu

In this repository I'll add documents, files, and templates for install Sensu Distribuited.

## Hightlights

You can see the _Sensu_ arquitecture in the [website](https://sensuapp.org/docs/0.28/overview/architecture.html)
to understand the installation steps.

I couldn't get all explanations in the documents pages on Sensu Website, 
so I let some notes about conf files and how to sort it.

When you install Sensu, you install the _core server_, that bring with it the Server, 
the Api and the Client and you'll can enable the three components or the Server and the Api or only the Client, it depends on which config files you will setup.

### Sensu Server

Configuration Files Directory:

/etc/sensu/conf.d/

			
### Sensu Api

### Sensu Client

### Uchiwa Dashboard


## Installation tutorial

I'll try install diferent kinds of install:

1. Debian Docker Images
* Install RabbitMQ as transport on Debian Docker.
* Install Redis as datastore on Debian Docker.
* Install Sensu client, api and server on Debian Docker.
* Install Uchiwa as dashboard on Debian Docker. 
2. CentOS Docker Images
* Install RabbitMQ as transport on CentOS Docker.
* Install Redis as datastore on CentOS Docker.
* Install Sensu client, api and server on CentOS Docker.
* Install Uchiwa as dashboard on CentOS Docker. 
3. Sensu Docker Images
* Install Sensu from Docker
* Install RabbitMQ from Docker
* Install Redis from Docker
* Install Uchiwa from Docker 

## Troubleshotting

## Notes

1. Debian Docker
* Problems on install sensu suite
2. CentOS Docker
* Problems on install sensu suite


