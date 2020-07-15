# Spells & Magic  
  
This mod aims to increase player options by adding new and revised spells, as well as new options for spellcasters (and, in some cases, non-spell casters).   

## Special Note: EEex
This mod does not require [EEex ](https://forums.beamdog.com/discussion/71798/mod-eeex-v0-7-0-alpha/p1), but many of the components will either work best with EEex installed, or will unfortunately be dependent on EEex (because there is no other reasonable way to implement the component).  As such, I encourage you to click on the link and install EEex if you are able.  

# Components Overview

##  Spells & Magic: 101-103: New Spells  

This group offers new spells, either imported from Icewind Dale, or Really new spells created from scratch (with a lot of help!).  See the next section for Spell Descriptions.  

## Known Issues (New Spells): 
- The illusory summoning spells (Phantasmal Force, Improved Phantasmal Force and Spectral Force) added by this mod allow players to bypass the normal limits on summoned monsters (i.e. they will be able to summon the maximum plus any creatures summoned by these spells.) 
- Ranger Exclusive spells like Stormbow can become available to druids where their alignment restrictions have been expanded.  Specifically, druids that can become something other than morally neutral will have access to these spells.  

### 101: All new spells (including IWDEE spells if applicable)  

This component installs all new spells provided by this mod.  That is, it will install both the Icewind Dale spells (if applicable), and the 'new new' spells offered by this mod.  See the Next Section for Spell Descriptions.  

### 102: IWDEE spells only

This component will only install IWDEE spells if they are not already installed.  

### 103: New spells only

This component will only install the unique spells offered by this mod.

## Spells & Magic: 111 - ???: Cantrips: Infinite Innate: Components   
These components offer innate infinite cantrips to various divine and/or arcane classes.  This component interacts with the 300 series of components (i.e. Cantrips: 1st level Cantrips) in that no class will have access to both infinite innate and 1st level cantrips.  So, for example, if you have infinite cantrips for all arcane classes installed, and you install 1st level cantrips for all classes, then only divine classes will get access to 1st level cantrips.  

See the Next Section for Cantrip Descriptions. 

### 111: Infinite Innate Cantrips for all divine and arcane classes
This component adds infinite innate cantrips to all divine and arcane classes.  If this component is installed, there will be no option to install 1st level cantrips   

### 112: Infinite Innate Cantrips for all divine classes
This component adds infinite innate cantrips to all divine classes. If this component is installed, divine classes will not have an option to cast 1st level cantrips.  

### 113: Infinite Innate Cantrips for all arcane classes
This component adds infinite innate cantrips to all arcane classes. If this component is installed, arcane classes will not have an option to cast 1st level cantrips.  

##  Spells & Magic: 201-???: Performance Fatigue
This group of components adds an extra cost to spell casting: fatigue.   
  
## Known Issues (Performance Fatigue): 
- 
  
### 301: Performance Fatigue: 
  
##  Spells & Magic: 301-???: Unique Spell Lists  
This group of components gives unique spell lists to different spell casting classes and kits.   
  
## Known Issues (Unique Spell Lists): 
- 
  
### 301: Unique Spell Lists: 

## 401-???: Turn bonus by Charisma
This group of components applies charisma bonuses to the turn attempts of clerics and/or paladins (as well as other classes that might get access to turn-like abilities).  
  
## Known Issues (Turn bonus by Charisma): 
- 

### 401: Turn bonus by Charisma: 

\page
  
## Spells & Magic: 501 - ???: New Items 

This group offers new magic items, either imported from IWDEE or completely new creations.  

### 501: Install All new items (including IWDEE items if applicable)

This component will install all new items, including IWDEE and unique items offered by this mod.  

## Spells & Magic: 601 - ???: Spontaneous Casting
This group of components offers various implementations of 'Spontaneous casting' for divine classes.  By Spontaneous Casting, I mean that affected characters can spontaneously 'convert' their existing spell slots to other spells, like the 3e+ cleric's ability to convert their spells to cure or inflict spells.  
  
## Known Issues (Spontaneous Casting): 
- 

###  601: Spontaneous Casting (By Pecca)

## Spells & Magic: 701 - ???: Use Scroll  
This group of components allows certain classes and kits use scrolls that they would not otherwise be able to use.  
  
## Known Issues (Use Scroll): 
- 

###  701: Use Scroll: 

## Spells & Magic: 801 - ???:  Illusion immunity for high int  
  
## Known Issues (Illusion immunity for high int): 
- 

###  801: Illusion immunity for high int: 

## Spells & Magic: 901 - ???:  Magical Defense Adjustment  
  
## Known Issues (Magical Defense Adjustment): 
- 

###  901: Magical Defense Adjustment: 

## Spells & Magic: 1001 - ???:  Spell Power for high attributes 
  
## Known Issues (Spell Power for high attributes): 
- 

###  1001: Spell Power for high Charisma: 

## Spells & Magic: 1101 - ???: Variant Turning 
  
## Known Issues (Variant Turning): 
- 

###  1101: Variant Turning: 



##  Spells & Magic: 4001 - ???: Magic Item Creation   

This group of components deal with magic item creation and recharging.  These components allow players to create scrolls, potions and wands, and they allow players to recharge wands.  There are a number of different creation subsystems for each, and users can install different subsystems for different items.  These components can also interact with the proficiency system (see below for details).  
  
This component adds new magic items, and item creation.
The general description of each component can be found below.  For a more in depth description of each, see the following sections.  

## Note  
The added items are identical to those added by Spells and Magic and B_Kits. However, consumable magic items--in particular scrolls and wands--work slightly differently in these three mods. These mods are completely compatible, however, and any changes will be noted in the description.

## Known Issues (Magic Item Creation): 
- 

### 4001: Install the Standard (Simulated PnP) version of Item creation for all casting classes

This component will install the standard version of Item Crafting and tries, as much as possible, to emulate standard pnp rules.       

##  Spells & Magic: 5001 - ???: High Level Abilities  
  
This group of components deal with high level abilities, either adding new HLAs, modifying existing HLAs, or both.  

## Known Issues (High Level Abilities): 
-  

<div class='wide'>  
  
# Spell Descriptions  
This section describes all New Spells (i.e. IWDEE spells, and spells added by this mod).  

## b_spells_settings.ini  
You can choose not to install any of the spells detailed below by setting the relevant variable to 0 in b_spells_settings.ini.  For example, if you do not want to install the Cantrip spell, then open b_spells_settings.ini and change this:

`OUTER_SET b_cantrip_spell                      =	1`

to this:

`OUTER_SET b_cantrip_spell                      =	0` 

You can also choose to install different variants for certain spells.  Find the details for each change below in the individual spell descriptions. 

</div>

<details>
  <summary>Template</summary>
  
### Level 1  

#### **Spell Name** (New)     
___  
(School)   
- **Level**: 1  
- **Range**: 0   
- **Duration**: 5 turns   
- **Casting Time**: 1   
- **Area of Effect**: The Caster    
- **Saving Throw**: None    

Description

>_**Revision Notes**_:  Revision notes if a revised spell

>_**Specific Additions**_
>1) variable names in b_spells_settings.ini

