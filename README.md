## Esposc Disclaimer
Forked from Uni's genBTC AutoTrimp's script. I have only made a few modifications to suite my endgame runs.

## 1.1
## Custom Map Options
- Speed Explorers, control how often to dive into maps to upgrade Explorers
- Map Modifer select list (TESTING)
- Jump extra map levels to grab Prestiges when using Poison (TESTING)

## 1.0.1
## AutoStance2
- Removing the worries about enemy crit causing stance changes. Crit enemies should be calculated into the block/health automagically
- Stay in Dominance stance until your remaining heatlh w/ block and peirce will kill your squad
- New Squad being ready is based on the global bread time. Dominance should always be set if total breed time is above the Geneticist timer

## Anticipation
- Changed areas where Anticipation calucation was set for 30s. Booleans allow up 45 if the mastery is purchased.
- ForceAbandon in VoidMaps should work if Anticipation stacks are less than maximum

## Breed Time
- Now follows the calculations detailed by Trimps itself
- Geneticists should be purchased/fired to keep the timer at the set breed timer value
- Hopefully fixed the bug causing all Geneticists to be fired when breeding has reached 0

# AutoTrimps-genBTC unimod
> Due to a myriad of reasons, I am finding it difficult to keep this project on my plate. Thus, it is unfortunately my decision that I have to put this project on hold. While I would still be around to tackle things that I can fix in under a minute, like writing a short script to pause the script at zone X for you, I don't have the time to add features as I would had liked. It seems that there is a new fork maintained: https://github.com/coderpatsy/AutoTrimps While I have not used it to vow for its reliability, there is that option.

Donate: <a href="https://paypal.me/unihedron">paypal.me/unihedron</a>

Based on AutoTrimp-genBTC. Modified by Uni. <b>Not backwards compatible with AutoTrimps-genBTC due to optimized save format! Please beware and backup your AT configs!</b> Also, not guarranteed the work. The reason why I'm building a fork instead of submitting PRs is that I have no idea how it really works and need a way to crash test. Also I don't want to hold other maintainers from having to deal with the technical debt I cause. If any horrible code I wrote gets in your way, sorry!

[![](https://cloud.githubusercontent.com/assets/5595067/24738958/d421a900-1acb-11e7-81af-d2402801fc71.png)](https://discord.gg/Vu4J4zc)
<del>I'm usually on zininzinin's AT chat. If I'm not online there or if you just want to yell at me about the script without any interference just PM me.</del>

## Current Roadmap
- Implement stuff that I want to see which isn't already in genBTC
- Implement changes that others have requested and I feel are doable
- Fix problems that were around in AT but wasn't resolved

## Script Installation
**Please backup your game via export before and during use to prevent losing your save due to corruption!**

**Please also backup your AT config, it will be converted into simplified format which is a NO RETURN PROCESS!**

https://github.com/unihedro/AutoTrimps/raw/gh-pages/.user.js

```js
javascript:with(document)(head.appendChild(createElement('script')).src='https://unihedro.github.io/AutoTrimps/AutoTrimps2.js')._
```

## Screenshots

![image](https://cloud.githubusercontent.com/assets/5595067/24824209/ec9923a4-1c39-11e7-95de-eab40cacd597.png)

![image](https://cloud.githubusercontent.com/assets/5595067/24824212/fea2c28a-1c39-11e7-933a-d2475a47ebcd.png)

Notes: https://github.com/genbtc/AutoTrimps/blob/gh-pages/README.md

I don't track detailed change logs, sorry. You can get that information by reading the commits or update notice in each version.
