#FCP #Coursework

# The story

The Story 
-   Name 
	-   Faye Keide 
-   Fake IDs (for bunnies) 
-   Also addicted to meth (but as a side gig) 

-   Has eemail conversations with kids about payment and stuff 
    
## Search sequence:
-   What type of foil is used for ID holographs 
-   Computer generated holograms 
-   Hybrid holograms
-   Reflection holograms 
-   Reflection holograms buy in bulk 
-   Fake ID buy and sell 
-   Click on various websites 
-   Pizza 
-   Dominoes 
-   Plain plastic cards 
-   Custom card making service 
-   Custom PLASTIC card making servivce 
-   Make your own custom plastic identity cards 

## Pen Drive? 

Maybe make it encrypted with the password stored in some file slack or something, include some images  

## Emails 
-   Mbox file to be found, gonna have to set up a couple of fake email addresses 
-   can be made using google takeout

## Steg 
-   Audio 
	-   change the waveform to contain data 
	-   Implant data in the actual audio 
-   Image 
	-   Have the password be in the image in plain sight and send it to your partner saying heres the password 
	-   Hidden in plain sight
-   Video
	-   Is essentially the other two combined, could be pretty tricky

## __Recycle Bin__ <-- important
- put stuff in and delete it
- then put more stuff in and dont delete it
![[Pasted image 20211015224027.png]]
![[Pasted image 20211015224147.png]]

## Thumbnail files
![[Pasted image 20211015224748.png]]

## Onedrive
<em>"What this means for the end user is that he or she could have a computer with  
only 256 GB of storage and still be able to browse a directory of OneDrive folders that contained 1 TB of data.  
This also means that logs for OneDrive would reference folders that weren’t physically on the computer"</em>

![[Pasted image 20211015225148.png]]
	
TraceArchive.ETL and TraceCurrent.ETL are logging files analyzing the file in notepad seems to work for rudimentary forensics.  
Below is a screenshot of the contents of the ETL file which references files that are stored only on OneDrive and not physically stored on the device.

![[Pasted image 20211015230358.png]]
	
## Logs
- Prefetch (superfetch)
	- These files store the following information:  
		• File path of all files accessed by the application during the first 10 seconds of running  
		• Number of time the application has been run  
		• The last time the application was run  
		• Any volumes or folders that were accessed

	
## Edge
	- would go here but our version doent have edge yet
	- actually contawins quite a lot, including cached pages

## Facebook
- windows  10 app is like really really good for this, but has been discontinued

## USB activity
``HKLM\System\CurrentControlSet\Enum\USBStor`` still stores artifacts related to USB devices connected to the  computer.

## Link files

https://github.com/ged/linkparser