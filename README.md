j05-plugin-genenal-pgb-helloworld
=================================

Just trying to see if we can test if a plugin is working using phonegap Build on Android



Just made a major discovery with phonegap build April 15, 2014.

The camera plugin does not work, if I remove the line written:

script type="text/javascript" charset="utf-8" src="cordova.js"

note:

the line could also say phonegap.js instead of cordova.



 Normally with phonegap build you do not have to include that line, but I guess since to use plugins you have to have a config.xml file and the config.xml file probably takes place of the auto injection of the phonegap.js file.
 
 
 That cost me hours and hours of headaches.








************************************************************************************************************

###Disclaimer: I spend my time getting complex things working in simple ways. I have no idea if I am doing anything correctly so please beware if you use my work. If you like this App and can hum, play or sing please help the musically illiterate, use a flash capable computer to add your favorite song at http://www.rocksetta.com 
