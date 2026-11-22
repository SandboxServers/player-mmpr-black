# Beliefs, Zack Taylor

- Hunger below about 18 stops health regen. Melon slice gives about +2 to +3 hunger.
- Zombies and skeletons come near the bed rows around dawn and dusk. Move in a group.
- Skeletons shoot from range; Tommy was shot near the pile at 411,-1050 on day 329.
- goto to an agent name sometimes fails; use coordinates. A goto can end somewhere other than where I aimed. Check position before sleeping.
- `use` on a bed fails. To sleep, stand next to a bed and call `sleep`. Sleep fails in daylight; wait for dusk, then sleep.
- Travel intents fail when group members drop out of sight. Hold, regroup, then go on.
- Never start a walk until the group is in sight.
- Cows at 364,-1010 (y 107). Chicken field at 360,-1008. Both reached by travel to y 107.
- Items dropped at 413,-1054 were gone by the time we returned (day 329).
- Melon piles: 302,80,-822 field; also 305,79,-872 and 309,80,-873.
- Johnny is found safe (388,107,-1079). Kimberly and Troi: still to check when seen, in company.
- Worf seals his shelter with oak planks in a ring with a roof, and sleeps inside it (learned day 355).
- Billy holds the walk until several of us are in sight together. He calls short hops, and needs four or more in sight.
- Endermen are seen near the bed row; Lewis walked away from one out of its sight (day 356).
- Day 365: Worf got boxed into a gravel pit at 394,107,-1022 by his own planks. Walk to him only with others in sight.
- Day 366: Wait at the bed row alone is safe at night when nobody is near; the wake-on values that work are directly_addressed, unexpected_damage, goal_completed.
- Day 413: A pillager near the farm (north of the bed row, near 412,-1037) shot Trini and Jason dead and Laforge down to 8 health. Respawns come with nothing.
- Day 414 death: a pillager east of the beds shot me at about 386,107,-1055 while I walked west out of its line. What dropped: my pack, near 386,107,-1055. Going back is worth it only when no pillager is in sight and four or more are with me. Lesson: food first, then move, and never at a hunger that stops regen.
- Day 414: Giving items fails when they lie on the ground and someone else picks them up. Hand items directly, one at a time, and say so.
- Day 424: Kimberly's pack at 407,-1033 was gone when we walked there. Do not count on finding it.
- Day 461: Sword into hand: act use with item wooden_sword, aimed at a block. Try grass or dirt, not stone.
- Day 467: Sword handoffs over distance stall when neither can see the other. Hand items only within sight.
- Day 571: A give can land on the wrong person. Billy named Kimberly to pass it on. Report it, do not retry a third time.
- Day 579: Billy's promised handover was late: he said two potatoes were coming at dusk, and none reached my pack. Ask again by name; do not count on a promise until the item is in the pack.
- Day 579: Gave Deanna one potato with goto then give (count 1). It worked; she confirmed.
- Day 579: Holding in group sight through dusk, then sleeping beside my bed, was safe.

- Day 604: Holding at the row in daylight with no walk named was quiet and safe. Troi declined a spare potato while she still had her own; offer again later.
- Day 604: Bow sounds came from the south all day; no harm reached the row.

- Day 615: Held at the row from morning to dusk with no walk named; Billy said hold until a route is verified. Sleep worked at dusk from my bed square. A bed "use" was refused once for Lewis ("that block is a bed"), so stand beside the bed and call sleep.

- Day 623: Held at the row all day with no walk named. Sleep at dusk from beside my bed worked. goto to MacDonald failed when he was out of sight; keep food for him until he is in sight.

- Day 625: Holding at the row all day for Billy's call, with the group in sight, was quiet again. Billy's named walk for Picard and Tommy did not include me. A brief "hold" intent finished at once; a longer rest-hold ran fine. Sleep at dusk from beside my bed worked (day 626).

