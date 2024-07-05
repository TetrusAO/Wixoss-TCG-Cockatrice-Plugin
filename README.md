# Wixoss-TCG-Cockatrice-Plugin

Welcome, and thank you for downloading this package for Wixoss TCG. This download contains everything you need to add this game to your Cockatrice program, along with some extra files to help newer players ease themselves into this amazing game.

**First, a disclaimer:**

I do not own anything related to the Wixoss franchise, including its anime series, trading card game, manga, and any other form of product or service. This is a package containing information that is readily available through multiple public sources on the internet. Everything included here is done without profit and solely to help bring personal enjoyment and spread awareness of the great game that is Wixoss TCG.

**Directions for first time install [Cockatrice](https://cockatrice.github.io/):**

Instructions are Windows-only and this will completely remove all Magic: the Gathering card data from the program. If you want to keep MTG around, follow the official Cockatrice Wiki [article](https://github.com/Cockatrice/Cockatrice/wiki/Custom-Cards-&-Sets) for custom set functionality, under the "to add custom sets follow these steps" section.  

1. Install Cockatrice (link above)

2. Open Cockatrice.  If the program tells you it's going to run Oracle, let it do so.

6. In this GitHub webpage that contains the Wixoss plugin, click the "Wixoss TCG.xml" file in the file list.

7. On the right side of the screen, click the button that says "Download raw file" when hovered over using the cursor, then save the file.

2. Open Start Menu, type "Folder Options", then open the "File Explorer Options" program that appears.

3. Click the "View" tab, then under the "Hidden files and folders" section, select "Show hidden files, folders, and drives."

4. Close File Explorer Options.

5. In Cockatrice, head to Card Database -> Manage Sets.  You should see a bunch of sets for Magic: the Gathering listed.

6. Click "Disable all sets",  then click a checkbox on exactly one set in the set list to re-enable it. Make a note of what you enabled here.

7. Close the "Manage Sets" window.

8. Go back into Card Database, then "Open custom sets folder."

9. Move the Wixoss TCG.xml file you downloaded from this GitHub page into this folder.

10. In the same window, click the "Cockatrice" that is directly to the left of "customsets" in the address bar.

11. Delete cards.xml

12. Close Cockatrice, then reopen it. It will show a new prompt showing a bunch of sets being added and is asking if you want to enable them or not. Click yes to that.

13. Go to Card Database -> Manage Sets.  Find the set you re-enabled in step 6 and disable it again.  Close the window.

13. Wixoss is fully added to Cockatrice. Enjoy! 

-- **Directions for updating the plugin for new content updates:** --

1. In this GitHub webpage that contains the Wixoss plugin, click the "Wixoss TCG.xml" file in the file list.

2. Right click the "Download" button, then select "Save Link As..." and save it to anywhere you can easily access later.

3. In Cockatrice, go to Card Database -> Open Custom Sets folder

4. Move the newly downloaded Wixoss TCG.xml you got from step 2 into this folder.  If it asks you to replace the old Wixoss TCG.xml with it, say yes.

5. Close the custom sets window.

6. Back in Cockatrice, go into Card Database -> Open custom image folder.

7. Click "pics" on the address bar above the folder contents. You should see two folders names "CUSTOM" and "downloadedPics"

8. Delete "downloadedPics".  This will tell Cockatrice to redownload these images upon encountering them in the client again, letting you see any new changes to the image files I made on my end.

9. Your Wixoss plugin is now fully updated.  Enjoy the new cards and images!


-- **Some useful functions to help operate Wixoss TCG on Cockatrice** --

- Placing cards face-down on the field from anywhere is an important mechanic for this game. To do this, hold the Shift key, then click and drag the card to wherever the card needs to be. For instance, to setup your 7 cards in your Life Cloth, hold Shift and click+drag the top card of your deck to the bottom row of your board seven times, making sure all the cards are stacked from left to right in order. Facedown cards are also numbered on the field, so take advantage of that when ordering your Life Cloth stack correctly for all players involved.

- Adding a card to your Ener Zone is quick and easy for the cards in your hand. Just double click any card in your hand to directly send it to the vertical zone on the board. This area will be treated as your Ener Zone.

-  Wixoss TCG is a game that uses 2 separate decks: the main deck and the LRIG Deck. The LRIG deck is accessed by looking at your sideboard ingame through pressing Ctrl+F3. Double click any card in the LRIG deck to directly place it on the bottom row of your field. When a card is to return to the LRIG deck for any reason, open up the sideboard window and drag the specific card back into that window.

-  Adding cards to your LRIG Deck in the Deck Edit screen is done by holding the Ctrl button then adding the card through your regular means. This will display as if it was added to the sideboard, but this is just general card game terminology at work.  Nothing to worry about here.

-  Wixoss TCG deckbuilding rules require the main deck to have a maximum of 20 cards with the [Life Burst] ability on them. These cards are noted with the |LB tag on the card type section of each card, next to the main card type (eg SIGNI|LB).

-  Assist LRIGs are also similarly marked with a LRIG|Assist tag.

-  Cards that have a (KS) label on the card type section are cards only legal in Key Selection and All Star formats.  The (DS) label is for cards legal for all currently available formats.  Cards with neither of these tags are legal in All Star only.  These labels will prove very helpful in building decks for specific formats, when used with the Cockatrice database filter function.

-  Any other functions that you may need to help play Wixoss TCG on Cockatrice can be found by right-clicking a card or empty area on the field or any zone available to you.

-  If you have any further questions, feel free to message me on Discord.  Name is Tetrus#0297.
