# External Firewall Configuration
Properly configured Firewall is the first line of deffence of your Virtual Private Server.\
**NEVER FORGET TO CONFIGURE IT AT FIRST STEP!**

## Choose your VPS Hosting Provider
Before you decide to hosting your own VPS it's good to make a good research aboutu VPS providers.\
Some of theme allow you to configure external firewall what is crucial in terms of security.\
\
Anyway if yor VPS provider do not allow you to configure external VPS there is nothing lost yet.\
You can still:
1. Create your own external firewall (eg. proxy)
2. Confiure your internal VPS Firewall (eg. UFW)

As I like to make all my workflows simple I prefer to use External Firewalls.\
It's much more easier and elegant to configure firewall via GUI (Graphical User Interface), rather than CMD (Command Line).

My personal choose for VPS Provider is **[Hostinger](https://hostinger.pl?REFERRALCODE=1WAIROUS35G77)**

## Example of Firewall Configuration
Following screen shows my configuration for **[Hostinger's External Firewall](https://hostinger.pl?REFERRALCODE=1WAIROUS35G77)**.\
You can still use it to configure your Internal Firewalls, as it's only an tamplate.\
\
What is most important abotu below configuration is fact that it block all ports and allow connection to only specific ports.\
**Red place is for your IP address to allow SSH communication only to specific IP's**
![image](https://github.com/CodastickFantastic/Secure-VPS-Traefik/assets/118989184/bc5b784e-d846-4c91-93cc-12d9ddf31e35)

