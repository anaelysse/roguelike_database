# roguelike_database
This repository contains the SQL relational database design for a video game that involves players, cards, NPCs, and inventory management. The database is structured to support features such as player card collection, NPC card drops, and card effects.

Features Supported
Player Inventory Management

Players can hold multiple cards, and the cardCount tracks the quantity.
NPC Drops

NPCs can drop specific cards with defined drop rates (dropRarity).
The canDrop flag determines if a card can currently be dropped.
Card System

Cards include attributes like:
Damage, cooldown, durability, and stack limits (maxStackable).
Cards are linked to unique effects.
Effects Management

Effects add variety to cards, storing names and detailed descriptions.
