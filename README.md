# Backgammon123

Advanced JavaScript Course Project 2023/2024

## What the project is about

Backgammon123 is an online backgammon platform with a simple interface.

## Main functionalities

### Accounts

Each user can create their own account and earn rating points.
Users are not required to create their own account, but this limits their sessions to playing only without earning rating points.

### Sessions

Users can both create and join other users' sessions.
Sessions can be either public or private, and to join a private session one requires a key that is provided to the user who created the session.
Sessions have settings where you can specify whether the winner receives rating points after the game ends.

### Chat

During gameplay, players can send text messages to each other.

### Rating points

After each game, the winner receives a points rating based on their probability of winning.
Players with a lower probability of winning are rewarded with more points when they beat a player whose probability of winning is higher than theirs.
