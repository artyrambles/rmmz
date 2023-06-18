# Arty's RMMZ Plugins
Here you can find all my released plugins. They have been tested with v1.5.0 of RPG Maker MZ and may not work on older versions. As a rule of thumb, don't assume that they work with RPG Maker MV, but you can try since my code tends to be rather basic.

## TERMS
My plugins are free to use for commercial and non-commercial projects, **as long as you give credit**. This "credit" has to be my name (Arty), and some sort of indication that it was my plugins that you used. It's not necessary to state which plugins it was.

**Example of crediting me:** "Plugins - Yancry, VictorSinner, SomeOtherCreator, Arty, SumUniqueDude, ..."

**Another example:** "Heal Over Time, Follower Vehicles, Post Battle Common Events plugins by Arty"

My RMMZ plugins are released under the GNU General Public License. You can use, share and modify them, but you cannot re-release them or modified versions of them as closed source/paid plugins.

### Arty_PartyMaxLevel.js
This plugin looks through the current party members and finds the highest level. But it doesn't know/remember who that actor is (I couldn't think of a possible reason). The party's highest level is now available as $gameParty.maxLevel, so you can use that value. For example, assign it to a variable, use it in Conditional Branches, etc.
