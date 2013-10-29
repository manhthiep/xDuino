xDuino
======

sanguine -adjective
--------
1. cheerfully optimistic, hopeful, or confident: a sanguine disposition; sanguine expectations.
2. blood-red; red.

sanguino -noun
--------
1. a fun microcontroller board inspired by the awesome Arduino project
2. a red colored microcontroller board based on the ATmega644P
3. italian - I'm bleeding! (ed. -oops. thanks for the heads up, google translate! </sarcasm>)

The Sanguino is based on the atmega644P chip.

Why make the Sanguino?
--------
I love the Arduino project and use it extensively, most notably in the RepRap project. Currently, we are driving a complete RepRap machine with a single Arduino. Unfortunately, we had to make quite a few compromises in order to achieve that. We are using every single pin, and we are also at maximum capacity for our flash memory. We needed a more powerful microprocessor, but we were reluctant to leave the warm bosom of the Arduino community.

So, we created a board that is more powerful, yet still compatible with the Arduino software. It was very easy, since the Arduino software is both amazing and open source.

Why not use the Arduino?
--------
We did, and it works great, but we needed a bit more power. Maybe you do too.

Why not use the Wiring board?
--------
The wiring board is SMT only, and no DIP version of the atmega128 exists.
It has very limited commercial availability, and is rather expensive. ($80 from Sparkfun)
It has much less acceptance in the wider hacking community vs. Arduino.
Designing your own board is fun and informative.

--------
More info: 
http://sanguino.cc/start
http://sanguino.cc/makeyourown
http://sanguino.cc/hardware
