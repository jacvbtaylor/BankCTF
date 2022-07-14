# BankCTF by jacvbtaylor


#  I created this CTF with the intent to help individuals who are wanting to learn how to hack but do not have any experiences doing so. 

# You will need access to an attacker virtual machine in order to investigate agaisnt this CTF machine. 
# If you aren't sure how to do that, follow the steps here: 

# https://www.youtube.com/watch?v=wX75Z-4MEoM&ab_channel=NetworkChuck




#               [!!!!] IMPORTANT [!!!!]
#    If you have both machines running but you cannot locate the IP for the CTF machine in STEP 2, 
#   try changing the network settings on your VM's. 
#   You should not have any issues if both are running on bridged mode



# Bank CTF has a detailed guide/walkthrough for players that get stuck or are brand new to CTF's
#        & was created with a beginner's approach in mind to capture 6 flags. 
 
# The objectives are to:
#   Download the CTF machine 
#   Locate it on your network via Nmap
#   Find open ports
#   Run dirb to find secret website pages
#   Use hydra to bruteforce a website login
#   Bruteforce SSH login
#   Escalate privilegs
#   Exploit a program to dump /etc/passwd 
#   Create a wordlist using crunch
#   Become root

#                          ~~~~~INTRO~~~~~~~
#Roger at work mentioned a new bank opening up in one of the small towns in your area. 
#He said someone had reached out to him about designing their website but he declined 
#because the pay was going to be too little and said whoever ends up building the site 
#probably won’t know what they are doing. 

#You decide you want to check out the site and look for some vulnerabilities...
#                  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


# Goodluck!



