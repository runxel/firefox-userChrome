# firefox-userChrome
**UPDATE**  
From Firefox 69 on you will need to set a flag in `about:config`. Otherwise the userChrome will be disabled.  
Set `toolkit.legacyUserProfileCustomizations.stylesheets`to `true`.  
_However_: It seems that `moz-binding` was disabled as well, which means you can't style the scrollbars anymore... :(

---

<del>This is my current configuration of the Firefox userChrome (located in your profile folder – yes, you have this, too).  
What's awesome here is it even styles the scrollbars!</del> <ins>See paragraph above. This is not longer in use for me.</ins>

---

Have a look [this gist of mine](https://gist.github.com/runxel/2a2bde05a83ea9ca9468495544b3e61b), where I collect some of the hidden flags in `about:config` you should be aware of.
