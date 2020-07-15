# mcjarfontgetter

Extracts the "Mojangles" font from a Minecraft .jar file.  
To use, open makefont.html in a browser (as long as it isn't Internet Explorer or Microsoft Edge) and choose the Minecraft .jar file in the file input.  

## How to get a Minecraft .jar file

First, go to your computer's Minecraft directory. The default Minecraft directory is:

Windows: `C:/Users/username_here/AppData/Roaming/.minecraft`  
macOS: `/Users/username_here/Library/Application Support/minecraft`  
Linux: `/home/username_here/.minecraft`  
replacing `username_here` with your username. May include hidden files.

Alternatively, go to the resource pack folder's parent directory. The resource pack folder is accessible from Minecraft's resource pack options.

Once you are in the Minecraft directory, navigate to `/versions/1.16.1/1.16.1.jar`  
replacing `1.16.1` with the Minecraft version you want to extract the font from.

This is the Minecraft .jar file.

## Libraries used

Uses code from [opentype.js](https://github.com/opentypejs/opentype.js), [jszip](https://github.com/Stuk/jszip), and [UPNG.js](https://github.com/photopea/UPNG.js).
