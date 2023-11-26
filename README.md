# Main Plot Plus
A plugin for the video game "endless sky" mostly centered around improving the main plot.

## Guided Start
This is an optional feature that can be enabled or disabled upon creating a new save or loading an existing one with this plugin installed for the first time. If you haven't chosen sides in the human civil war by 3017, Guided Start will allow you to join the Free Worlds, and also the Syndicate if you have the Crisis in Management plugin installed. It will additionally allow you to remain neutral (see below). Any conditions blocking the campaigns from starting will be cleared. If you depart and land or reload your save, then enter the spaceport a map indicator will lead you to the planet to get started and remind you to enter the spaceport if necessary. This is necessary because the game only checks `to offer` conditions when landing or loading a save.

## Neutrality
You can choose to remain neutral in the human civil war. To do this, wait until 3023 without choosing sides, then when aksed what side you are on, say that you are neutral. When pressed, continue to remain neutral. Shortly after, land on any world one jump away from a Pug planet and tell the Pug that you are neutral, and you will be able to skip the main plot. However, there's a catch: a different pilot will do the free worlds campaign instead, and they will choose checkmate. If you want the reconciliation ending, join the Syndicate with the Crisis in Management plugin or join the Free Worlds and choose reconciliation. The missions are designed so that you will be relocated to Ruin and time will advance by several years, but this is waiting on several pull requests to be merged, so at the moment you will have to use your imagination.

### Compatibility
Work is still in progress on correcting assumptions about what you know or did made by other missions in the base game. You are told about the Pug war, the Free Worlds having nuclear weapons, and some of the new outfits produced by humanity: the plasma turret, flamethrower, s-970 regenerator, s-270 regenerator, ionic afterburner, typhoon torpedo launcher, electron beam, and catalytic ramscoop. This isn't everything, as it excludes the stack core due to it not being sold by Kraz Cybernetics, but it is enough to cover everything in the Coalition intros. You also learn about the Oathkeepers upon landing on Farpoint, but you don't meet Danforth yet. That is coming soon to fix the Wanderers campaign. I have additionally patched a mission that assumes you know Alondo. This works for both Neutrality and Crisis in Management.

## Road to Hai Reveal
Hai Reveal is still in a work in progress state. Additionally, it at the moment requires you to specifically join the Free Worlds, or none of the missions after the leak will offer. As a result, I have completely blocked Hai Reveal if you did Crisis in Management or the Neutrality option. However, I am planning on working on a series of missions called "Road to Hai Reveal" that will allow you to do the intro of Hai Reveal if you have done Neutrality or Crisis in Management, however, know that you aren't missing much, as nothing past the intro of Hai Reveal is complete. I have patched all of the post war reactions, see below.

### Post War Reactions
The post war reactions by default all assume you have directly fought with the Pug, which isn't necesarily true in Crisis in Management and definitely isn't true in the Neutrality option. I have replaced all three of these with patch missions which vary depending on how you interacted with the Pug, based on this plugin, the vanilla Free Worlds Reconciliation branch, and Crisis in Management. It also tries to test if you have done the vanilla version of Free Worlds Checkmate instead, if needed. I also removed a stupid section about the Free Worlds and Navy captains joking about almost killing each other. Other than that, doing Free Worlds should result in the same post war reactions as vanilla, but doing Crisis in Management or the Neutrality option will give you different outcomes that make sense for what you've done.

## Syndicate
The Syndicate now use their new technology on their ships if you complete the main plot, though they still won't sell it to you if you did reconciliation. The weights of the variants are based on the ones for the republic Mark II ships. A few of the Mark II variants are used in vanilla for a few missions in the reconciliation branch, but I added a bunch more so that all of the Syndicate ships used in their main fleets have Mark II variants. The Syndicate rarely uses nuclear missiles before the war in the eastern parts of the Core where they get raided by the Korath. They stop in 3014 because of the impending war.

### Test Dummies
Do you know those test dummy missions that you have to do? Well, there's a reason for them. Amazinite's Checkmate improvements include "automatic" ships. I have added these ships to occasionally show up in the Syndicate fleets after the main plot. They are essentially the same as the normal "mark II" ships, except that they have a special government that can change hails to use the test dummy ones, they cannot be bribed, they have the same confusion as the target practice jobs, they have the "automaton" and "self destruct" attributes from the jobs, they are always called "Syndicate Test Vessel," and, being expensive, try to avoid battle and run away if threatened. Speaking of the test dummies, you can no longer fight them after the main plot, as the Syndicate has moved to the next phase of their testing and has started to incorporate them in their fleet.

