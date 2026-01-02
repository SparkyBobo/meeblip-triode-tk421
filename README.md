# That Time I Promised My Friend a Synth… and Finally Delivered (40 Years Later!)



Let’s rewind to the 1980s—big hair, neon everything, and me, a seventh grader with a wild electronics obsession. Enter my buddy “F” (not his real name, but let’s roll with it—think F Murray Abraham from Amadeus,

because inside jokes are forever). F was the piano prodigy, I was the kid who thought soldering irons were cool, and together we were the ultimate middle school odd couple.



One day, I had a brilliant idea: “Hey F, why don’t you give me a few hundred bucks so I can build you a Moog-style synthesizer from a magazine article?” Because that’s how open-source worked back then—no GitHub, just guts and glue.

F, being the wise soul, realized this was probably a recipe for disaster (and possibly a fire hazard). Instead, F asked for a Roland synth for Christmas. Smart move, right? That was the moment F’s musical journey truly began.

He’s now a fantastic musician, and we rocked out in our high school band, the *Residudes*. F swears my synth hype is what nudged him from classical piano to modern music, so I’ll take partial credit for his rockstar status.



Fast forward: F and I still swap music nerd tidbits. He’s even inspired me to learn music (shoutout to my 70+ day Duolingo streak!). But here’s the kicker—I never actually built that synth. Oops. So, I decided it was time to

make good on my decades-old promise. After some deep dives into my parts bin and the wilds of the internet, I found the perfect open-source project: the [MeeBlip Triode](https://meeblip.com/products/meeblip-triode-synthesizer). It’s affordable, it’s awesome, and it’s my way of finally delivering on that synth promise from the Reagan era.



So here’s to friendship, music, and never letting a 40-year-old promise die. Sometimes, the best things really are worth the wait.

## Build Notes: AKA “How I Frankensteined This Synth Together”

* Parts Bin Olympics: My main goal was to spend as little money as possible on parts, not to be cheap, just to makes this a thing I threw together as much as possible.
* Analog Chip Hunt: Turns out, my stash didn’t have the right analog chips. Had to buy those. Same story for eight matching 10k potentiometers—those got ordered, but I did have a vintage audio taper 10k for volume just chilling in the bin.
* Processor Swap: The original build called for a different processor, but I had an ATMega 644 lying around, so why not? Plus, the DIP-40 package gives it that retro “I built this in the 80s” vibe. I tried to stick to the original circuit and microprocessor connections as much as possible not because I'm afraid of firmware changes, I just thoughts it would be easier.
* Through-Hole Throwback: Most resistors and capacitors are through-hole, because that’s what I had and they look delightfully vintage. Non-electrolytic caps? All from a random kit I bought for experimenting.
* Why use 1 part when 2 will do: Some components ended up with two passives in parallel or series. Why? Because I was determined to use what I had instead of buying new stuff. If you spot C14.1, C14.2, R15.1, or R15.2 looking a little extra, that’s just me flexing my parts bin muscles.
* Surface Mount Sneak-In: A few surface mount parts made it in, mostly to save space and because I had leftovers. Sorry for the modern touch, but hey, it’s all about balance.
* PCB Front Panel Hack: I love using PCBs as front panels—Kicad makes layout a breeze and it’s cheap. This synth is rocking three boards: bottom for the guts, middle for perfect potentiometer height, and the faceplate for that pro finish.
* Oldest Part Award: The power switch is a true relic—I’ve been lugging it around since the late 80s. It's actually an ON-OFF-ON switch but I thought when else am I gonna use it? And what's so bad about having 2 on positions? Runnerup is the resistors: Straight outta my college electronics kit from the late 80s/early 90s.



## Where Credit Is Due

Let’s be real: this project is standing on the shoulders of other. I didn’t just whip up the MeeBlip Triode out of thin air—there’s a whole crew who did the heavy lifting long before I ever busted out my soldering iron. So, here’s a big, sparkly shout-out (because it’s not just what the license says, it’s the right thing to do):



MeeBlip Contributors:

* Jarek Ziembicki: The OG—created the original AVRsynth, which is the backbone of this whole project.
* Laurie Biddulph: Translation superstar! Worked with Jarek to make those comments readable in English and ported the code to Atmega16.
* Daniel Kruszyna: Idea machine—extended AVRsynth and sprinkled in several concepts that MeeBlip now rocks.
* Julian Schmidt: Filter genius—came up with the original Meeblip digital filter algorithm.
* Axel Werner: Code ninja—optimized, squashed bugs, and brought in new bandlimited waveforms.
* James Grahame: Hardware and firmware mastermind behind MeeBlip’s physical and digital awesomeness.
* [MeeBlip Triode on GitHub](https://github.com/MeeBlip/meeblip-triode)



So, if you’re loving this synth saga, send some good vibes to these legends. Without their brainpower, my 40-year-old promise would still be stuck in the parts bin!

