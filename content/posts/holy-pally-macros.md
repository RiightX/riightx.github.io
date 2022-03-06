---
title: "Some helpful Holy Paladin macros"
date: 2022-03-06T04:10:07-06:00
draft: false
toc: true
wowhead: "yes"
images:
tags:
  - wow
  - paladin
  - holy paladin
  - macro
---

## Judgment target's target

```
#showtooltip judgment
/assist [@mouseover]
/use judgment
/targetlasttarget
```

This macro will cast <a href="http://www.wowhead.com/spell=20271" data-wowhead="spell=20271">Judgment</a> on your friendly target you have moused over. This is helpful for things like hitting your tank's target with <a href="http://www.wowhead.com/spell=183778" data-wowhead="spell=183778">Judgment of Light</a> if you are talented into it.

## Hit closest enemy with Crusader Strike

```
#showtooltip crusader strike
/cast [harm] crusader strike
/stopmacro [harm]
/targetenemy
/cast crusader strike
/targetlasttarget
```

This macro will target the nearest enemy and hit it with <a href="http://www.wowhead.com/spell=132331" data-wowhead="spell=132331">Crusader Strike</a>, and then target your last target. It seems to be a bit touchy if it re-targets the last target, especially if it's a target that's died while hitting the macro.