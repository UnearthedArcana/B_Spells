# B_Spells

# log

ADD A PRIEST SCROLL COMPONENT: MORE PRIEST SCROLLS (ALSO PRIEST SCRIBING?)  

NEED TO KEEP UP WITH IMMUNITY/REMOVAL CODE ESP WITH NEW SPELLS

SEPERATE FNP NEW SPELLS (EG  FROM NON FNP NEW SPELLS (EG ALARM)

THERE IS A PROBLEM WITH THE REQUIRE PREDICATES

Version 0.88.07

2018-06-03

- ADD_SPELLed Waves of Agony

- Created scrolls for Cause LW and Curse (not placed, though)


2018-06-02

- Just realized the IWDification check isn't working.  Checking directly for spells in tp2 (first component only so far...REVISE THE WHOLE THING!)

- Rebuilt Entropy Shield from ground up.  Need to double check protections, especially with other mods (and see above) DONE

- Updated weidu to v 245
2018-06-01

- Fixed a few errors in entropy_immunity.tpa and immunity.tpa

- Added checks for FnP specific new spells and all new spells in entropy_immunity.tpa

2018-05-29

- Test install: Problem with entropy_immunity

Version 0.88.05

2018-05-25

- Reorganizing components installation procedure

2018-05-24

- Added modvar in tp2 intro

2018-05-23

- Entropy Shield: Fixed bug with Sunscorch blocking CONTINUE LINE 134 (entropy_immunity.tpa); CREATE BATCH ARRAYS FOR E SHIELD

2018-05-22

- Rechecking FnP wiz spells: Snilloc's Snowball Swarm (entropy shield doesn't seem to prot against)
- Shows me that I need to reimplement Entropy Shield protections...Started with text modifications for SSS and Icelance. 
- CONTINUE Line 103 of entropy_immunity.tpa

2018-05-20

- Tested with DR.  Installs if DR installed.  Not sure about how compatible they are

2018-05-19 

- Finished blood rage prot strings

2018-05-18

- Second pass at prot strings in BGEE.  Next is BG2EE and EET

2018-05-17

- Redoing Blood Rage: Did prot from text in BGEE

2018-05-14 

- Bloodrage specific immunities and removals
- Installed...installs, but there are...issues.  e.g. Bloodrage gives protection with some weird conditions that I don't think are intentional...

2018-05-13

