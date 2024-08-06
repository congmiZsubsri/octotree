# To Find A Driver For This Device Click Update Driver
  
So, I had to install a new Power Supply for my PC a couple days ago because my PC wouldn't start. After I had life again and thought all was good, I immediately noticed I was unable to connect to my wired internet.
 
**DOWNLOAD >> [https://onsowinmu.blogspot.com/?um=2A0Tbv](https://onsowinmu.blogspot.com/?um=2A0Tbv)**


 
I went to device manager and noticed my ethernet device wasn't even listed under network adapters but now under other devices as "ethernet controller". When I clicked on it, I was met with the following device status: -The drivers for this device are not installed. (Code 28) -There are no compatible drivers for this device. -To find a driver for this device, click Update Driver.
 
I tried troubleshooting multiple times through windows but when I followed their steps and restarted my PC, still nothing changed. Then, I went to Intel forums, videos, and websites supporting my issue and went through various guided steps to try and solve this.
 
After installing the latest version of Intel Ethernet Adapter Complete Driver Pack and many hoops and bounds later, I went back into device manager and noticed my ethernet device was now showing under network adapters as "Intel(R) Ethernet Controller (2) I225-V".

In device manager, I attempted to automatically install the driver through windows and it would not work being unable to find a compatible driver. I also tried manually installing it and choosing a driver and was still unsuccessful.
 
After enabling/disabling my ethernet device, trying the steps over and over again, trying to install an older version of the driver, updating my BIOS, made sure my ethernet cables were stable and good, and going down tons of rabbit holes, I end up where I started with the same device statuses.
 
2. I don't know what caused my last power supply unit to fail. I was able to power on and operate my PC the night before like any typical night, but the next day it wouldn't power on at all after trying a different power cord, outlet, etc.
 
When I go into device manager and attempt updating the driver with the file I extracted from the Intel Ethernet Adapter Complete Driver Pack zip file I downloaded, I am met with this screen (image applies to both searching automatically for drivers, and browsing my PC files for driver.
 
I also made the discovery that when I click on "Let me pick from a list of available drivers on my computer", and choose any of the listed Intel driver devices to try and install, I am met with the same (Code 10) this device cannot start. Additionally, now my device name of "ethernet controller" moves from the other devices tab to under the network adapter tab and matches the name of the driver device tried installing prior as you can see in this image:
 
So I went to your link and downloaded and extracted the zip file of "Intel Network Drivers" version 26.2.0.1 under the subcategory "LAN Drivers". I auto ran the app and attempted to install it was met with this screen:
 
Since you are using MSI product, with embedded NIC, contact MSI support for further assistance. They may be able to provide additional troubleshooting steps or even replace the motherboard if it is found to be defective.
 
Please be informed that we will now close this request since we haven't received any response from our previous follow up. Just feel free to post a new question if you may have any other inquiry in the future as this thread will no longer be monitored.
 
Intel does not verify all solutions, including but not limited to any file transfers that may appear in this community. Accordingly, Intel disclaims all express and implied warranties, including without limitation, the implied warranties of merchantability, fitness for a particular purpose, and non-infringement, as well as any warranty arising from course of performance, course of dealing, or usage in trade.
 
I have uninstalled previous successful installatin of drivers and rebooted. Reason I had to reinstall everything was because I was running a double nat setup and for some reason I could not get my hardwired device with the router to communicate with the printer.
 
Update - called back in. One hour wait but it was worth it. Got another tech named Cory who had me up and running in about 15 minutes. Two things additional things he tried. One - drop the all in one installer (in my case "MF731CMFDriverV5401W64usEN") into the root of your C drive (aka "C:\") and install from there with admin privileges through Windows explorer (right click/run as admin). Two - I think more importantly what did it. There is a program in the "misc" folder (whether you are in the x32 or x64 folder). The file is called, " UNINSTAL.exe" Yes it has one "L." Run that as admin. It should wipe out any traces of old files and registry entries from previous installs. Final thing to download as a bonus if you are using the scanner. Program is called, "[Windows 32bit & 64bit] MF Scan Utility Ver.1.9.0.0." You can download it from the software tab.
 
After one or more unsuccessful printer or driver install attempts, it possible for windows to retain incorrect settings, such as TCP/IP port or WSD information making these resources unavailable to the driver when it tries to install.
 
Last step, software doesn't always remove every piece of a device's installed configuration. You can go a step further and delete the port or WSD information from Device and Printers > Propertes > Ports tab as well.
 
This is a great tool - MS Install / Uninstaller Utility Completely safe, from microsoft and specific for windows. Is similar to the old Revo uninstal utility, but differs in that it corrects installation problems in addition to removing orphaned registry entries.
 
Thank you for the tips. I just spent 75 minutes on the phone with Canon support and the rep had no idea how to fix the problem. Wen't to print managment and removed any instances of Canon. Disabled firewall and antivirus. Tried installing with admin privileges (even though I already had them. Tried installing just the scanner driver. Same error every time with that all in one installer. Nothing helped.
 
No question all of my computers can see the printer on the network. I can put in the IP address and the setup program finds the printer. I don't think lack of a static IP is the issue. The second router (the onhub) is wired behind the Netgear Nighthawk 7000 on a different subnet.
 
The problem is that every time I try the install with the "all in one" program, I immediately get the above message (could not install print driver). After getting off with Canon support, I tried downloading just the print driver ("[Windows 64bit] Generic Plus UFR II Printer Driver V2.10") and it installs. I was able to print a test page.
 
Thanks Rick for showing me where to find the ports section. I don't remember from all the installs and uninstalls of the drivers, but at one point I would see the device listed but there was no way to select properties (I was looking to see if I could print a test page). Anyway, thanks again for your help. Do you work for Canon? If not, they should put you on the payroll.
 
I've got an old laptop (2nd gen i7) with a fresh install of Windows 10 Pro 21h1 that I'm using in my new workspace to get back into tinkering, which I haven't done in several years. I know I need to install the driver for the CH340 controller to work properly, but I can't seem to install it. I've downloaded several times from multiple sources. The installer will launch, but when I click the install button I get "Driver install failure!"
 
I've tried compatibility mode and disabling driver enforcement (as recommended on this forum as far back as 2017), but nothing is working. I also tried on my main PC (also newer than the last time I tinkered with an Arduino) and it's also failing here with the same nondescript error.
 
I suspect Microsoft's recent over-enthusiastic "protect users from themselves" Apple mentality is to blame. I've had other issues with programs being blocked with no option to unblock them in the past few months leading to large amounts of frustration.
 
I apologize if this has been recently covered. But, I've searched quite a bit (over the last 2 hours) and I keep winding up on the same threads from 4 years ago, nothing more recent is coming up & those solutions are not working.
 
Where did you get the driver? I recommend always using the one from the CH340 manufacturer's website:
 \_EXE.html
(click the cloud with a downward pointing arrow button)
I believe they also have an English language version of the website at wch-ic.com, but I haven't found the time to investigate that option, so I am still recommending the original wch.cn site as the best source for this driver.
 
Just as an experiment, I grabbed an even crappier old laptop and installed Windows 10 1903 and the driver installed just fine. It seems the problem lies in newer versions of Windows 10 as I suspected.
 
I had not, but I just gave it a try and had the same problem as you. I actually think I have only ever used the driver installer once. I always use the .zip file and install the drivers via Windows Device Manager because some driver installers also install additional applications to manage that device and I only need the driver itself in this case.
 
Hi @k9tr. You can try running the .exe file that is in the unzipped driver folder. This is an installer provided by the chip manufacturer. I haven't had any success with running that (even though the procedure I describe above works perfectly for me), but another user reported that the manual driver installation via Device Manager did not work for them, but running the installer did work. So it's worth a try.
 a2f82b0cb4
 
