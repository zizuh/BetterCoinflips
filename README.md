# BetterCoinflips
<a href="https://github.com/Mikihero/BetterCoinflips/releases"><img src="https://img.shields.io/github/downloads/Mikihero/BetterCoinflips/total?label=Downloads" alt="Downloads"></a>  
  
SCP:SL plugin that adds a Risk-Reward mechanic to the in-game coin. Whenever you flip a coin a 'random' effect will happen depending on the coinflips outcome.

# Features:

- Whenever a player flips a coin and it lands on heads one of the following will happen:  
 1. They will receive a Containment Engineer/Facility Manager keycard.  
 2. They will recevive a 'medical kit' consisting of a medkit and painkillers.
 3. They will be teleported to the escape zone doors.  
 4. They will be healed by 25 health.
 5. Their hp will be increased by 10%.
 6. They will get an SCP-268.
 7. They will receive a random good effect for 5 seconds.
 8. They will get a Logicer with 1 ammo.  
 9. They will receive an SCP-2176. 
 10. They will receive a pink candy. 
 11. They will receive a revolver with the worst attachments possible. 
 12. They will get an empty micro hid.
 13. MTF/CI will respawn immediatly.
 14. Their scale will be set to 1.3/0.5/1.3.
 15. They will receive a random item.

- Whenever someone flips a coin and it lands on tails one of the following will happen:  
 1. Their hp will be reduced by 30%.  
 2. They will be teleported to Class D cells.  
 3. They will get a random bad effect for 5 seconds.  
 4. The Alpha Warhead will be enabled or disabled depending on it's current state.  
 5. Lights all across the map will be turned off for 10 seconds.  
 6. A live grenade will appear on their head.
 7. A live flash grenade will spawn on their head.
 8. They will be teleported to an SCP if there are any alive, otherwise they'll lose 15 hp.
 9. They will lose all but 1 hp.
 10. Thye will receive a primed SCP-244.
 11. They receive an SCP-173 tantrum.
 12. A fake CASSIE is sent saying that SCP-173 was killed by a Tesla gate.
 13. They will be forceclassed to a random SCP.
 14. Their inventory will be reset.
 15. Their role will be changed to the opposite one (class d - scientist, mtf - ci etc.)
 16. An instantly exploding grenade will spawn on their head.
 17. They will swap places with another player.
 18. They will be kicked.
 19. They will be replaced by a random spectator.
 20. They will be teleported to a random tesla.
 21. Their inventory will be swapped with another player's inventory.
 22. They will be teleported to a random room.
 23. They will be handcuffed and lose their items.

- The plugin will prevent the spawns of a specified amount of coins around the map.
- The plugin will replace a specified amount of the chosen item (by default SCP-500) with a coin in the SCP pedestals.
- The plugin will assign a random amount of uses to every thrown coin. This amount can be read or set with a command. If a coin runs out of uses it breaks.

# Commands

- GetSerial - gets the serial number of an item held by you or another player.
- CoinUses - gets or sets the number of uses a specific coin has. Example usage: `coinuses get player 5`, `coin uses set player 4`, `coinuses set serial 10` 

# Permissions

- bc.coinuses.set - grants access to the CoinUses Set command
- bc.coinuses.get - grants access to the CoinUses Get command

# Default config
[Read the Config.cs](https://github.com/zizuh/BetterCoinflips/blob/cbfd8c43b26d18963498b7b527b81aae809588f9/BetterCoinflips/Configs/Config.cs)
