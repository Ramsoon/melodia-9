# loadbalancing-by-nginx-proxy
This explores request distribution with nginx proxy using loadbalancing concept

This project explores how Nginx can be use as Load Balancer in your app deployment with 

This project demonstrates how to use Nginx as a reverse proxy and load balancer in front of multiple web servers running in Docker containers. I also configured SSL with a self-signed certificate to only accept ecrypted requests from client and Least Connections algorithm was configured to override the default round robin.

In summary, nginx is configured to:

Distribute requests across 3 backend servers using the least connection algorithm.

Accept only HTTPS (SSL/TLS) connections.

Redirect all HTTP (:80) traffic to HTTPS (:443) using a 301 redirect.

Use a self-signed SSL certificate for encryption.

Feel free to access this in my repo: https://github.com/Ramsoon/loadbalancing-by-nginx-proxy

