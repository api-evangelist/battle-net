# Battle.net (battle-net)
Battle.net is Blizzard Entertainment's online gaming platform and developer API ecosystem. It provides game data and player profile APIs for World of Warcraft, Diablo III, Hearthstone, and StarCraft II via OAuth 2.0-secured REST endpoints, enabling developers to build applications that access character data, game statistics, leaderboards, card collections, and auction house data.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/battle-net/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Games, Gaming, Blizzard, World Of Warcraft, Diablo, Hearthstone, Starcraft

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-04-19

## APIs

### World of Warcraft Game Data API
Provides access to World of Warcraft game data including achievements, auction house listings, character classes, races, realms, guild data, items, spells, zones, and PvP leaderboards. Requires OAuth 2.0 client credentials flow.

**Human URL:** [https://community.developer.battle.net/documentation/world-of-warcraft/game-data-apis](https://community.developer.battle.net/documentation/world-of-warcraft/game-data-apis)

#### Tags:

 - Games, Gaming, World Of Warcraft

#### Properties

- [Documentation](https://community.developer.battle.net/documentation/world-of-warcraft/game-data-apis)
- [Authentication](https://community.developer.battle.net/documentation/guides/using-oauth)

### World of Warcraft Profile API
Provides access to player profile data for World of Warcraft including character summaries, equipment, achievements, collections, mythic keystone profile, and PvP profile data. Requires OAuth 2.0 authorization code flow with user consent.

**Human URL:** [https://community.developer.battle.net/documentation/world-of-warcraft/profile-apis](https://community.developer.battle.net/documentation/world-of-warcraft/profile-apis)

#### Tags:

 - Games, Gaming, World Of Warcraft, Player Profile

#### Properties

- [Documentation](https://community.developer.battle.net/documentation/world-of-warcraft/profile-apis)
- [Authentication](https://community.developer.battle.net/documentation/guides/using-oauth)

### World of Warcraft Classic Game Data API
Provides game data for World of Warcraft Classic (Era and Seasonal), including classic realm lists, auction house data, character classes, races, and items specific to the classic game versions.

**Human URL:** [https://community.developer.battle.net/documentation/world-of-warcraft-classic/game-data-apis](https://community.developer.battle.net/documentation/world-of-warcraft-classic/game-data-apis)

#### Tags:

 - Games, Gaming, World Of Warcraft Classic

#### Properties

- [Documentation](https://community.developer.battle.net/documentation/world-of-warcraft-classic/game-data-apis)
- [Authentication](https://community.developer.battle.net/documentation/guides/using-oauth)

### Diablo III Game Data API
Provides access to Diablo III game data including season index and season data, era index and era leaderboards. Requires OAuth 2.0 client credentials flow.

**Human URL:** [https://community.developer.battle.net/documentation/diablo-3/game-data-apis](https://community.developer.battle.net/documentation/diablo-3/game-data-apis)

#### Tags:

 - Games, Gaming, Diablo

#### Properties

- [Documentation](https://community.developer.battle.net/documentation/diablo-3/game-data-apis)
- [Authentication](https://community.developer.battle.net/documentation/guides/using-oauth)

### Diablo III Community API
Provides access to Diablo III community data including character profiles, hero data, item data, follower data, artisan data, and act information. Requires OAuth 2.0 for profile endpoints.

**Human URL:** [https://community.developer.battle.net/documentation/diablo-3/community-apis](https://community.developer.battle.net/documentation/diablo-3/community-apis)

#### Tags:

 - Games, Gaming, Diablo

#### Properties

- [Documentation](https://community.developer.battle.net/documentation/diablo-3/community-apis)
- [Authentication](https://community.developer.battle.net/documentation/guides/using-oauth)

### Hearthstone Game Data API
Provides access to Hearthstone card data including card search, card back collections, deck building, and metadata such as card sets, classes, card types, rarities, and keywords. Requires OAuth 2.0 client credentials flow.

**Human URL:** [https://community.developer.battle.net/documentation/hearthstone/game-data-apis](https://community.developer.battle.net/documentation/hearthstone/game-data-apis)

#### Tags:

 - Games, Gaming, Hearthstone

#### Properties

- [Documentation](https://community.developer.battle.net/documentation/hearthstone/game-data-apis)
- [Authentication](https://community.developer.battle.net/documentation/guides/using-oauth)
- [OpenAPI](openapi/battle-net-hearthstone-game-data.yaml)
- [JSONSchema - Card Schema](json-schema/hearthstone-game-data-card-schema.json)
- [JSONSchema - Card Back Schema](json-schema/hearthstone-game-data-card-back-schema.json)
- [JSONSchema - Deck Schema](json-schema/hearthstone-game-data-deck-schema.json)
- [JSONSchema - Metadata Schema](json-schema/hearthstone-game-data-metadata-schema.json)

### StarCraft II Game Data API
Provides access to StarCraft II game data including league data for multiple game modes. Requires OAuth 2.0 client credentials flow.

**Human URL:** [https://community.developer.battle.net/documentation/starcraft-2/game-data-apis](https://community.developer.battle.net/documentation/starcraft-2/game-data-apis)

#### Tags:

 - Games, Gaming, Starcraft

#### Properties

- [Documentation](https://community.developer.battle.net/documentation/starcraft-2/game-data-apis)
- [Authentication](https://community.developer.battle.net/documentation/guides/using-oauth)

### StarCraft II Community API
Provides access to StarCraft II community data including player profile, ladder summaries, grandmaster leaderboards, and static game data for profile, legacy, and ladder resources.

**Human URL:** [https://community.developer.battle.net/documentation/starcraft-2/community-apis](https://community.developer.battle.net/documentation/starcraft-2/community-apis)

#### Tags:

 - Games, Gaming, Starcraft

#### Properties

- [Documentation](https://community.developer.battle.net/documentation/starcraft-2/community-apis)
- [Authentication](https://community.developer.battle.net/documentation/guides/using-oauth)

### Battle.net OAuth API
Provides OAuth 2.0 authorization services for Battle.net including client credentials flow for game data access and authorization code flow for player profile data. Token endpoint, authorization endpoint, and token validation endpoint are available per region (US, EU, APAC).

**Human URL:** [https://community.developer.battle.net/documentation/battle-net/oauth-apis](https://community.developer.battle.net/documentation/battle-net/oauth-apis)

#### Tags:

 - Authentication, Gaming, OAuth

#### Properties

- [Documentation](https://community.developer.battle.net/documentation/battle-net/oauth-apis)
- [Authentication](https://community.developer.battle.net/documentation/guides/using-oauth)

## Common Properties

- [Portal](https://community.developer.battle.net/)
- [Documentation](https://community.developer.battle.net/documentation)
- [GettingStarted](https://community.developer.battle.net/documentation/guides/getting-started)
- [Authentication](https://community.developer.battle.net/documentation/guides/using-oauth)
- [RateLimits](https://us.forums.blizzard.com/en/blizzard/t/api-access-clients-rate-limits/5602)
- [GitHubOrganization](https://github.com/Blizzard)
- [Support](https://us.forums.blizzard.com/en/blizzard/c/api-discussion)
- [TermsOfService](https://www.blizzard.com/en-us/legal/a2989b50-54f6-43f3-b55c-fa78e0ca3b38/blizzard-developer-api-terms-of-use)
- [SDK - Passport.js Battle.net Strategy](https://github.com/Blizzard/passport-bnet)
- [SDK - OmniAuth Battle.net Strategy (Ruby)](https://github.com/Blizzard/omniauth-bnet)
- [CodeExamples - Java OAuth Sample](https://github.com/Blizzard/java-signature-generator)
- [CodeExamples - Node.js OAuth Sample](https://github.com/Blizzard/node-signature-generator)
- [CodeExamples - Ruby OAuth Sample](https://github.com/Blizzard/ruby-signature-generator)

## Features

| Name | Description |
|------|-------------|
| OAuth 2.0 Authentication | Supports both client credentials flow for game data and authorization code flow for player profile data access. |
| Multi-Region Support | APIs are available across US, EU, and APAC regions with regional base URLs (us.api.blizzard.com, eu.api.blizzard.com). |
| Game Data APIs | Access static and dynamic game data including items, spells, realms, seasons, leaderboards, and card metadata. |
| Player Profile APIs | Access authenticated player data including character profiles, achievements, equipment, and PvP records. |
| Localization Support | API responses support multiple locales per region, enabling localized game data in multiple languages. |

## Use Cases

| Name | Description |
|------|-------------|
| Game Companion Apps | Build companion applications for WoW, Hearthstone, or Diablo that display character stats, gear scores, and progression. |
| Auction House Trackers | Monitor World of Warcraft auction house data to track item prices and market trends. |
| Leaderboard Displays | Show StarCraft II, Diablo III season, and WoW PvP leaderboards in custom applications. |
| Deck Builders | Create Hearthstone deck-building tools using the card data, metadata, and deck APIs. |
| Guild Management Tools | Build guild management utilities using WoW guild roster, achievements, and activity data. |

## Integrations

| Name | Description |
|------|-------------|
| Passport.js | Battle.net OAuth strategy for Node.js applications using Passport.js authentication middleware. |
| OmniAuth | Battle.net authentication strategy for Ruby on Rails applications using OmniAuth. |
| Microcks | API mocking and testing platform for Battle.net API contract testing. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Battle.net Hearthstone Game Data API](openapi/battle-net-hearthstone-game-data.yaml)

### JSON Schema

- [Card Schema](json-schema/hearthstone-game-data-card-schema.json)
- [Card Back Schema](json-schema/hearthstone-game-data-card-back-schema.json)
- [Card Back Search Response Schema](json-schema/hearthstone-game-data-card-back-search-response-schema.json)
- [Card Search Response Schema](json-schema/hearthstone-game-data-card-search-response-schema.json)
- [Deck Schema](json-schema/hearthstone-game-data-deck-schema.json)
- [Deck Card Schema](json-schema/hearthstone-game-data-deck-card-schema.json)
- [Deck Class Schema](json-schema/hearthstone-game-data-deck-class-schema.json)
- [Metadata Schema](json-schema/hearthstone-game-data-metadata-schema.json)
- [Metadata Item Schema](json-schema/hearthstone-game-data-metadata-item-schema.json)
- [Error Response Schema](json-schema/hearthstone-game-data-error-response-schema.json)

### JSON Structure

- [Card Structure](json-structure/hearthstone-game-data-card-structure.json)
- [Card Back Structure](json-structure/hearthstone-game-data-card-back-structure.json)
- [Deck Structure](json-structure/hearthstone-game-data-deck-structure.json)
- [Metadata Structure](json-structure/hearthstone-game-data-metadata-structure.json)

### JSON-LD

- [Battle.net Hearthstone Game Data Context](json-ld/battle-net-hearthstone-game-data-context.jsonld)

## Vocabulary

- [Battle.net Vocabulary](vocabulary/battle-net-vocabulary.yaml) — Unified taxonomy mapping 9 resources, 3 actions, 0 workflows, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Battle.net Spectral Rules](rules/battle-net-spectral-rules.yml) — 30 rules across 9 categories enforcing Battle.net API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
