# AuctionFilterPlus
Purpose: Adds flyout filters and a reset button to the auction house.

Command-line: NONE

Author: Dsanai of The Crimson Knights on Whisperwind

Thank you to the authors of AuctionFilterRL (Joshaze), AH_Reset (AnduinLothar), and AH_Wipe (Neriak), as these mods formed the base for this extension.

I've added a few more filters that I always wished I'd had when shopping (such as only-20-piece stacks, and exact search), changed it to a low-clutter Flyout display, added the ability to clear and save one's filter settings,  merged the two mods into one, and added tooltips so users have more information about what each filter does.

## FEATURES

- Adds a Filter button and a Reset button to the AuctionHouse frame.
- Pressing the Filter button will cause a Flyout menu to appear.
- The filter checkboxes on the flyout allow you to limit your AH results or change the display of certain information.
- You can clear your filter settings with a single click.
- You can clear your Auction House search boxes with a single click.
- You can save your filter settings as your default setup, which will persist across sessions, characters, and servers.
- You can clear your settings temporarily and then reload them without relogging.
- Each of the filter checkboxes has an explanatory tooltip.
- Ready for localization (please help do so, if you are German- or French-speaking). You will be credited!
- Compatible with Auctioneer.

#### NOT DONE YET

- Fixed Dressing Room bug. Should now show the correct item even if filters are turned on.
- Fixed Chat Link bug. Should now link the correct item in chat.
## VERSION HISTORY

#### v10900-1

- Fixed slash command (courtesy Aingnale@WorldOfWar)
- Added "Grey Out Unbid Items" option. Will grey out the prices for items that have not been bid on yet. (idea courtesy myShowBid by mhsin)
- Show Best Deals now takes into account Greater Essences (will be valued as 3 items when competing against Lesser Essences)
- Fixed so that Auctioneer Beta will also be supported (variable name courtesy barryj@Curse)

#### v1800-6

- Added AuctionSort functionality (courtesy Abraha)
- Added Show Best Deals, which will evaluate prices and tell you how an item fares against the average for the search results.
- Show Best Deals will also take into account how many pieces of cloth were used to create bolts of cloth, when rating its value.

#### v1800-5

- DE translation reworked (courtesy dan2507@Curse)
- Increased the width of the flyout panel, and of the Clear button, so localized strings should fit.
- Can be set to color known recipes, plans, schematics, etc. (courtesy LeisureLarry@Curse)
- Added command-line to open flyout panel, if the button is unclickable due to other mods.

#### v1800-4

- Really disables itself when KC_Items is scanning. Thanks, Sharky@Curse.
- Globalized the "Already Known" string, so all clients should now be able to use that filter. Thanks, Olivier@Curse.

#### v1800-3

- Disables itself when KC_Items is scanning.
- German localization completed (courtesy Dan2507 and Naboradd)
- Localized checkbox description text.
- Attempt to fix the occasional tooltip error on line 492. Let me know if tooltips show the wrong item.

#### v1800-2

- Disables itself when Auctioneer is scanning.

#### v1800-1

- Initial release

### POTENTIAL FUTURE ADDITIONS (Subject to change)
- Filter: Don't show auctions listed by people I've Ignored. (Don't fund the idiots.)
- Filter: Only show items that haven't been bid on yet. (Try to find ones I can snag at a bargain, without a bidding war.)
- Filter: Only show XX quality items. (Blizzard quality filter shows that level AND higher.) NOTE: Read Blizzard dropdown.