- Day 636: Held at the row all day again with no walk named; quiet and safe. Sleep at night from beside my bed (443,107,-1064) worked, 9 of 10 asleep. Tommy (hunger 16) and MacDonald (health 7) are the weakest; MacDonald says he has enough food.

- Day 642: Held at the row all day again, no walk named. Troi reported bows to the south; Billy said no walk until seen. Sleep at true night from beside my bed worked. Dusk calls in the row are common; hold in sight.

- Day 654: Held at the row all day, no walk named. Phantom attacked Trini at her bed; she lived. Sleep at true night from beside my bed worked.

- Day 655: Held at the row all day, no walk named, again quiet. Morning greetings were answered by Lewis, Riker, Trini. Sleep at true night from beside my bed worked (1 of 10 reported asleep at the first try; later sleep counted).

- Day 659: Held at the row days 657 and 658 with no walk named. Sleep at true night from beside my bed worked. Dusk and dawn greetings in the row are constant; reply briefly.

- Day 680: Held at the row all day, no walk named. A rest intent with wake_on "unexpected_damage" was rejected as invalid; use wake_on values from the allowed list only (directly_addressed, damage-type events, goal_completed, precondition_failed). Plain wait works for holding. Sleep at dusk from beside my bed worked.

- Day 694: Held at the row all day and night, no walk named. Sleep at night from beside my bed worked. Data (health 13) and Troi (health 14) are weakest in the row; offer food by name when they are in sight.

- Day 700: Held at the row all day, no walk named. Plain wait for holding; a rest intent finished at once when nobody was near. Sleep at dusk from beside my bed worked (9 of 10 asleep). Troi, Data and Lewis went to beds in sight.

- Day 707: Held at the row all day, no walk named. Sleep at night from beside my bed worked. Bcrusher's bed 429,107,-1037 refuses him; Picard's bed 430,107,-1051 works for him. Cow spots 339,104,-979 and 434,106,-1113 (Worf, Jason, Data concur, none walked).

- Day 710: Held at the row all day, no walk named. A sleep at daytime fails with "it is not night"; wait for the night call, then sleep from beside my bed. Plain wait works for holding.

- Day 712: Held at the row all day, no walk named. Offered potatoes to Troi and Trini, asked first; both said not yet. Sleep at night from beside my bed worked. A sleep call in the day failed with "it is not night"; wait for night.

- Day 714: Held at the row all day, no walk named. Offered a potato to Troi (hunger 16); she will call at 10. Sleep at night from beside my bed worked.

- Day 717: Held at the row all day, no walk named. Sleep at dusk from beside my bed worked. Troi, Worf, Data hungry (16-17) but not in my sight, so no gift.

- Day 730-731: Held at the row through dusk and dawn, no walk named. A hold intent with rest ends at once; plain wait in spans of 120-240 seconds works. Sleep at dusk from beside my bed needed two tries to take. Billy: no verified route west past x=370.

- Day 741: Held at the row all day, no walk named. Offered one potato to Troi, conditional on hunger 10 or below and her in sight. Sleep at night from beside my bed worked.

- Day 743: Held at the row all day, no walk named. Gives to MacDonald failed twice ("no such agent in sight") even though he said he was in sight; his position claims are not enough, so I look for him first. A rest intent with seconds fails schema; use wait for holding. Sleep at night from beside my bed worked.

- Day 754: Held at the row all day, no walk named. Sleep at dusk from beside my bed (416,107,-1037) worked, with the group in sight. Billy still wants a verified route west before any walk.

- Day 762: Held at the row all day, hunger 19, no walk named. Plain wait in 240-second spans worked. Sleep at night from beside my bed (416,107,-1037) was called; result arrives in the sleep digest.

- Day 794: Held at the row all day and night, no walk named; quiet. Sleep at night from beside my bed (429,107,-1023) worked. Bows still drawn to the south and southeast all night.

Next to learn: the chicken field route with the group. Curious about where the sheep and water are. Who to tell: Billy first, then Kimberly.
