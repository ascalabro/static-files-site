## My static site


#### /anth.photos/

This is wired with Nginx to point to http://anth.photos/

The line used for this url in the site config for Nginx is 
```
    # This embeds the site on the proxy_pass domain to live at the location url
    location /anth-photos/ {
            proxy_pass http://anth.photos/;
            proxy_redirect off;
    }

```


### Weirdiality

The other 2 weird directories are sites ripped from http://osxnotes.net/ & http://2048.fi/

I took them because some of the information in the text files is useful to me.
