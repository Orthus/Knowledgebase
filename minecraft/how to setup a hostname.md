By default, all server IP addresses are not very human friendly. Utilizing a technology known as DNS (Domain Name System) we can setup an address or alias to an IP address to make it much more human readable. It's best to think of DNS is to IP addresses as a Street Address is to GPS coordinates.

For example if we have an IP address of 127.0.0.1 we can create a hostname of mycraft.mcnode.net and either address can be used ingame to connect. This has an added benefit of being much more easy to remember for players and should your IP ever change you can adjust the DNS settings without changing your address from "mycraft.mcnode.net".

### Setting up a Sub-Domain/Hostname with NodePanel
We provide a free hostname for all of our customers via NodePanel. This allows you to simply provide the name you want and our system will handle the technical setup required. Simply type the name you would like and use one of the many domains we offer and you're setup. That was it!

< img goes here >

### Setting up a fully qualified domain name
The most commonly asked question regarding hostnames is how to setup an address such as mycraft.net rather than using mycraft.mcnode.net. The setup and configuration of these not free and requires you to make changes your DNS settings once you've purchased the domain.

### 1. Purchasing the domain
Before you can setup anything, you first need to acquire a domain. The easiest way to do this is to use a company such as Namecheap.com as they provide affordable domains and free DNS service, but you'll need to find a domain which isn't already taken by another person and registered it. If you are having trouble finding a domain that isn't already owned by someone else you can use a tool such as [Domize](http://domize.com/) to find an available domain.
### 2. Configuring the DNS for the domain
Once the domain has been purchased, you will need to setup the proper DNS to ensure that your players can use your domain to get ingame. We highly recommend using a subdomain such as play.mycraft.net or mc.mycraft.net rather than the primary address of mycraft.net, as this allows you to setup a website for players to visit rather than just using a domain for in-game content.
You need to find the DNS management interface with your provider and add an **A Record*** pointing to the IP address of your server. NameCheap has a great guide for this which can be [found here](https://www.namecheap.com/support/knowledgebase/article.aspx/544/51/how-do-i-set-up-host-records-for-a-domain-when-i-use-freedns). For example, if my server's IP was 127.0.0.1 I would setup a DNS record as follows:

**A Record** 
Address: 127.0.0.1
Hostname: play.mycraft.net

If you need any further assistance regarding the DNS settings for your domain,we recommend contacting the provider that you purchased your domain with.