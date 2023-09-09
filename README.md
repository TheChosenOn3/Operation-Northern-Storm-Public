![Operation Northern Storm](/Images/Banner.png)

# Overview:
**Operation Northern Storm** is a new persistent mission set in Syria, running a custom build of MOOSE and the DCT Framework. A passion project inspired by Flashpoint Levant from the Lima Kilo Team, the mission takes place in the year 1999, offering more modern payloads and over 130 unique missions. In this scenario, Syria has launched a formidable offensive campaign into Turkey, and it is your mission to thwart their advance.

## Features:
- **DCT Mission Framework by Instigator:** Interactive mission system that provides engaging objectives for players.
- **Payload limit system:** Realistic loadouts for sorties and restrict weapons to match the time period.
- **Custom IADS (Integrated Air Defense System):** Dynamic enemy SAM sites with advanced defense mechanisms.
- **Custom Bomb Script:** Larger bombs and weapons have their explosive power accurately adjusted.
- **Sneaker by b1naryth1ef:** A website-based AEW&C (Airborne Early Warning & Control) interface for GCI's to facilitate efficient communication and coordination.
- **OverlordBot by Rurounijones:** An AWACS Voice bot that utilizes SRS to communicate with players.
- **TextOverlordBot by Rurounijones:** Similar to OverlordBot but employs text alerts instead of voice, accessible through the F10 Menu.
- **CTLD Integration:** Transport helicopters can drop troops and vehicles that actively engage nearby missions (note: troops must be dropped within a 10km radius of the mission center for engagement).
- **Campaign Persistent CSAR (Combat Search and Rescue):** Player-ejected pilots can be rescued by friendly helicopters and transported back to nearby FARPs.
- **Balanced missions to make all airframes enjoyable.**
- **FARPs and Dedicated Regions tailored for helicopter gameplay:** Helicopters stationed at FARPs will receive nearby missions within their allocated regions.
- **Render Manager (LK Team):** Improves server performance significantly by despawning units that are out of range from players.

## DCT Mission Framework:
The server utilizes the DCT Framework to provide an interactive mission system for players. Players can request missions available for your airframes by using the F10 menu.

