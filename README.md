> ESX-KR-ADVANCED-SHOPS and ROBBERY INCLUDED

**History**
_Long time project, some of the coding is old, if you find any bugs please contact me on discord at: KRILLE#2428
If you liked this project make sure to give it some love for more future updates and scripts._

**Purpose**
_Today is actually my birthday, lol. Also to celebrate that i've being a member for a year (couple of days a go) in this forum and in the FiveM community. Aslo to celebrate the good response of the last scripts i've published._

**Updates**
Version 1.0

**Future updates**
_- I might add a NUI when you're buying the shop._
_- I will add so you can give your shop to a player (incl. NUI)._
_- I might add a proper translation, if anyone want to do it feel free to do so._

**Features**
 _- You can buy and operate your own shop._
 _- You can put and remove items from your shop._
 _- You can put your own prices on the items you're selling._
 _- It has it's own shiping system._
 _- It's configurable._
 _- You can rob other shops and get 10% of the shops worth (configurable)._
 _- If the robber runs too far away the robbery automaticly cancels._
 _- You have to physically brake the valut to succeed the robbery._
 _- It has a beatiful NUI._
 _- You can toggle all the shop blips on/off on the shopcenter._
 _- You can sell your shop_
 _- You can name your shop, the shop name and shop icon is showing on the map._
 _- It's own boss system._
 _- And much much more._

**TO-DO (IMPORTANT)**

1. If you want any more items in your shipment menu you'll HAVE to add it ON **Config.Items**
EXAMPLE:
```
[3] = {label = "Telephone",   item = "phone",   price = 1000},
```
You'll have to add up the highest number (default 2) so it becomes 3. If you already have a 3 you'll have to add an 4 and so on.

2. The shop **16** is actually Bahama Mamas Club and MUST be used with: https://forum.fivem.net/t/release-bahama-mamas-with-working-doors/140195
If you don't want the Bahama Mamas Club remove **16** from the database **ROW**.

3. If you wish to add other icons to your shop you first have to add a new row in your table (Config.Images), with src as in the image name and format and where it is located. Then you'll have to start it in ```__resource.lua```. But if you don't have a icon do not worry, i've provided you with a default box which goes in by default if the program doesn't find any other icon with the matching name.

4. You will have to configure the prices so it matches your server's economy.
Watch screenshot: https://gyazo.com/405a47991651d5de6d6c4469830c7c8b
Change delivery price by changing **price** and set it equal to whatever the price you want it to cost.

5.  You also will have to configure the shops price so it matches your server's economy.
Watch screenshot: https://gyazo.com/bed56f2e03b9f1c797ccc61f5db3d901
It's all the values **ShopValue** to change the price of the shop.

**Download**
You can download the script [here](https://github.com/KRILLE123/)

**Installation**

1. Download the files and insert them into your resouce folder.
2. Write esx-kr-advanced-shops in your server.cfg.
3. If you have any other shop script i stronly suggest you to turn them of.
4. If you are using esx_shops, please remove the table **shops** from your database.
5. Insert the SQL.
6. Enjoy the script.

Video
**https://streamable.com/0yhd1**

https://streamable.com/0yhd1
