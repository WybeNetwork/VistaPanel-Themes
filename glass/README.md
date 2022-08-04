# Glass Theme
This stylesheet uses the cPanel Glass theme. It is a minimal light theme, with not much to it.

# Installation, and customization
Aside from the main installation instructions, this theme requires a special configuration to work properly.  
FontAwesome icons are used in it, so you need to add them to your code.  
Add this to your header advertising area:
```
<script src="https://kit.fontawesome.com/8b2e8e690f.js" crossorigin="anonymous"></script>
```
You may elect to replace our link with [your own kit's](https://fontawesome.com/kits), provided you use FontAwesome 5.x.

## Why is there an icon_spritemap file, if icons are disabled? How can I add icons?
I chose to keep icon_spritemap.css for those that may want to use the Glass theme with icons.  
To do that, you need to add this part to your footer advertising area:  
```
<style type="text/css">
.spriteicon_img {
    display:inherit !important;
}
</style>
```
It may not look as great, but you can always customize it further.

# Credits
[Anyx](https://github.com/4yx) for modifying the theme to work with VistaPanel.

[creatort](https://github.com/creatort) and [iFastNet's cPanel Demo](https://sv4.byethost4.org:2083/login/?user=demobye&pass=password) for providing the files required.