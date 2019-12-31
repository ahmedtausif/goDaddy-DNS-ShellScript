# goDaddy-DNS-ShellScript
Shell script to help update DNS. Can be scheduled in Task Schedular for automatically updating DNS.

This script is used to check and update your GoDaddy DNS server to the IP address of your current internet connection.
First go to GoDaddy developer site to create a developer account and get your key and secret
### https://developer.godaddy.com/getstarted
Be aware that there are 2 types of key and secret - one for the test server and one for the production server. Get a key and secret for the production server

# Scheduling
In schedular you can do following action:
### GoDaddyDNS.sh YourDomainzToUpdate