>***Notes***:    Compatibility notes

  
</details>

\page  

<div class='wide'>  

# Spell Descriptions: Arcane Spells  
This section describes Installed Arcane spells, whether Cantrips, IWDEE spells, or completely new Arcane spells.      
 
</div>

\page  
<div class='wide'>  

## Spell Descriptions: 0-Level Arcane Cantrips 
    
 
</div>

PLUG IN SPELL DESCRIPTIONS HERE
 
\page     
<div class='wide'>  

## Spell Descriptions: New Arcane Spells 
  
### Level 1  
 
</div>

PLUG IN SPELL DESCRIPTIONS HERE

<div class='wide'>  

# Spell Descriptions: Divine Spells  
This section describes Installed Divine spells, whether Cantrips/Orisons, IWDEE spells, or completely new Divine spells.      
 
</div>

\page  
<div class='wide'>  

## Spell Descriptions: 0-Level Divine Orisons  
    
 
</div>

PLUG IN SPELL DESCRIPTIONS HERE

<div class='wide'>  
  
# Item Descriptions  
This section describes all New Items

## b_spells_settings.ini  
You can choose not to add any of the items detailed below by setting the relevant variable to 0 in b_spells_settings.ini. 

</div>


\page  

<div class='wide'>  

# Item Descriptions: Potions  
This section describes Installed Potions, whether IWDEE potions, or completely new potions introduced by this mod.        
 
</div>

# extra stuff

# Class 'Extras': 10001-???
This group of components is just a collection of 'extra' options related to arcane and/or divine casting.  Note that these components are identical to those with the same names found in Skills & Proficiencies or B_Kits.  So, if you've installed that modification in one of these other mods, they should not be installed again.  In this case, Spells & Magic _should_ skip any duplicates.  Please let me know if it does not.  
