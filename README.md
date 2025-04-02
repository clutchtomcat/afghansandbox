# DCS Afghanistan map sandbox mission
This is a sandbox mission encompassing the entire Afghanistan map with multiple client slots, tankers, and tasks generated via the F10 communications menu.

## Features Overview
* On-demand CAS tasks with AI voiceovers
* On-demand strike tasks
* On-demand troop transport tasks
* Dynamic cargo
* Supercarrier with Airboss script for cyclic operations
* Tankers for aerial refueling
* Kneeboards with comms plan, waypoints, and navaids
* Forward operating bases and outposts (templates by PeneCruz)
* AI traffic for ambiance

![Alt text](/MAPS/NorthEast.png) ![Alt text](/MAPS/South-Central.png)

## On-demand CAS tasks
CAS tasks are available for all platforms through the communications menu F10 "other" > F1 "CAS Tasks" > F1-F7. Tasks are generated in one of the 7 AOs indicated on the map. Some are time sensitive or use smoke markers, so the player should ensure that they are within the AO boundary before initiating a task. Any tasks that instructs "advise when..." requires further interaction through the F10 menu to continue the task. Task coordinates will be given in UTM, but may not always be in 10-digit format and may include elevation. Any task that does not give coordinates will be marked with smoke or an F10 map marker. There are 5-10 tasks per AO. It may take multiple call-ins to initiate a task due to the DCS random roll system. When all tasks have been exhausted there should be a message indicating task completion for that AO.

## On-demand Strike tasks
Strike tasks are available for all platforms through the communications menu F10 "other" > F2 "Strike Missions" > F1-F2. Strike missions are split into East and South-Central areas of the map. When a strike mission is initiated, a brief description message will appear and the location will be marked on the F10 map. A brifing image with DMPIs will be loaded into the briefing screen (Esc > Briefing).

## On-demand troop transport
Troop transport tasks are available for the CH-47 and Mi-8 through the communications menu F10 "other." When a transport task is initiated, a brief message will appear and locations will be marked on the F10 map. Pickup/dropoff is done by the embark/disembark functions in the comms menu (F7 "Airborne troops").

## Dynamic cargo
Dynamic cargo is available at all blue coalition airbases, heliports, and outposts with a FARP helipad.

## Supercarrier
Super carrier module is way down south with Airboss script running 3-hour cycles. Launch/recovery windows are 45 minutes, with the next event starting three hours after the previous event. E.g.: Event 1 at 0600-0645; Event 2 at 0900-0945. Mission time needs to be set at least 5 minutes before a scheduled event else the carrier will not turn into the wind.

## Tanker support
Five tankers are availalbe. Boom tankers can be commanded to slow down or speed up via the F10 "other" menu F3 "Tanker speed." Slow is 230kts for A-10s, fast is 270kts for everyone else.

## Kneeboards
Kneeboards are included in the mission by default. They are also available for download/printing in the GitHub folders.

## Other features
* "Strongholds." There are three strongholds marked in red on the map: Payindi, Korengal, and Tora Bora. AAA and MANPADS are known to be in these areas.
* "Thorns." These are single insurgents around high-traffic areas that may take potshots at you if you wander into their range. Tactical overheads are recommended when landing.


