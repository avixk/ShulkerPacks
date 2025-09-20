# ShulkerPacks
open shulker boxes without placing them down

![Image of Title](https://i.imgur.com/m1Y8zsr.png)

### Description:
Tired of having to put down your shulker to open it? Or maybe youre in claimed land? Now you can right click the shulker in your inventory to open it, or just right click the air with it in your main hand!

This also works in chests (GUIs can be blacklisted with their inventory name in the config)

### Permissions:
shulkerpacks.use (lets the player use shulker packs)

### Config:
```
# BLACKLIST AUCTION INVENTORIES HERE
# blacklist works as follows:
# if you include the word "a" in the blacklist, every inventory with the letter "a" will be blocked.
# because of this, try to be as precise as possible.
# If your inventory contains extra characters, such as "Auction Page 8", simply blacklisting "Auction Page" will block every page
blacklistedinventories: ["&4&lMineXChange", "test inventory","Crafter"," Contents","Auction","Preview","DeathSign"," Item", "&cTrade with","Editing","Grave"]

canopeninair: true            #false will prevent users from opening shulkerboxes by clicking the air
canopenininventory: true      #false will prevent users from opening shulkerboxes in their inventory
canopeninchests: true         #false will prevent users from opening shulkerboxes in chests
canopeninenderchest: true     #false will prevent users from opening shulkerboxes in enderchests
canopeninbarrels: true        #false will prevent users from opening shulkerboxes in barrels
canplaceshulker: true         #false will prevent users from placing shulkerboxes by accident

# true will prevent users from opening shulkerboxes within 7 seconds of being hit by a player
disable-in-combat: false

# cooldown for opening shulkers in milliseconds
shulker_open_cooldown: 100

defaultname: "&0Shulker Box"
shiftclicktoopen: false # applies to both ingame and in inventory
shulkervolume: 1              #0.1 is quiet, 1 is loud

# go to previous menu instead of just closing the shulker
open-previous-inventory: false

```

![Image of Boost](https://i.imgur.com/8OAtOy5.png)

Can conflict with auto-sorting inventory plugins
