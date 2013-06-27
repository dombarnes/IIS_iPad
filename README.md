# IIS iPad Distribution
This is a simple tool to allow you to distribute enterprise or beta iOS apps via an IIS web server

## Requirements:
• Windows Server 2007 and IIS 7
• .ipa file created in Xcode
• .mobileprovision file from the Apple Developer Portal

## Installation
There are already loads of tutorials on creating an IPA file for beta distribution. Follow one of those to get your file.

1. Create a new site or a subfolder on your IIS server
2. Clone this repo into that folder
3. Drop in your .mobileprovision and .ipa files
4. Edit the manifests.plist file with the full path to your IPA file, bundle ID and 
5. Edit the index.php file with your two file names and customise the title, h1 and paragraphs to fit
6. Add your own CSS to style.css

## Additional Info
I use [Twitter Bootstrap](http://twitter.github.io/bootstrap/) in my setup just for some added niceness. Just follow their instructions to use.  

Then you just need to browse on your iPad to the server address and follow your own instructions.