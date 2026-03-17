# Version 0.41 (3/4 2026):
  - Updated one piece bronze badge emoji to look more distinguishable from gold
  - prestige icon emojis
  - embed util funcs
  - trade command bugs
  - market rework
  - give command
  - unified inv id vs gs
  - added series to numbered info
  - added single auction page
  - added auction reminders
  - added youve been outbid noti dm
  - new prestige badge emojis
  - reformat profile
  - if new user, start journey
  - clandys +++++
  - add clans and tickets to profile
  - add new ticket emoji
  - added new energy emoji
  - added clan tag to pvp
  - user item inv
  - added latest command
  - active boosts cmd
  - display badge

# Version 0.40 Economy Update (2/27-3/2 2026):
  - Bug Fixes:
     - Fixed a bug with energy command displaying outdated energy values
     - Fixed a bug with bt all and bt mass not working on bosses
     - Fixed a bug with market level filter
     - Fixed a bug with market remove all
  - You can now trash cards in market, it will just remove them
  - Cards getting removed from a user removes all listings of that card
  - Added more area backgrounds
  - Added card prestige visibility on most things
  - Added prestige filters for inv and market
  - Added max price filter for market
  - Updated inv function to use skip/limit for efficiency
  - Added trade board
      - Post trades to other users!
      - Add up to 10 specific cards you want to trade for
      - Accept any of the same rarity
      - Accept any modded card
      - Automatically trades when someone offers a card that matches your listing
      - Trade board views all posted trade listings
      - Filter trade board by any card filter
      - Filter trade board by what the posts are looking for
          - Use -lf filter and rarities (m,rare,etc) or card ids (luffy is 1)
          - Use -lfm filter to find listings that accept all mods
  - Added auctions
      - All auctions are 24 hours
      - Post to the auction house with your starting price
      - Posts will delete market/trade baord posts
      - Can not remove posts
      - If no one bids, you keep your card
      - Cannot bid on your own auction
      - Must have the bid amount of coins when placing bid
      - Bid minimum amount or specify a higher amount
      - Auctions can be filtered by all card filters
      - Auctions automatically complete within a minute after expiration

# Version 0.39.5 (2/26/2026):
  - Added soul/coin rewards when getting collection badges
  - Added DM notify when getting badges
  - Added coin rewards to bt all and bt mass
  - Added card prestige
      - At level 100, card can prestige
      - Costs (prestige level * 1000) coins
      - Reset all stats and stat points
      - Gives 10% stat bonus in battle (multiplicative)
      - Gives +1 stat point every time they're awarded
  - Added new 'poisoned' mod
  - Updated PvE fights to use Area background

# Version 0.39 (2/25/2026):
  - Added bt all and bt mass to auto logs
  - Added user xp
  - Added user level ups
      - Adds +1 max energy (cap 100)
      - 5 energy refilled
  - Created and added new one piece badge custom emojis
  - Added badges command to view your badges
      - Also works on other players by pinging
  - Added new badge type (collection)
      - For each world
      - Bronze: all epic and under cards
      - Silver: all legendary and under cards
      - Gold: all cards

