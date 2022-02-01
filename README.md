# hash_spider
A module for CME that spiders hashes across the domain with a given hash.

# Setup
Simply copy the hash_spider.py module to your CME module folder. Requires access to a BloodHound database configured in ~/.cme/cme.conf. Please see the included example.

# Usage
Run CME against a PC your user has local admin access to and call the hash_spider module.
```
cme smb <IP> -u <user> -p <password> -M hash_spider
```
<img width="1366" alt="hash_spider" src="https://user-images.githubusercontent.com/86318031/152021343-279343e9-3bc2-4def-91ec-f876b6a15f0c.png">
