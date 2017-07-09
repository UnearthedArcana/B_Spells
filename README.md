# B_Spells

log
v. 0.88

2017-07-08

- New Spells: Added Protective Shell (Thanks Subtledoctor!) as a first level wiz spell.  Changed casting speed to 6 from 0
- New Spells: Added Anticipation (thanks Subtledoctor!) as a first level wiz spell.  +5 to AC, +5 breath (still 3 rounds).  Maybe tone down and make a cantrip 
- Added Alarm
- Briefly tested (installation and Alarm)
- Added Frost Ray wizard cantrip
- Added jolt cantrip.  Test (also, maybe too good)
- Added Drowse Cantrip (thanks subtledoctor!)

2017-07-07

- Finsihed cantrip 'bless' removal code (bless, chant, prayer, curse and doom)
- Added Protective Shelll to New Spells.  Change exclude flag from abjurer to transmuter

2017-07-06

- Started cd_batches cantrip removal macro (b_bless_cantrip_arrays) TEST!

2017-07-05

- Started special immunity code
- IWDEE spells converted some spells to ALTER_SPELL_HEADER 



2017-07-04

- Removed haste immunity from free action (still need to change haste effects from 126 to 176)
- Exp. retreat changed to 176

2017-07-01

- Nature's Wrath: Added fist itm, modified stats to fit description.  Fixed it(?)

2017-06-20

- Entropy prot.  Adding prot from each pro twice.  The action must be running SOMEWHERE...

- fixed (duh, each component was running it...)

- Started splitting up tra (IWDEE divine spells so far...need to go spell by spell to seperate fnp, and revision apsects of it )

2017-06-19

- Improved entropy prot.  BUT adds pro from sunscorch pro twice.  Not sure if it adds pro from snowball swarm or other addded spells.  CHECK AND FIX

2017-06-18

- Copied entropy prot to flash drive.  Looks like SR and 'vanilla' are almost identical (with SR just having a difference for sunscorch).  Simplify the process...

2017-06-17

- Actually added the decastave spell (forgot to put the actual spell in folder)

- Improved entropy shield protection (esp. projectiles) BE SURE IT INTERACTS WELL WITH FnP AND SR BEFORE RELEASE

- NEED TO ADD SR ENTROPY SHIELD PROTECTION

2017-06-11

- Added scroll to hand of carnage.  Didn't place, however

2017-06-10

- Added decastave, cat's grace

- squashed a bug with scrolls (i.e. alter check for wrong opcode)

- Added Lance of disruption and Beltyn's Burning Blood

2017-06-09

- Added Expeditious Retreat IWDEE spell, though need to test!!!

2017-06-04

- Fixed cause/inflict minor wounds in both cantrip and revised spells

- Added scroll for emotion: courage

- New spells: Made eyes of dead cantrip if zero lev cantrip installed

2017-06-01

- Added scrolls and added them to stores/creatures: SSnoeballStorm, Shadow mon, V sphere, ice lance

- Started Cantrip Alternate spells: Cause/Inflict minor wounds.  Need to fix that one!!!  Check both sides (cantrip and alter code)

2017-05-25_2

- Updated cause minor wounds.  Tested sucessfully with IWDIFICATION ANd Revise

2017-05-25

- Updated Cure minor wounds/canticle/malediction/Meditation (tested with IWDIFICATION)

2017-05-24

- Added immunity to cure minor wounds

- Eh, on second thought, maybe seperate out compatibility after.  Test what I have for now, though..

- Started compatiblity cantrips and other spells.  Going to do compatibility in it's own tpa at the very end of cantrips.  Same with IWDEE spells, etc.
   - Just a blank tpa right now.  Need to concentrate and test before moving on...(especially with Prayer Spell...
   - Installed IWDIFICATION on main laptop beamdog bgee for testing purposes. (both for cantrip compatibility and to install only spells not installed by that mod)
   - Test  possible orders: Cantrips/IWDification/IWDEE spells
                            Cantrips/IWDEE spells/IWDification
                            IWDEE spells/Cantrips/IWDification
                            IWDEE spells/IWDification/Cantrips
                            IWDification/IWDEE spells/Cantrips
                            IWDification/Cantrips/IWDEE spells

2017-05-22

- Tested traified REPLACE_TEXTUALLY in cantrips (cure minor wounds)  WORKS!!

2017-05-20

- Fixed icons for Misfortune (though, I think that's the icon for misfire...)

2017-04-02

- Portrait icon for emotion: courage (IWDEE Spells)

- Portrait icon for good prayer (IWDEE SPELLS)

2017-04-01

- Cure minor wounds (compatibility with revised spells and fnp) UPDATE FNP!!!

2017-03-14

- Updated Exaltation, blood rage, Imp Sanctity of mind and Entropy Shield to new block system

- Fixed Shadow Monsters

- Fixed Recitation (though, still want to update 'friendly' bam

- Reverted to IWDEE pro names

- Added Wizard spell: Shout

2017-03-11

- Fixed issue with Prayer and Recitation.  NEED TO ADD TO FNP.

- Added Wizard 4th level emotion spells (sometime in the past--I think I deleted past progress documentation!)

- Updated Blood range and imp sanctity of mind using cleaner method (NEED TO DO Exaltation)