### To select or join a mission:
1. Open the communication menu (`\`) and select "Other..." by pressing F10.
2. Press F4 to open the "Mission..." menu.
3. Press F1 to choose the desired mission type.
   - Select a mission type compatible with your aircraft.
4. Press F2 to view a list of the nearest missions based on your current location.
   - Choose the mission you want to undertake.
5. Press F4 to join a specific mission by entering its corresponding code.
   - Use the function keys (F1 = 1, F9 = 9) to input each digit of the mission number.

### After selecting a mission, you will receive the following information:
- **Mission Number:** A unique identifier for the mission that can be shared to other players to allow them to join.
- **Coordinates:** The location relevant to the mission that's provided in a format compatible with your airframe.
- **Briefing:** A situation report including potential threats and mission objectives.
- **Map Labels:** Labels visible exclusively to mission participants, aiding navigation and coordination.

![Mission Briefing](/Images/MissionExample.png)

## Payload Limits:
The server enforces payload limits for sorties, ensuring that loadouts align with the designated time period. Each aircraft is assigned an A/G (Air-to-Ground) limit of 60 points and an A/A (Air-to-Air) limit of 20 points. Exceeding the allocated budget will trigger a warning, prompting you to modify your loadout accordingly. It is important to note that certain airframes may have specific variations in their A/G limits or additional restrictions.

The payload restriction sheet can also be found in the kneeboard and mission briefing.

![Loadout Restrictions](/Images/WeaponRestrictions.png)

## Radio Frequencies:
The server utilizes SRS (Simple Radio Standalone) for seamless communication among players. SRS is used as a reliable means of interaction and coordination on the server. Additionally, SRS is used to communicate with the Overlord bot through voice channels. You can find the comprehensive frequency sheet in both the kneeboard and mission briefing for easy reference.

![Radio Frequency Sheet](/Images/FrequencySheet.png)

## Overlord Bot & Text Overlord:
Overlord bot is available on the server to assist with communication and coordination. To find the Overlord bot frequencies, check the communication sheet on your kneeboard or refer to the briefing images. Every aircraft comes preloaded with presets for all the frequencies used on the server. Text Overlord is also available to all players, and can be accessed from the F10 Menu. For a quick tutorial on using the Overlord bot, watch this short video: 

<div align="center">
  <a href="https://www.youtube.com/watch?v=oGm7Y5rH4QE"><img src="https://img.youtube.com/vi/oGm7Y5rH4QE/0.jpg" alt="OverlordBot"></a>
</div>

## Situational Map:
The regional map dynamically changes based on players' mission progress and outcomes.
- **Blue:** Represents friendly territory.
- **Purple:** Signifies contested areas.
- **Red:** Indicates enemy-controlled territory.

![Starting Regions Condition](/Images/WorldRegions.png)

## Aircraft Carriers:
- **USS George Washington (CVN-73 Supercarrier):** Enables naval operations for F-18s and F-14s.
- **USS John C. Stennis (CVN-74 Free Carrier):** Hosts AI-controlled aircraft patrolling the Mediterranean Sea.
- **Admiral Kuznetsov (Supercarrier):** Serves as a carrier for Su-33 aircraft and acts as a smoke signal reference for lost naval pilots.
- **USS Tarawa (LHA-1):** Functions as an AV-8B carrier in close proximity to the Latakia region.

## Friendly Bases:
- **Incirlik:** A large military airfield situated safely in Turkey, housing most fast jets on the server. Nearby friendly tankers are available.
- **Gaziantep:** A small military airfield near the Syrian border, designated for CAS (Close Air Support) aircraft and hosting a few older airframes.
- **Hatay:** A friendly airfield located in contested territory. Players can use this base for rearming and refueling near the frontline, but they should be cautious of potential attacks from enemy ground forces and airplanes.
- **FARP London:** A makeshift helicopter base on the border between Turkey and Aleppo. Currently, it is under heavy attack by Syrian forces. Players spawning at this FARP will be assigned missions in the Aleppo region as a priority.
- **FARP Dallas:** A repurposed cement factory serving as a helicopter base. Players spawning at this FARP will be assigned missions in the Kharab region as a priority.
- **FOB Warsaw:** A roadbase accommodating Swedish Viggens and Finnish Hornets. It is set up slightly closer to the frontline for enhanced operational efficiency.

## Additional Notes & Tips:
- The server will restart every 6 hours. During the restart, the map will switch to a different version with a new weather preset and time (Morning/Afternoon). Completed missions will persist until the campaign restarts or a side loses.
- At the start of the campaign, it's recommended to prioritize SEAD (Suppression of Enemy Air Defenses) to facilitate the completion of other mission types in the regions.
- The server utilizes a custom IADS (Integrated Air Defense System) script. SAM sites will hold fire until you're within kill range. Be cautious of SAM launches and react defensively immediately when being shot at.
- The IADS script also shuts off radars when anti-radiation missiles are detected. Firing a HARM at a SAM site will disable the site temporarily, allowing the HARM to pass through the area. If you choose to destroy SAM sites using HARMs or other anti-radiation missiles, you'll need to adopt a "Wild Weasel" approach, putting yourself at potential risk of being shot down.
- By exploiting the IADS script's behavior, you can use missile shots to buy yourself or a teammate time to engage the SAM site with air-to-ground munitions. This is why SEAD missions recommend having two pilots, but most airframes can complete SEAD missions on their own.
- The server implements a custom bomb script to adjust the explosive power of larger bombs accurately. Larger bombs, such as the 1000lbs Mk 83's or 2000lbs Mk 84's, have a significantly wider explosion radius. Utilize this to your advantage, and be careful of low altitude drops :slight_smile:
- The server has over a 130 missions for players to complete, with about 40 missions primarily designed for helicopter gameplay. There are two FARPs available (London and Dallas), with helicopter-friendly missions in those areas. The DCT Framework will only hand out missions in the regions close to the FARPs.
- On the red side, the server employs a custom A2A (Air-to-Air) and A2G (Air-to-Ground) Dispatcher. It dynamically deploys CAP flights, interceptors, SEAD, recon, and CAS planes to defend territories and attack the blue side. After taking down CAP flights and interceptors, they can take anywhere from 30 minutes to an hour to respawn. Bombing runways can also deny enemy flights from taking off on that runway for an hour.
- The enemy CAP and interceptor detection relies on SAM sites and EWRs (Early Warning Radars). Eliminating these targets will significantly decrease the effectiveness of enemy CAP and interceptors. Flying low and undetected will help you avoid interception.
- The server is equipped with an AI Balancer that automatically spawns Bluefor planes to assist with CAP (Combat Air Patrol) in mission areas when the server has a low player count. As more players join the server, the number of AI CAP flights will be adjusted accordingly, reducing their presence.

---

# Changelog

## 0.5.1 (2023-08-05) - Midnight Mission
### Map Updates:
- **Added Midnight Version** of the Map, rotating in every second day.
- **Introduced Dynamic Winds**: Different wind directions between missions, with the addition of strong winds and a chance for wind direction flipping.
- **Included A-4E Mod compatibility**: No mod installation required to join the mission. A-4E Slots now available at Gaziantep and Incirlik.
- **Added MiG-25 CAP/Intercept Squadrons** to Hama.

### Missions:
- Added 6 new **SHORAD missions** to guard vital airfields.
- Added 4 new **SAM Missions** in the Taftanaz Region.
- Added 4 new **Convoy BAI missions**.
- Added 7 new **Strike Missions** (Special thanks to @bullet_za & @\_weasel\_).

### Lighting and Effects:
- **Added Night Lighting** for FARP London.
- **Implemented Flare effects** for arriving helicopters at FARP London.

### Adjustments:
- **Adjusted Mission Date** to align with Full Moon for more visibility at night.
- Revised some of the older missions and updated corresponding briefings.
- Relocated friendly SAM sites near Gaziantep to ensure they won't hit friendly planes coming in for a landing.

## 0.5.0 (2023-07-24) - Syria Lighting Update 
- Updated all the Strike Missions with the new Object ID's.
- Carriers have been assigned a priority region of Latakia. Players spawning on the carriers will be prioritized mission in the Latakia region.
- Updated the Template Files.
- Added 1 new Strike Mission.
- Updated Latakia Fuel Dump 1's Mission briefing with the help of ChatGPT.

## 0.4.9 (2023-07-18) - Label & Syria Update Prep 
- Updated Strike Templates for upcoming Syria update.
- Fixed F-15E Fuel.

## 0.4.8 (2023-06-23)
- F-15E Fast align.
- F-15E DDM.
- F-15E Mission Set.

## 0.4.7 (2023-06-22) - Corrected Mission Name & Update 
- Corrected Mission Name.
- Added F-15E S4 with 90 AG Points.
- Added F-15E S4 to Incirlik.
- Updated Weapon Restriction.

## 0.4.6 (2023-05-27)
- Adjusted MB-339 Spawns (FFS IFE).
- Adjusted AI Difficulty.

## 0.4.5 (2023-05-25)
- Removed WW2 Asset Pack Requirement.

## 0.4.4 (2023-05-25)
- Added Priority Region.
- Adjusted Fuel of Russian Helicopters.
- Removed Strike Missions from Apache.

## 0.4.3 (2023-05-19)
- Added AGM-114L Radar Hellfire.
- Updated AGM-114K Laser Hellfire cost.
- Removed CAS from MB-339.
- Updated Weapon Restriction Sheets.
- Added support for CSAR Rearm Truck.

## 0.4.2 (2023-01-26)
- Added Mirage F1EE.

## 0.4.1 (2023-01-22)
- Added Experimental Aircraft to Gazipasa.
- Bugfix for A2G Dispatcher.
- Added CSAR Persistence.

## 0.4.0 (2023-01-19) - Operation Northern Storm Initial 
- Removed Flashpoint 1999 References.
- Renamed Mission.
- Added 20+ Missions.
- Updated Description and Images.

## 0.3.9 (2022-12-28)
- Fixed broken %LOCATIONMETHOD% in some missions.
- Optimized Borders.
- Removed Useless payload increase for F-5E and M2K.
- Misc Fixes.
- Moved Older aircraft to Gaziantep.
- Added Black Shark 3
- Added Finish Hornets to FOB Warsaw
- Added Additional Options for A2G Dispatcher for BAI and CAS Missions
- Moved Kuweires Recon to Bassel Al-Assad.

## 0.3.8 (2022-11-20)
- Nerfed Abu-Al Duhur MiG-23's
- Adjusted Tanker Positions

## 0.3.7 (2022-11-19)
- Moved Land-based Harriers from Incirlik to Gaziantep.
- Updated the CVN-73's Recovery Tanker. Will now stay in pattern and within 10NM from the carrier.
- Updated F-14's AN/ALE-39 Default Loadout to 40 Flares/20 Chaff (Can be updated in Ground Crew Menu)

## 0.3.6 (2022-11-18)
- Added BAI Missions to F/A-18C
- Removed SEAD from MB-339A
- Fixed an Issue with Aleppo-BAI-1

## 0.3.5 (2022-11-15)
- Added TACAN to Gaziantep
- Updated Frequency Sheets.
- Updated setErrorMessageBoxEnabled to hide error messages.

## 0.3.4 (2022-11-11)
- Added HARM Codes to Mission Briefing
- Added Mission Difficulty Text to some difficult missions
- Added Restrictions to AIM-54C MK.60, LS-6-100 & LS-6-250
- Added Mission Restrictions for MB-339A
- Adjusted Tanker Positions to more safe orbits
- Updated Weapon Restriction Sheets

## 0.3.3 (2022-11-01)
- Updated for DCS 2.8
- Added MB-339 Slots to Gaiziantep
- Adjusted Slot positions at Gaziantep
- Added F-5E's to Gaziantep.
- Fixed Naming convention of units at Gaziantep.

## 0.3.2 (2022-11-01)
- Added Description to .DCT Files, instead of templates
- Implemented Priority System
- Moved all players slots to CTJF.

## 0.3.1A (2022-10-16) - Bugfixes & Squadrons
- Bugfix for TextOverlordBot
- Misc Bugfixes
- Bugfix for Squadrons

## 0.3.1 (2022-10-08)
- Fixed Recon Group
- Added CAS and BAI MiG-21 groups to Aleppo
- Removed CTLD script as it's been integrated into DCT
- Sneaker & DCT CTLD prep stuff.

## 0.3.0 (2022-10-02)
- Updated Frequency Sheet & Briefing to include IL-76.
- Updated Weapon Restriction Sheets.
- LD-10 & AGM-88 HARM moved to 30 points.
- LD-10 Double pylons disabled.
- Laser Guided bombs (GBU-10, GBU-16) changed to 15 points.
- IL-76 Flight path adjusted.
- Second Batch of Optimizations.
- Optimized FARP London (Further optimization might be needed).
- Adjusted the IL-76 Tanker.
- Updated LoadScripts.lua addition in the mission, and disabled the GRPC load script.
- Removed over 200 Infantry from missions.
- Added Config Files for Telemachus, Opentelemetry and more.

## 0.2.9 (2022-09-20)
- First batch of Optimizations (Needs to be tested).
- Removed large amount of units & smoke from the map.
- Removed assets from FOB's and FARP's.
- Disabled A2G Dispatcher (Pending performance tests).
- Added IL-76 Tanker for Kuznetsov and Su-33.
- Moved Bassel SA-5 to it's own region with priority of 15.
- Moved Latakia to priority 10.
- Moved Taftanaz to priority 15.
- Moved Aleppo to priority 5 (Needs to be tested).

## 0.2.8 (2022-09-01)
- Implemented Script Loader.
- Adjusted Final Mission to make it more difficult.
- Correct wording in Hama Final and SHORAD-Aleppo-3.
- Implemented Point Back system for CSAR (Untested).
- Adjusted Tabqa region priority.

## 0.2.7 (2022-09-01)
- Updated CTLD Save Path to "C:/DCT/".
- Added MiG-21 Intercept to Bassel.
- Added three new BAI Missions.
- Added two SHORAD missions to Aleppo.
- Fixed Existing SHORAD Mission protecting Minakh & Taftanaz.

## 0.2.6 (2022-08-30)
- Initialized Hama Region.
- Added Final Mission in Hama Region.
- Added SA-11 Mission in Hama.
- Adjusted Latakia Fueldump Mission.
- Updated Mission Briefing & Kneeboard Images.
- Implemented Final Mission Trigger.
- Implemented Allied Loss Trigger.

## 0.2.5 (2022-08-28)
- Fixed Recovery Tanker racetrack altitude.
- Nerfed F-15's with AAMRAMS.
- Moved MiG-25 CAP zone more west.
- Adjusted Bassel CAP zone.
- Fixed Frequencies of aircraft on carriers.
- Enabled JF-17 LD-10 Double Racks.

## 0.2.4 (2022-08-27)
- Added Weather Presets.
- Added Mission Restart.
- Improved Latakia SA-5 Sites.
- Updated Communication Sheet & Weapon Restrictions.
- Carrier ATC Fix.
- Carrier Frequency Hotfix
- Updated Weather

## 0.2.3 (2022-08-07)
- Simplified Borders.
- Fixed some slots.
- Removed Unused Regions.

## 0.2.2 (2022-08-05)
- Added Strike Missions to Latakia.
- Removed Moose Player Menu.

## 0.2.1 (2022-08-03) - Flashpoint 1999
- Changed name of the mission.
- Added Mirage F1 player slots and settings.
- Added Yak-52 and P-48D-40 Slots.
- Fixes for Minakh Shorad.

## 0.2.0 (2022-07-15)
- Added CTLD
- Added 5 new BAI Missions
- Added 2 new SA-8 SAM Missions
- Adjusted & fixed broken SAM missions in Aleppo Region
- Simplified the borders for performance

## 0.1.9 (2022-07-06)
- Added DCT Borders
- Moved FARP Dallas to the Kharab region.
- Added Hatay Region
- Added Cyprus Region
- Added Isreal Region
- Added Jordan Region
- Added Iraq Region
- Added Damascus Region
- Added Hama Region
- Added Taftanaz Region
- Added Deir Region
- Added Lebanon Region
- Renamed Bassel Al-Assad Region to Latakia.
- Moved missions around to appropriate regions.

## 0.1.8 (2022-06-18)
- Fixed A-10 Payload Limits
- Adjusted Northern AWACS position
- Added OverlordBot

## 0.1.7 (2022-06-17)
- Added 8 BAI Missions to the Minakh Region
- Added BAI Missions for the M-2000, JF-17. F-16
- Removed Armed Recon from the Ka-50, JF-17 and AH-64D
- Removed CAS from JF-17 and F-16
- Updated Frequency Sheet in the briefing to be more readable.
- Updated Frequency & Weapon Restriction Sheets for Kneeboard.

## 0.1.6 (2022-06-16)
- Adjusted Tanker Speeds to be more user friendly.
- Adjusted few red scouting zones.
- Moved one of the blue defenders at FARP London, to reduce the likely hood of friendly fire incidents.
- Adjusted recon values for all lower intel missions, to be more precise and provide better coordinates.
- Adjusted the artillery armed recon missions in the Minakh region to be in slightly better spots, and added artillery fire command for cinematic effect.
- Added three more CAS missions to the Aleppo/Minakh region.
- Created the Kharab Ishk region
- Added ten CAS missions to the Kharab Ishk region.
- Added nine Armed Recon missions to the Kharab Ishk region.
- Updated Configuration files for upcoming Overlord Bot Integration.

## 0.1.5 (2022-06-10)
- Fixed A-10CII Gaziantep Group Names
- Added gRPC Scripting for OverlordBot
- Added Misc files for the mission
- Hid the Smoke and Invisible FARP Objects from the Map
- Increased the interval respawn time for the MiG-23's being spawned at Al-Duhur
- Reduced the skill of enemy CAP Aircraft being spawned in the Aleppo Region
- Changed F-18C's to F/A-18C Lot 20's on the CVN-73
- Added ICLS (13) to CVN-73
- Added Patrol between waypoints for Carriers
- Updated Carrier Alert State to engage enemy aircraft.
- Fixed Couple of Group names for player slots
- Changed Couple of Armed Recon & CAS mission to be spawned in constantly when players are nearby.
- Added two JTAC Slots
- Added LotATC Support

## 0.1.4 (2022-06-10)
- Added Render Manager.
- Added over 200+ player slots with different airframes and all with radio presets to be used on the server.
- Adjusted Airframe restricted weapon in ME to stop players from selecting banned weapons.
- Updated Briefing.
- Added Briefing Images.
- Adjusted Weapon Restrictions & Added Weapon Restriction to briefing.
- Added FOB Warsaw (Viggen Roadbase).
- Added USS Tarawa.
- Added FARP Dallas for future missions at the cement factory.
- Removed Region Limits & Added Spawnalways to certain templates.
- Added two new tankers at Incirlik.
- Added TACAN's for FARP's and FOB's.
- Added Gaziantep to the theatre.
- Adjusted Redfor A2G Dispatcher Squadrons, and increased timings of SEAD squadrons substantially.
- Added MiG-23 CAP to Abu al-Duhur

## 0.1.3 (2022-06-04)
- Fixed FARP London not allowing some helicopters to rearm
- Added CAS Mission 7 at Hatay border checkpoint
- DCT Bugfix for FARP London
- Fixed F-16CM Default Coordinates
- Removed viewing of enemy units as blue
- Adjusted Helicopter Mission Max parameters

## 0.1.2 (2022-06-04)
- Added Additional Strike missions of all categories to Aleppo.
- Added Substantial Amount of SAM Missions to Bassel Al-Assad.
- Adjusted Mission Limits for playtest.
- Added Strike Mission Template to repository.
- Added SAM Mission Template to repository.
- Added "On Demand" parameter to all missions to allow all missions to be done in future stage, when despawning is implemented.
- Adjusted RED SEAD Flights.
- Adjusted Mission Zones for A2G Dispatcher.
- Adjusted Weapon Restrictions to be closer to final values.

## 0.1.1 (2022-05-29)
- Removed A2GDispatcher Logging
- Fixed more issues with FARP London
- Updated ATO for airframes
- Reduced amount of spawned mission for ArmedRecon, CAS, SEAD, Strikes
- Added Regional Settings for Switch to FPL DCT

## 0.1.0 (2022-05-29)
- Fixed FARP London causing DCT Generation Issues
- Added Modified WeaponRestrictions
- Added Mission Template Folder (Temp)
- Added Syria Borders from Levant Mission (Modified)
- Adjusted A2ADispatcher
- Added A2GDispatcher with Recon, SEAD, CAS and BAI Flights.
- Fixed Admiral Kuznetsov
- Added More blue units to the frontline on the Syria border
- Adjusted Bluefor Plane skins
- Adjusted Redfor Plane Skins
- Adjusted CAP/Intercept Behavior, will now release drop tanks when empty.
- Adjusted weapons on some Red CAP Flights
- Adjusted Blufor & Redfor Borders to induce more fights
- Added North Eastern Border zone to protect Tabqa
- Assigned some flights to North Eastern Border
- Adjusted Blufor CAP Detection in regards to helicopters
- Added more blufor balancer types.
- Added Minakh Region
  - Added 6 CAS Mission
  - Added 9 ArmedRecon Missions
- Added Kuweires Region
  - Added 1 SAM Mission
- Added Jirah Region
  - Added 1 SAM Mission
- Added Tabqa Region
  - Added 4 SAM Missions
  - Added 1 EWR Mission

## 0.0.7 (2022-05-25) - Added CSAR & Dynamic Loading of Moose
- Added CSAR for blueside (Needs Tone).
- Added Dynamic Loading to Moose.
- Added Misc units to Hatay Region.
- Added Invisible Farps for the Helicopters at FARP London.
- Fixed Interceptors spawning with no cooldown.
- Fixed KC-130 (Shell-3-1) Orbit Altitude and speed.
- Fixed Shell-1-1's Codename.
- Added EjectedPilotKiller.

## 0.0.6 (2022-05-18) - Added FARP London
- Added FARP London close to Syria Border in the north.
- Added Helicopters and FARP London to DCT Theatre.

## 0.0.5 (2022-05-17) - CAP Adjustments and Briefing
- Added Briefing.
- Adjusted Frequencies of Tankers and AI AWACS.
- Changed Borders of Blue and Red to reduce the number of collisions.
- Reduced Red CAP at Aleppo Region.
- Moved Southern Interceptors to Palmyra.

## 0.0.1 (2022-05-01)

- Initial
