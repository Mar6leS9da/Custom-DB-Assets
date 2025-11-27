# How to use Chrome to Override DuelingBook MR1 SVG Files with local files.

Good morning afternoon or evening to you, my name is Mar6leS9da, If you've come here from my YT tutorial, welcome. if not, you can access that here, and it's highly recomended. **PLACEHOLDER FOR LINK** 

If you know anything about duelingbook, you've probably heard of macros, if not, you're missing out, there are ways to make DB more *tollerable* to play by adding controls to the site that make moving cards and performing game actions much easier, and even customizing the look of the site to our liking, the most popular, and arguably the best of these macro extrensions is called Custom DuelingBook, which you can take a look at [here](https://github.com/killburne/custom-duelingbook) (shout out to **killburne** for making an amazing extension btw) Custom DuelingBook has so many customization options that its really hard to find complaints with it but I have one. you can customize the duel fields for the current format, (mr5, but mr4 board iykyk), but no option for mr1, which are the zones used for Edison and GOAT format, which are **EXTREMELY** popular, idk any metrics, but again, iykyk.

So I developed a bit of a workaround, with Google Chrome you can override website assets with local files, I tinkered for a while and made some files as a sort of proof of concept, using the original SVG files as a guideline for spacing and sizing.

in the YT video I talk about how to make your own custom SVG files and why you's want to do that.

ive also hosted all of my custom images that re natively compatible to imigur, but you can easily just download my Custom Db settings json file and it will apply all of the features you see in the video as well 



**IMPORTANT! ONCE YOU FINISH THIS TUTORIAL, ON ANY SUBSEQUENT LOG IN AFTER YOU'VE CLOSED YOUR DB TAB, YOU WILL HAVE TO PRESS F12 AND WITH THE MENU OPEN REFRESH THE PAGE, OTHERWISE THE OVERRIDES WILL NOT TAKE AFFECT I HAVE NOT FOUND A WAY TO MAKE IT PERMANENT, ANY HELP IN THAT WOULD BE GREATLY APPPRECIATED**

1. in chrome go to [DuelingBook](duelingbook.com)

2. Go watch an Edison or GOAT duel.

3. Press F12

4. Make sure you are in the in Sources tab, and page tab respectively, then open the dropdown for "images.duelingbook.com"
![](https://i.imgur.com/eZ1rSW9.png)

5. In this dropdown, you're going to open the SVG folder, and scroll unil you find "field_zones1.svg"
![](https://i.imgur.com/QdQe8PS.png)

6. right click that file, then click "Override Content", this will prompt you to enable overrides for the site, and make a folder to store the overrides(make this easy to access), while also downloading the field zone file, whatever you name the folder, the contents should look like this with the field zone file located in **xxx\your_override_folder\images.duelingbook.com\svg\field_zones1.svg**

![](https://i.imgur.com/81DTKkT.png)

7. Take the contents of the DB overrides folder and copy them into your override folder replacing all files in the destination. it should now look like this

![](https://i.imgur.com/eJC9WC5.png)

8. at this point you should be good to go, **REMEMBER TO LOAD THE FILES WHEN YOU OPEN DB HIT F12 AND RELOAD THE PAGE, OTHERWISE THE OVVERIDES WON'T APPLY**
