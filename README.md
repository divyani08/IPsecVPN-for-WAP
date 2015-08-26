# IPsecVPN-for-WAP

                                                                      IPsec S2S VPN for WAP

The VM name is DIVYANI-TEST-VPN (10.235.151.78)
The Virtual Network created on WAP portal is S2S-BLR and S2S VPN is S2S-VPN.
STEP 1:
Creation of  network with S2S VPN on WAP portal.
 
VPN Gateway-  10.235.151.78 (Private  IP of VM)
Address Space- 10.240.135.76 /30 (VM IP segment)
STEP 2:
Configure the network  S2S-BLR on the VMM Console by creating a logical switch and IP Pool for the same network.
 





STEP 3:
Configuration on firewall.
PHASE 1 Configuration:
 

PHASE 2 Configuration:
 
STEP 4:
Map the configuration in the VM Manager for the Virtual Network created on the portal.
 
 
The authentication parameters is same as that on the firewall.

















                                                                                



