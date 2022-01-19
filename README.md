# load_image
This playbook copies Cisco IOS image from TFTP Sever to the switch
It also verifies the MD5 hash 
MD5 hash from the cisco website needs to be provided for reference.
I have tested this on Cat-4510 and Cat-3850 swtitches
Please note Cat-4510 uses bootflash, whereas Cat-3850 uses flash.
So the command under ios_command task needs to be adjusted accordingly

