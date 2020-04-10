# HappyShield.GitGub.io Contribution Guide

## Translations

### Introduction

Thank you so much for your help translating the HappyShield website and instructions!

We hope to translate the following files in this website (`XX` is the [ISO 639-1 code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) for the language): 

<pre>
* index_<b>XX</b>.md <i>(Homepage)</i>
* Instructions/HandCreasing/handCreasing_<b>XX</b>.md <i>(Hand creasing method instructions)</i>
* Instructions/LaserCut/laserCut_<b>XX</b>.md <i>(Laser-cut method instructions)</i>
* Instructions/LaserCutAndPressureCreasing/laserCutAndPressureCreasing_<b>XX</b>.md  <i>(Laser-cut and pressure-creasing method instructions) </i>
* Instructions/WaveShield/waveShield_<b>XX</b>.md <i>(WaveShield production method instructions) </i>
</pre>


### Instructions

Here's how to contribute translations!

### 1. Create a Free GitHub Account

1. If you don't have one already, [create a free GitHub account](https://github.com/join). (If you sign up using an academic email address you are eligible for a free 2-year upgrade to GitHub Pro, but this is not necessary for creating and editing translations to happyshield.github.io).
2. Navigate to [this repository](https://github.com/HappyShield/happyshield.github.io), making sure that you are viewing the main version of the repository: "HappyShield/happyshield.github.io" 

To translate (or edit an existing translation):

### 2. Create and Edit Translation Files

Watch [our video explaining how to create and edit translations files for HappyShield.Github.io here!](https://youtu.be/XLiHhSyrW8A)

The instructions are also shown below: 

##### If the translation file already exists:

1. Navigate to the relevant file in this repository.
2. Click "Edit this File"
3. Type any changes you would like to make to the text in the file. 
4. Add a description explaining the changes you have made.
5. Commit the changes ("Propose File Change")

You can also see this process explained nicely here! https://guides.github.com/activities/hello-world/#commit

##### If the translation file does not yet exist:

1. Navigate to the English version of the file (for example: `Instructions/HandCreasing/handCreasing_EN.md`) which you will be translating into another language. 
2. Click the edit button.
3. Select all of the text in the file and copy it.
4. Close the file. You should have made no changes, so no commit is necessary. 
5. Navigate to the folder where the file should exist.
6. Click create new file, and choose the appropriate name: `Instructions/HandCreasing/handCreasing_TR.md` for "Hand Creasing" instructions in Turkish (TR), for example.
7. Paste.
8. Edit this text, replacing English with your translated text.
7. If you want to save your progress at any point, commit the changes, and provide a description of the changed made since the previous commit.  

#### What should I translate? 

Please translate the following files from English (EN), into your language: 

(Please note that the English version of the homepage (`index.md`) has no `_EN` ending. When creating your translation for this page, please name your new, translated copy of the home page `index_XX.md` where `XX` is your languages's [ISO 639-1 code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes).)

<pre>
* index_<b>XX</b>.md <i>(Homepage)</i>
* Instructions/HandCreasing/handCreasing_<b>XX</b>.md <i>(Hand creasing method instructions)</i>
* Instructions/LaserCut/laserCut_<b>XX</b>.md <i>(Laser-cut method instructions)</i>
* Instructions/LaserCutAndPressureCreasing/laserCutAndPressureCreasing_<b>XX</b>.md  <i>(Laser-cut and pressure-creasing method instructions) </i>
* Instructions/WaveShield/waveShield_<b>XX</b>.md <i>(WaveShield production method instructions) </i>
</pre>

When translating these files, please also modify the "header" of the file to correspond to your language:

For example, if we are translating `Instructions/HandCreasing/handCreasing_EN.md` the header we would see to begin with would be:

<pre>
---
layout: page
title: <b>Hand Creasing</b>
tagline: &nbsp <span class="instructionsTaglineEmojiLinks"> <a href="https://youtu.be/8RvlrtrebBE"><i class="em em-video_camera" aria-role="presentation" aria-label="VIDEO CAMERA"></i></a> <a href = "https://github.com/HappyShield/HappyShield/tree/master/Templates/HandCreasing" ><i class="em em-triangular_ruler" aria-role="presentation" aria-label="TRIANGULAR RULER"></i></a></span>
permalink: /hand-creasing/<b>en</b>/
language: <b>en</b>
---
</pre>

Please translate the `title` field, and update the `permalink` and `language` fields to the [ISO 639-1 code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) of your language.

For example, for Portguese (ISO 639-1=`PT`), this would result in:

<pre>
---
layout: page
title: <b>Vincar Manualmente</b>
tagline: &nbsp <span class="instructionsTaglineEmojiLinks"> <a href="https://youtu.be/8RvlrtrebBE"><i class="em em-video_camera" aria-role="presentation" aria-label="VIDEO CAMERA"></i></a> <a href = "https://github.com/HappyShield/HappyShield/tree/master/Templates/HandCreasing" ><i class="em em-triangular_ruler" aria-role="presentation" aria-label="TRIANGULAR RULER"></i></a></span>
permalink: /hand-creasing/<b>pt</b>/
language: <b>pt</b>
---
</pre>


### 3. Submit a Pull Request for Your Translation

When you are ready for your work to be incorporated into the main repository, you will submit a pull request, which is a request to have these changes incorporated into the live website.

Watch [our video explaining how to submit a pull request for your translations files for HappyShield.Github.io here!](https://youtu.be/eBnob0MgYTU) 

The instructions are also shown below: 

1. Click Pull Request. 
2. Click Create Pull Request
3. Add any helpful description along with your Pull Request to explain to others what you have added or changed to the text.
3. Submit your Pull Request. 

Auri (or whoever is managing the repository!) will review and approve the pull request, and then merge these into the main repository, where they should be rendered on the live website within 3-5 minutes. : ) 
