# B_Spells

# log

TO DO 1: ADD A PRIEST SCROLL COMPONENT: MORE PRIEST SCROLLS (ALSO PRIEST SCRIBING?)

TO DO 2: NEED TO KEEP UP WITH IMMUNITY/REMOVAL CODE ESP WITH NEW SPELLS

TO DO 3: Do summoning spells as they are in IWDEE (according to the new style)

TO DO 4: CONTINUE TO UPDATE CRAFTING CODE

TO DO 5: POTION REVISION AND NEW POTION COMPONENTS

TO DO 6: RUN PROTECTIOn/REMOVAL BATCHES OVER CREATURES AND ITEMS

TO DO 7: Modify tooltip.2da to give proper names to wand sec spells

TO DO 8: Look to make ALTER_SPELL_TYPE text changes more non-english friendly...

TO DO 9: ADDRESS WANDS INT/WIS REQUIREMENTS for wands creatable by both wizards and priests (maybe have different wands for each)

TO DO 10: Create batch for Entropy Shield

TO DO 11: Add check for charm component for charm monster (and add charm monster in charm component if new spells installed)

TO DO 12: Trade out @10 'Scroll' reference for @900009016.  DONE: Setup_IWD_Wiz.tpa and Setup_New_Spells.tpa

TO DO 13: Create Custom portrait icon for bleeding effect

TO DO 14: Specifically exclude Abundant Ammo and StormBow (Hidespl.2da) from druid, add to all rangers

TO DO 15: Continue D. Door

TO DO 16: Continue Minor Creation lib/fnp_new_spells.tpa

TO DO 17: B_ILL01.itm needs to add additional protections

TO DO 18: Make disbelieve destroy nearby illusions of right level

TO DO 19: 5th level IWDEE wiz spells (D.Shadow Monsters SPWI525) And make compatible with B_Attributes (See Setup+int_pnp_Illusion.tpa component for shad mons)

TO DO 20: Finish D. Door

TO DO 21: Redo summoning by sumtables

TO DO 22: Add SR School naming scheme into alter_spell_type macro (schools and sphere names/combos)

TO DO 23: Cause Moderate Wounds (SR Revision)