- Immunity: Rage (though, I'm not sure...this needs to be tested to see that it does what it should...)

2018-05-12

- I did it CAM's WAY!!! (immunities, fear arrays)
- Added Fear, and prot from spell levels 1-4

2018-02-13

- Created mod_folder var

2018-01-28

- Updated new_spells.tra with fnp specific entries

2018-01-20

- New: Added Murderous Command
- New: Added Feral Instinct

2018-01-19

- Fixed a bug w/solvent of corrosion (wrong reference)
- Revised: Mist of Eldath to Cleansing Mist (5 rounds)
- New: Created dictate (as command, but 5 rounds)

2018-01-18

- Revised: N. Poison to Cure Affliction (also cures paralysis)

2018-01-16

- New: Iron Mind first draft 
- New: Watery Fist first draft (Credit Requiem & Mordeus)

2018-01-15

- New: First draft of Reprieve spell

2018-01-13

- Revised: Sep individual change of Goodberry (i.e. recover fatigue) from global healing boni
- New: Inclde fist bam and 3rd eff for conjure water elemental to proper folder
- New Spells: First draft Enthrall

2018-01-08

- Removed Armor prof stuff from fnp effects batch (using its own for sanity)

2018-01-05

Version 0.88.03

- Completely redid conjure water elemental
- Corellon's Arrow: specified that the bonuses apply only when in a frenzy in kit description

2017-12-30

- New Spells: 1st draft of Snilloc's Major Missile
- New Spells: 1st draft of Detect Traps and Portals
- New Spells: 1st draft Solent of Corrosion

2017-12-28

- Started Charm Monster (as a new spell)

2017-12-27

Version 0.88.02

- Dire Charm (can't control enemy) 

2017-12-26

- Charm Person or mam (can't control enemy) Have to test to see what AI does in presence of other enemies...

2017-12-23

- Hypnotism  (first draft)
- Charm person (can't control enemy)

2017-12-16

- Started Wall of force (air?) found in newspells/force_wall
- Changed to an attaction spell (still in wall_force folder--probably make party friendly and require a save.

2017-12-13

- Created Setup_IWD_Style_Spells.tpa for IWDEE style spells installation

2017-12-10

- Revised Globals (Cure med wounds)
- Revised Globals (Cure serious wounds)
- Revised Globals (Cure crit wounds)
- Revised Globals (Mass cure)


2017-12-09

- Revised globale (Cure Light Wounds) 
- Revised global (cause light wounds)
- Revised global (cure moderate wounds)
- IWDEE Cure mod wounds: Used replace_Textually
- Infravision Cantrip: Made area affect
- New Spells: Disrupt Undead (life sphere if FnP installed)

2017-12-04

- Cantrips: Fixed a few cantrips (global opcodes) and added 'no failure' to patched cantrip/spells. 

2017-12-03

- Cantrips: completed 1st draft of drench
- Cantrips: first draft drowse
- Orisons: second draft Calm
- Cantrips: Second draft of Jolt
- Cantrips: Frist draft of Chill Touch

2017-12-02

- Cantrips: Detect Evil/ALignment, 
- Cantrips: Started Drench (animation only)

2017-12-01

- Created first blush versions of abundant ammunition and camoflauge (sp) New Spells (which, btw, needs a complete overhaul)

V. 088b

2017-11-30

- Updated Stormwall

2017-11-25
- Updated Readme
- Updated Disrupt Undead
- Reorganized tras 

2017-11-24
- Cleaned up cause/inflict minor wounds cantrip and revise
- Unfailing endurance/remove fatigue improved and iwdee spells

2017-11-23
- Infravision cantrip cleaned up, and revised cleaned up
- Hold animal cantrip and revised coordinated (also w/sr)

2017-11-22
- Infravision-->Heat Vision


2017-08-11

- Shades: Fixed reference so it shouldn't crash anymore...
- Shades: Removed umber hulk reference (amimations in BGEE)
- Shadow Monsters: Added missing summons (liz men)
- Shades and SMon: Made it so up to 6 cre can be summoned

2017-07-29

- Updated fear removal
- Updated emotion removal/protection
- Tested install.  Installed, but need to test further (executes an array witin an array)
- Fixed an error with fear removal batch
- Updated and applied (generally) remove and protect vs. berserk
- Charm protection added (general) for strings

2017-07-28_2

- Updated Lev 3 prot
- Updated Lev 4 prot
- Tested: Prot lev 1-4 looks good (cursory obervation)

2017-07-28

- Updated-again!-lev one protection
- Tested. Installed
- Updated lev two protection

2017-07-25

- Added protection from slow and haste arrays to exp. retreat
- Created remove slow and haste arrays and applied to exp retreat
- Created magic item and spell removal arrays and applied to Decastave and bone darts
- Tested...installs 


2017-07-22

- Applied fear, confusion, beserk/rage, and feeblemind removal/immunity to Exaltation.
- Added Mordenkainen's Force Missiles
- Added Mordenkainen's Force Missiles pro to entropy shield protection
- Added Darts of Bone (protected from entropy shield?) 

2017-07-20

- Prayer: Used cantrip removal batch, and updates cantrip descriptions (may externalize...).
- Created disease batch.
- Applied Disease batch to cause disease
- Created and applied lev 2 immune to Cause MW, Beast Claw, Al lance, Cure mod wounds, Resist fire/cold
- Created and applied lev 3 immune to Prayer (sec spells), cause disease

2017-07-19

- Updated Fnp compatibility: Curse, cause light wounds and Sunscorch
- Updated Sunscorch blindness notification (via batch)
- Updated fnp compat: cure mod wounds, Alicorn Lance 


2017-07-18

- Added maladiction, cure and cause minor wounds, infravision, canticle, meditation, and frost ray cantrips to 1st lev immunity

2017-07-17

- Created 1st lev immune array
- Applied 1st lev immune array to globes of invuln

2017-07-16_2

- Used Replace_textually with curse spell
- Used Replace_textually with cause light wounds spell
- Created compatibility folder (in lib) and tpa files (not edited yet).  Move compatibility to these files...

v. 0.88a

2017-07-16

- Tested install successful (after a few bug fixes)

2017-07-15

- Updated Blindess immunity
- Updated Deafness Immunity
- Updated invis detection immunity
- Updated Sleep Immunity
- Updated stun
- Updated dispel magic
- Applied stun batch to icelance
- Applied fear immunity and removal to emotion: courage
- Created fear batch
- Applied fear batch to Emotion: fear
- Applied fear removal to Emotion: Hope
- Created deafness batch
- Applied deafness batch to shout
- Created curse batch
- Applied curse batch to curse spell
- Externalized (to immunity.tpa) curse interactions (also, to some degree prayer)

2017-07-14

- Started death immunity
- Updated invisibility immunity

2017-07-13

- Updated Charm batch
- Updated Disease batch
- Finished Level drain batch
- Updated poison immunity batch
- Batch: web immunity delete 'held' string protection.  Create batch that removes that string.  Create new 'webbed' string

2017-07-12

- Updated drain batch.  A few stringrefs missing for BGEE and IWDEE... Also, need to REMOVE unneded strings
- Added Calm Orison
- Updated Fear batch

2017-07-11

- Included OHTYR1 in exaltation protection (needs to be heavily expanded...)
- Batches: Updated slow immunity and confusion immunity by EE game engine
- Created Berserk immunity batch

2017-07-10

- Added rage removal/protection to batches (tested with exaltation)  Need to update how exaltation et al. implemented (no longer need dif spls for dif games)


2017-07-09

- cantrips: gave a +2 bonus to saves for jolt and frost ray.  Reducted duration of drowse to 1 round, period

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