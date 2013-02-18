# Camtwist Syphon

Simple Quartz Composer module to use Syphon with Camtwist. 
In practice, this is **Syphon -> Virtual Webcam** 

## Why?
---

Camtwist can create a virtual webcam. Joining it with Syphon, you can
stream your VJ directly to applications that doesn't have Syphon, but can
read camera streams , like... Skype, Flash, WebRTC, etc...


Try streamming your VJ to Skype or make a VJ session in chatroullete


## Installation
---

First, you need to install [Syphon QTZ Plugin](http://syphon-implementations.googlecode.com/files/Syphon%20For%20Quartz%20Composer%20Public%20Beta%202.dmg).

Copy the modules located in `modules` to `~/Library/Application Support/CamTwist/Effects`.
Create that folder, if it doesn't exist.

    $ mkdir -p ~/Library/Application\ Support/CamTwist/Effects
    $ cp modules/*.qtz ~/Library/Application\ Support/CamTwist/Effects

## Usage

* If you want to **fetch**    Syphon input, use the effect `Syphon In`.
* If you want to **send** to Syphon, use the effect `Syphon Out`

## Screenshot

## Author

        __
       / /              
      / /                
     / /  
    /_/ bî̫͔n fc ⚑.

    <barrabin.fc@gmail.com>
