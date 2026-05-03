# Bot_Bot Market System

This project is a market intelligence and trading system.

## News Profile (Market Intelligence)

The NEWS profile is responsible for collecting, processing, and serving all market intelligence data used by the app.

### Source Attribution (IMPORTANT)

All data must preserve attribution:

- source_name
- source_url
- provider
- provider_item_id
- attribution

The app must display the source for every news item or market data shown.

## Architecture

- NEWS = Market Intelligence Engine
- BOT = Trading Scanner (TK/TG)
- PUSH = Live Feed / Notifications

All data flows through memory files.

The app and server DO NOT connect directly to external providers.
