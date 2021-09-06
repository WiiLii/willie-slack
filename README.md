# SIT-LearningFiesta-V2
An MMORPG-like game, but for SIT.

## Database Requirements
### User Login
  - UserID
  - Username (can be email)
  - Nickname
  - Password (SQLite 3rd-party Encryption)

### User Progress
  - UserID (Foreign Key)
  - Coins DEFAULTS to 0
  - Task Progress (Tasks 1-13, for example) DEFAULTS to 0

## Multiplayer

### Current Implementation
  - Photon Unity Network
  - HARD Limit: 100 concurrent users
  - Chat may be carried over

### Proposed Implementation

  > [Mirror Networking](https://mirror-networking.com/)

  > [AWS Guide](https://mirror-networking.com/docs/Articles/Guides/DevServer/AWS/index.html)

## Housekeeping (Unity)
 - All sprites go into the sprites folder
 - Scripts go into Scripts folder under their respective category
 - All test and development Scenes go into the Scenes folder
