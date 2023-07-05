#
#epic gui made by gfhsd4gd
#
on right click:
	if player is holding grass block named "&a&lWorlds":
		cancel event
		set {_gui} to a new chest inventory with 3 row with name "&5Teleport &aGUI"
		set slot 0 of {_gui} to gray stained glass pane named "&0"
		set slot 1 of {_gui} to gray stained glass pane named "&0"
		set slot 2 of {_gui} to gray stained glass pane named "&0"
		set slot 3 of {_gui} to emerald named "&a&lFavorite!"
		set slot 4 of {_gui} to player's head named "&bCreate your own server!"
		set slot 5 of {_gui} to gold ingot named "&6Money" with lore "&6Balance: &e%player's balance%"
		set slot 6 of {_gui} to gray stained glass pane named "&0"
		set slot 7 of {_gui} to gray stained glass pane named "&0"
		set slot 8 of {_gui} to gray stained glass pane named "&0"
		set slot 9 of {_gui} to gray stained glass pane named "&0"
		set slot 11 of {_gui} to grass block named "&2Overworld" with lore "&aClick to teleport!"
		set slot 13 of {_gui} to netherrack named "&cNether" with lore "&aClick to teleport!"
		set slot 15 of {_gui} to end stone named "&eEnd" with lore "&aClick to teleport!"
		set slot 17 of {_gui} to gray stained glass pane named "&0"
		set slot 18 of {_gui} to gray stained glass pane named "&0"
		set slot 19 of {_gui} to gray stained glass pane named "&0"
		set slot 20 of {_gui} to gray stained glass pane named "&0"
		set slot 21 of {_gui} to gray stained glass pane named "&0"
		set slot 22 of {_gui} to barrier named "&c&lClose"
		set slot 23 of {_gui} to gray stained glass pane named "&0"
		set slot 24 of {_gui} to gray stained glass pane named "&0"
		set slot 25 of {_gui} to gray stained glass pane named "&0"
		set slot 26 of {_gui} to gray stained glass pane named "&0"
		open {_gui} to player
 
on inventory click:
	if name of event-inventory is "&5Teleport &aGUI":
		cancel event
		if index of event-slot is 3:
			send "&bType /favorite to add the server to your favorites!"
			close player's inventory
		if index of event-slot is 11:
			send "&aTeleported you successfully to &2Overworld&a!"
			execute command "/mvtp %player% world"
		if index of event-slot is 13:
			send "&aTeleported you successfully to &cNether&a!"
			execute command "/mvtp %player% world_nether"
		if index of event-slot is 15:
			send "&aTeleported you successfully to &eEnd&a!"
			execute command "/mvtp %player% world_the_end"
		if index of event-slot is 22:
			close player's inventory
		if index of event-slot is 4:
			close player's inventory
			set {_gui} to a new chest inventory with 3 rows with name "&bCreate your server"
			set slot 0 of {_gui} to gray stained glass pane named "&0"
			set slot 1 of {_gui} to gray stained glass pane named "&0"
			set slot 2 of {_gui} to gray stained glass pane named "&0"
			set slot 3 of {_gui} to gray stained glass pane named "&0"
			set slot 4 of {_gui} to gray stained glass pane named "&0"
			set slot 5 of {_gui} to gray stained glass pane named "&0"
			set slot 6 of {_gui} to gray stained glass pane named "&0"
			set slot 7 of {_gui} to gray stained glass pane named "&0"
			set slot 8 of {_gui} to gray stained glass pane named "&0"
			set slot 9 of {_gui} to gray stained glass pane named "&0"
			set slot 10 of {_gui} to gray stained glass pane named "&0"
			set slot 11 of {_gui} to gray stained glass pane named "&0"
			set slot 12 of {_gui} to grass block named "&bCreate your SMP!" with lore "&e&lClick to create a new SMP!"
			set slot 13 of {_gui} to gray stained glass pane named "&0"
			set slot 14 of {_gui} to compass named "&bVisit other SMPs!" with lore "&e&lClick to visit other SMPs!"
			set slot 15 of {_gui} to gray stained glass pane named "&0"
			set slot 16 of {_gui} to gray stained glass pane named "&0"
			set slot 17 of {_gui} to gray stained glass pane named "&0"
			set slot 18 of {_gui} to gray stained glass pane named "&0"
			set slot 19 of {_gui} to gray stained glass pane named "&0"
			set slot 20 of {_gui} to gray stained glass pane named "&0"
			set slot 21 of {_gui} to gray stained glass pane named "&0"
			set slot 22 of {_gui} to gray dye named "&7&lGo back"
			set slot 23 of {_gui} to gray stained glass pane named "&0"
			set slot 24 of {_gui} to gray stained glass pane named "&0"
			set slot 25 of {_gui} to gray stained glass pane named "&0"
			set slot 26 of {_gui} to gray stained glass pane named "&0"
			open {_gui} to player
			
