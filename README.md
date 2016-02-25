Fancin
===

Fancin is a theme for nginx' fancyindex module, bootstrap is used in this Fancin. More info about this can be found [here](https://github.com/aperezdc/ngx-fancyindex).

This project is modified on [Nginx-Fancyindex-Theme](https://github.com/TheInsomniac/Nginx-Fancyindex-Theme)

[Demo](http://mirrors.opencas.org)

#####Usage:
 - Compile nginx with the fancyindex module.
 - Include the following config to your nginx conf.
 		
 		fancyindex on;
 		fancyindex_localtime on; #on for local time zone. off for GMT
    	fancyindex_exact_size off; #off for human-readable. on for exact size in bytes
    	fancyindex_header "/fancin/header.html";
    	fancyindex_footer "/fancin/footer.html";
    	fancyindex_ignore "fancin"; #ignore this directory when showing list
    
 - copy the remaining items in your web root under 'fancin'.
 - copy the remaining items in your web root under 'fancin'.
  - header.html
  - footer.html
  - css\style.css
  - images\logo.png
 - Restart your nginx server.

#####More
 - Mime type icons from [Splitbrain](http://www.splitbrain.org/projects/file_icons)