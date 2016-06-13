# INFORMATION

This repo is not a HumHub Module! It is a tutorial with the needed files to integrate a game section or a simple portfolio into your HumHub installation.



***


## REQUIREMENTS

You need the HumHub Custom Pages Module to get the Game Section working and you need the files here at the repo.

***


## Tutorial

-upload the **css, images, js** folders of the repo via FTP into a new generated folder called **games** within your default HumHub folder. You dont have to upload the index.html. It should look like this:

![folders](https://github.com/WebCrew/HumHub-GameSection/blob/master/hh-games.jpg?raw=true "folder structure")

-Create the following pages in the order I use here. 

-Use the **Custom Pages module** of HumHub to create these pages and take the **iFrame** fuction for it. Only with the **Play Games** page you have to use the **html** type.

-Where it comes to, which navigation type to use, use this one: **Without adding to navigation (Direct link)**
only with the **Play Games** page you have to use: **Top Navigation**


###1.Page:

**Name it:** Nimian Legends

**iFrame link URL:** http://nimianlegends.com/empires/index.htm

now save the new page and lets do the next.


###2.Page:

**Name it:** Bananabread

**iFrame link URL:** https://kripken.github.io/BananaBread/cube2/index.html

now save the new page and lets do the next.


###3.Page:

**Name it:** Adventurequest

**iFrame link URL:** http://www.aq.com/play-now/

now save the new page and lets do the next.


###4.Page:

**Name it:** Felspire

**iFrame link URL:** http://p.37gamesde.com/platform/index/index.html?scid=404_de.de37games.com/11gw/23fs/6.html

now save the new page and lets do the next.


###5.Page:

**Name it:** League of Angels

**iFrame link URL:** http://angel.gtarcade.com/server

now save the new page and lets do the next.


###6.Page:

**Name it:**Under Control

**iFrame link URL:** http://undercontrolgame.com/promo/8/de?sm_type=ads&sm_st1=de_gamespipe&sm_st2=618_&click_id=311633322

now save the new page and lets do the next.


###7.Page:

**Name it:** Battlestar Galactica

**iFrame link URL:** http://en.bsgo.com/?bptid=9785a46ee2212d704088c0f5d6bff239

now save the new page and lets do the next.


###8.Page:

**Name it:** Legends of Honor

**iFrame link URL:** http://legendsofhonor.com/game/

now save the new page and lets do the next.


###9.Page:

**Name it:** Play Games

IMPORTANT! This page has to be done with custom pages "html" page feature.

**Where it comes to the "Conten-field":** you have to input the code of the index.html of the repo. Open the index.html of the repo, copy the code and paste it to the "Content-Field"

**Where it comes to "Navigation-Field":** choose "top Navigation" Important!

**Where it comes to "Sort-Order-Field":** use 500

now save the new page and lets do the next.


###10.Page:

**Name it:** Sparta

**iFrame link URL:** http://plarium.com/play/de/sparta/tv_navy_sevengames?plid=61702&pxl=sevengames&clickID=102e92de98217f24a3289d9cec94fa&publisherID=1004_

now save the new page and lets do the next.


###11.Page (last we need):

**Name it:** Clash of Avatars

**iFrame link URL:** https://coa.amzgame.com/

now save

###Last step:

Control the URLs of CustomPages you made per game. Within your **Play Games** page code, the href="" atributes should point to the correct link/url of the generated custom pages page.  I know it sounds a bit complicated and you are right, its something goofy to explain. 

If you have questions, or are stuck, then contact me at the HumHub community "Andreas Holzer" and I try to help you.


***
## THANKS

Thanks for Your interest!

Kind regards to all of You.

Andreas Holzer


***
## Extra Note

You can use the repo also to do a portfolio. Just replace the images of the repo, texts and links in the index.html with the ones you want to use.
To edit the text of the "->play now" button, you have to open the grid.js line 347 and rename it to your needs.
