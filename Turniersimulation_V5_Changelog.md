# Version 5 - Cleanup!
Not long ago Version 4 released and there were some minor problems which led to a bad user experience. But fear not! These Problems are fixed in this Version of the Tournamentsimulation! And there is more to come...

#### New Features:
- Detailed Log
- Tiebreaker
&nbsp;

#### Updates:
- When a Multi-Simulation is cancelled the already simulated Tournaments will be written in the Log. Now you have absolutely no excuse anymore if somebody challenges you to a 1v1 in the Rift!
- You might not have noticed, but there was actually a Limit on how many Tournaments could be simulated at once (it was 2.147.483.657 Tournaments). I maxed out this Limit to astonishing 9.223.372.036.854.775.807 Tournaments! (If you can manage to simulate this amount of Tournaments at once, send me a proof and I will increase this Limit even further -.-)
&nbsp;

#### Bugfixes:
- Fixed the Problem that the CPU usage was permanently increasing with the time the program was running. This led sooner or later to the crash of the program due to too low CPU capacity. If you are asking yourself now whether you can Multi-Simulate more Tournaments than you could in Version 4 then you are absolutely correct. Try the largest number you want without worrying about killing your CPU!
&nbsp;

#### Detailed Log:
You asked for it, you get it! The placings of the top 8 Teams in the Multi-Simulation are now saved to the log in the Categories: 1st, 2nd, 3rd, 4th, Quarterfinal-Participations. Simulate as many Tournaments as you want and analyze the results later!
&nbsp;

#### Tiebreaker:
To be honest the simulation of the Brackets wasn't perfect up to Version 4 since the Placements were mostly random if two teams reached the same amount of wins during this stage. This led to the problem that the 4th and the 5th place of the groups were sometimes not correct which could have resulted in non-accurate Winners of the Tournament in special cases. This has now been solved by matching the 4th and the 5th place in a Tiebreaker Match (Bo3) if this Situation occurs.