# How to contribute to Engineered Compatibility

Engineered Compatibility accepts contributions given that they follow the guidelines below.    
Contributions not following the guidelines will be closed, often without comment.

## Did you find a bug?
That's great! Please identify the file name that is in error from your log or the recipe that you feel is incorrect.    

**Then:**
 1. Check to make sure the bug has not already been reported. Use the search function, and try similar/synonymous terms!
 2. Open an issue [here](https://github.com/voidsong-dragonfly/engineeredcompatibility/issues)
 3. Include your Engineered Compatibility version and a full debug log (Accessible via holding down F3+C for ten seconds)
 4. Clearly state in the title, _without a version number_, a short description of the bug with Engineered Compatibility
 5. Describe the bug in full in the issue body
 6. Submit the issue

## Did you find a missing compat for an existing mod Engineered Compatibility adds compat for?
That's great! Please first check the below list of features that cannot be implemented at the moment, and then treat it as a bug as above.

**List of features whose compat cannot/will not be added:**
 - Aether and Deep Aether berries in the Cloche:
     - Neither of these mods add berries in a method that works well with the Cloche
     - For this to change, they would need to properly have growth states like other BushBlocks (eg, Sweetberries)
 - Blue Skies crops and external farmlands in the Cloche:
     - The Cloche does not easily support adding any kind of farmland to any recipe
     - Additionally, Brewberries need special handling for their soil changes
 - Eidolon herbs in the Cloche:
     - Eidolon herbs are meant to grow soley in Eidolon _Planters._ The cloche is not a planter. Use the Eidolon blocks.
 - Nether's Delight crops in the Cloche:
     - Special crops need special code to grow. Propelcane is a special crop. Engineered Compatibility is a datapack.
 - Undergarden gloomgourd recipes in the Cloche:
     - Gloomgourd stems are actually two, separate blocks, and not a singular block with blockstates
     - This works fine for Undergarden (mostly) but could be considered a bug in Undergarden

## Do you have a mod you want Engineered Compatibility to add compat for?
That's great! Please first check that the mod is not on the list below of mods that denigrate the IE experience too much for me to add compat to.    

**Mods for which compat will not be added:**
 - Thermal Expansion, Integration, or any else of the Thermal [x] series
     - Third-party addons to the Thermal series whose primary intent is adding content to Thermal
 - Industrial Foregoing
 - Mekanism, Mekanism Generators, or any else of the Mekanism [x] series
     - Third-party addons to the Mekanism series whose primary intent is adding content to Mekanism

**Then:**
 1. Check to make sure that the mod is on the latest development version (Currently 1.20.1 NeoForge)
 2. Take a look at the amount of compat that would need to added
 3. If the amount of compat is larger than ~20 recipes, Engineered Compatibility accepts PRs [here](https://github.com/voidsong-dragonfly/engineeredcompatibility/pulls)
 4. If the amount of compat is relatively small, then treat it as a bug as above
