# hash_spider
A module for CME that spiders hashes across the domain with a given hash.

# Installation
Simply copy hash_spider.py to your CME module folder.

# Setup
Simply copy the hash_spider.py module to your CME module folder. Requires access to a BloodHound database configured in ~/.cme/cme.conf. Please see the included example.

# Usage
Run CME against a PC your user has local admin access to and call the hash_spider module.
```
cme smb <IP> -u <user> -p <password> -M hash_spider
```
![hash_spider](https://user-images.githubusercontent.com/86318031/151194508-52972e02-8fea-411a-834f-06dd7ea3aeb5.png)
