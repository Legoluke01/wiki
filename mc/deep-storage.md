# Deep Storage Plugin

## What is it?
The Deep Storage plugin is a mod much like the popular mod **Applied Energistics**. It allows for mass storage in one single chest, along with allowing wireless access via the wireless control.

## Resourcepack
When joining the server you'll be asked to use a resourcepack, this is **not** required!
It's only to give custom textures to the Deep Storage items. If you don't use the resourcepack though, you'll just see stone axes/shovels, but everything will still work.

**Pro Tip #1:**
If you don't want to use the resourcepack and hate having the prompt show up, you can follow these steps:
1. Multiplayer
2. Select the server
3. Edit it
4. There is an option under the address bar, change it to Disabled

**Pro Tip #2:**
If you want to use the resourcepack but hate having it to unload/load it every time you join, you can simply download the resourcepack and have it enabled all the time.
First, follow the steps in **Pro Tip #1**, then, download the resourcepack here: https://drive.google.com/uc?export=download&id=13ZZzmERLZUb_NVG76BctAWnzVkUr6WLb
Once you've downloaded it, move it into your resourcepacks folder and enable it.

{% hint style="success" %} To see if it's working, do `/crapi book`, if you see the custom textures, you did it! If you see stone axes/shovels, please open a ticket in #support. {% endhint %}

## Getting Started
First off, you'll need to get yourself quite a bit of the following materials: Quartz, Iron, Diamonds, Redstone, Glass, and Emeralds.

Next, you'll need to make a **Special Crafting Table**. The recipe for it is below.

![4 Iron Blocks, 4 Glass, 1 Diamond Block](../.gitbook/assets/deepstoragecraftingtablerecipe.PNG)

A little expensive, but worth it!
After you craft that, that'll be your new crafting table for all things **Deep Storage**.

The next thing you'll need to make is a **Deep Storage Loader**. The recipe is shown below.

![4 Iron, 1 Quarts](../.gitbook/assets/deepstorageloaderrecipe.PNG)

Next, you'll want to get an **empty** double chest, and right-click the chest with the **Deep Storage Loader**.

Now, you need to make a **Storage Cell**. Storage cells are used to craft **Storage Containers**, which are used to determine how many items a unit can hold.
The recipe for the smallest storage cell is shown below.

![4 Redstone, 4 Quartz, 1 Gold](../.gitbook/assets/storagecell1krecipe.PNG)

{% hint style="info" %} **Storage Cells** can be upgraded, run `/crapi book` to see the recipes for the rest of the **Storage Cells**. {% endhint %}

Now, you have to make a container for your **Storage Cell**. The recipe for it is shown below.

![2 Glass, 3 Redstone, 1 Storage Cell (1k), 3 Iron](../.gitbook/assets/storagecellcontainerrecipe.PNG)

{% hint style="info" %} If you are wanting to craft a **Storage Container** for an upgraded **Storage Cell**, the recipe will be different, please see `/crapi book` for the recipes involving larger **Storage Containers**. {% endhint %}

Great! Now you have a **Storage Container**.
The final step is to insert the **Storage Container** into the Deep Storage Unit (the chest you right-clicked with the **Deep Storage Loader**).

Your **Deep Storage Unit** should now look like this:

![](../.gitbook/assets/deepstorageunitexample.PNG)

Congratulations, you have successfully created your first **Deep Storage Unit**!

{% hint style="success" %} To know if it's working or not, try putting some blocks in (netherrack, cobblestone, anything you have a lot of)! {% endhint %}

## Extra Info regarding Storage Containers/Units
So, in each chest you can have a maximum of 5 **Storage Containers** regardless their size. Each storage container may only hold 7 different types of blocks, so for every double chest, you are limited to only having 34 different types of blocks.

Another thing to note is that you can transfer **Storage Containers** chest-to-chest, all data will sync in to chest once you place it inside.

The **Deep Storage Units** work with hoppers, when you open the chest/unit, click the wrench item on the bottom-right. It'll switch the menu on the right to have two options, **Input** and **Output**. Simply click the block that you would like to output from the unit, and it will automatically start the transfer. One thing to note with hoppers attempting to place items **in** the unit is that the chest will only accept items that are in your **Storage Containers**. Items that aren't will just stay in the hopper.
Using an IO upgrade (see `/crapi book` for recipe) allows you to increase the input/output speed for the chest/unit.

## Wireless Terminal
The Wireless Terminal will allow you to access Deep Storage Units from anywhere in the server. You can only link these to **one** unit though.
The Wireless Terminal requires you to also craft a Wireless Receiver, see below for the Wireless Receiver recipe:

![](../.gitbook/assets/wirelessreceiver.PNG)

The Wireless Terminal recipe is shown below (you **need** to have 32 redstone blocks [total of 64]):

![](../.gitbook/assets/wirelessterminal.PNG)

{% hint style="info" %} Only **VIPs** can use Wireless Terminals. Become a VIP here: https://srnyx.xyz/donate {% endhint %}