## Improved Checkmate
Amazinite had, a long time ago, added changes that improved the Checkmate branch, that ultimately didn't go anywhere, other than some changes in the first part of the campaign rework. These changes will likely be added as part of the next parts of the campaign rework. However, as I am a fan of the Checkmate branch already, I think more people should be doing it, so I am incorporating these changes now, along with some minor fixes. Mostly, these allow you to ask about progress made by the Syndicate in finding the terrorists, and eventually allow you to "fight" them with automatic ships after the Pug invasion. I am also changing one major thing: the nuke launcher has been replaced with "augmented nuclear missiles," which are essentially the buffed nuclear missiles proposed by Azure3141. When these begin being sold, the Syndicate also begin using them instead of regular nukes in a new "Mark II Nuclear" loadout in the systems raided by the Korath. This Manta loadout has four augmented nuclear missiles and two sidewinder missile launchers, the latter of which ensures that the Mantas use the "missile boat" AI, making them less likely to blow themselves up.

## Fixed Scanning
Everything in the game has 100 times better scan efficiency. This essentially means scanning is ten times faster than it was before, however, due to the maximum scan time of ten seconds, this really means that ships can actually have noticable changes in scan times with more scanners. It is still a "minigame" of trying to stay near the ship, and there is still a noticable difference between ships with a lot of cargo and not much cargo, and the same for outfits. Scan power is untouched. This helps when you need to do that mission to scan a cruiser: you can now do so without it always taking ten seconds. It also makes missions like "corporate espionage" possible.

## Landing Fees and Tax
I have improved and implemented the "Landing Fees and Tax" plugin by Rafael Ramawadh. A few months after the bombing of Geminus and Martini, you will have to start paying a daily tax of 10,000 credits along with landing fees on all inhabited Republic, Syndicate, Free Worlds, and Neutral planets, along with the planet Humanika. The landing fees range from 1,000 credits on dirt belt planets to 9,000 credits in the Sol and Alpha Centauri systems . You will also have to pay 15,000 credits to land on Kor Efreti planets at any time, and 10,000 credits to land on Hai and Unfettered Hai planets once the existance of the Hai gets leaked. This will only block "minor" missions from offering when you first have to pay a landing fee for a given planet, or on Pirate worlds that have been temporarily occupied.

## Han Sizer Month
On PR 7805 by Zitchas, I mistakenly thought on stopover appeared on every stopover. There was going to be a popup that appeared on the last stopover of a Han Sizer month job, but it was removed as it was thought to be annoying. I have readded it to the longest, rarest mission, so that you at least get something after having visited four planets. In vanilla, you would visit four planets, get absolutely nothing, then finally get a reward when landing on the destination. It's not truly part of the main plot, of course, but I felt like this should be added, as I was the one who messed up my review.

## Bugs
I have playtested this plugin and fixed any bugs, edge cases, and warnings I could find. There may still be bugs, especailly with content added since then, but if there are, I couldn't find them. Bug reports and pull requests fixing bugs are welcome.

## Other Plugins
There is a plugin called "Constellations" that modifies the Pug wormhole to point to Queri instead of Over the Rainbow. As remaining neutral will eventually send you to Ruin once the relavent PR is merged, this change would softlock the game. As a result, remaining neutral will cause the wormhole to point to Over the Rainbow as is the case in vanilla. I could have made it kick you out of the Pug galaxy permanently once you leave, but this seems like it would create more problems than it would solve, at least to me. If you don't like the decision I made, this plugin is open source. Just modify it.

## Copyright
This plugin was initially dedicated to the public domain, however, I have taken and modified text from missions in the base game, which is technically code, so it is now licensed under the GPL v3 or later to ensure that I do not violate the endless sky license terms. See the "copyright" file for more details.

## Note on Breaking Changes
Due to the pending PRs and mission compatibility, I do not consider this plugin "ready for release." As a result, I have not made any releases. You are free to clone this repo to your "plugins" folder if you wish to try it out. However, as I have not made releases, I may make breaking changes, including, but not limited to, renaming the plugin, renaming files, removing files, reorganizing files, splitting files, merging files, and modifying data files without providing patch missions or other backwards compatibility features. Treat this like you would the "continuous" branch of endless sky and do not be surprised if you end up with broken saves. Remember, there is no warranty.
