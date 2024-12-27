# Fantasy-Football-App
Software Requirements Specification
for
 Fantasy Football App
 
Prepared by Carlos Sandoval

12-27-24
 
1.	Introduction

1.1	Purpose

The purpose of this app is to provide an interactive and engaging fantasy football experience for users, allowing them to play with friends and customize various aspects of the game. Users can create and manage fantasy football teams, draft players, and track live updates of player performance, including injury status and game statistics. The app also enables users to monitor the overall team scores, individual player scores, and the status of NFL teams, including their position on the field and possession of the ball.
An administrator can set up the league, invite participants, and define the league's rules, such as team size, draft rules, bye weeks, playoff schedules, and other fantasy football settings. The app will be accessible via Android, iOS, and a web platform, ensuring a wide reach for users to enjoy the game on their preferred devices.

1.3	Intended Audience and Reading Suggestions

The intended audience for this SRS includes developers and anyone interested in understanding the details of the fantasy football app. This document provides an in-depth overview of the app’s features, functionalities, and system requirements.

1.4	Project Scope

This app will allow users to create a league, conduct a draft with league members, and manage a team with drafted players. Users will have access to a free agent section to add and remove players from their teams. The administrator will be responsible for setting league rules, monitoring transactions made by each team, and modifying team rosters when necessary. The admin will also have the ability to update the league rules as needed. Users can participate in multiple leagues and manage multiple team rosters. Additionally, the app will provide live game updates for NFL teams, including player performance and injury status.

2.	Overall Description

2.1	Product Perspective

This fantasy football app is a standalone product aimed at enhancing the user experience of managing fantasy football leagues. The app will be designed for use on Android, iOS, and web platforms, ensuring accessibility across different devices. It will interface with live NFL game data to track player performance and injury updates, but it will not depend on any third-party services for the core functionality of league management, player drafting, or team administration.

The app will not be directly integrated with existing fantasy football platforms but will offer unique features like customizable league rules and the ability to modify scores manually.

2.2	Product Features

League Creation and Management: Users can create and manage their own leagues, invite members, and set league rules (e.g., team size, draft rules).

Team Drafting: Users participate in a draft to select players for their fantasy football teams.

Team Management: Users can manage their teams by adding and removing players through a free agent section.

Live Game and Player Updates: The app provides real-time updates on NFL games, including player performance, injury status, and team scores.

Admin Controls: League administrators can manage league settings, monitor transactions, and modify teams and player stats if needed.

Multiple League Participation: Users can be part of multiple leagues and manage multiple teams from a single account.

2.3	Operating Environment

The fantasy football app will operate in the following environments:

Mobile Platforms:

iOS (version X.X and above)

Android (version X.X and above)

Web Platform:

Supported browsers: Chrome, Firefox, Safari, and Edge (latest versions recommended)

Platform: Web-based application accessible via standard browsers on desktop and mobile devices

3.	System Features
   
3.1	User Account Management

3.1.1	Description 

	Users can create an account, sign in, and manage their profile.
 
3.1.2	Functional Requirements

REQ-1:	Users must be able to create an account using their email or a third-party login (Google/Facebook).

REQ-2:	Users should be able to edit their profile and view their teams and leagues.

REQ-3:    Passwords should be securely stored, and users can reset them if forgotten.

3.2	League Creation and Management

3.2.1	Description 

	Users can create and manage fantasy football leagues
 
3.2.2	Functional Requirements

REQ-1:	Admins can set up league rules (e.g., number of teams, draft settings, etc.).

REQ-2:	Users can invite others to join the league.

REQ-3:    Admins can modify league rules at any time.

3.3	Player Drafting and Team Management

3.3.1	Description 

	Users can participate in a draft and manage their fantasy football team.
 
3.3.2	Functional Requirements

REQ-1:	Users can view available players, draft them to their team, and manage player positions.

REQ-2:	Users can add/drop players from their roster.

REQ-3:    Users can trade players with other teams within the league.

3.4	Live Game Updates and Player Performance Tracking

3.4.1	Description 

The app tracks real-time NFL game data and updates player scores and performance.

3.4.2	Functional Requirements

REQ-1:	The app will display live game scores, player statistics, and injury updates.

REQ-2:	Users can view the performance of players on their fantasy team and update scores accordingly.

REQ-3:    Notifications will be sent for major game events affecting a user's team (e.g., a touchdown, injury, or trade).

3.5	Free Agent Section

3.5.1	Description 

	Users can create and manage fantasy football leagues
 
3.5.2	Functional Requirements

REQ-1:	A list of players not yet drafted will be available, and users can add them to their team.

REQ-2:	Users can filter by position, performance stats, and other criteria.

3.6	Admin Control and Monitoring

3.6.1	Description 

League admins can monitor and manage team activities and league rules.

3.6.2	Functional Requirements

REQ-1:	Admins can view and approve/reject trades, player adds/drops, and monitor league transactions.

REQ-2:	Admins can modify the league rules and settings at any time during the season.

