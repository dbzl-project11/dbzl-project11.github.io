---
layout: default
title: Ki Charging
nav_order: 2
parent: Useful Info
---

## Notes on charging

I noticed a few weeks ago that there were some questions about charging that kept coming up in chat, especially for Androids. So I decided to pull out some notes I had made on charging and polish them up a bit in order to share them with everyone else. I hope you find them useful.

Charge potaras: <br>
- Unleash latent power 1, 2, 3 – increases the base ki bar level by 2, 3, or 4 bars respectively, also decreases ki charge rate (ULP 1 is a ki -1, ULP 2 is a ki -2, etc).
- (Blue potaras) Ki + 1, Ki + 2 – increases charge rate by 20 and 40% respectively. These affect both active and passive charging.

- Launch's Support – equivalent to ki +1
- Fighting Spirit – Ki +.5 per health bar lost
- (passive charge potaras) Hatred of Saiyans, Tension Up, High Tension – passive charge 1 bar of ki every:

    - Hatred of Saiyans – 60 seconds
    - Tension up – 40 seconds
    - High Tension – 20 seconds 

Notes on when to use the different potaras (note that for reasons, I use 20 second intervals for all charge rate calculations):

- ULP – think very carefully about this, as the ki minuses are hard to workaround after the first level. Tension Up/High Tension are probably going to be better, as they don't have the same minuses. But it will depend on how much you're willing to spend on charge potaras.

Note the math on what ULP 1 will be if you decide to use it (with no other charge potaras) for the passive portion of charging, and that charge rate is 1 bar/10 seconds:

    .8 bar/10 seconds * 20 seconds = 1.6 bars/20 seconds (compared to 2 bars without the ki -1). 

And if you passively charge 1 bar every 7 seconds:

    .8 bar/ 7 seconds * 20 seconds = ~2.4 bars (compared to just under 3 bars) 

Generically, the formula would look something like this:
    
    ((blue potara modifier /(base charge time per bar of ki)) * time to charge in seconds)  + (additional ki from HT or TU/time to charge 1 bar from that potara)
    
Where your modifiers from league legal blue potaras are
    * Super +2/Ki -1 = .8
    * Ki +1 (or Launch's Support) = 1.2
    * Ki +2/Super -1 = 1.4
    * while not a blue potara, Fighting Spirit's bonus would be added here, and it's an additional .1 per bar of ki missing.
        * so if you have one bar of health missing and just FS, the modifier is 1.1; if Ki +1 and FS, it would be 1.3, etc.

To make this calculation easier, it's recommended you calculate charging in increments of 20, 40, or 60 seconds, as that matches up with the additional charge from the passive charge potaras.

But note that some characters could charge up to all 5 bars with ULP 1, which means that they will essentially be an android. If that character doesn't like to charge, and can passively charge up to 4 bars already, it may be worth using ULP 1 and Ki +1 or Ki +2 to increase charge rate. (Especially considering that the Ki+1/+2 will negate the charge negative, allowing active charging to go unaffected.)

- Blue potaras/Launch's Support– core part of a build
- Fighting Spirit – use when you think it'll do better for you than Hatred of Saiyans, or if already equipping a passive charge potara.

Passive Charge Potaras: so this is where it gets a bit complicated, as all androids charge to full power on their own by default, so passive charge potaras can be considered much like the regular charge potaras. (For simplicity's sake, I'm only dealing with Android characters below)

So here's the math behind the passive charge potaras:
On average, a match lasts about 10 minutes, and if you make the assumption that each player has an equal amount of time on the field (2.5 minutes) this equates to:

    2.5 bars of ki for Hatred of Saiyans
    3. 75 bars of ki for Tension up
    7.5 bars of ki for High Tension 

So the question becomes when to use these potaras instead of the blue potaras (or in conjunction with them):
The first step is to determine what trade offs you're willing to accept with your character. Spending 4-5 points for charge potaras may not be worth it for a melee character, but may be perfectly acceptable for a B2 character (especially one using Super +2).
Then you need to do a little bit of math on your character by finding out what their base charge rate it. Let's use 17 as an example. His base charge rate is ~6.3 seconds to passively charge one bar of ki. So if I'm considering giving him charge potaras, I've got to consider 2 main scenarios, one with a blue potara, and one using passive charge potaras.

With Ki +1

    1.2 bars/6.3 seconds * 20 seconds = 3.87 bars every 20 seconds 

With Tension Up

    1 bar/6.3 seconds * 20 seconds + .5 bar ki (per 20 seconds) = ~3.67 bars/20 seconds 

With High Tension:

    1 bar/6.3 seconds * 20 seconds + 1 bar of ki = ~4.17 bars/20 seconds. 


To sum it up, if your character has a base charge rate slower than 1 bar/8 seconds for passive charging, you're better off with Tension Up to improve passive charging. If faster, then use one of the blue potaras. High Tension will usually be better than Ki +1, but not Ki +2 for passive charging.

For non-Android characters, the math is a little different, as the characters don't passively charge up to full power (a lot of characters only passively charge 2-3 bars, and then have to use active charging). In those cases, passive charge potaras may not be quite as useful unless the character doesn't like to charge or you're already using a blue potara and still want to charge more.
