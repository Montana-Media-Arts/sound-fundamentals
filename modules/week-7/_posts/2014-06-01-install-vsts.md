---
title: Install VSTs
module: 7
jotted: false
toc: true
math: false
topic: Install 3rd Party VSTs
---



# Plug-In Formats & Installation Guide

## 🎛️ Why Use Plug-Ins?
Reaper, like most DAWs, is an insanely powerful tool for working with audio. But even with all its built-in capabilities, sometimes you need extra features—this is where **plug-ins** come in!

A **plug-in** is a separate software program that runs inside a DAW, adding new features, effects, or instruments. Reaper (like all modern DAWs) can host third-party plug-ins, expanding your creative possibilities. 

---

## 🔌 Plug-In Formats
Just like video or document files come in different formats, plug-ins also have various types. Some DAWs only support certain plug-in formats due to **optimization, system architecture, or licensing issues**.

###  What Plug-Ins Work in Reaper?
Reaper supports **VST-based** plug-ins.

- **VST (Virtual Studio Technology)** was developed by Steinberg Media Technologies.
- If a plug-in is available in **VST format** and is compatible with your operating system, you can use it in Reaper.

> **Note:** There are two versions of VST you might encounter: **VST** and **VST3**. Reaper supports both!

---

## 🎯 Install Your First Plug-Ins
To expand Reaper’s functionality, let’s install some plug-ins! These are **freeware plug-ins**, meaning they don’t come with fancy installers, so we’ll install them manually.

---

