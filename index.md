# Galoga Bootstrap Boilerplate
> #### Version 3.20.5
> #### Date : 2020-05-23

## Welcome to the configure page
### Introductions
This configure instruction will take you through how yo configre the boilerplate to your tailored needs.

### First things first
When you have downloaded and opened the zip file, it will it contain the following:

**/includes**  
&nbsp;|-- -- /controller  
&nbsp;|-- -- /class  
&nbsp;|-- -- /model  
&nbsp;|-- -- /vendor  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- -- /Parsedown  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- -- /PHPMailer  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- -- /phpqrcode  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- -- /TCPDF  
&nbsp;|-- -- /view   
&nbsp;|-- -- .htacess  
&nbsp;|-- -- autoloader.inc.php  
&nbsp;|-- -- version.inc.php

**/public**   
&nbsp;|-- -- /content  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- -- /footer  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- -- /markdown  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- -- **/templates**  <=  Step 5  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- -- **index.inc.php**  <=  Step 4  
&nbsp;|-- -- /css  
&nbsp;|-- -- /files  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- -- /downloads    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- -- /uploads     
&nbsp;|-- -- /images.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- -- /favicon    
&nbsp;|-- -- /services  
&nbsp;|-- -- .htacess      
&nbsp;|-- -- index.php  
&nbsp;|-- -- **settings.inc.php** <=  Step 3
### Deployment 

Step **1.** Move all content in the folder <code>/public</code> to the public folder of your webserver 

Step **2.** Move the folder <code>/includes</code> next to the public folder of your webserver - this is to have all the files that run the site seaparate from the content part. Safe and sound!

### Where it all starts
Step **3.** Configure the variables in the settings file called:

<code>/public/settings.inc.php</code>

Step **4.** Add content to the main content page: 

<code>/public/content/index.inc.php</code>  

This has a welcome placeholder function out of the box - that is easily removed.    
Just open the file and follow the instructions. 



### Pages and templates
All pages are called via the <code>/public/index.php</code> in the public folder. Don't touch this file!

Step **5.** Pages template are avaialbale in <code>/public/content/templates/</code>

All contents file are to be saved as <code>file-name.inc.php</code> and must be placed in the <code>/public/content/</code> to work properly.


