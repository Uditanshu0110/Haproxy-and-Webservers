![Screenshot](0*X79_Y1mqwzUZMQ3O.gif)


# Haproxy-and-Webservers


## Load balancing refers to efficiently distributing incoming network traffic across a group of backend servers, also known as a server farm or server pool.

## HAProxy (High Availability Proxy) is a TCP/HTTP load balancer and proxy server that allows a webserver to spread incoming requests across multiple endpoints. This is useful in cases where too many concurrent connections over-saturate the capability of a single server. In this repo we will be Using Ansible playbook and we will Configure Reverse Proxy i.e. Haproxy and update it’s configuration file automatically on each time new Managed node (Configured With Apache Webserver) join the inventory.


# For detailed explanation 
https://uditanshupandey00.medium.com/deploying-a-load-balancer-and-multiple-web-servers-through-ansible-944d0c460103