# Version 0.38 (2/23-2/24 2026):
  - Created and added new custom soul flame fragment emoji
  - Added 'character groups'
  - Reworked special dialogues to work off of character groups
  - Added soul flame fragments as PvE drops (3-5 per fight)
  - Added souls command to view your soul flame fragments
      - Added button to sell from the viewing souls embed
  - Added souls sell (ID) command to sell souls for 1 coin each
  - Added souls summon command to summon cards
  - Added souls to trading
  - Added energy that can be used to farm soul flame fragments
      - 1 energy per battle
      - Uses your last beaten battle
      - Auto regens every 5 minutes
      - Has a max that increases with player level
  - Added bt all command to use all energy
  - Added bt mass (#) command to use (#) energy
  - Added energy command to view current energy

# Version 0.37 (2/19/2026):
  - Added "Hidden Levels" requiring user to use a specific card to enter
  - Added baseCardIds to pulled cards for faster DB lookup
  - Added pulledIds to user to track what cards they've pulled
  - Created custom red background x emoji
  - Created Gachadex to show user's beaten, owned, and pulled cards
  - Added new user setting dex locations to show where cards are located
  - Added descriptions of settings into settings embed

# Version 0.36 (2/17-2/18 2026):
  - Added empty worlds object to user data on start command usage
  - Added back button on stat points shop
  - Created all PvE levels, commands, interactions and more
      - Added all areas and levels to one piece world
          - Added character pools for each level
          - Added 'difficulties' on fights
              - "Elite" +10% attack
              - "Boss" +10% attack and +10% hp
          - Added scaling base card difficulty
          - Added scaling XP through levels
          - Added stars on level completion
              - 1 star for completion
              - 2 stars if no elemental advantage
              - 3 stars if no elemental advantage and beaten in 5 or less rounds
          - Added stories before fight which change based on characters
          - Player's card gets bonus stats if from the world they're fighting
          - Added automatic completion tracking and badge distribution
      - Added all commands to access PvE battles
      - Added all commands also as button interactions 

# Version 0.35 (2/13-2/16 2026):
  - Added new "badges" and badge custom emoji for profile
  - Created world "one piece" and all areas and levels for it
  - Fixed bug when passing improper page args into inv command
  - Updated commands to accept a wider variety of syntax for filters
  - Added world selector
      - Added paginator for world selector
      - Each world has an area selector
          - Each area has a level selector

# Version 0.34.5 (2/12/2026):
  - Fixed major bug with "thank you, next" mod not consuming properly
  - Added mods command to view the bonuses of all mods
  - Added visual elements chart to elements command

# Version 0.34 (2/11/2026):
  - Added more inventory sorting methods
      - Name, element, ability
  - Reset spent stat points for 1,000 coins
      - Reset (Inv ID) command
      - Reset button in stat point shop
  - Added admin settings
      - Admin command brings up admin settings embed
      - Must be admin or have mod role to use
      - Added mod role customization
      - Added select channels - bot only responds in selected channels
          - Default is still all channels
      - Remove all button for selected channels

# Version 0.33 (2/10/2026):
  - Added multiple value handling for inventory filters
  - Added all filters to info command (previously only name)
      - Rarity, element, ability, series
  - Fixed bug allowing users to pass as bot in inv command
  - Added user settings
  - Added settings command to change your settings
    - Defaults left as is
    - Toggle shiny visuals
    - Toggle detailed card stats
    - Change inventory sorting method
      - Ascending/Descending
      - Serial, rarity, level, mod, series
  - Made stat point spend confirmation embed ephemeral
    - Added button removal after spending last point

# Version 0.32 (2/09/2026):
  - Fixed major trading bugs
      - Users both adding cards
      - Adding cards after confirming
      - Added 10 card cap per user per trade
  - Added auto logs
      - Bot sends log embeds to secure channel
      - All major DB transactions are logged
  - Trading/selling cards now unfavorites them
  - Added series (-ss) filter to inventory

# Version 0.31 (1/21/2026):
  - Added levels to cards
      - XP requirement scales
      - Stats increase every level
      - Bonus stats every 2nd level by card archetype
      - Bonus stats shown in card info (if not 0)
      - Max level 100
      - Added stat points system
          - Every 5 levels, get 5 stat points
          - Use in stat points shop to choose what stat to upgrade
  - Mods correctly affect battle rewards/stats
  - Instant DR changed to only work for card with higher def
  - Fixed shiny image display bug caused by discord lazy image resolve
  - Added 20 round battle cap and tiebreaker
      - Tiebreaker uses damage dealt and hp remaining
  - Updated hp bar visual logic

# Version 0.30 Battle Update (1/16-1/20 2026):
  - Added battle command (PvP)
      - Battle other users
      - Added confirmation embed
      - Added battle background with user avatars to confirmation embed
      - Created and added default user image (when user does not have discord avatar set)
      - Store live battles in redis with pair lock
      - Battle progression by half a round at a time
      - Battle progression visually updates every 3 seconds
      - Added crits and evasion
      - Added elemental advantages (damage multipliers)
      - Updates user stats after battle finishes (PvP wins and matches)
      - Added buttons (replay and delete) to battle end embed
      - Added shiny visuals in battle
      - Added replays
          - Added full round by round replays
          - Added buttons to switch rounds
          - Added timeout when replay expires in DB
      - Gives coins as reward (random amount)
      - Gives cards XP as rewards
  - Reformatted select command to work off globalSerial (internally only)
  - Updated hp custom emojis
  - Updated profile mythbound text

# Version 0.29 (1/14-1/15 2026):
  - Added select command for battles
  - Added selected command to view currently selected card
  - Added 'selected' text in inventory
  - Updated trash command
  - Added coins command
  - Added in app cache for shiny cards
  - Created this changelog D:
  - Added changelog command
  - Updated paginator display
  - Updated market sell command
  - Updated market list default sorting
  - Added mass remove from market (ex: remove 1,9,15)

# Version 0.28 (1/13/2026):
  - Migrated images to use discord CDN
  - Updated custom hp emojis
  - Created and added shiny image mask
  - Added shiny card visual effects throughout bot

# Version 0.27 (1/12/2026):
  - Created and added custom hp bar emojis
      - Segments and different colors based on current hp
  - Created battle background
  - Got image creation for battles between cards organized
      - Different positioning by rarity due to different borders

# Version 0.26 (12/18/2025):
  - Added series filter to market
  - Added embed to view all market listings
      - Added filters to market viewing
  - Added listing command to see what you personally are listing on market
  - Added remove all command for market listings

# Version 0.25 (12/12/2025):
  - Added market
      - Added buy and sell commands for market
      - Added market status to mongoDB
      - Added remove command for market

# Version 0.24 (12/10-12/11 2025):
  - Added mod all filter to inventory
  - Updated trash command
  - Added trade command
      - Added trade safeguards
      - Added trade embed
      - Added live updates on embed
      - Migrated trades to redis
      - Coins and cards allowed in trade
      - Auto update account mods/stats after trade
      - Added mass card adds to trades

# Version 0.23 (12/02/2025):
  - Added trash command
      - Added card specific warnings
      - Card value determined by mod, rarity, etc
  - Updated help commands
  - Updated info commands
  - Added shop command
      - Use coins to buy more tokens
  - Created and added custom emojis for tokens

# Version 0.22 (11/26-11/28 2025):
  - Optimized info embeds for mobile devices
  - Updated pull commands
  - Added message to new users to start their journey
  - Added shiny visibility to pulls
  - Added custom emojis for rarities
  - Switched inventory command to an embed
      - Added pages
      - Added emojis for elements, rarities, and shinies
      - Added mod visibility to inventory
  - Added element command for advantage chart
  - Added favoriting to cards
      - Added favorite filter to inventory
  - Added favorites command

# Version 0.21 (11/25/2025):
  - Returned mod visibility to pulls
  - Added more user stats
  - Added profile command to show profile embed
      - Added 'author' to user profiles
  - Added account wide modifier tracking
  - Added info command for cards (by name)
  - Added card descriptions to DB
  - Added card series to cards
  - Added world copies counters for each card
  - Added option for multiple names in one info command call
  - Added cycle buttons to info command
  - Added info command for inventory cards
  - Added card XP
  - Added trash buttons to most embeds

# Version 0.2 Aesthetic Update (11/24/2025):
  - Updated pulls to an embed
      - Added pull background image
      - Added pull character image
  - Added card art to DB
  - Created and added rarity based card borders
  - Added more cards to DB
  - Added admin command
  - Updated help command
  - Added pull again buttons

# Version 0.17 (11/21-11/22 2025):
  - Added inventory command
      - Added inventory filters
  - Updated ping command with latency
  - Added card elements

# Version 0.16 (11/20/2025):
  - Changed token requirements for pulls
      - Each pull uses its own token type
  - Added pull lock (one pull at a time per user)
  - Added start command to register users
      - Gives 10 copper tokens
  - Added help command

# Version 0.15 (11/19/2025):
  - Setup server for near 100% bot uptime
  - Added shinies and shiny visibility to pulls
  - Added token requirement for pulls
      - Updated test command to give 10k tokens for testing
  - Fixed bug with suggestion command

# Version 0.11 (11/18/2025):
  - Added more cards (common and uncommons)
  - Added visible rarity and mods to pulls

# Version 0.10 (11/10-11/17 2025):
  - Setup entire database
      - MongoDB for persistence
      - Local Redis for quick cache
  - Added test command to register users to DB
  - Added first few cards to DB
  - Added pull commands
    - Basic, enhanced, premium
  - Added card mods
  - Added card rarities
  - Added random chance logic (mods, rarities, etc)
  - Added suggest command
  - Added user stats

# Version 0 (10/07/2025):
  - Registered bot with discord
  - Added ping command
