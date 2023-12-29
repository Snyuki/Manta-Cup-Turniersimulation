# Version 6 - The Upgrade!
**We are Back!** Finally a new enhanced Version of the incredible MantaCup Turniersimulation is released. *Yaaay! Horraay!* <br>
The last Version was released on April 28th in 2022. That's astonishing 610 days ago! And we bring a huge load of new Features including some Updates as well this time. It's totally an upgrade in all sorts of ways. Or is it? It seems like ... the performance took a little hit... <br>
Well it can't be that bad, right?

#### New Features:
- Progress Bar
- Estimated Remaining Time
- Toggle Table View
- MVPs
- Tournament-Winrate
- Configs
&nbsp;

#### Updates:
- The Multi-Simulation-Log is now beautiful! Got no time? Don't you worry. You can now extract the needed information with as much as one short glimpse on the log-file and you will know what you were looking for! 
- There was actually a rather big change in how a Match is simulated. Starting with this version the winner of a Match is determined based on the Elo-Differences between lanes and not (like before) based on the average elo in the Teams. So there will be five Face-Offs in each Match and the Team that won at least three of them wins the Match. As a sidenote: This is also the main reason the time needed to simulate a tournament increased, since the main algorithm quintupled in calculation time.
- As a direct consequence of the newly implemented way of simulating a match, I adjusted the win probabilities slightly to match the new model. The formula for calculating the percentage went down from $(1.5x)^2$ to $(1.3x)^2$ with $x$ being the *elo differnce* between the laners. This might seem like a small change but now it takes at least $5.44$ eloDiff to reach maximum win-probability instead of $4.71$.
- To eradicate non-existing Bugs in this program, an error-log-file was added. But be aware: It's not a bug, it's a feature!
- For convenience, the elo of each player is now editable via a dropdown menu.
- Since it was annoying to click the save-button on each TeamPanel in order to update the tab-names and the average elo, those are now beeing updated on every simulation automatically. Handy right?
- Following the changes it is not possible to simulate without having all Teamnames set to a custom value. It is very well possible though, to give two teams the same name if you so desire.
&nbsp;

#### Bugfixes:
- Maybe you didn't notice but actually the title of the last three version held the wrong version number (v2). This is now fixed and you can admire a lovely "v6" in the name of the program!
- Equally to the update of the TeamPanels on a simulation, the teamnames and average elo will now be properly displayed on startup without the need to manually save each tab.
- After a multi-simulation, the table view of the winners wasn't properly scrolled to the bottom at the end of a task. This is now fixed as well.
&nbsp;

#### Progress Bar
Imagine yourself sitting in front of a running multi-simulation and waiting for the rows to run through, always roughly estimating how far in the simulation you already are. Tiring isn't it? This problem is now solved! Behold the mighty Progress Bar! It indicates how far you still have to go! And you don't have to do the nasty calculations based on the current iteration! To ease your experience even further I got the next Feature for you!
&nbsp;

#### Estimated Remaining Time
May I humbly present \**dom dom dom\** a timer! ... What can a timer possibly do good in the shadows of a progress bar you might ask. But think about it! It shows you the estimated time that is remaining to the ongoing multi-simulation without doing any calculations at all! Even though it lacks in the aspect of the "progress made since start"-matter, combined with the progress bar this forms an invincible duo to bring your experience to new heights! <br>
Note that that the timer is by no means perfectly accurate. It's still an estimation and will need some time to calculate the correct remaining time.
&nbsp;

#### Toggle Table View
This feature involves the possibility to disable and enable the table view in the ongoing multi-simulation window. *"Why would I ever do this?"* one might ask himself while reading this. Well that's a good question! The answer is simple. To regain at least some of the lost performance of course! Because of the change in the way a Match is simulated, one iteration of a Tournament now takes about five times as long. To compromise this I had to save calculations in some places and this was one of them. Though it's the only one you still can turn back. So feel free to stare at the flooding rows of winners in amazement but be aware that the program could run faster if you didn't. What a dilemma...
&nbsp;

#### MVPs
Finally, he is here! The Most Valuable Player of the Tournament! And you can watch him live in 3D! Well mostly in 2D and only his name but hey, you still get to know who it is! In the event of a multi-simulation, you even get a neat view on how many of these amazing titles each participating player got! There is even a percentage number waiting for you to save you valuable time that could be spent on the Rift.
&nbsp;

#### Tournament-Winrate
This feature is long overdue and intends not only to save you time but also your sanity, when it's again long past midnight and you keep staring at the resulting numbers of a multi-simulation, thinking *"How high is the winrate of this Team?"*. Guess what: I'm doing this for you now. So don't waste your time on calculations a program could be doing for you! Not that you would a calculator would you?
&nbsp;

#### Configs
Ever wanted to set some configurations for the program without even opening it? No? I don’t care so I implemented this feature anyway! Even through it boasts only one setting so far there will surely be more in the future. What the one existing setting does you ask? It sets the initial visibility state of the table view in a multi-simulation of course!
&nbsp;

#### Wrapup:
To wrap things up you could say this release is one of the biggest ones so far. I wouldn't have done a new release if there wasn't another MantaCup though, so let's hope there will be a fifth one in the future. Even though the *BlackManta* Team disbanded, they pulled themselves together to have one hopefully not last stand. With these words, I will end this edition of the Tournamentsimulation-Changelog. I hope you find joy in using this tool. Feel free to message me if you encounter any problems! <br>
<br>
Snyuki aka. BLM Reaper

