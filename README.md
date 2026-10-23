# DMC1 PS2 Infinite Yellow Orbs Patch

The original Devil May Cry for PS2 is a fun game with a fairly old-fashioned lives system that kind of requires you to ration your lives out over the course of the game so that you can retry bosses without having to replay the entire mission leading up to it.

Although I strongly recommend playing the game as it was originally designed for first-time players, I found the system frustrating and wished I could disable it for repeat playthroughs, so I created this patch.

While not providing literal 'infinite' Yellow Orbs per se, this patch makes it so that Yellow Orbs are not consumed when retrying, making them functionally infinite so long as you have at least 1 Orb (you start the game with 4).

## Instructions

Download the patch file matching your regional copy of the game (most players will be using USA since it runs at the correct game speed, but Europe is provided for completeness).

Then apply the patch to your `.iso` copy using your preferred xdelta tool - GUI users will likely prefer [Delta Patcher](https://github.com/marco-calautti/DeltaPatcher) but if you're comfortable with the command line you may use the sample command below.

```
xdelta3 -d -s "Devil May Cry (USA).iso" "Devil May Cry (USA) Infinite Yellow Orbs Patch.xdelta" "Devil May Cry (USA) Patched.iso"
```
