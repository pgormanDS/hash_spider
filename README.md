# hash_spider
A module for CME that spiders hashes across the domain with a given hash.

# Setup
Simply copy the hash_spider.py module to your CME module folder. Requires access to a BloodHound database configured in ~/.cme/cme.conf. Please see the included example.

# Usage
Run CME against a PC your user has local admin access to and call the hash_spider module.
```
cme smb <IP> -u <user> -p <password> -M hash_spider
```
![image](https://user-images.githubusercontent.com/86318031/152021215-c5a7fc48-5428-45ce-a87f-552efb54acae.png)
