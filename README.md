# Microsoft-Windows-Defender-and-Firewall

## Objective

In this project I review Windows Security Virus and threat protection, update threat definitions, and run Windows Defender Antivirus quick scan in order to detect or verify any threar analysis in the system or the device.


### Skills Learned

- Microsoft Windows Defender.
- Windows Firewall. 

### Tools Used

- Microsoft Defender Antivirus: Understanding how to configure, manage, and use Microsoft Defender Antivirus is a fundamental skill for protecting Windows systems from malware and other threats.
- Windows Defender Firewall: Learning how to configure and manage the built-in firewall in Windows for network security purposes.

## Steps
Problem: Run a custom scan that only scans the files in the Downloads folder.

<p align="center">
Access and review Windows Security Virus & threat protection where is a built-in security feature that scans for threats on our system. In this same window we accesss to the scan options so we can guarantee a custom scan<br/>
<img src="https://i.imgur.com/aJSsEul.png" height="80%" width="80%"/>
<br/>
<br/>
In the scan options window I select the custom scan so it can realize the scan needed in the specific file<br/>
<img src="https://i.imgur.com/Bo5LKlN.png" height="80%" width="80%"/>
<br/>
<br/>
I select in this case required the Donwloads folder to do the scan for threats or any suspect file<br/>
<img src="https://i.imgur.com/gcVkY9g.png" height="80%" width="80%"/>
<br/>
<br/>


Problem 2:  Use Windows Defender Firewall with Advanced Security to block Windows Remote Management on the Public network.

<p align="center">
As we select Advanced settings on the Firewall & network protection screen. Here there is an Overview in the center panel. Inbound rules: Inbound rules determine what traffic is allowed to the computer.  Note that some of the rules have a green checkmark next to them. This indicates that the rule is enabled to allow inbound communication. The rules without a checkmark are available for use but are not enabled.
<br/>
<img src="https://i.imgur.com/UiAjgH6.png" height="80%" width="80%"/>
<br/>
<br/>
I select the Windows Remote Management inbound rule in the Overview panel of Windows Defender Firewall with Advanced Security.
<br/>
<img src="https://i.imgur.com/fb7jToO.png" height="80%" width="80%"/>
<br/>
<br/>
Because we want to allow communication only with the domain and private networks, For Public this box should not have a checkmark.
<br/>
<img src="https://i.imgur.com/p0yBypW.png" height="80%" width="80%"/>
<br/>
<br/>
Made an inbound rule that blocks communication with the public network. Since the new rule will be similar to the last, I copied the existing rule. Since we want to block connection with the public network, I selected Block the connection on the General tab.
<br/>
<img src="https://i.imgur.com/Jh2qKRc.png" height="80%" width="80%"/>
<br/>
<br/>
In the Advanced tab I put the checkmark in the Public only 
<br/>
<img src="https://i.imgur.com/mBwtml3.png" height="80%" width="80%"/>
<br/>
<br/>
Now it appeared a green checkmark appears next to the first rule indicating that the rule allowing communication is enabled. A circle with a line through it appeared next to the second rule indicating that the rule blocking communication is enabled.
<br/>
<img src="https://i.imgur.com/fqqpMnh.png" height="80%" width="80%"/>
<br/>
<br/>