on inventory click:
	if name of event-inventory is "&bCreate your server":
		cancel event
		if index of event-slot is 22:
			close player's inventory
			set {_gui} to a new chest inventory with 3 row with name "&5Teleport &aGUI"
		set slot 0 of {_gui} to gray stained glass pane named "&0"
		set slot 1 of {_gui} to gray stained glass pane named "&0"
		set slot 2 of {_gui} to gray stained glass pane named "&0"
		set slot 3 of {_gui} to emerald named "&a&lFavorite!"
		set slot 4 of {_gui} to player's head named "&bCreate your own server!"
		set slot 5 of {_gui} to gold ingot named "&6Money" with lore "&6Balance: &e%player's balance%"
		set slot 6 of {_gui} to gray stained glass pane named "&0"
		set slot 7 of {_gui} to gray stained glass pane named "&0"
		set slot 8 of {_gui} to gray stained glass pane named "&0"
		set slot 9 of {_gui} to gray stained glass pane named "&0"
		set slot 11 of {_gui} to grass block named "&2Overworld" with lore "&aClick to teleport!"
		set slot 13 of {_gui} to netherrack named "&cNether" with lore "&aClick to teleport!"
		set slot 15 of {_gui} to end stone named "&eEnd" with lore "&aClick to teleport!"
		set slot 17 of {_gui} to gray stained glass pane named "&0"
		set slot 18 of {_gui} to gray stained glass pane named "&0"
		set slot 19 of {_gui} to gray stained glass pane named "&0"
		set slot 20 of {_gui} to gray stained glass pane named "&0"
		set slot 21 of {_gui} to gray stained glass pane named "&0"
		set slot 22 of {_gui} to barrier named "&c&lClose"
		set slot 23 of {_gui} to gray stained glass pane named "&0"
		set slot 24 of {_gui} to gray stained glass pane named "&0"
		set slot 25 of {_gui} to gray stained glass pane named "&0"
		set slot 26 of {_gui} to gray stained glass pane named "&0"
		open {_gui} to player
 
on inventory click:
	if name of event-inventory is "&5Teleport &aGUI":
		cancel event
		if index of event-slot is 3:
			send "&bType /favorite to add the server to your favorites!"
			close player's inventory
		if index of event-slot is 11:
			send "&aTeleported you successfully to &2Overworld&a!"
			execute command "/mvtp %player% world"
		if index of event-slot is 13:
			send "&aTeleported you successfully to &cNether&a!"
			execute command "/mvtp %player% world_nether"
		if index of event-slot is 15:
			send "&aTeleported you successfully to &eEnd&a!"
			execute command "/mvtp %player% world_the_end"
		if index of event-slot is 22:
			close player's inventory
		if index of event-slot is 4:
			close player's inventory
			set {_gui} to a new chest inventory with 3 rows with name "&bCreate your server"
			set slot 0 of {_gui} to gray stained glass pane named "&0"
			set slot 1 of {_gui} to gray stained glass pane named "&0"
			set slot 2 of {_gui} to gray stained glass pane named "&0"
			set slot 3 of {_gui} to gray stained glass pane named "&0"
			set slot 4 of {_gui} to gray stained glass pane named "&0"
			set slot 5 of {_gui} to gray stained glass pane named "&0"
			set slot 6 of {_gui} to gray stained glass pane named "&0"
			set slot 7 of {_gui} to gray stained glass pane named "&0"
			set slot 8 of {_gui} to gray stained glass pane named "&0"
			set slot 9 of {_gui} to gray stained glass pane named "&0"
			set slot 10 of {_gui} to gray stained glass pane named "&0"
			set slot 11 of {_gui} to gray stained glass pane named "&0"
			set slot 12 of {_gui} to grass block named "&bCreate your SMP!" with lore "&e&lClick to create a new SMP!"
			set slot 13 of {_gui} to gray stained glass pane named "&0"
			set slot 14 of {_gui} to compass named "&bVisit other SMPs!" with lore "&e&lClick to visit other SMPs!"
			set slot 15 of {_gui} to gray stained glass pane named "&0"
			set slot 16 of {_gui} to gray stained glass pane named "&0"
			set slot 17 of {_gui} to gray stained glass pane named "&0"
			set slot 18 of {_gui} to gray stained glass pane named "&0"
			set slot 19 of {_gui} to gray stained glass pane named "&0"
			set slot 20 of {_gui} to gray stained glass pane named "&0"
			set slot 21 of {_gui} to gray stained glass pane named "&0"
			set slot 22 of {_gui} to gray dye named "&7&lGo back"
			set slot 23 of {_gui} to gray stained glass pane named "&0"
			set slot 24 of {_gui} to gray stained glass pane named "&0"
			set slot 25 of {_gui} to gray stained glass pane named "&0"
			set slot 26 of {_gui} to gray stained glass pane named "&0"
			open {_gui} to player
on inventory click:
	if name of event-inventory is "&bCreate your server":
		cancel event
		if index of event-slot is 12:
			send "&bType /createsmp <name> to create your SMP!"
			close player's inventory
		if index of event-slot is 14:
			send "&bType /visitsmp <name> to visit other SMPs!"
			close player's inventory
