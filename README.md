
# My Projects
-  routers for my local network
- pihole adblock for my local network
- a self-hosted wireguard host for my personal use
- nginx-proxy-manager for better domain names (such as server.local)
- git for source control
- a small [game engine](https://github.com/GimmeDataNow/falling_sand) modeled after the Falling Everything engine
- a small math exercise generator for my little brother
- some minor websites
- my linux config
# The skills I learned
### routers
> In order to set up my WLAN for my home, I had to buy and set up my own router. Having been provided a static IP, I learned how set up my network. I first learned the different operation modes (Router | Access) and their purpose. Afterwards I was introduced into static IPs and some of the important parameters that surround it ( IP, subnet mask, default gateway, etc.).  Having entered my static IP, I was introduced to the split between WAN and (LAN + WLAN). I learned of DHCP and it's importance in a network. I configured the DHCP server with an IP address pool and reserved some IPs for some certain devices, and then bound these devices to the corresponding IP.

In short I learned about: WAN, LAN, IP, subnet mask, default gateway, DHCP, router operation modes, IP reservation and 

### pihole and routing
> After having used my network for a while I came to know about local network wide adblocker (such as Pihole) that require no additional installation on the clients. I found out that Pihole acts as a local man-in-the-middle DNS server. At the time I was still quite unfamiliar with DNS servers, so this was a new and welcome exposure to networking. I initially set this up as a base application on my Raspberry Pi (but later moved to a docker container). While configuring the pihole (and setting it as the default DNS server on the DHCP server) I found out more about IPv4 and IPv6 while also learning about DNS filtering. The Pihole comes equipped with the handy feature of auto updating the filter list, given that you provide all the urls (source: [firebog](https://firebog.net/)).

In short I learned about: DNS, DNS filtering, IPv4, IPv6

### docker
> I eventually became got wind of docker as an virtualization tool, which I then wanted to integrate into my setup. I first learned what exactly a docker container is and how to compose one. Following that I used it to first install a gui docker container manager (portainer). I moved my pihole install into a docker container in order to learn more about docker and its inner workings. Having ported my pihole setup I began to look out for other container programs to install (these are covered in their respective sections). 

In short I learned about: virtualization, docker, docker-compose, docker-stacks and environments using portainer as my docker manager. 

### nginx-proxy-manager
> Having used docker for a while to host all sorts of servers I grew tired of entering a hard to remember IP and port. I looked into getting my own local (free) domain name up and running on my local network. I found and installed nginx-proxy-manager in my docker environment. I first set up some domains (e.g. pihole.local) on my pihole and then configured my proxy manager to redirect these request to the correct port. Although I did initially attempt to set up https support, I quickly realized that that would require an external SSL service which I had no need for. I also explored some of the settings that nginx provides (such as redirection hosts). 

In short I learned about: port-forwarding, http and https, ssl, proxy, reverse proxy, 404 Hosts, redirection hosts
### wireguard
?
### git
source control using git
### rust
rust, toml
### webgpu / wgsl
using wgpu
### css + html
for some old websites that I made
### basic bash scripting
for linux
> hello
