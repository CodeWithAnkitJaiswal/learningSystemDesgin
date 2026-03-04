# System Desgin

cloud - kisi aur ki machine 
myLaptop can also be a server if i give a public ip to it and make it running 24x7

---

## DNS

> System that converts human-readable domain names into IP addresses so computers can locate servers on the internet.

---

## Vertical Scaling

> upgrading the physical resources like *RAM, CPU, etc*.

It can upgrade as load comes *for example: on our college predictor rush increased just after result decleration so ram and cpu upgraded from `2cpu, 4gb ram` to `16cpu 32gb ram`* but cannot upgrade while running server need to be restart for upgrade so it has some *Downtime*

---

## Horizontal Scaling

> we are adding the replica of server i.e. Adding another machine.

Servers have their own IP so multiple servers have their different IPs but DNS can return only one IP to solve this problem there's come Load Balancer (It is also a server) has it's own IP and we have to register that IP to our DNS

### Load Balancer

It has several algorithms to divide the load to particular servers

## API Gateway

It is just like a signal post guiding requests to their specific load balancer or sever. It will route requests to thier services

















