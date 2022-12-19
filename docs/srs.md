## Introduction

### Purpose

Senate is a word-based multiplayer game to improve your debate and eloquence skill (speechcraft)

### Scope(benefits, objectives and goals)

Unique experience, that will train people to be more skilled in a debate
Ranking similar as in chess.com
Support this intellectual acivity in a proper way may open ways to generate income in future
Inspired by: mafia word-based game, chess.com

### Definitions and Acronyms

This is a free software projects. Every profit will be shared between contributors, that mean that only risk - lack of intrerest during implenmentation. Product can be unfinished.

## Overall Description

### User needs

Product may be interested for competitive debaters, students, politicians and philosophers

### Assumptions and Dependencies

Only JS, because javascript is the most known language and for simplicity.
We are assuming that every developer is familiar with javascript.
We are assuming that tech research is a significant part of development process.
Dependencies: Node.js, JavaScript

## System Features and Requirements

### Functional Requirements

 - Every player must have an account
 - This means sign up, sign in, ouath2.0 with google etc.
 - Each game has multiple player roles: arbitors, team1(one or more players), team2(one or more players), host, viewers
 - There are two game modes: one vs one and team vs team
 - Each game starts from creating a wait-room for players
 - There are settings for a game: number of players in a team, duration of preparation, duration of speech rounds, number of arbitors.
 - Topic of a debate must be setted up.
 - Each player can join one waiting room with specific role(host, player, arbitor).
 - Viewers can join any time
 - Players must split into teams with different position about a debate topic or one vs one.
 - When room is full players must decide which team they are joining if it is team mode and if they are not decided yet.
 - Then a popup with accept button will appear, game starts after all players are accepted. There must be a timeout to accept a game and after timeout - afk player must be removed.
 - Game contains several rounds.
 - Preparation round, arbitors and host are waiting. Team members prepare arguments and speeches collaborative.
 - Speeches round. Team members are making speeches as configured, e.g. 5 speeches for 2 minutes each.
 - Arguing round. Team members are questioning and arguing with oponents position. Similar as speeches, time and count limitations must be configured.
 - Final round. Arbitors have a speech, where they explaining their descicion. Who wins, who had better arguments, who was better in arguing and why. Extra point can be added from host based on viewers votes.
 - After game is done - winners are becoming rating points (maybe losers must los, but I am not sure about competetive part design)

It is a high communicative app
Video + voice chats must be impelmented.
Game rooms, chats, messages, votings must be implemented.
