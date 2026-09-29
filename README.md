# Reanimated Dead × Vara Reference Integration

This repository is the planned public home for the Vara Network integration components proposed for **Reanimated Dead**, a live browser-based trading card game.

**Project:** Reanimated Dead  
**Live game:** https://reanimateddead.com  
**Network:** Vara Network  
**Status:** Proposed / pre-development

## About Reanimated Dead

Reanimated Dead is a free-to-play browser trading card game built around gameplay first and optional digital ownership.

Players can play without cryptocurrency, a wallet, or an NFT.

The live game currently supports:

- Solo and multiplayer gameplay
- Ethereum NFT utility
- Solana NFT utility
- Stripe and Ethereum purchases
- Player profile badges

Additional cosmetics, owner-driven lore, tournaments, spectator functionality and other player features are in development or testing.

## Proposed Vara Integration

The proposed work adds a Vara-native ownership and progression layer to the existing game.

The planned integration includes:

- Vara account linking
- Vara-native collectible ownership
- Six selected collectible templates
- Four selected badges/cosmetics
- Participation and championship awards
- One three-state progressing cosmetic
- Sponsored claim flows using bounded gas vouchers
- One approved owner-driven lore/version path
- Ownership reconciliation
- Competitive rewards
- Production instrumentation and reporting
- A public competitive activation with spectator access

Existing Ethereum and Solana functionality will remain supported.

Core Reanimated Dead gameplay will remain off-chain and wallet-optional.

## Native Vara Architecture

The proposed integration is intended to use Vara's native development stack rather than an EVM port.

Planned technologies include:

- Rust
- Sails
- WebAssembly
- Vara Network
- Vara native NFT / VNFT infrastructure
- Vara gas vouchers
- JavaScript / TypeScript client integration

Reanimated Dead's existing backend remains authoritative for gameplay rules, moderation, private player data and game entitlements.

Vara programs will manage the agreed blockchain ownership, collectible and claim state.

## Planned Public Components

Subject to final grant scope and technical review, this repository is intended to contain separable components created through the Vara integration, including:

- Vara / Sails programs created for the integration
- Account-linking reference interfaces
- Collectible and ownership integration examples
- Sponsored-claim examples
- Entitlement interfaces
- Configuration examples
- Automated tests
- Deployment and recovery documentation
- Technical implementation notes
- Production case-study findings

The goal is to provide other game developers with a practical example of integrating Vara-native ownership and sponsored collectible claims into a conventional game backend.

## Player Experience

The intended player journey is simple:

1. Play Reanimated Dead normally.
2. Become eligible for a selected collectible or competitive award.
3. Optionally connect a Vara account.
4. Claim the eligible asset through the supported flow.
5. Reanimated Dead verifies the resulting ownership.
6. The corresponding collectible, cosmetic, progression state or recognition appears in the game.

Blockchain participation will not be required for ordinary gameplay.

## Gas Vouchers

The proposed integration will evaluate and use bounded Vara gas vouchers for selected claim interactions.

The goal is to avoid requiring an eligible player to acquire VARA solely to pay the transaction fee for receiving an earned collectible.

Voucher usage will be limited to approved programs and interactions and will operate within a defined project budget.

## Owner-Driven Lore

Reanimated Dead is developing a system in which eligible asset owners can contribute approved lore associated with supported game assets.

For the proposed Vara implementation:

1. Ownership of an eligible Vara collectible is verified.
2. The owner may submit lore through defined rules.
3. Content is moderated and versioned.
4. An approved version can be associated with the relevant asset.
5. Reanimated Dead recognizes that approved state.
6. Any resulting game effect remains bounded by Reanimated Dead's rules.

Arbitrary owner-authored content will not execute directly as game logic.

## Competitive Integration

Reanimated Dead is actively developing and testing tournament and spectator functionality.

The proposed Vara integration will include selected participation and championship collectibles and culminate in a public competitive activation.

Production measurements will distinguish:

- Reanimated Dead game accounts
- Vara-linked accounts
- Successful collectible claims
- Award recipients
- Repeat usage
- Relevant gameplay participation

Internal tests and retries will not be presented as player adoption.

## Open-Source Boundary

This repository is intended for the **separable Vara-specific integration components** developed through the proposed project.

It is **not** the source repository for the complete Reanimated Dead game.

The following remain proprietary:

- Reanimated Dead core game source
- Characters and artwork
- Card designs and game content
- Proprietary gameplay systems
- Private backend systems
- Player/account data
- Commercial infrastructure
- Reanimated Dead brand and other commercial IP

The final public-source scope and license will follow the applicable grant agreement and third-party license requirements.

## Current Status

This repository was created in preparation for the proposed Vara integration.

**No Vara production deployment or grant award is claimed at this time.**

Development artifacts, programs, tests and documentation will be added if and as the proposed work proceeds.

## Team

### Joshua Kassabian
Technical Lead

Software architecture, game development, blockchain/payment integrations, production systems and technical delivery.

### Jeff Vongore
Creative & Product Lead

Game/product development, art, collectibles, physical-product direction and distribution.

The team has worked together for approximately four years across cryptocurrency, NFTs, digital products and Reanimated Dead.

## Links

**Play Reanimated Dead:**  
https://reanimateddead.com

**Vara Network:**  
https://vara.network

---

Reanimated Dead is an independent project. References to Vara Network or Gear Foundation describe a proposed integration and should not be interpreted as an endorsement, partnership or grant award unless explicitly announced by the relevant parties.