# Tiny Garage Tycoon: Free Demo

You start with a backyard garage and $200. Cars roll up with brake trouble, wiring faults and flat tires, and you fix them yourself in quick mini-games. Earn enough and you can buy better tools, hire help and build more bays. Let the queue pile up, or spend more than you earn, and the bank shuts you down.

This is the free demo: the first two of the game's fifteen garage levels. It runs in your browser. No install, no account, and it keeps working offline once the page has loaded.

**Play it:** use this repository's GitHub Pages link (it's under *About*, on the right), or download the files and open `index.html` in a modern browser. No server needed.

**Want the rest?** The full game has 13 more levels, a fuel station, EV charging and a lot more to build. You'll find it on [itch.io](https://alphazolozyro.itch.io/tiny-garage-tycoon) and on PromptBase, both under the name alphazolozyro.

## How a day in the garage goes

Customers pull up in the street and lose patience after about 45 seconds. Tap a car (or use the **Queue** tab) to send it to a free bay, then press **Repair** to play the mini-game for that job. The space bar works too.

- **Brake job (timing):** stop the moving marker inside the green zone. You need three clean bolts.
- **Wiring fault (memory):** watch a four-step fault code, then tap it back. Three wrong pads and the job fails.
- **Flat tire (pumping):** tap to pump, then hold the pressure in the green zone for about three seconds. Pump too far and the tire bursts.

How well you do sets what you get paid: the job price times (0.6 + 0.5 x your score). Score under 30% and the job fails, so you earn nothing and satisfaction drops by 6. A customer who gives up and leaves costs you 8 satisfaction, and a full queue costs 3. Satisfaction (0 to 100) also controls how fast new customers turn up, so it's worth looking after.

Rent and wages come due every 60 seconds, which is one game day. If your money falls below -$150, the shop is closed.

## What's in the demo

- Garage levels 1 and 2. Hatchbacks and sedans only, with **Major** jobs (1.7x pay) unlocking at level 2.
- Up to 2 bays, 2 employees and tools up to level 2.
- A receptionist who sends waiting cars to free bays for you, and a rush hour every day.
- 6 of the game's 16 achievements.
- A **Garage Pass**: a text code (Goals tab) that backs up your garage. You can load it into the full game and carry on where you left off.

The demo ends the moment you'd reach level 3. You'll get a summary screen, and you can keep playing and earning, but experience stops there.

## What the full game adds

15 garage levels, 7 vehicle types (from hatchbacks to supercars that pay 2.2x but won't wait around), Major, Premium and Elite jobs, up to 4 bays and 6 workers, tools up to level 9, a training center, a fuel station and EV charging with their own mini-games, all 16 achievements, and a Garage Legend finale at level 15.

## See it in action

A few videos of the game are up on YouTube:

1. https://youtu.be/psKRFI1c5mQ
2. https://youtu.be/a_62hobCmgA
3. https://youtu.be/MbXpi9RAJk4
4. https://youtu.be/Qnf5_9C1Tlk
5. https://youtu.be/cb312mKJ2iA
6. https://youtu.be/7EI01QGmYiU
7. https://youtu.be/674mxZSw980

## Controls

Tap or click cars, bays and buttons. **Space** triggers the active mini-game, **P** pauses, and **Esc** closes a dialog. The bar along the bottom has Pause, Sound, Save, Load, Help and Restart (Restart asks before it wipes anything). Sound cycles through effects and music, effects only, and muted, and there's a volume slider at the top. On a phone, the mini-game opens as a sheet at the bottom so you can still see the garage.

## Good to know

- Progress autosaves at the end of each game day, and you can save by hand. Saves live in your browser's local storage, so clearing site data erases them. The Garage Pass code is your backup. The demo's save is kept separate from the full game's.
- It was built and tested in Chromium browsers (Chrome, Edge and friends). Other browsers should work, but they haven't been tested.
- Sound is generated in the browser, with no audio files, and starts after your first tap or click because browsers insist on that.
- A repair you're halfway through isn't saved. If you reload, that car goes back to its bay as "waiting".
- The game pauses by itself when you switch tabs.

## Feedback

Found a bug or have an idea? Open an issue here or leave a comment on the game's itch.io page.

## Copyright

Tiny Garage Tycoon v1.0.0 (demo) is copyright (c) 2026 alphazolo. All rights reserved. You're welcome to play this demo and to share a link to it. You may not copy, redistribute, resell or modify the game or any part of it, or present it as your own work, without written permission from the author.