TO DO 24: Further update prest scroll code  (need to further update it, check for spell type, include specific res spells where I know they exist (e.g. in FnP)

TO DO 25: Update scroll placement but using ACTION_PHP_EACH by either sphere (fnp) or class (van) rather than file name (i.e. only B_P, etc. nec)

TO DO 27: Modify scroll placement to automate adding scrolls to stores that sell similar spells (e.g. a level y necro spell that sells other level y necro spells)

TO DO 28: Finish wand of darkness (summon shadow effect) B_WAN18.itm

TO DO 29: Figure out how to add sounds to custom creatures

TO DO 30: Add certain spells added in revision (e.g. hold beast; devil's eyes) to new spells component (make sure checks are in place to ensure compatibility)

TO DO 31: Revise Reprieve spell as per description on github. 

TO DO 32: go back to Chill Touch range 10' IFF touch to target spells global is installed

TO DO 33: Put Devil's Eyes in New Spell section (offer to replace Infravision or add as 2nd level spell as Spectral Hand).

TO DO 34: Add different versions of Fog and banishment for those wands if SR not installed(?) 

TO DO 35: Custom Portrait Icons: Accelerate Metabolism, Alarm (innate), Anticipation, detect traps/portals, enervating ray, farseer, hypnotism, Ice Knife(numbness),  

TO DO 36: Protection Lists:

TO DO 37: Dispel Lists:

TO DO 38: To be remove lists: regen_list, 

Version 0.90.21

2020-12-08

- Corrected icons and port icon images

- Small fix to add_icons.tpa (but needs a lot of work)

Version 0.90.20

- Not completely sure...need to recheck just about everything :(

Version 0.90.19

2020-11-29

- Updated icons and port icons for a number of spells 

2020-11-14

- Revised Spells: Bless

Version 0.90.18

2020-11-07

- orison: created splprot_orisons.tpa and included it in orison installation (to check for current hp)

- create preserve life orison

2020-10-30

- Magic Stone 0 level cantrip: 1st draft

- Delay Death: 1st draft

2020-10-30

- Sixth Sense Cantrip: First Draft

- Shadow Dagger: First draft

- Magical Stone (0 level version): First draft

2020-10-27

- Fixed ESP Icon

- Moved Bind to 1st level

- Icons for Tasha's Uncontrollable Hideous Laughter,

Version 0.90.17

2020-10-24

- icons for alter self, binding (fin but missing), Blastbones, Bolt of Paralysis, Choke, Hypnotic Pattern, l trap, protection from paralysis

2020-09-26

- Created regen_list for Accelerate metabolism

2020-09-24

- fixed description for filth's bane

- changed hypnotism so it doesn't rely on command (because that can lead to problems)

Version 0.90.16

2020-09-22

- Bam icons for destroy undead

- cleaned up a few bams (a bit--they still don't look great)

- applied fixes to alarm, anticipation

- changed internal ref for alarm spell (conflict in bgee)

- nerfed Enervating Ray (cuz boyhowdy, that was op)

- 

2020-09-21

- bam icons for Camouflage

2020-09-19

- Bam icons for Carpet of adhesion, animate zombie, Protective Shell, Read Magic, Reprieve, Abundant Ammunition, binding and Vanish

2020-09-15

- Changed Detect magic to Reveal Magic (for compatibility w/ospells)

- Bam icons for reveal magic, phantasmal force

2020-09-13

- redid bam icon for bless water

- Added bam icons for devil's eyes, e ray, farseer, ice knife


Version 0.90.15


- bam icons for anticipation

2020-09-12

- Updated wand tier list with existing wands

- Wand tier list: SR wand of fog

- bam icons snowball spell (Credit Mordus)

- Bam icons for alarm spell, Animate Skeleton

2020-09-11

- Started room_for_spells.tpa

2020-09-05

- Icons: Binding, bless water

- Missing Wands: Wand of darkness, wand of eyes, animated wand,

2020-09-02

- Missing Wands: Animated Wand, wand of banishment,

2020-08-30

- Spell icons for Polymorph any object

Version 0.90.14

- missing wands: wand of the heavens, gremlin wand,wand of force, wand of fireball, wand of freshness, wand of knock, wand of spiders, 

2020-08-29

- Added spell icon bams for mass dominate and demand

- Missing wand: added wand of freezing death, wand of magic missile, wand of lightning, wand of armory, Wand of Polymorph, Wand of Freezing Death, Wand of Cloudkill

Version 0.90.13

2020-08-25

- Added spell bams for accelerate metabolism, detect magic, exterminate, mindsight, Filth's Bane, Fire burst, Hypnotism

- Note: GET BACK TO RECHARGE!

2020-08-15

- Continued on Recharge

2020-08-08

- Started Recharge Spell

2020-08-01

- Started Polymorph any object

- First Draft: Algarth's Embattlement

2020-07-29

- First Draft: Mass Dominate

2020-07-25

- First Draft: Unfailing Premonition

- First Draft: Delayed Magic Missile

- First Draft: Poison (wiz version)  

2020-07-24

- First Draft: Weird

- First Draft: Demand

2020-07-19

- First Draft: Destroy Undead Spell

Version 0.90.11.01

2020-07-17

- Started Structural Revision of tp2 (but too many distractions!)  

2020-07-15

- Fixed and improved Sepia, including script and special item.  

- Set up ini for mindsight, Phantasmal killer, Snilloc's Major Missile, Usurp Shell

- Finially started limiting scope for version 1

2020-07-14

- Finished (first draft of) Sepia Snake Sigil (Tested: add script to monster and script doesn't seem to fire...)

2020-07-13

- Started Sepia Snake Sigil

2020-07-12

- Changed control plant to 3rd level, and summon swarm to level 4 (because wizards shouldn't be better than druids at druidy things)

2020-07-11

- Started ESP spell (revised)


2020-07-10

- Started Bind spell (which I revised)

2020-07-09

- Changed Disrupt life to a 3rd level spell, and made first draft

- Modified Detect Magic

2020-07-07

- Made carpet of adhesion actually install in iwdee

- Started Animate Zombie 

Version 0.90.11

2020-07-04

- Started Carpet of adhesion, detect magic, 

2020-07-03

- Added ini entries charm monster, Sepia Snake Sigil, Fabricate

- Fixed a number of installation errors for New Arcane Spells

- Fixed issue with animate skeleton spell (missing cre in certain games)

2020-07-02

- Added ini entries Summon Swarm, Pyrotechnics, Protection from Paralysis, Tasha's Laughter 

2020-07-01

- Added ini entries Control Plants, Disrupt Life, ESP

2020-06-30

- Added ini entries for detect magic

2020-06-27

- Added ini entries for Iron mind, explosive runes, solvent of corrosion, Augment Undead

2020-05-16

- Added notebook and page bams/items for 

2020-05-02

- Restructured tp2

2020-04-30

- Created ingame notebook for item crafting recipies

Version 0.90.10

2020-04-20

- Ice Knife

- Casting time alteration to Anticipation

- Fire Burst

2020-04-19

- Snowball to 2nd level

2020-04-18

- Animate Skeleton

- Carpet of Adhesion

- Snowball

2020-04-17

- Bolt of Paralysis

2020-04-16

- Skeleton of Illusory Fireball spell

- A few details on blastbones

- Final first draft of blastbones

2020-04-11

- First Draft of Blastbones

- Fixed missing vanish text ref

2020-04-08

- Put Hold Animal Lev change in Revised Component, and Hold Beast in New Spells Component

Version 0.90.09

2020-03-30

- Started Moving Hold Beast to New Spells (while keeping hold animal change level in Revised)

2020-03-29

- Moved Devil's Eyes to New Spells and made it non-destructive

2020-03-28

- Put Spectral Hand in New Spell

Version 0.90.08

2020-03-27

- Started adding Spectral Hand (revised spell)

- Incorporated ADD_SPELL_HEADER (credit: Adarnis)  

2020-03-26

- Changed chill touch to innate to make space for new spell (and so scripts can make better use of it)


2020-03-21

- Finished affect undead chill touch (for iwdee w/o SR)

- Chill touch 10' range

Version 0.90.07

2020-03-18

- Finished affect undead (though test) for Chill Touch

- Chill touch fear undead stuff

Version 0.90.06

2020-03-18

- Undead affect undead spell text 

2020-03-15

- Added chill touch affect undead code (not tested; also need to check for SR and IWDEE) 

2020-03-14

- Began incorp. of ini into 0-level cantrips

- Added replace_text.tpa

- Added Armor mod

2020-03-13

- Spell checked a few cantrips


Version 0.90.05

2020-03-08

- Started Exterminate spell

- Started Filth's Bane

- Started Cantrip spell (very prelim pre alpha draft) 

2020-03-07

- Fixed ini ref error in revised spell component

- Began incorporating ini for new spells: all 1st lev wiz spells (completed or not)

2020-02-27

- Revised Traps settings in b_spells_settings.ini (but not actual component--still in development)

2020-02-26

- Completed Hold Animal/Hold Beast revision

2020-02-25

- Infravision --> Devil's Eyes 4 versions

- b_spells_settings.ini Arcane vs divine cantrip settings

2020-02-24

- Added add_spell_ex (thanks k4th...)  

- incorporated b_spells_settings into revised spells

- used add_spell_ex to create var for hold animal spell level

2020-02-22

- Potion of vision (150 gp)


2020-02-14

- Started potion code: automating tier list based on cost

2020-02-11

- populated b_spells_settings.ini a bit

2020-02-09

- Organizing spells (to better see what is missing from each spell)

Version 0.90.04

2020-01-27

- Fixed "PRO_HEHER" text and duplicate @900000033 in items.tra

Version 0.90.03

2020-01-21

- Fixed a bug and commented out a few components that aren't ready yet (thanks Majber)

- Added 'pretty' pdf readme and allowed display

2020-01-18

- started ini

2020-01-17

- Renamed divine smite to divine wrath

- First draft of guidance spell

2020-01-07

- Renamed destructive smite-what a terrible name!-to divine smite (not much better, but still better).

- Began reorganizing fnp_new_spells to get a better picture of what still needs to be done

2020-01-05

- Updated make_cantrip.tpa to have option to give innate version of spl, and to NOT change level text

Version 0.90.02

2019-12-29

- Fixed minor issue with wand of fog (SR required wand)

2019-12-28

- Probably updated wand store distribution (but test! backup made 2019-12-28 before this update, so it can be reverted)

Version 0.90.01

2019-12-27

- Got a working version of wand store distribution working

2019-12-26

- Finished gremlin wand (except gremlin sounds...)

2019-12-25

- Set prices (fin so far) for wands by encyclopedia magica

- Revised wand of healing, fireball and illumination (as per encyclopedia magica)

- Tooltip: Bonewand, Wand of Eyes and Wand of Spiders

2019-12-24

- Added wand list by tier.  Started filling it out.

- Set prices (up to wand of freshness) for wands by encyclopedia magica

2019-12-23

- New Potion: Potion of Vitality (needs portrait icon)

2019-12-22

- Wands: Wand of darkness: blindness and smite effects (need to still create summon shadow effect)

- Wands: Completed Wand of Illumination


Version 0.90.00

2019-12-21

- Finished fnp priest scroll (specifically scroll placement)

- Finished normal priest scrolls

- Wands: Gremlin wand (basic item and description).  Needs to be actually created, though


Version 0.89.11

2019-12-20

- Finished fnp compatibility spells (but revise placement as 25)

2019-12-18

- fnp scroll compatibility (SD's procedurally gen spls)

2019-12-17

- Fnp scroll compaitiblity: life and universal spheres (not including exceptions)

2019-12-16

- Started priest scroll compatibility w/fnp

2019-12-15

- Redid auto bam creation and bg2ee bams because somehow I deleted it.  blah

- continuing with custom spl folders

-
2019-12-14

- Excluded odd lev 3 summon spell scrolls from placement (still exist in game though--hopefully, not an issue)

- Scroll Placement: IWDEE: changed 3rd level placement to cure disease check, as at least one temple uses cd but not remove curse

- Scroll Placement: Excluded SPPR599 from placement (still creates the scroll, tho. I think it's related to Harm).

- Created scroll icons for "SPPR" spells without scroll icons (pretty much just for new ADD_SPELL spls)

- Added bg1 scroll icons in bg2ee scroll installs

- Improved code to create scrolls from custom spls (mine and SD's)

- Scrolls: Pricing: 100 * spell level

- Externalized backup folder


Version 0.89.10

2019-12-09

- Priest scrolls: now actually cast the right spells... duh!

- Imporoved scroll placement to work with iwdee

2019-12-08

- Fixed issue where DUHM subspell scroll and shaman scrolls (lev 1 and 2) was being added to stores - scrolls still being created tho...)

- Improved scroll placement using camcode!

Version 0.89.09

2019-12-07

- Priest scrolls (general code to add gen/cle lev 1-3 scrolls in all temples)
- Temple of wisdom (lev 1-3 druid scrolls)

2019-12-06

- Aligned tp2 setup with readme

2019-06-15

- Created alter_effect_add

2019-06-11

- Updated priest scroll code to capture all of my custom priest spells (may be too inclusive--check).  Update for SD's and Raz, at least

2019-06-08

- Priest scrolls: Added cost (level x50)

- Added placement of priest scrolls for a few BGEE stores

2019-06-06

- Updated Priest scroll code to check for spell type

2019-06-04

- Updated Priest scroll code

2019-06-01

- Cleaned up REPLACE_TEXTUALLY in global cure tpa for IWDEE spell wording.

2019-05-29

- Converted tras to UTF-8 (grr, see if that is what was messing with TEXTUAL issues re SR) 

2019-05-28

- Global Cure Moderate Wounds (NOT SR VERSION)

2019-05-27

- Sep Global heal and global charm from revised spells tpa (as they are distinct components)

- Revised cure/inflict minor wounds to just check for actual cantrip spls (because, easier)

- Streamlined Global cure for cmw (SR SHOULD be accounted for...test)

2019-05-19

- Started cantrip install in tp2

- Broke up infinite innate priest and arcane cantrip components

2019-05-18

- removed bless/curse etc immunity from benediction

- Added add_spell_header (thanks Adarnis)

- Added Adarnis' tooltip macro

2019-05-17

- Added location to spell type macro

2019-05-16

- Added support for add_spell to c_icon in alter_spell_type

2019-05-15

- Added first draft of school and sphere text for alter_spell_type macro

- Adapted alter_spell_type to modify even SR text (hopefully)

- Created c_icon STR_VAR for alter_spell_type

2019-05-12

- Added CamDawg's sumtable mod macro

2019-05-11

- Finished Universal Scrolls(?) 

- Updated Scroll Placement

- split alignment restriction from school restriction and wildmage restriction from cleric/druid restriction in ALTER_SPELL_TYPE.tpa

2019-05-10

- Started revising 'universal_scrolls.tpa' (ready to test for druid scrolls)

2019-05-09

- Replaced @10 with @900009016 for scroll names in fnp_new_spells.tpa

2019-05-08

- Replaced @10 scroll ref in Setup_New_Spells.tpa (any others left?) 

Version 0.89.08

2019-05-05

- Updated setup_cantrips.tpa with new alter_spell_type and make_cantrip as necessary

- cantrip: exp retreat removed text alteration reduncancy

2019-05-04

- Created Make_Cantrip.tpa (only an option for 0 lev right now)

- Created second_opp.tpa 

2019-05-03

- Successfully tested Second Restricted School

2019-05-02

- Continued with ALTER_SPELL_TYPE: aded generalist and abjuration additional exclusion flags TEST!

2019-05-01

- Continued with ALTER_SPELL_TYPE (need ot add a few more...)

2019-04-30

- Added both cannot and can cast in combat to ALTER_SPELL_TYPE

- Tidied up the divine spells in new_spells.tpa

- Did more with ALTER_SPELL_TYPE (need to fix cleric_druid_wild--right now only really works to make spell uncastable by wildmage-- and expand spell flags)

2019-04-29

- Updated ALTER_SPELL_TYPE to Change level text 

- Updated ALTER_SPELL_TYPE to change school text for changed school (Abjuration only--need to check description of a few spells before finishing)

- Updated ALTER_SPELL_TYPE to include a function to add ignore wild surge and prohibit indoor casting

2019-04-28

- Test install cantrips (fixed 1 false tra reference)

- Cleaned up IWD cat's grace and Decastave

- Cleaned up IWD SSS, Icelance, LoD, BBB, DD (THOUGH INCOMPLETE), and Emotion: fear and courage

- Compatibility code between curse and benediction (text notifications)

- Cleaned up Benediction, calm and canticle

2019-04-27

- Finished ALTER_SPELL_TYPE macro...hopefully

- Added CANTRIPS_RECAST for infinite casting

- Added Exp Retreat cantrip (and coded compatibility with added IWDEE spell regardless of order...hopefully)

2019-04-25

- Cleaned up Exp Retreat (going down the list) CONTINUE WITH CANTRIP VERSION (make 1 round and innate, but cast from spell menu)

- Trading out @10 'Scroll' reference so that value can be used in Install.tra ( in Setup_IWD_Wiz.tpa)

- Started ALTER_SPELL_TYPE macro.  See Test in BD version of BG

Version 0.89.07

2019-04-24

- Finished Shroud of Flame

- Cleaned up some of the scroll placement code in Setup_IWD_Wiz.tpa and Setup_New_Spells.tpa

2019-04-23

- Started Shroud of Flame (do icons and scrolls, etc.)

2019-04-20

- Created Invisibility to Animals

2019-04-19

- Added Phantasmal Killer (Credit: Raduziel)

2019-04-15

- Added Compatibility with B_Attributes pnp illusion immunity Int 22 lev 4 illusion immunity (prot from shadow beasts) for both fnp added wiz priest SB and iwdee added SB

- Apparently, I missed at least 1 lev 5 IWDEE wiz spell (Demi-Shadow Monsters...) Added to TO DO


2019-04-13

- Created first draft of Invisibility to Undead (for cleric and wizard)

2019-04-06

- Added Illusion.bcs for bgee or iwdee to illusory cre (in ph force)

2019-04-01

- Updated Phant Force (disbelieve prot vs. lev dep illusions)

2019-03-30

- Fixed tra errors

- Phantasmal Force: First Draft

Version 0.89.06

2019-03-24

- Started Minor Creation spell

- Updated new_spells.tra with fnp ex ret 

Version 0.89.05

2019-03-09

- Added Pecca's Spon Casting for Priests (though, untested)

Version 0.89.04

2019-03-08

- Added Castigate priest spell

Version 0.89.03

2019-03-07

- Updated Binding Spell Duration

Version 0.89.02

2019-03-07

- Created Binding Spell

Version 0.89.01

2019-03-03

- Updated spl tras from FnP

Version 0.89.00

2019-02-28

- Fixed a few parse errors (thanks Subtledoctor)

2019-02-23

- Added fnp wiz spells back to Wiz installer

- Updated Add_ids

- added iwdee_sr_readd.tpa

- added sr_readd.tpa

- updated IWD_spells from fnp

- Added Magic Weapon

- Started D. Door

2019-02-15

- Reassigned tra references of wiz spells for fnp compatibility

2019-02-13

- Finished first draft of abundant ammo

2019-02-12

- Continued with Ab Ammo: Hunting and keen bolts and arrows, weighted and balanced bullets so far

2019-02-11

- Created Hunting Arrows for Abundant Ammunition spell

- Created Bleeding spell (for hunting arrows)

- Modified cure spell removing bleed effect via bg2ft_effect_batches_fnp.tpa and immunities.tpa

2019-02-09

- Got rid of #bonecir.spl

- Updated Anticipation (giving weapon/spell speed boni) 

- Redid elemental ammos for abundant ammunition (though let's make them interesting)

Version 0.88.24

2019-02-08

- Will not replace infravision with Devil's eyes if METweaks is installed

- Reduced duration of Devil's eyes to 1 turn, and crit threat to +1 (rather than +2)

2019-02-02

- Fixed issue with entropy patch in immunities.tpa

Version 0.88.23

2019-01-26

- Removed false blindness notification (e.g. 'get him') ...hopefully

- Cloak of Shadow: removed flashing animation; made it unstackable 

2018-12-08

- Wand of Death

2018-12-07

- Added Potion of Animal Control

2018-12-02

- Created Wand of Healing

- Revised Wand of Banishing (stun for 3 rounds if no remove)

- Wand of Spiders

- Wand of Swarming

2018-12-01

- First Draft of Storm Bow

- First Draft of Wand of Banishment

- Potion of Teleportation

Version 0.88.22

2018-11-29

- Finished first draft of Wand of Freshness

- Added ADD_IDS for SR compatibility (Thanks DavidW)

- Created Wand of Fog

2018-11-28

- Finished first draft of Wand of Eyes

Version 0.88.22

2018-11-23

- Started Abundant Ammunition revision (needs a lot of work--see notes txt in main folder)

- Updated Readme

2018-11-22

- Finished (first draft of) bonewand

- First draft of Wand of Force

- First draft of Potion of Farsight

Version 0.88.21

2018-11-21

- Finished (first draft of) Animated Wand

- Started Bonewand (B_WAN07.itm) Create second ability

2018-11-20

- Created Storm Brew

- Created Vitriolic Ooze

- Created Frostfell Draught

- Started Animated Wand (B_WAN06.itm).


Version 0.88.20

2018-11-18

- Updated Cloak of Shadow

2018-11-15

- Created wand of command

- Created Wand of Fireballs

2018-11-14

- Created Wand of Knock

- Created Wand of Teeth

- Created Mistletoe (wand)

2018-11-10

- Added craft components: Beholder Eyestalk, Spider fang, Skull, Tentacle, Liquid Mercury, Demon Claw,

2018-11-08

- Added Gulp to potions (IWDEE at least)

- Added empty potion bottle (as a material component)

- Add first draft of pyro delight

2018-11-07

- Started New wand component: Wand of Teeth (just item in wand folder)

- Started Wand of knock (just file)

- Started Mistletoe (wand)

- Started potion of persuasion (potion)

- Potion of vision started

Version 0.88.19

2018-10-26

- Created scroll bam for Murderous Command

- Created Scroll bam for Snare

2018-10-25

- ADDSPELLE'd Storm Wall

- ADDSPELL: Misfire

- ADDSPELL: Assassin Vines

2018-10-24

- Started Potion Revision and New Potion components

- Started Item Crafting Components (basically just copied over TnB spells and scripts for now)

- Added SR NWN spell deflection compatibility (courtesy of SubtleDoctor)

- Created scroll bam for Cloak of Darkness

- ADDSPELL'd Cloak of Darkness, changed it to Sun Sphere (for non-FnP games)

2018-10-22

- Continue with scroll code

- Druid usability spells mostly identified, need to add usability code (i.e. remove clerics from use)

2018-10-20

- Added code for scroll usability exclusivity (i.e. for druids right now--just a check)

Version 0.88.18

2018-10-19

- Developed a better way to create scrolls (twice)

Version 0.88.17

2018-10-17

- Created Scroll of sanctuary and added to temps of oghma, and wisdom

- Added Vanish to Feldpost's inn store in bgee

- Created Scroll of bless and added to temps of oghma, helm and wisdom

- Created scroll of command and added to temple of helm

- Improved code such that the description and name of orig spell gets copied to scrolls.


2018-10-16

- Started Priest Scrolls component: Detect Evil created and added to temple of Oghma and temple of wisdom

2018-10-07

- Tweaked Bless Water

2018-10-06

- Created first draft of Bless Water

Version 0.88.16

2018-09-30

- Removed party vision from alarm and corrected description 

- Fixed a couple misnamed scrolls (Alarm and Farseer)

- Various description corrections

- Detect Traps and portals (changed spl to speed 9)

- Reprieve: changed casting time to 1

- Vanish: Reduced duration to something managable

- Updated Reprieve

- Readme popup


Version 0.88.15

2018-09-29

- Changed Ray of Fatigue to Enervating Ray

- Added a scroll to Accelerate Metabolism

- Modified Alarm so that it follows caster (to be more useful)

- Added Anticipation scroll

- Added Detect Traps and Portals scroll

- Created Farseer icon bams

- Added Farseer Scroll

- Added Hypnotism Scroll

- Created protective shell scroll

- Bolt of Paralysis scroll created

2018-09-27

- Added missing spl for snare

2018-09-26

- Revised Camoflauge (sp)

- Revised text for a few new spells

2018-09-23

- Updated Siphon Vitality to something more reasonable

- Created first draft of Bolt of Paralysis

- Created first draft of Farseer

- Created first draft of Mindsight

2018-09-22

- Changed Heat vision to devil's eyes 

- First draft of siphon vitality done

Version 0.88.14

2018-09-16

- Update to Ray of Fatigue

- Update Detect Traps and Portals

- Update to Camoflauge (sp)

Version 0.88.13

2018-09-15

- Created Ray of Fatigue, Ursup Shell and Snare (first drafts)

2018-09-08

- Removed an extra END in tp2

Version 0.88.12

2018-09-04

- Added new cantrips to 1st level protection batch

2018-09-02

- Created first draft of Audible Glamer

- Made Malediction comparible with AG (save pen and increased duration at higher levels)

2018-09-01

- Vitrolic Sphere, Soul Eater, Decastave, Lance of Disruption, Beltyn's Burning Blood, Mordenkainen's Force Missiles, Darts of Bone set to correct opposition school

- Canticle: Added some advancement at higher levels to AC

- Cure Minor Wounds: changed to cure 4hp (or 2 + 10%)

- Malediction: Casting time: 3, added save negates

- Drench: increased dam to ice/fire creatures.

- Created Benediction cantrip

- Drowse: Only affects cre of at most your own level

- Frost Ray: Reduced damage progression

- Jolt: Got rid of immunity for 8 hours

- Added first draft acid splash

- Added first draft of fire bolt (credit SubtleDoctor)

- Added first draft of magic bolt (credit SubtleDoctor)

2018-08-19

- Snilloc's Snowball Swarm, Icelance, Shadow Monsters, Emotion: Courage, Emotion: Fear, Emotion: Hope, Shout, Shades, Acid Storm set to correct opposition school

2018-08-18

- Drench now removes earlier instances

- Canticle removes earlier versions of itself and meditation

- Maladiction no longer indicates that it is only usable every 3 rounds (not implemented).

- Meditation removes canticle

2018-08-11

- Checking Shatter, Watery Fist, Detect Traps and portals, hypnotism

- Created Vanish

2018-08-08

- Altered Forbiddance to have an effect even on save (to make it more competetive with entrhall and hold person)

- Added Ice List, and added Ice Blade to that list (in case some spell will want to cancel certain ice spells like that cloud spell does for fire blade)

2018-08-07

- Changed Accelerate Healing to Acceleerate Metabolism

- Removed prot from spell from Alarm

- Altered Enthrall to make competetive with hold persion (casting time 2)

2018-08-06

- Created First Draft Accelerate Healing

Version 0.88.11

2018-08-06

- Changed name of Hand of Carnage to Destructive Smite

- Doubled duration of camoflauge to compete with sanctuary

- Notes for compatibility (with self and FnP)  Will go back through for SR notes

Version 0.88.10

2018-08-05

- Improved Camoflauge to allow caster to hide for duration

- Added invis helm for camo cre to prevent attacks against it

Version 0.88.09

2018-08-04

- Added pause to caster for Eyes of the dead and animal eyes

- Updated weidu to 246

2018-07-28

- Finished (I think) abundant Ammo

- Modified animal eyes to blind caster

- Camouflage, changed port icon to 'non-detection' until custom icon is ready

- Disrupt Undead: Changed progression up to 10th level

2018-07-26

- Upgraded Weidu to v 246

- Removed an extra "END" in tp2

2018-07-25

- Reverted back to 0.88.07, except Waves of Agony is no longer ADD_SPELLed-That MAY have been the only thing lost...

- Hopefully recovered changes from 2018-07-14 and 2018-07-01

Version 0.88.08

2018-07-14

- Updated fear protect arrays

2018-07-01

- Reorganized tp2 to check directly for added spells in spell.ids


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