##########################################
#  PerWorldInventory configuration file  #
#                                        #
#  If new values are added to the        #
#  config, they will not automatically   #
#  be added here. They will default to   #
#  false if not present.                 #
##########################################

# Version of the config.
# When updating config, copy the new verison number here.
# Only ever change when adding new config options!
# Used to notify administrators on config updates.
config-version: 4

# If true, the server will change player's gamemodes when entering a world
# The gamemode set is configured in the worlds.yml file
manage-gamemodes: true

# If true, players will have different inventories for each gamemode
separate-gamemode-inventories: true

# If true, any worlds that are not in the worlds.yml configuration file will share the same inventory
share-if-unconfigured: false

# All settings for players are here:
player:
  # Save and Load players' economy balances. Requires Vault!
  economy: false
  # Load players' ender chests
  ender-chest: true
  # Load players' inventory
  inventory: true
  # All options for player stats are here:
  stats:
    # Load if a player is able to fly
    can-fly: true
    # Load the player's display name
    display-name: true
    # Load a player's exhaustion level
    exhaustion: false
    # Load how much exp a player has
    exp: false
    # Load a player's hunger level
    food: false
    # Load if a player is flying
    flying: true
    # Load what gamemode a player is in. This is shadow-set to false if
    # 'manage-gamemodes' is true, to stop infinite loop
    gamemode: false
    # Load how much health a player has
    health: false
    # Load what level the player is
    level: false
    # Load all the potion effects of the player
    potion-effects: false
    # Load the saturation level of the player
    saturation: false
    # Load a player's fall distance
    fall-distance: false
    # Load the fire ticks a player has
    fire-ticks: false
    # Load the maximum amount of air a player can have
    max-air: false
    # Load the current remaining air a player has
    remaining-air: false

# Config Version 2 below this line #

# Configure the amount of time between saves, in seconds
# Default is 5 minutes (300 seconds)
save-interval: 300

# Config Version 3 Additions below this line #

# Attempt to figure out which world a player last logged off in
# and save/load the correct data if that world is different.
# REQUIRES MC 1.9.2 OR NEWER
load-data-on-join: true

# Print out debug messages to the console for every event that happens in PWI
debug-mode: false

# Config Version 4 additions below this line #

# Disables bypass regardless of permission
# Defaults to false
disable-bypass: false
