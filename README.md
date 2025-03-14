# Basic command lines and how to navigate files using the text interface

The command prompt, or CMD, is a vital source for troubleshooting basic issues in the IT help desk industry so its essential to know some key every day commands by heart and how to navigate. You can open the CMD by typing in command prompt or cmd in the search bar of your start page on the bottom left of your desktop or by clicking the windows key + R 

<img src="https://sigmawire.net/i/03/3PvmZA.png" height="40%" width="40%" alt="VirtualBox set up wizard"/> 

  <H> Need to know commands </H>
  
   - <b> Ping </b>
        - Tests the network connection of a machine. Mostly used for the first step of troubleshooting when there is an issue with network connections
          
   - <b> nslookup </b>
        - After typing the command and then pressing enter, you will be able to check the DNS records to verify it is working properly 
    
   - <b> ipconfig </b>
       - This command is great for showing the overall configurations of your machines network connections including wireless adapters, bluetooth, and ip address
  
   - <b> getmac </b.
        - Using this command does exactly what it say. It displays the mac address for the current machine
  
   - <b> systeminfo </b>
  
       - Similar to ipconfig this displays information om the machines connections expect it is more in depth on the OS, hardware, boot time and more
   
   - <b> sfc/scannow </b>

       - Sfc, or system file checker, is primarily used to scan the files when there is a sudden issue such as the blue screen of death or other sudden crashes. This command will go through the files and repair if needed/possible. You can also use sfc/verifyonly if you want to just do a scan and not a repair just yet
   
   - <b> chkdsk </b>

        - Similar to the sfc command, this command checks the files except primarily on hard disks
    
   -  <b> arp-a, arp -d </b>

        - Otherwise known as address resolution protocol, this command modifies the cache for arp interfaces. The arp -a command, specifically displays the actual cache while the arp -d actual deletes it. This is usful for when you are having network issues or if there is an issue with ARP spoofing

   - <b> winver </b>
   
        - This command is used to display the verison of windows on your machine

   - <b> netstat </b>

      - The netstat command shows all port connections with TCP and IP information included, as well as all active network connections
     
   - <b> tracert </b>

       - Used for network troubleshooting, this command will track the packets and the hops it takes from the source to the destination. This would be used best when testing the speed of a network if you are having issues

   - <b> route print </b>

       - When a machine has mutiple network cards it can be hard to track which route it is taking. This command will map out the entire route including the destination, netmask, gateway, and more

   - <b> tasklist taskkill /(pid number) /f </b>

       - Similar to the task managers GUI, this command will display a numorus of tasks and processes being performed on the machine. To end the task, use the taskkill command

   - <b> gpupdate/gpresult </b>

       - When you need to update a policy on mutiple people in a group, it is easiest to use this command and use the gpresult command to verify your changes 

   - <b> rsop </b>

       - Thus command can be usful when picking up where another help desk left off. It shows the current group poloicy settings and it requires you to run it as admin so it is also a little tighter on security as well

   - <b> dcdiag </b>

       - If you are the administrator, it is important to know this command so you are able to verify the condition of your domain controllers and making sure they are healthy

   - <b> net stop, net start </b>

       - This basic command is used to start and stop windows services. It is very useful in situations such as when the printer will not stop, you can use the net stop spooler command, so you can troubleshoot the issue better

   - <b> shutdown, shutdown /r shoutdwon /d </b>

       - As the name suggests this will shutdown the machine. Very useful if you are having issues with the GUI or are booted in safemode. Using the /r will restart the machine and using the /d will show you the shutdown logs

   - <b> cls </b>

        - This basic command is used to clear the screen should you need to get rid of clutter or sensative information

   - <b> hostname </b>

        - This will display the name of the machine you are currently on

   - <b> dir </b>

        - This displays the directory, very useful for navigation should you need to access files from the cmd

   - <b> cd </b>

        - This is used to changed INTO a directory. For example if you are going from users into photos in the users files 

   - <b> .. cd </b>

        - To get out of that directory you moved into, type this command followed by the name to exit out of it
          
   - <b> rmdir </b>

        - Using this command will actuall remove that directory, if it is empty already        

   - <b> robocopy </b>

        - This command will copy all of the files and folders to a new location such as a new drive or server, essentially a better xcopy, which is mainly used for folder to folder

   - <b> del </b>

        - If there is a file or folder you need to delete in order to remove a directory, use this command followed by the name of what you need deleted

   - <b> format </b>

        - When you need an entire storage such as a hard drive or usb, this will get it done. Just type format, follwed by a space wuth the drive and file system

   - <b> exit </b>

        - This will close the CMD
          
   - <b> help </b>

       - If you are unsure or need more information, this will display some defualt commands that may assist
      
    
  
