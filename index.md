# Galoga Bootstrap Boilerplate
> #### Version 3.20.1
> #### Date : 2020-01-26

## Welcome to the configure page
### Introductions
This configure instruction will take you through how yo configre the boilerplate to your tailored needs.

### First things first
When you have downloaded and opened the zip file, it will it contains the following:

![File layout map](site.png)

### Deployment 

1. Move all content in the folder <code>/public/</code> to the public folder of your webserver 

2. Move the folder <code>/includes/</code> next to the public folder of your webserver - this is to have all the files that run the site seaparate from the content part. Safe and sound!

### Where it all starts
1. Configure the variables in the settings file called:

<code>/public/settings/settings.inc.php</code>

2. Add content to the main content page, this has a placeholder function out of the box - that is easily removed. Just open the file and follow the instructions. 

<code>/public/content/index.inc.php</code>

### Pages and templates
All pages are called via the <code>/public/index.php</code> in the public folder. Don't touch this file!

All contents file are to be saved as <code>file-name.inc.php</code> and must be placed in the <code>/public/content/<code> to work properly.

Pages template are avaialbale in <code>/public/content_templates/</code>

