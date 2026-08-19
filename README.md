 ----------------------
| PROJECT YORHA-SERVER |
 ----------------------
-------------------------------------
My Personal Home Lab Server Project
-------------------------------------
--------------------
Yorha-Server Specs:
--------------------
CPU: i5 7200u

GPU: Intel HD 620

Ram: 12gb DDR4 2400mhz

----------
Storage: 
----------
   128gb SATA SSD
         
   1Tb External Hard Drive
   
--------------------
Home Lab Services:
--------------------
---------
 Pihole:
--------
Network Wide DNS filtering and adblocker

   -Acts as a DNS Server and DNS sinkhole
   
   -Blocks Domains,configured to block domains that serve ads and tracking domains
   
   -Runs in a docker container

----------
Jellyfin:
----------
Self hosted Media server for streaming shows and movies

   -Local Library from the server 
  
   -Can stream media from the server files via Client or Web
  
   -Files are mostly configured in HEVC.265,AAC,SSA/ASS 
  
   -Runs in a docker Container

-----------
 Tailscale:
-----------
Uses the Wireguard protocol for end to end encryption and acts as a mesh P2P network (tailnet)

   -Used for remote access to Pihole and Jellyfin services
   
   -Configured the server to have an exit node for the option of internet traffic going through the server for remote users
  
   -Provides tailscale IPs for every device connected in the Server's tailnet

  
