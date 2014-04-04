#Empornium Quick Thumbnail Preview
Add mouseover-previews to the new and improved Empornium's search/browse function.

## Installation
Click on the file ending in `.user.js` and click on the _Raw_ button to open the file directly. This should trigger your userscript plug-in to ask you to install the script.

## Issues / Requests / Questions...
To report any issues, make requests or ask questions about the script please use GitHub's issue tracker.

---

## Description
This script allows you to view the preview pictures of Empornium torrents without going to the detail page. Just move your mouse cursor over the icon in the type column (far left) and a tooltip will open which allows you to go through the previews, thank the uploader and download a torrent without ever leaving the browse page.

## Features
* View preview pictures
* Download torrents
* Thank uploader
* Read torrent description
* Leave a comment
* Navigate browse pages
* Thumbnails of supported image hosts are automatically replaced with the full-size images
* Mark torrents as visited

## Instructions
* Place your cursor on the category icon in the type column of a torrent to load it's preview pictures. This will load the first available picture.
* Use the __left arrow__ and __right arrow__ keys to move to the __previous/next preview__ picture for the current torrent
* Press the __SHIFT__ key to open the current preview picture in a __new window/tab__
* Press the __DEL__ key to __download__ the .torrent file of the torrent you are previewing
* __Double click__ the category icon to open the __details page__ for a torrent
* Press __CTRL__ to __thank the uploader__ for the torrent you are previewing
* __Click__ the category icon once to __keep the previews visible__ when you move your mouse away. All hotkeys will still work. Click anywhere to unlock the previews
* To __automatically thank__ the uploader when downloading a torrent with this script click the Tampermonkey icon and click on [EQTP] Toggle auto-thanks.  
  This is activated by default.
* To __automatically leave a comment__ when downloading a torrent with this script click the Tampermonkey icon and click on [EQTP] Toggle auto-comment.  
  This is deactivated by default.
* To change the text of the auto-comments click on the Tampermonkey icon and click on [EQTP] Edit auto-comment. 
* Default comment: Thank you!
* Seperate multiple comments with | to post a random comment on each download.
* All auto-thanks and auto-comment settings are stored in your browser. They are not linked to your Empornium user!
* While holding __CTRL__ use the __left/right arrow__ keys to go to the __previous/next browse page__.
* Press __V__ to mark a torrent as __visited__.

## Controls
```
Next Image............[->].............Shows the next image or cycles to the first one
Previous Image........[<-].............Shows the previous image
Download Torrent......[DEL]............Downloads the .torrent file of the current torrent
Thank The Uploader....[CTRL]...........Thank the uploader of the current torrent
Open Image............[SHIFT]..........Opens the current image in a new tab/window
Open Details..........double click.....Opens the details page of the current torrent
Keep Visible..........click............Keeps the preview box visible when moving the mouse
Mark Visited..........[V]..............Mark a torrent as visited

Next Page.............[CTRL]+[->]......Loads the next browse page
Previous Page.........[CTRL]+[<-]......Loads the previous browse page
```
