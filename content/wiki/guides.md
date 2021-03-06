---
title: Guides
author: YourMCGeek
---

Table of Contents
- [Chunk Loaders](#Chunk-Loaders)
  - [Always Online vs Online Only](#Always-On-vs-Online-Only)
  - [Checking Your Balance](#Checking-Your-Balance)
  - [Creating a Chunk Loader](#How-to-Create-Chunk-Loaders)
  - [Viewing Active Chunk Loaders](#How-to-View-Active-Chunk-Loaders)
  - [Reading Chunk Coordinates](#How-to-Read-Chunk-Coordinates)
- [Claiming](#claiming)
  - [How to Claim](#how-to-claim)  
  - [2D vs 3D](#2d-vs-3d)
  - [How to Subdivide](#how-to-subdivide-claims)
- [Crates](#crates)
- [MultiMC](#multimc)
  - [How to Install](#how-to-install)
  - [Login to your Profile](#login-to-your-profile)
  - [Allocate More Ram](#allocate-more-ram)
  - [Setup an Instance](#setup-an-instance)
    - [With Link](#with-link)
    - [With ZIP](#with-zip)
  - [Archive Cannot Find instance.cfg](#archive-cannot-find-instance.cfg)
  - [Adding Java Arguments](#adding-java-arguments)


# Chunk Loaders
Modded Chuck Loaders have been disabled on ShadowNode servers globally, therefore we have added a plugin known as Better Chunk  Loaders to achieve their purpose. There are two types of Chunk Loaders, Always On and Online Only. To view chunk borders, hit ``F3+g``

The most basic command in the plugin is ``betterchunkloader``, or just ``bcl`` for short. Executing this command will open an interface in the chat that the user may interact with. The interface will contain a list of active chunk loaders you currently own, along with some user-friendly icons. An example of the interface is below. 
![Interface](https://www.shadownode.ca/attachments/upload_2018-7-1_23-49-25-png.305/)

### Always On vs Online Only
Always On is a chunk loader which is online 24/7 and will keep the chunk loaded. However, the chunk loader will stop loading the chunk after 3 days of activity. Once the owner returns, it will resume loading the chunk.The Online Only chunk loader will only load the chunk when the owner of the loader is online.

### Checking Your Balance
To check the number of chunks you may use/have used, you can click the ``Balance`` or run ``bcl bal``. The interface will state the number of both Always Online and Online Only chunks that are currently active (used) and are available. 
![Balance](https://www.shadownode.ca/attachments/upload_2018-7-1_23-54-41-png.306/)

### How to Create Chunk Loaders
From the main interface, you should click the ``Create`` icon to begin the process of creating a Chunk Loader. An interface will open and should look like the following image.
![Create a Chunk Loader](https://www.shadownode.ca/attachments/upload_2018-7-2_0-2-38-png.307/)

The interface will state the name of the chunk loader Owner. It will also give you the coordinates of the chunk that you are currently standing in. Please note that these coordinates are different than regular XYZ coordinates. To create an Always Online chunk loader or Online Only chunk loader, click their respective icons. You should be prompted with the following interface.
![Create a Chunk Loader](https://www.shadownode.ca/attachments/upload_2018-7-2_0-15-28-png.308/)

The ``Radius`` icons will determine the size of the chunk loader. You can only load as many chunks as your balance allows. Hovering over the icon will display how many chunks will be loaded with each radius upgrade.
![Radius](https://www.shadownode.ca/attachments/upload_2018-7-2_0-27-8-png.309/)

After you select your radius size, your chunk loader will be created. You will be shown a confirmation window which will display your name, loader id, and state. If you'd like to delete your loader and regain your chunk balance, click the ``Delete`` icon.
![Chunk Confirmation](https://www.shadownode.ca/attachments/upload_2018-7-2_0-36-1-png.310/)

## How to View Active Chunk Loaders
Once you have Chunk Loaders active, running ``bcl`` will contain some information regarding regarding your active chunk loaders. You can hover over the ``Chunk`` icon to view the coordinates of the chunk loader. Clicking ``view`` will pull up the same prompt that was displayed after you created your loader originally. 
![BCL Balance](https://www.shadownode.ca/attachments/upload_2018-7-2_0-53-17-png.311/)

## How to Read Chunk Coordinates
to view the coordinates of the chunk you are currently in, press ``F3``. You will see the typical statistics of your game, which should resemble the image below. The value in the red box is your chunk coordinates.
![Chunk Coordinates](https://www.shadownode.ca/attachments/upload_2018-7-2_0-58-15-png.313/)

# Claiming
All of our servers use the latest Grief Prevention plugin for claiming.

## How to Claim
To claim you can either use a Golden Shovel you make, or one provide to you when you first join the server (some servers do not start with the golden shovel or have had their claim tool changed). Every block claimed is accounted for. You can buy claim blocks from the tokenshop, or from the store. Before claiming any land, please make sure to check which method of claiming you currently are using, [2D or 3D](#2D-vs-3D). Once your method of choice is confirmed, we can begin claiming. If you are in 2D mode, right click two opposite corners of the intended claim. For 3D mode, right click two opposite corners, one at the lowest point in the claim, and the other at the highest point in the claim. You can right click the air or ground with a stick to see who claims the block you are looking at.

### 2D vs 3D
2D means that no what Y level you claim the blocks on, Grief Prevention will make your claim from bedrock to make build level. 3D will require you to claim your area in a cube and will only claim what is inside the cube.

## How to Subdivide Claims
Subdividing your claim means making smaller sections in the bigger claim to allow people to build/access certain parts of your base. To subdivide claims, hold your golden shovel and run the command ``subdivideclaims``. This changes your golden shovel to create smaller claims. This is always in 2D mode, but it reaches to the highest level of your main claim. When you select two corners you see iron blocks instead of golden blocks. To get out of subdivideclaims mode, scroll your mouse wheel off the golden shovel and then back onto it. This can be used to make towns and/or sell plots to other players for in-game currency.

# Crates

We use a plugin called HuskyCrates to manage our crates. Crates contain items, the quality of which depends on the tier of the crate. To open a create you must hold the crate key in your hand and right click the corresponding crate. You can obtain crate keys by either purchasing them from our [store](https://shop.shadownode.ca), or buy buying them in our token shop. [This spreadsheet](https://goo.gl/9dXBT6) shows everything you can get from crates. It's listed by crate tier and mod. Some items on this list may not be on your server as some modpacks don't have all the mods as others. 

# MultiMC
MultiMC is a Minecraft launcher. It can be used to launch vanilla Minecraft, custom modpacks, or regular modpacks. The launcher is very good for Linux users or those who don't like the Twitch Launcher. **We strongly recommend this launcher.**

## How to Install
1. Head to [MultiMC](https://multimc.org) and select which software is most appropriate for you.
2. Locate the downloaded zip file and export it into a folder.
  - On most machines, you can right click the folder, click export files and select your destination. If your machine does not have this option, head to Google!
3. Open the MultiMC folder generated at the location specified during export and double click the MultiMC executable.
4. Complete the final setup details that it asks for, such as your preferred language and java version.

## Login to your Profile
1. Click Profiles at the top
2. Click Manage Accounts in the dropdown
3. Click Add on the right side and fill out the request information

## Allocate More Ram
*This must be done before setting up an instance*
1. Click the settings, found at the top of your toolbar
2. Head to Java on the left side
3. Under the memory section you will be able to change your minimum and maximum allocation
  - We do not suggest going above 6144mb
  - 4096mb is the average selection

## Setup an Instance
### With Link
1. Copy the link address from the modpack download page
2. In MultiMC, select the white blank paper at the top that says Add Instance
3. Check the box next to Import Modpack (local file or link)
4. Paste your link into the text box below
5. Enter the name of the modpack
6. Click on the instance and launch

**To update you must reinstall the new update in the same manor as you downloaded the pack oringinally. Remember to save any world files for single player worlds.**
### With Zip
1. Download a zip file of the modpack from the modpack download page
2. In MultiMC, select the white blank paper at the top that says Add Instance
3. Check the box next to Import Modpack (local file or link)
4. Click the 3 dots and locate your zip
5. Once located, click ok
6. Launch and enjoy

## Archive Cannot find instance.cfg
Ensure that you are running a version higher than or equal to 0.6.0. You can find your version at the top of the launcher toolbar. If your version is not higher than or equal to 0.6.0, follow [this tutorial](https://github.com/MultiMC/MultiMC5/wiki/Switching-update-channels)

## Adding Java Arguments
1. Locate the Settings tab at the top of the toolbar
2. Click Java on the left side
3. Locate JVM Arguments in the Java Runtime section
4. Fill in your desired arguments in the blank
5. Click test to verify everything is working properly.