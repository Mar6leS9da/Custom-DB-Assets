# How to use Chrome to Override DuelingBook MR1 SVG Files with local files.

Good morning afternoon or evening to you, my name is Mar6leS9da, If you've come here from my YT tutorial, welcome. if not, you can access that here, and it's highly recomended. **PLACEHOLDER FOR LINK** 

If you know anything about duelingbook, you've probably heard of macros, if not, you're missing out, there are ways to make DB more *tollerable* to play by adding controls to the site that make moving cards and performing game actions much easier, and even customizing the look of the site to our liking, the most popular, and arguably the best of these macro extrensions is called Custom DuelingBook, which you can take a look at [here](https://github.com/killburne/custom-duelingbook) (shout out to **killburne** for making an amazing extension btw) Custom DuelingBook has so many customization options that its really hard to find complaints with it but I have one. you can customize the duel fields for the current format, (mr5, but mr4 board iykyk), but no option for mr1, which are the zones used for Edison and GOAT format, which are **EXTREMELY** popular, idk any metrics, but again, iykyk.

So I developed a bit of a workaround, with Google Chrome you can override website assets with local files, I tinkered for a while and made some files as a sort of proof of concept, using the original SVG files as a guideline for spacing and sizing..

>[!NOTE]
>In my YT video I talk about how to make your own custom SVG files and why you'd want to do that in the first place. for this project I used [Boxy SVG Editor](https://boxy-svg.com/app) (not sponsored)

Ive also hosted all of my custom images that are natively compatible with Custom DB to imgur, but you can easily just download my Custom Db settings json file and it will apply all of the customization options I have set on my DB (excluding this tutorial of course

# Begin Tutorial

1. in chrome go to [DuelingBook](duelingbook.com)

2. Go watch an Edison or GOAT duel.

3. Press F12

4. Make sure you are in the in Sources tab, and page tab respectively, then open the dropdown for "images.duelingbook.com"
![](https://i.imgur.com/eZ1rSW9.png)

5. In this dropdown, you're going to open the SVG folder, and scroll unil you find `field_zones1.svg`
![](https://i.imgur.com/QdQe8PS.png)

6. Right click the file, and select "Override Content" this will prompt you to enable overrides, then create an overrides folder (make this easy to access), and finally it will download the `field_zones1.svg` file 

7. We're also going to fo this for replays since that is a *technically* a "seperte" site, and requires us to, so open an Edison or GOAT replay and repeat steps 3-6, but instead of creating another override folder, select the one you already made, (it probably auto selects it but I can't remember) then open your overrides folder and it should look like this:

![](https://github.com/Mar6leS9da/Custom-DB-Assets/blob/a8e03044ad1c12dbbc2c68e63653c25e9fa7045e/Repository%20Assets/step%207.PNG)


8. Take the contents of the DB overrides folder and copy them into your override folder replacing all files in the destination. it should now look like this

[![]([https://i.imgur.com/eJC9WC5.png](https://github.com/Mar6leS9da/Custom-DB-Assets/blob/a8e03044ad1c12dbbc2c68e63653c25e9fa7045e/Repository%20Assets/step%208.PNG))

9. at this point you should be good to go, refresh DB with f12 open, and go watch another GOAT/Edison duel and the field zones should be applied, you can close the f12 menu and game away,

10. In the `Asset Example` folder, you can find some more svg files to play with, you can change out the mr1 zones for these by copying the one you want into both svg folders, deleting the `field_zones1.svg` files, and renaming the new files to, you guessed it, `field_zones1.svg` then in DB with F12 open refresh the page to apply your changes.

>[!IMPORTANT]
>NOW THAT YOU'VE FINISHED THIS TUTORIAL, ANY TIME YOU OPEN DB, TO APPLY THE OVERRIDES, YOU WILL HAVE TO PRESS F12 AND WITH IT OPEN, REFRESH THE PAGE, OTHERWISE THE OVERRIDES WILL NOT TAKE AFFECT. I HAVE NOT FOUND A WAY TO MAKE IT PERMANENT, ANY HELP IN THAT WOULD BE GREATLY APPPRECIATED.
