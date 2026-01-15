# Version 0.29 (1/14-1/15 2026):
  - Added select command for battles
  - Added selected command to view currently selected card
  - Added 'selected' text in inventory
  - Updated trash command
  - Added coins command
  - Added in app cache for shiny cards
  - Created this changelog D:
  - Added changelog command

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

# Version 0.2 (11/24/2025):
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
