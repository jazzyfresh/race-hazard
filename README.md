# race-hazard
demonstrate programmatic race conditions in a video game


## Overview

Simulated spacecraft shenanigans

Gameplay generates events, which require action.
Some action requires communication.
All action must be done within a timely fashion, or else expect impending doom.

Every player has a Role.
Role is composed of Monitors + Controls.

Every player has a Feed, eg. their communication with other players.
This feed is how individual players can become aware of the full state of the system.

Through teamwork & collaboration you can reach the center of the galaxy~~~~**

## Gameplay
Phase 0: Command Line Interface/Text-based Adventure
* Nyan-cat ascii art to depict spaceship progress

Phase 1: Actual graphics???
* You know, bits & stuff

## Notes
* Different roles can solve different types of problems
* Part of the strategy is choosing your role distribution at startup
* Channels of communication can go down, requiring you to communicate thru a middleman

* Feed
  * Simple: Chat log
  * Complex: Integrated video chat (thru some 3rd-party video application)

