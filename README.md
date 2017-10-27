# Dauntless Subreddit Theme

## Installation Guide

1. Download the whole repository as a .zip
2. Go to "edit flair" in the Moderation Tools and make sure the following settings are set:
  * Flair Options: enable user flair in this subreddit
  * Flair Options: allow users to assign their own flair
  * User Flair Position: right
  * Link Flair Position: right
3. Click on "user flair templates" in the same "edit flair" page and add the following templates:
  * Flair text: Drask,     css class: drask
  * Flair text: Embermane, css class: embermane
  * Flair text: Gnasher,   css class: gnasher
  * Flair text: Pangar,    css class: pangar
  * Flair text: Quillshot, css class: quillshot
  * Flair text: Shrike,    css class: shrike
  * Flair text: Skraev,    css class: Skraev
4. Click on "link flair templates" in the same "edit flair" page and add the following templates:
  * Flair text: Dev Response, css class: dev-response (this flair puts the "Dev Response" besides the title)
  * Flair text: Official, css class: official (this flair puts the Phoenix Labs logo in the background right of the thread)
5. Click on "grant flair" in the same "edit flair" page, and for each dev that is using reddit, you can grant them the official flair by typing their username and adding them the flair text: Phoenix Labs and css class: phoenix-labs
6. Go to "edit stylesheet" and upload every image in the folder "/images/" from the .zip file (not the subfolders) with the same name of the file
7. Copy and paste from /stylesheet.min.css to the stylesheet text area, then save
8. The theme is now installed!

## Sidebar Guide

To get the special important list up top you **MUST** put the list at the start of the sidebar, it should be the first thing written down there.

*CSS takes the first list from the sidebar element, and move it up*

```markdown
* [Important stuff link #1](http://google.com)
* [Important stuff link #2](http://google.com)
* [Important stuff link #3](http://google.com)
* [Important stuff link #4](http://google.com)
* [Important stuff link #5](http://google.com)
```

The rest should be straightforward, here's the rest of the test sidebar:

```markdown
#PLAYDAUNTLESS.COM
Dauntless is a co-op, action RPG coming to PC in 2017. Discover a shattered world, forge powerful weapons, and hunt the ferocious behemoths threatening our survival.

##GAME STATUS

[See all the current system status](https://status.playdauntless.com/)

**This month planned maintenances/updated**

|Date|Version|Description|Link
|-----|--------|-------|----|
|8.24.2017|0.1.3|Bug fixes and optimizations|[Forum](https://forums.playdauntless.com/t/founder-s-alpha-8-24-2017-patch-0-1-3-notes/)
|8.22.2017|0.1.2|Several fixes and optimizations|[Forum](https://forums.playdauntless.com/t/founders-alpha-8-22-2017-patch-0-1-2-notes/)
|8.19.2017|0.1.1|Patch 0.1.1|[Forum](https://forums.playdauntless.com/t/founders-alpha-8-19-2017-patch-notes-updated/)
 
##FIND FELLOW SLAYERS
* Dauntless Community Discord (unofficial)
* Dauntless German Community Discord (unofficial):
* Dauntless Community Stream Team (unofficial):
* Dauntless Twitter
* Dauntless Facebook
```