HOW TO USE: field_zones1.svg

Because the Custom DB extension does not have an option to change the Master Rule 1 Board like it does with modern and mr3, the only way I have found to change it is overriding the SVG file. 
to do this in chrome: go into a GOAT/Edison game on db and press f12, on the top left of the f12 window make sure "Page" is highlighted. you should see a list under that starting with "Top" 
and listing a bunch of items with a cloud icon next to them. 
look for the cloud labeled "Dev Tools Performance Metrics", and open the drop down to see the contents,
open the revealed drop down for "SVG" and scroll until you find "field_zones1.svg" 
right click and select "Override Content" this will prompt you to create an overrides folder, once that's done it will download the file to its own folders inside of the overrides folder, 
find the field zones file in there and replace it with the file here, (names must match) then go back to db, and refresh the page with the f12 menu open and it should work. 
you will have to reload db with f12 open every time you log in to make the change happen, but as long as you don't refresh the page without f12 open, you should be good.
you will hve to do this process seperately for the replay page, as it recalls all items on intital load.
if anyone knows how to make these changes permanent without having to open f12 everytime pls lmk

For anyone who wants it I'll be making a youtube tutorial on this too will be linked
