# IDS702-Final Project Proposal - PUBG Winning Strategy

## Overview

### Background

PlayerUnknown's Battlegrounds (PUBG) is a popular shooting game in a setting where up to 100 players parachute onto an island and scavenge for weapons to kill while avoid being killed. The available moving area of the game shrinks in size periodically, forcing players to face each other over time. The last player or team surviving wins the battle.

### Summary

This project aims to analyze PUBG user post-game stats to come up with winning strategies to increase the odds of winning for each battle. Winning is defined as getting into top ten percentile in a match.

### Scope 

The project analyzes winning strategies only on two groups of data - individual players and squad team players. There are several different battle modes for the game, here the project only focuses on the classic mode.


### Data

A large number of anonymized PUBG game stats where each row contains one player's post-game stats are provided by Kaggle. The data comes from matches of all types: solos, duos, squads, and custom.
Variables included:  UserId, groupId, matchId, assists, boosts, damageDealt, DBNOs, headshotKills, heals, killPlace, killPoints, kills, killStreaks, longestKill, matchDuration, matchType, maxPlace, numGroups, rankPoints, revives, rideDistance, roadKills, swimDistance, teamKills, vehicleDestroys, walkDistance, weaponsAcquired, winPoints.

Size of the data: test data - 1048575 rows of data, 28 attributes

Possible problems: There exists missing data. There is also no guarantee of there being 100 players per match, nor at most 4 player per group, which might be a factor influencing the winning odds.

### Project Plan

Logistic model will be attempted, multilevel linear model and multilevel logistic model are considered as well. To ensure the project is completed in time, initial EDA exploration is scheduled to be done by mid-Nov, model selection, assessment, and interpretation is scheduled to be completed at the end of Nov. Presentation slides will be finished on Dec 5, with report due in Dec 10 2019.