##  1. SocaLab Tone Generator (Sine Wave Oscillator)
**Download link:** [SocaLab Tone Generator](https://socalabs.com/developer-tools/tonegenerator/)

### 🖥 macOS Installation:
1. Open **Finder**.
2. Go to **Go > Go To Folder…**.
3. Type:/Library/Audio/Plug-Ins/
3. Drag and drop `ToneGenerator_64b.dll` into this folder.
4. **Restart Reaper**.

---

## 🚀 Loading the Plug-In in Reaper
1. Open Reaper.
2. Add an FX to a track.
3. In the **Add FX** window, search for:
4. Select and load the plug-in.

---

## 🛠️ Troubleshooting
### 🔍 Can’t find the plug-in?
1. Open **Reaper Preferences** (`Ctrl + P` or `Cmd + ,`).
2. Go to **Plug-ins > VST**.
3. Click:
   - **Auto-detect**
   - **Re-scan**
   - **OK**
4. Try adding the plug-in again.

---

## 2. SoundHack Delay Bundle
This next set of plug-ins is from **Tom Erbe’s SoundHack project**.

**Download link:** [SoundHack Delay Bundle](http://www.soundhack.com/freeware/)

### Installation:
Follow the same steps as the **SocaLab Tone Generator** installation.

---

## 🎶 3. Valhalla DSP Plug-Ins
These plug-ins come with automatic installers, making installation **super easy**!

- **[Valhalla Super Massive](https://valhalladsp.com/shop/reverb/valhalla-supermassive/)**
- **[Valhalla Space Modulator](https://valhalladsp.com/shop/modulation/valhalla-space-modulator/)**
- **[Valhalla Freq Echo](https://valhalladsp.com/shop/delay/valhalla-freq-echo/)**

### Installation:
1. Download the installer.
2. Run it and follow the instructions.
3. Restart Reaper and enjoy!

---

## 🔁 4. ++Audio Rubbadub Delay Plug-In
Another great plug-in with an automated installer!

**Download link:** [Rubbadub - ++Audio](https://www.interruptor.ch/vst_overview.shtml)

###  Installation:
1. Download the installer.
2. Run it and follow the instructions.
3. Restart Reaper and enjoy!

---

## Wrapping Up
Now you have an expanded arsenal of plug-ins in Reaper! If you run into any issues, double-check the installation paths and try rescanning in **Reaper Preferences > VST**.

🚀 **Time to make some noise!**
```




<!--
Reaper, as with most DAWs is a complex, capable, and overwhelmingly powerful tool for working with audio. We have not even began to scratch the surface of what it is capable of.

Yet, even with this powerful tool, there are reasons to extend and add to its capabilities. Reaper, as with all modern DAWs, can "host" external plug-ins. As you learned earlier, a plug-in is a separate software program that runs from within a DAW. One of the strengths of this architecture is that it allows for users to add 3rd party plug-ins to the DAWs, thereby creating additional opportunities for creativity.

## Plug-In Formats

A plug-in, as with a video file, word document, etc. can be one of a few different types. Likewise, certain DAWs have the ability host only certain types of plug-ins. This is due to issues such as optimization and system architecture, as well as issues such as licensing fees for various plug-in formats.

Reaper has the ability to host VST-based plug-ins. VST stands for [Virtual Studio Technology](https://en.wikipedia.org/wiki/Virtual_Studio_Technology) and was originally a plug-in format developed by Steinburg Media Technologies, makers of music and sound software and hardware. So, any plug-in that has a VST version and can run on your operating system can be added to Reaper.

**{ NOTE: }** There are two types of VST plug-ins you may run across, _VST_ and _VST3_.

## Go Get A Couple Plug-Ins

For this week, I want you to be able to utilize two processes, that are not capable in the basic version of Reaper you downloaded. So, we are going to install a few plug-ins to offer this additional capability.

Since these are freeware plug-ins, they do not come with fancy installer programs, and we will need to install them manually.

### SocaLab Tone Generator

The first plug-in I want you to install is a _Tone Generator_ from [SocaLabs](https://socalabs.com). This tone generator will serve as a sine wave oscillator.

The plug-in is available for download from:

- [socalabs.com/developer-tools/tonegenerator/](https://socalabs.com/developer-tools/tonegenerator/)

Since these plug-ins do not come with an installer, we need to manually place them in the system plug-in folder.

#### for macOS

 On macOS, you will need to do the following to install these plug-ins;

- Navigate to finder
- Under the "Go" menu, select "Go To Folder...".
- Type in the following: `/Library/Audio/Plug-Ins/`

![Example of 'go to folder' on macOS](../imgs/gotofolder.png "Example of 'go to folder' on macOS")

- After opening this folder, you will see a number of sub-directories.
- Reaper can use anything in the VST, VST3, and AU directories.
- The plug-in from SocaLab is a "_VST_" plug-in. So open that directory.
- You can then simply drop in the `.vst` file from the `ToneGenerator_Mac` directory.
- This is a system level directory, so you may need to authenticate this action with your system password.
- **{ NOTE: }** _If this directory does not exist, you may need to create it._

![Example of dropping in the file. ](../imgs/macAddVST.gif "Example of dropping in the file. ")

#### for Windows

- On windows you will want to similarly open your system's VST directory.
- This directory should be `C:\Program Files\VSTPlugins\`
- You can then drop in the `ToneGenerator_64b.dll` file to this directory.

#### on Both Systems

After moving the plug-in to the directory, you should open Reaper (or close and reopen, if it was already open).

Once open, click to add a plug-in in a track. When the "Add FX to" window comes up, search for `tonegenerator` and you should see your newly installed plug-in.

![Example of loading the plug-in](../imgs/load-plugin.gif "Example of loading the plug-in")

#### Trouble Shooting

If you are unable to find your plug-in, and you followed the procedures above, you should next try the following;

- Open Reaper's system preferences
- Navigate to the "VST" tab under "Plug-ins"
- Click the "Auto-detect" then "Re-scan" buttons.
- Finally click "OK".
- Try finding and opening the plug-in again.

![VST settings tab in Reaper.](../imgs/rescan.png "VST settings tab in Reaper.")

### soundhack

The next set of plug-ins is from Tom Erbe and his Sound Hack project. Please download the "Delay Bundle" from the following website. (_You should select the correct version for your operating system._)

- [SoundHack](https://www.soundhack.com/freeware/)

You will install these plug-ins just like above.

### Valhalla

The next plug-ins we are going to install this week are three from [Valhalla DSP](https://valhalladsp.com).

These plug-ins come with installers, so, they should install themselves automatically.

- [Valhalla Super Massive - Valhalla DSP](https://valhalladsp.com/shop/reverb/valhalla-supermassive/)
- [Valhalla Space Modulator: Flanger Plugin - Valhalla DSP Plugins](https://valhalladsp.com/shop/modulation/valhalla-space-modulator/)
- [Valhalla Freq Echo: Freqency Shifter Plugin - Free Reverb Plugin](https://valhalladsp.com/shop/delay/valhalla-freq-echo/)



### ++audio

Finally, please install the "Rubbadub" delay plug-in from ++audio.

- [Rubbadub - ++Audio](https://ccrma.stanford.edu/~adam/++/index.php?page=effects&effect=rubbadub)

Like the Valhalla Plug-Ins, these include an automated installer.

-->


## Video Demo

<div class="embed-responsive embed-responsive-16by9"><iframe class="embed-responsive-item" src="https://www.youtube.com/embed/pKbJTAg3vJA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
