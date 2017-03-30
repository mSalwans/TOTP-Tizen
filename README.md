# TOTP-Tizen
TOTP client for Tizen (Gear S/S2)

# Setup
 1. Find 'one time password' in GalaxyApps and Install this.
 1. You need create key info "auth_keyinfo.txt" like following:  
  Service1:Account_A:JBSWY3DPEHPK3PXP  
  Service2:Account@B:JBSWY3DPEHPK3PXP  
  Service3:AccountC:JBSWY3DPEHPK3PXP  
  ....
  
  Service1/2/3 is service name (eg. Google/Microsoft)  
  Account?? is account in service. (eg. your@mail.com)  
  JBSW... is TOTP secret key.  
  service name/ account is just label. It is not related to the calculation of TOTP.  
 1. Push the file to GEAR://documents/auth_keyinfo.txt 

# Gear S
 You can copy to "documents" folder from PC via USB 
 
# Gear S2
  You *CANNOT* copy to "documents" folder from PC via USB  
  You need a utility such as Filesmaster.


# For Gear S2 v1.1
This is not yet release GalaxyApps

It added a place where auth_keyinfo can be placed.

 1. copy auth_keyinfo.txt to GEAR://documents/
 1. copy auth_keyinfo.txt to GEAR://downloads/
 1. copy auth_keyinfo.mp3 to GEAR://music/
    1. rename auth_keyinfo.txt to auth_keyinfo.mp3 (Change only the file name, do not change contents)
    1. push it as music data by GearManager 
