# Main Plot Plus
A plugin for the video game "endless sky" improving the main plot.

## Guided Start
This is an optional feature that can be enabled or disabled upon creating a new save or loading an existing one with this plugin installed for the first time. If you haven't chosen sides in the human civil war by 3017, Guided Start will allow you to join the Free Worlds, and also the Syndicate if you have the Crisis in Management plugin installed. It will additionally allow you to remain neutral (see below). Any conditions blocking the campaigns from starting will be cleared. If you then enter the spaceport a map indicator will lead you to the planet to get started and remind you to enter the spaceport if necessary.

## Neutrality
You can choose to remain neutral in the human civil war. To do this, wait until 3023 without choosing sides, then when aksed what side you are on, say that you are neutral. When pressed, continue to remain neutral. Shortly after, land on any world one jump away from a Pug planet and tell the Pug that you are neutral, and you will be able to skip the main plot. However, there's a catch: a different pilot will do the free worlds campaign instead, and they will choose checkmate. If you want the reconciliation ending, join the Syndicate with the Crisis in Management plugin or join the Free Worlds and choose reconciliation. The missions are designed so that you will be relocated to Ruin and time will advance by several years, but this is waiting on several pull requests to be merged, so at the moment you will have to use your imagination. Work is still in progress on correcting assumptions about what you know or did made by other missions in the base game. Most of this will likely result in a conversation similarly to the one you already have, but some, such as Hai Reveal, may involve replacement missions instead. Pull requests are welcome fixing these. At the moment, hai reveal and the end of one mission chain for the Coalition is blocked as a result.

## Syndicate Mark II
If the Syndicate is willing to sell you their outfits they developed during the Free Worlds campaign, they will now also use them on their ships. First, only a few of their ships will be upgraded, but over time, more will be the new Mark II variants, which are used in vanilla for a few missions in the reconciliation branch. Note that if you do choose reconciliation, the Syndicate do not sell you their "advanced" outfits, so they will not appear in their fleet once you finish the main plot.

## Bugs
I have playtested this plugin and fixed any bugs, edge cases, and warnings I could find. There may still be bugs, but if there are, I couldn't find them. Bug reports and pull requests fixing bugs are welcome.

## Other Plugins
There is a plugin called "Constellations" that modifies the Pug wormhole to point to Queri instead of Over the Rainbow. As remaining neutral will eventually send you to Ruin once the relavent PR is merged, this change would softlock the game. As a result, remaining neutral will cause the wormhole to point to Over the Rainbow as is the case in vanilla. I could have made it kick you out of the Pug galaxy permanently once you leave, but this seems like it would create more problems than it would solve, at least to me. If you don't like the decision I made, this plugin is open source. Just modify it.

## Copyright
This plugin was initially dedicated to the public domain, however, I have taken and modified text from missions in the base game, which is technically code, so it is now licensed under the GPL v3 or later to ensure that I do not violate the endless sky license terms. See the "copyright" file for more details.

## Note on Breaking Changes
Due to the pending PRs and mission compatibility, I do not consider this plugin "ready for release." As a result, I have not made any releases. You are free to clone this repo to your "plugins" folder if you wish to try it out. However, as I have not made releases, I may make breaking changes, including, but not limited to, renaming the plugin, renaming files, removing files, reorganizing files, splitting files, merging files, and modifying data files without providing patch missions or other backwards compatibility features. Treat this like you would the "continuous" branch of endless sky and do not be surprised if you end up with broken saves. Remember, there is no warranty.
