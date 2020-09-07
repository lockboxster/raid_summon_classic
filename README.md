# raid_summon_classic
Summoning tool for WoW classic, currently under Development

Version 1.0 Goals : 
Summon Tracking, indicate a player has a summon pending in raid window, and/or debuff.

Tasking : 
#
# Set up window
#
# Configure Warlocks in Raid
# Run Scan in Raid for all
# Class API call Returns Array :
# className = String ie. Warrior, Warlock, Mage dependant on Class ID
# classFile = String ie. WARRIOR WARLOCK MAGE dependant on Class ID
# classID   = number
#
# classInfo = C_CreatureInfo.GetClassInfo(classID)
# Will use this to determing the class of Players in Raid
# RaidWarlocks =
#
# Array of Summon Targets
#
#  Check if RaidWarlocks are casting Summoning spell , if so what target.
#
#   Summon Spell ID : 698
#  API Command : isCurrent = IsCurrentSpell(spellID)
# isCurrent = IsCurrentSpell(698)
# if true return PlaceIcon or PlaceDebuff ( Haven't decided if I'm going to place these in just the Addon Window, or also displaying as a Debuff or Flashing color on Bar.
#
#
 
