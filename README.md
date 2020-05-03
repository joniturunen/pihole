# Raspberry pihole with dhcp inside Docker container
> AdBlocking DNS & DHCP

## What is this?

Docker compose file for running pihole inside a container with host networking mode active.
 
Edit volume information in `docker-composer.yaml` and create `.env` from `sample.env` to match your criteria.

There is also a macvlan option included but I personally had problems with it. If you are interested using it you might want to [check the official site for more info.](https://docs.pi-hole.net/docker/DHCP/)

## Forgot the password? 

If you lost your pihole admin password you can reset it with `docker exec -it pihole pihole -a -p`.
