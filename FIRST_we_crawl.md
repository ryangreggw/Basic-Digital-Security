## END-POINT USER SECURITY
### #1: ROUTERS
- ***PHYSICAL INSPECTION***
  - Always begin with a physical inspection of cables, ports, various plug-ins. With regards to a router, ensure that the power supply unit (PSU) is plugged in all the way to the device/wall outlet and that the antennas are screwed in completely.  
- ***PASSWORDS***
  - A great place to start when enhancing personal security/privacy is your router. The router is an access point (AP) that connects your personal devices to your modem which subsequently connects to your internet service provider (ISP). A router with default configurations is a point of failure when addressing personal security. Some configuration changes that will increase your security are the following:
      - Change the router's default password. There are files on the internet that contain all of the various routers' default passwords. These can be easily manipulated with a password cracker such as hydra, john the ripper, burpsuite, etc.
    
![time to crack a password](https://github.com/ryangreggw/Basic-Digital-Security/assets/25268281/10863685-7b97-44e6-8e8e-c8df1dff4bdb)

- ***SSID***
  - Hide your service set identifier (SSID):  
    - There are numerous routers on the market and each one will take a different path to the SSID settings. Typically it will be under basic wireless settings. By disabling SSID, you mask your router from public view. It will not show up when people are searching for a wireless access point (WAP).
      
![cisco ssid](https://github.com/ryangreggw/Basic-Digital-Security/assets/25268281/56d603d0-410c-45b5-b302-427898414f9b)

### #2: COMPUTER SETTINGS
- ***BITLOCKER***
  - BitLocker comes on recent editions of Windows Operating System (OS) by default. The key features of BitLocker for our purposes are: Full-Disk Encryption (FDE; provides comprehensive protection against unauthorized access to your data at rest.), Pre-Boot Authentication(before your O/S loads, BitLocker requies the user to provide authentication credentials. This ensures the user accessing the system is authorized.), Recovery Keys (Recovery Keys are provided incase a user forgets their password/personal identifiable number (PIN).), and overall **Data Protection**.
  - BitLocker Set-up:
    - On Windows 11, right-click the start button (windows icon) on your task bar.
    - Scroll Down to "Related." Click on BitLocker and follow the task wizard.
      
 ![bitlocker1](https://github.com/ryangreggw/Basic-Digital-Security/assets/25268281/33650c6e-fd87-4246-979a-c48f09602cbc)

![bitlocker2](https://github.com/ryangreggw/Basic-Digital-Security/assets/25268281/86c4deac-123c-4061-8f46-7a02cab9682e)

- ***DISABLING AUTO-PLAY FEATURE FOR PLUGGED IN DEVICES:***
  - By default, your computer will come with the "auto-play"  for all media and devices feature enabled. This poses a vulnerability to your system because someone could plug in a universal serial bus (USB) that contains malware (Trojans/Worms that can spy, steal sensitive data, gain remote access, and log keystrokes.)
  - https://www.cnet.com/tech/mobile/pegasus-spyware-and-citizen-surveillance-what-you-need-to-know/
  - In order to disable auto-play:  
    I. Type "control panel" into your search box on your taskbar.  
    II. You will now be in your control panel. On the right side of the control panel box, change the "view by" setting to "Small icons." The first setting in the first column should be "AutoPlay."  
    III. Click on the box next to "Use AutoPlay for all media and devices" to disable to feature.
    
![control panel](https://github.com/ryangreggw/Basic-Digital-Security/assets/25268281/6f7f999a-e2b8-4696-bf7a-00b07c397533)
![autopplay](https://github.com/ryangreggw/Basic-Digital-Security/assets/25268281/beabc55d-94f6-4425-914f-2ddc81c7f903)

browsers, vpns, disabling guest account, blocking ports: (21 -ftp, 23 - telnet, 80 - http; 3389 - rdp; 2323 - ?), disable WPS on devices connected to your network.


