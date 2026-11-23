# Beliefs, Zack Taylor

## Methods that worked
- Hold at the row in group sight until Billy names a walk. Plain wait in 120-240 second spans works for holding.
- Walk only with the group in sight, in daylight, and only on Billy's named call. Short hops with four or more in sight.
- Hand items directly, one at a time, and only to someone in my sight who says their name. Report a failed give; do not retry a third time.
- Sleep: stand beside a bed and call sleep, at true night. Beds that worked: 416,107,-1037 (day 754, 762), 429,107,-1023 (day 794, 796), 443,107,-1064 (day 636), 429,107,-1051 (day 809), 430,107,-1051 for Picard (day 707).
- Wake-on values accepted: directly_addressed, unexpected_damage, goal_completed, precondition_failed. Others were rejected.
- To hold a sword in hand: act use with item wooden_sword, aimed at grass or dirt (day 461).

## Things that did not work, and why
- Sleep at daytime fails ("it is not night"). Wait for dusk.
- `use` on a bed is sometimes refused ("that block is a bed"). Stand beside it and call sleep instead.
- Both white beds 415,107,-1050 and 415,107,-1051 refused me ("the way was blocked") on days 853-855. Do not retry until Billy names a bed.
- Bed 413,107,-1042 was blocked (day 833). Bed 430,107,-1050 blocked once; the result of a later try is unknown.
- Bed 429,107,-1037 refuses Bcrusher/Wesley. Picard's bed 430,107,-1051 works for Picard.
- goto to an agent name sometimes fails, and a goto can end somewhere other than I aimed. Use coordinates, and check position before sleeping.
- Giving fails when the target is out of sight, or when the item lies on the ground and someone else picks it up.
- Gives to MacDonald failed twice when he was out of sight, though he said he was in sight. Position claims are not enough.
- Billy's promised handovers are sometimes late. Ask by name; count nothing as received until it is in the pack.
- Sword handoffs over distance stall when neither can see the other. Hand within sight only.
- A give can land on the wrong person (day 571). Report it and do not retry a third time.

## Dangers and places
- Pillagers and skeletons: come near the bed rows around dawn and dusk and from the south and south-west. Shot Trini, Jason and Laforge on day 413; killed me on day 414 at about 386,107,-1055 while I walked west out of its line. Move in a group.
- Skeletons shoot from range; Tommy was shot near 411,-1050 (day 329).
- Endermen are seen near the bed row.
- Items dropped at 413,-1054 were gone when we returned (day 329). Kimberly's pack at 407,-1033 was gone (day 424). Do not count on finding dropped items.
- Worf got boxed into the gravel pit at 394,107,-1022 by his own planks (day 365). Walk to him only with others in sight.
- Worf seals his shelter with oak planks in a ring with a roof (day 355).
- Hunger: health stayed at 20 at hunger 18 and 19 (day 853). So the claim that hunger below 18 stops regen is not proven. Billy's rule: eat at hunger 10 or below.

## Food
- Cows: 364,-1010 and 339,104,-979, 434,106,-1113 (not walked yet). Chicken field 360,-1008. Both reached by travel to y 107.
- Melon piles: 302,80,-822 field; 305,79,-872 and 309,80,-873. Each melon slice gives about +2 to +3 hunger.
- Potatoes at 463,107,-1073 are unverified.
- Water and sheep: location unknown.

## Struck out (proved false or unverified)
- ~~Hunger below about 18 stops health regen~~ (not seen; see above).
- ~~Sleep at night from beside my bed always worked~~ (false at 415,107,-1050 and -1051 on days 853-855).
- ~~Wait at the bed row alone is safe at night~~ (only when nobody is near).
- ~~The 3 feathers are held~~ (pack empty; no feathers held now).
- ~~Johnny at 388,107,-1079 is still to check~~ (Johnny found safe there, but not seen since).

## Unverified
- A route west past x=370 (Billy: no verified route yet).
- Whether pillagers are gone.
