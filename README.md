#Cross Browser Video

[Live Example](http://www.galengrover.com/projects/Cross-Browser-Video/)

##A cross browser video implementation written in pure HTML and CSS that supports the following browsers:

 - Firefox 3.5+
 - Chrome 3.0+
 - Safari 3.1+
 - Internet Explorer 6+
 - iPhone, iPad
 - Opera 10.5+
 - Konqueror 4.4+
 - Epiphany 2.28+

###Flash player

This uses the free version of the [JW Player](http://www.longtailvideo.com/players/jw-flv-player/), which is free for non-commercial use (or $89 per domain).
 
More Flash players options:

 - [FLV-Scrubber](http://www.topfstedt.de/weblog/?page_id=208) Free for non-commercial. $50 per domain.
 - (Flowplayer](http://flowplayer.org/download/index.html) Free, but a flowplayer watermark is dispalyed. $95 per domain.
 
Demos for each flash player are included in index.html.

###Encoding

For a mac I recommend [Miro Video Converter](http://www.mirovideoconverter.com/). It can convert into all format except FLV. For FLV conversion I use [Quick Media Converter](http://www.cocoonsoftware.com/) on a PC.  Quick media converter can convert to and from all formats of video.

##Server setup

You need to make sure your server returns the correct mime types.

**Apache:**

Add this to your .htaccess file

    AddType video/ogg  .ogv
    AddType video/mp4  .mp4
    AddType video/webm .webm

**IIS**

 - Open IIS Manager and right-click your server.
 - Click *MIME Types…*
 - Add the mime types to the list
