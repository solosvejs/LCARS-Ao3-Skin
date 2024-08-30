# LCARS-Ao3-Skin
A site skin for archiveofourown.org


# Introducing: LCaorS

aka "What if AO3 but more _Star Trek: The Next Generation_?"

  

<p align="center">

  <img src="https://github.com/solosvejs/LCARS-Ao3-Skin/blob/main/LCaoRs-mainpage.png?raw=true">

</p>

<p dir="auto"><img src="https://github.com/solosvejs/LCARS-Ao3-Skin/blob/main/LCaoRs-fandom.png?raw=true" alt="screenshot of the ao3 page for Star Trek: The Next Generation, using the LCARS ao3 skin" width="1115" height="502" align="middle" /></p>
</div>
<div>
<p align="center"><em>Work listing<br /></em></p>
<p align="center">&nbsp;</p>
<p align="center">&nbsp;</p>
<p dir="auto"><img src="https://github.com/solosvejs/LCARS-Ao3-Skin/blob/main/LCaoRs-work.png?raw=true" alt="screenshot of a fanfic on Ao3, using the LCARS ao3 skin" width="1115" height="502" align="middle" /></p>
<p align="center"><em>Viewing a fanfic<br /></em></p> 
  
# Things to Know

First things first: **this skin is very much “aesthetic” over function**. The original LCARS design was created for a TV show in the 80s, back when computers were barely a thing yet. You can find a lot of articles from real professional UX people about whether this would actually work as a user interface (I have read none of them).

I did my best to try and make the colors as easy on the eyes as possible. Should you use this as your everyday Ao3 skin? Maybe, I'm not your optometrist! 

Secondly: This skin will likely not work on a phone. It _might_ work okay on an iPad or similar-sized tablet display. The animations will not work on any mobile device, though.

Speaking of animations: I am aware that the dropdown menu when you hover over “Hi, [name]” is aligned kind of weird. I’d recommend having your mouse more on the “hi” than the name part. If anyone knows how to fix it, please tell me because I haven’t been able to figure it out for two years. 
 

And finally, I only tested this on Firefox so let me know if you run into issues with other browsers.

# How to use

1. Go to the GitHub repository here: https://github.com/solosvejs/LCARS-Ao3-Skin/
2. Navigate to the file called “LCARS-Ao3-Skin.css” - in the top right, where it says “Raw”, you can either Copy the contents of the file to your clipboard, or download it. 
			NOTE: I would STRONGLY recommend downloading a copy of the file to somewhere on your computer. Why? Ao3 is set up to **r**emove all comments** from the skin when you add it to your profile, which will make it harder to change colors/font sizes/etc after the fact. 
3. Once you have the file, open it up in any text editor (notepad, etc), select EVERYTHING, and copy. Then, head over to Ao3!

## Setting up the skin on Ao3

1. Make sure you're logged into your Ao3 account.

2. Go to your Dashboard (first link under the "Hi, [Name]!" menu in the top right) then navigate to "Skins".

3. Select "Create Site Skin"

4. Under "Type", leave the drop-down as "Site Skin".

5. Give the skin a title -- it doesn't matter what, only you will see it. Feel free to add something to the description if you want.

6. Under the “CSS” section, paste the **entire** file you just downloaded/copied! 

7. Open the "Advanced" heading - you should see two sections: Conditions and Parent Skins. We can ignore the first one – use the button called "Add Parent Skin"  and type "Reversi" into the box that comes up. This will make sure that the skin inherits the proper dark mode styles.

7. Finally, hit "Submit"  – if everything went well, you’ll be taken to a page with a bunch of the code you just added.  Scroll all the way to the bottom, and click on “Use” to start using it, or “Preview” to see how it will show up. 

You can now enjoy a Star Trek of Your Own! 

  
# FAQ

## I don't like some of these colors, can I change them?

Of course! 
Anytime you see a line that starts with “color: “ or “background: ” and has a bunch of numbers or letters with a # sign, that’s a color. You can change them as desired. The easiest way is probably to find the color you want to change, and then use Find and Replace to change all instances of it. 

I've tried to leave as many comments as I could regarding what part does what. If you're confused, feel free to reach out and I will try to help out. 

## How do I turn off the sliding animations?
To turn off the sliding animations in the header and the pagination:
* In your text editor of choice, hit ctrl + f; type/paste in: "transform: translate"
* You can either delete the lines where that code appears, OR "comment them out" by typing `*/    /*` around them. This will keep the code intact but turn it off so your browser won't read it - then, if you want to turn that section back on again, you can simply remove the `*/  /*` around the line.

## I found a form/button/box that looks weird!

Let me know, and I'll try to fix it! I tried to cover as much of the site as I could, but the Ao3 front-end isn't always consistent or intuitive to style, so I might have missed something. Most likely, things will still WORK perfectly fine, but they might look wonky.

## Can I use some of your code to make my own skin?

Sure! I'd love to see what you do with it, so please drop me a line!
 
