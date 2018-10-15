---
layout: post
title: "What is ArrowOS?"
description: ""
thumb_image: "/assets/logo.png"
tags: [arrowos, android]
---

With tons of custom roms available out in the OpenSource community these days, we have always lacked a thing or two and been compramised with ourselves to stick around looking for a better alternative. Here at ArrowOS team we being the daily android users clearly understand your pain. This is where the whole idea of ArrowOS originated from, with the sole goal of providing a stable custom rom without any heavy framework customisations and keeping the performace to a full boost. Since then we have grown stronger with an ever supporting community of android enthusiasts and been pushing out the most stable and feature balanced custom rom available so far.

## Features:
#### Status bar:
  - Double tap to sleep.
  - Status bar items customisation.
  - Clock and Date customisation.
  - Traffic indicators

#### Buttons:
  - Device buttons and Nav bar customisation
  - Advanced reboot menu
  - Enable or Disable Nav bar
  - Navigation bar editor and layout configs
  - Volume rocker playback, wake and reorient controls

#### QS Panel:
  - Customise rows and columns
  - QS panel transparency
  - Quick pulldown
  - QS tiles title

#### SystemUI themes:
  - Automatic(wallpaper based)
  - Light
  - Dark
  - Black

#### Accent color:
  - AmberAccent
  - BlackAccent 
  - BlueAccent 
  - BlueGreyAccent 
  - BrownAccent 
  - CyanAccent 
  - DeepOrangeAccent 
  - DeepPurpleAccent 
  - DuiDark 
  - GBoardDark 
  - GreenAccent 
  - GreyAccent 
  - IndigoAccent 
  - LightBlueAccent 
  - LightGreenAccent
  - LimeAccent 
  - OrangeAccent 
  - PinkAccent 
  - PurpleAccent 
  - RedAccent 
  - SettingsDark 
  - SystemDark 
  - TealAccent 
  - YellowAccent 
  - WhiteAccent

#### Lockscreen:
  - Lockscreen shortcuts
  - Double tap to sleep on lockscreen
  - Music visualizer

#### Misc:
  - Tap to wake
  - Pocket detection
  - AOSP recents clear all fab(oreo recents)
  - Weather
  - Swipe up on home button
  - Double press power button for camera

## Why use ArrowOS?
#### Three words:
  - Stability 
  - Performance 
  - Timely security updates

## Installation

Installing ArrowOS on your devices is fairly simple and a straight forward process which you'll find on all our officially supported device specific threads on XDA along with any additional steps mentioned if needed.

Here are the common steps to be followed for most of the devices:

- Boot to your custom recovery(TWRP preferred).
- Head over to the Install option and choose your device zip package of ArrowOS.
- Go ahead flash the package and wait for the process to complete.
- Flash Gapps or any other other additional packages
- Reboot and you should be greeted with the ArrowOS homescreen if everything went well.

## Development

In order to start developing ArrowOS for your device you must be on a Linux environment and start by syncing our source code which can be done by running the following command in your terminal:

{% highlight bash %}
mkdir arrow
cd arrow
repo init -u https://github.com/ArrowOS/android_manifest.git -b arrow-9.x
repo sync  -f --force-sync --no-clone-bundle -jX
{% endhighlight %}
Where X in the above command is no.of threads your CPU can handle.

We have more detailed post on this topic [here](https://blog.arrowos.net/posts/compilation-guide)

## Contributing

Before you push any of your changes please make a build and test:

Head over [here](link here) on how to push your changes to our [gerrit](https://review.arrowos.net/)

_If you have any questions regarding ArrowOS contact us on our telegram community <a href="https://t.me/ArrowOS" title="telegram community" rel="noreferrer noopener" target="_blank">here</a>!_
