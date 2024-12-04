# Permitted and Prohibited Uses of Assets

Section 4.4 of the Catch License outlines the rules for using assets from other mods in compatibility patches. This section is crucial for maintaining the integrity of mod authors' work and ensuring that compatibility patches are created responsibly.

However, it is also (intentionally) the most imprecise section and open to interpretation, because often it is difficult to define the exact boundaries of what constitutes a "compatibility issue". Similarly subjective and subject to changes, not only but especially by the tools we use nad, is the question about which assets or asset parts of original mods need to be included in a patch.

Below are examples of permitted and prohibited uses of assets in compatibility patches a wide range of the community can hopefully agree on. Keep in mind that these examples assume no specific permissions or communication between the mod author and a patch creator except for the inclusion of Catch License. In a lot of cases, more permissions are granted by the mod author anyway and one doesn't need to worry about the specifics of the Catch License.

## Permitted Uses

1. Modifying Levelled Lists
	- Scenario: Mod A adds new weapons, and Mod B overhauls levelled lists for enemy gear. Without a patch, the new weapons from Mod A won’t appear in Mod B’s levelled lists.
	- Solution: The patch includes an updated levelled list that integrates the weapons from Mod A into Mod B.
	- Why Permitted: The patch uses Mod A’s weapon references in the levelled list solely to resolve a specific incompatibility.
2. Texture Alignment
	- Scenario: Mod A changes the architecture in Skyrim to medieval-style buildings, and Mod B enhances lighting effects. However, Mod B’s lighting creates graphical glitches on Mod A’s textures.
	- Solution: The patch adjusts Mod A’s texture files to make them compatible with Mod B’s lighting system.
	- Why Permitted: The adjustment directly addresses a graphical conflict between the two mods.
3. Script Compatibility
	- Scenario: Mod A uses a script to add custom follower mechanics, and Mod B modifies follower AI. The two scripts conflict, causing followers to break.
	- Solution: The patch edits and merges the scripts to ensure compatibility.
	- Why Permitted: Script edits are minimal and focused on enabling the two mods to work together.

## Prohibited Uses

1. Standalone NPCs
	- Scenario: Mod A adds a new character model, and a patch creator uses this model to create unrelated NPCs in a patch.
	- Why Prohibited: The character model is not strictly necessary for resolving any conflict or compatibility issue. It is being used to create unrelated content.
2. Repurposing Textures
	- Scenario: Mod A introduces custom armor textures. A patch creator uses those textures to create an unrelated new armor set.
	- Why Prohibited: The textures are not needed for resolving conflicts or ensuring compatibility with another mod.
3. Unrelated Asset Extraction
	- Scenario: A patch creator extracts assets from Mod A to include them in a standalone location, unrelated to any conflicts with other mods.
	- Why Prohibited: The extracted assets are used for standalone purposes, not to address compatibility.

## Notes

It's important to remember that these examples are not exhaustive and may not cover every situation. If you're unsure whether a specific use of assets is permitted under the Catch License, consider the following questions:

- **Is the asset strictly necessary to resolve a compatibility issue between mods?**
- **Does the asset contribute to the intended functionality or appearance of the mods when used together?**
- **Is the asset used in a way that respects the original mod author's intent and permissions?**

Keep in mind that most mod authors are open to communication and may grant additional permissions if you reach out to them. If in doubt, it's always best to ask for explicit permission when being unsure about the use of assets.

Most mod authors are also okay with you using their assets in a compatibility patch, as long as you credit them and don't monetize the patch. However, it's always best to check the original mod's permissions and the Catch License to ensure you're following the rules correctly.
