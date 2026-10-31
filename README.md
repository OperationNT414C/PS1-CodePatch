# PS1-CodePatch

Revival of a PlayStation CD from 1997 which allow to inject Action Replay codes

## Origin

25 years ago, I was using this burnt CD on my modded PS1 to cheat in some games. On a recent FPGA emulation context with some restrictions, I thought about dumping this CD because it would be a way to have some cheats in this context. The advantage of this CD is that, as it's very minimal, the dump takes less than 1 MB.

## AI improvements

Unfortunately, the original CD was working only on few games (for example, FF7 in PAL version): most other games were crashing on start or at the first cinematic. It was an issue I also had 25 years ago on the original hardware. So, I use an AI assistant to get some fixes and improvements for my usage context.

* **Original** folder: contains the original CD dump (without any change)
* **Fixed** folder: contains a version fixed to work on every games (only tested on Crash Bandicoot 2 PAL and Ace Combat 2 NTSC, where the original was crashing)
* **Improved** folder: contains improved versions
  * V0: All sets of codes are saved using only one slot of memory card and a loaded set of codes can be merged with already entered or loaded codes.

## Credits

* Tayan for the original executable creation on 1997 (unfortunately, I could not find any track online)
* Claude AI for reverse engineering, fixes and improvements
