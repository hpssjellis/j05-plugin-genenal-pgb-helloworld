j05-plugin-genenal-pgb-helloworld
=================================

Just trying to see if we can test if a plugin is working using phonegap on Android



Just made a major discovery with phonegap build April 15, 2014.

If I remove the line
<script type="text/javascript" charset="utf-8" src="cordova.js"></script>

when using the camera plugin, then the plugin does not work. Normally with phonegap build you do not have to include that line.
