Funny goobHome 

** how to use ** 
Pretty much to start using this just open the "main.html" file, your chosen web browser will 
run the file and you will see the "website" which is stored all locally within your computer
It will be running on file:// instead of https://.

If you want to edit the bookmarks just open the bookmarks.js file with notepad, test it out
with the example part

Games are contained at the bottom of the webpage (just scroll down)



** what is goobHome? **
goobhome is simply just a homepage for users to use when using their web-browser, quick and easy access
to the time, weather and their own bookmarks




** enabling flash **
Enabling flash locally was a bit of a challenge 
(There was no other work around to get ruffle or any unity game to work otherwise.)

Pretty much if you want to know what the shortcut does, it allows web pages from the file:// protocol
to access other assets in your local system, the reason why ruffle and stuff needs this is because
it needs to access the swf files (which is on your system locally) and it cannot do that if this shortcut
isn't enabled (because it cant fetch the files otherwise!)

Why is this needed?
By default, Chrome blocks file:// protocol pages from accessing other local files 
Some applications, like Ruffle rely on accessing local assets (./sources) stored on your system to function properly.

If the shortcut isn't working for some reason, just add this to the "Target" in properties
"C:\Program Files\Google\Chrome\Application\chrome.exe" --allow-file-access-from-files




** other features **
By pressing "K" you will remove the entire lower part (removing the games section until you reload)

"Space" will open a search bar to simply just search on google

You can change your wallpaper by going into main.html with a text editor of your choice, search for
"wallpaper", and replace the lower bit that says "background-image: url("./images/SK_region_art.png");"
with your own image (or gif!)

If you want to make any other changes to the page, i made it very easy by adding a lot of comments within the page
to make it easier to understand where everything is


