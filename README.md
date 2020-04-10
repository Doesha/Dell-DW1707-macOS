# Dell DW1707 NGFF WiFi Card

Device Properties:

		Atheros AR9565 802.11b/g/n
		PCI Express 2.0 x 1
		Device ID: 168C-0036
		Subsystem ID: 1028-020E
		Device Class: 0280 (Network Controller)
		

Installation:

		There is no need to install in S/L/E or L/E as Opencore and Clover can both inject these two kexts leaving macOS libraries as untouched as possible. I saw no difference with performance between leaving them in one or the other. 
        
Compatability:

          10.12 (Sierra) - 10.15.4 (Catalina)

Requirements:
  
		Lilu.kext 
          IO80211Family.kext
          ATH9KInjector.kext

Issues:

		- Cosmetically I notice the WiFi signal tree will randomly drop down to one or no bars and randomly full strength. Allthough this happens I saw no performance drops when this happens.
		- Tx/Rx speed is moderate at best. Some claim 75mbps and others claim 11mbps, and honestly its the cheapest option for NGFF wireless that will work with macOS that I have found. 






