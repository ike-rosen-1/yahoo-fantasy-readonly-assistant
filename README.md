# Personal Yahoo Fantasy Read-Only Assistant

This repository describes a small personal, non-commercial tool being developed
for a single user's own Yahoo Fantasy Football league.

## Purpose

The assistant retrieves read-only fantasy data on demand and helps its owner make
better-informed decisions. It provides recommendations only; the owner reviews each
recommendation and manually performs any desired action in Yahoo.

Typical questions include:

- Which available players are strong waiver candidates?
- Which roster player could be dropped for a waiver addition?
- What would be a reasonable FAAB bid?
- Which players should be started or benched?
- Which mutually useful trades might exist within the league?

## Yahoo data requested

The tool requests read-only access to:

- League settings and scoring rules
- Standings and weekly matchups
- Team rosters
- Available and waiver players
- League transactions
- Player statistics

## Usage and privacy

- Single user and single Yahoo league
- Local execution on the owner's Mac
- On-demand refreshes, normally only a few times per week during the NFL season
- Local caching to reduce repeated API requests
- No public Yahoo data feed
- No sale or redistribution of Yahoo data
- No automated adds, drops, bids, trades, or lineup changes
- No request for Fantasy Sports write access

The project is seeking Yahoo Fantasy Sports API read access (`fspt-r`) for this
limited personal use case.
