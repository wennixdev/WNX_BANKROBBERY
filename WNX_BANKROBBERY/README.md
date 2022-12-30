◉ WNX_ToFFleeca
Fleeca Robbery
- Discord link https://discord.gg/ygfvJ6YRGx

Preview Video : https://youtu.be/ndWjGjR8qAM

◉ You need to
- ox_target https://github.com/overextended/ox_target.git
- ox_inventory - https://github.com/overextended/ox_inventory - Documentation : https://overextended.github.io/docs/ox_inventory/
- ox_lib - https://github.com/overextended/ox_lib - Documentation : https://overextended.github.io/docs/ox_lib
◉ Item used for the robbery
- 1x id_card_f
- 2x thermalcharge
- jewels
- goldingots
- black money
it can be easily modified in the server file

Locales cs and en

**for the fleeca items, u can add these to the file \ox_inventory\data\items.lua  (check if they doesn't exist before add lines)**
```
    ['thermalcharge'] = {
        label = 'Charge Thermique', -- put your translation here
        weight = 1000,
        stack = true,
        close = false,
        description = nil
    },  
    --------------------------------------------------------------------------
    ['id_card_f'] = {
            label = 'id card f',  -- put your translation here
            weight = 150,
            stack = true,
            close = false,
            description = nil
    },
    --------------------------------------------------------------------------
    ['jewels'] = {
		        label = 'jewels',
		        weight = 250,
		        stack = true,
		        close = false,
		        description = nil
	  },
    --------------------------------------------------------------------------
    ['goldingot'] = {
            label = 'Zlata Cihla',  -- put your translation here
            weight = 1000,
            stack = true,
              close = false,
              description = nil
    },
        --**(if it's the last item of the file items.lua, delete the coma)**
```

two different zones to loot whith different items
### first zone (black_money, jewels, cards)
The door to access to the second room need to be forced too
### second room (goldingots)


# No Spam Loot
Timer function to avoid spam loot

# LSPD blip
it appears during 10 minutes, and the lspd in and out of services are mention, cauz protect and serve ;-) 
it can be easily modified in the server file.
