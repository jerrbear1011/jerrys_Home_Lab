## PiHole
# Purpose 
    - provide DNS services 
    - filter out common ad/tracking domains 
    - allows monitoring of DNS

# Issues 
    - Runs on a single pi, if it goes down my netowrk goes down 

# deployment
    - Host: RaspberryPi
    - OS: Raspbian

# Config
    - upstream DNS: google 8.8.8.8, and xfinitys 75.75.75.75
    - filters out common ad/tracker Domains using lists from github



# to do
    - add redundancy  to the pi
    - migrate to a centralized VM 
    - add a fail over in the event my local dns goes out devices can still reach the internet/ use public DNS
    - automatic backups 