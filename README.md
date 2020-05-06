Put all your extra stuff in .gitignore and make sure its all in the right folder and you should be good to go

**For those of you who aren't github masters, or want an easier way of downloading the pack, simply follow the guide below.**

NOTE: this assumes you've already downloaded and installed 1.12.2 forge version 14.23.5.2847 from http://files.minecraftforge.net/maven/net/minecraftforge/forge/index_1.12.2.html

STEP 1: Download the pack
  
- go to https://github.com/bkepps/MingherafRelease and click the green button on the right side, then from the dropdown click download zip.   

NOTE: for those of you who are very saftey-conscious the link is to my github page, I'm the only one maintaining it so it's safe
	
	
STEP 2: Extract from zip and put in .minecraft
	
- If you have windows, right click the file you just downloaded and click "extract all" 
- next, "extract" and put the MingherafRelease-master folder inside the MingherafRelease-master folder in your .minecraft folder.
	
	
STEP 3: Create a new minecraft installation
	
- open the minecraft launcher, go to installations then new. 
- Type whatever you want to call this pack where it says name. 
- Under version scroll to the bottom, click on release 1.12.2-forge1.12.2-14.23.5.2847. 
- Under game directory click "Browse" navigate to AppData\roaming\.minecraft\MingherafRelease-master, click "ok".
- click more options and under where it says JVM Arguments, replace what's there with the following: 
	"-XX:+UseG1GC -Xmx4G -Xms4G -Dsun.rmi.dgc.server.gcInterval=2147483646 -XX:+UnlockExperimentalVMOptions -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M".

NOTE: this is purely to allocate more memory to minecraft so it can acctually launch with the pack. If you want to use more or less you can change the numbers in -Xmx4G & -Xms4G

- Finally, click create.


Step 4: Play!

- click on the thing to the left of the play button and select the instalation with the name you typed earlier and hit play
