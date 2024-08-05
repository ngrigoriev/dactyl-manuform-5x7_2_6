# Dactyl Manuform build 5x7_2_6

This project contains the information on my first build of Dactyl Manuform keyboard.

# The end

I think the best place to start is by showing the end result:

[![top view](pics/kbpic_small_22.jpg)](pics/kbpic_22.jpg)
[![side view](pics/kbpic_small_17.jpg)](pics/kbpic_17.jpg)
[![left half](pics/kbpic_small_18.jpg)](pics/kbpic_18.jpg)
[![right half](pics/kbpic_small_19.jpg)](pics/kbpic_19.jpg)

# Brief history

I wanted to try the split ergo keyboard and after looking at various commercial options and Dactyl Manuform builds made by different people, I have decided that it will be fun challenge to build one. I have enough experience with 3d printing and electronics so this project did not appear too challenging.

I started exploring various options and, initially, I wanted to build a monster with trackball, OLEDs, RGB LEDs etc. Then finally I have realized that I do not know what I am getting into and what the end result may be. So, instead, I have decided to concentrate on what the keyboard really is: a set of switches with the keycaps, organized in certain shape. Andmy goal was to build something that appears to be usable, but expect the first "product" to be a step to a better one.

Or maybe I won't like it at all? At the end, maybe I won't be able to really appreciate this keyboard? Not everything that is good is absolutely good for everyone. So, being ready to fail relatively fast and after reasonable amount of expenses was important too.

Consequently, I have made the following decision:

- no integrated trackball
- no LEDs, I do not really look at the keyboard when typing
- no OLED screens
- wired only model, I am getting fed up with the wireless accessories lately

I did want to make it hot-swappable because I was not sure about my ultimate switch preference.

# Inspirations

I found tons of resources about Dactyl Manuform keyboards and how to make them. Probably way too many ;) I would like to mention some I found extremely useful for me and express my gratitude for their creators:

## General
- [Video tutorial for those who would rather see than read](https://www.youtube.com/watch?v=dWC_8BOArzc)
- [Dactyl Generator](https://dactyl.mbugert.de/)
- [Dactyl Generator Demo](https://github.com/yejianfengblue/dactyl-generator-demo)

## Other's build logs

- (https://morphykuffour.github.io/keyboards,/ergonomics,/qmk/2021/12/29/Dactyl-Manuform.html)
- (https://dkojovic.medium.com/detailed-guide-on-how-to-build-your-first-dactyl-manuform-keyboard-a412630de76f)

## Understanding the wiring
- (https://www.reddit.com/r/olkb/comments/nq31tt/dactyl_manuform_5x7_wiring_diagrams_and_code/)
- (https://www.reddit.com/r/ErgoMechKeyboards/comments/kntsxg/dacyl_manuform_5x7_wiringfirmware_at_my_limit/)
- (https://deskthority.net/wiki/Arduino_Pro_Micro#Pinout)
- (https://golem.hu/article/pro-micro-pinout/)

Many thanks to those who take time to write all these pages for others!


# Materials

I will post the detailed list of materials and parts later.

# Layout

Somewhat close to the beginning of building my keyboard, I have realized that I have no idea what kind of layout to use. How many rows? Columns? Extra buttons? Thumb cluster size? This was somewhat frustrating - like trying to pick a parking spot on an empty parking lot ;) Finally, I used the following arguments:

- I would rather build something with some keys I do not use than lack the keys I need
- I absolutely wanted the maximum number of keys for my thumbs, because I believed this was one of the main things about these keyboards
- I rarely use the function keys
- 5x4 is the absolute minimum to fit all basic keys, but you are still left with some keys that you need to put/assign somewhere ("+", "-" etc)

Some of these thoughts were caused by my lack of understanding what Dactyl keyboard is about - generall about *NOT* moving your hands to reach the keys.

So, I ended up with the layout that I considered to be a good middleground between the excessivness and minimalism:

- 5 rows 7 columns
- only two keys in the last row
- the last column would have 3 index keys
- the outer columns would use wider keys (1,5u)
- so will do two closest thumb keys, the remaining 4 will be the regular ones

This layout was also inspired by my exercises with various generators

# Generators

I ended up trying these two:

- https://ryanis.cool/dactyl/#manuform (and https://ryanis.cool/cosmos/)
- https://dactyl.mbugert.de/manuform

Finally, I have settled on the latter. I was getting the most consistent and clean results from it.


# Course corrections

When I started to plan printing the case, I have decided to first play with some slicer settings and print a small fragment of the case instead of the full one. This idea saved me tons of time, material and frustrations. I could get the sample in 2 hours and judge if my settings were correct.

This is how I found that:

- I cannot really print something usable for mounting the hotswap sockets. This was beyond the capabilities of my Ender 3 Max printer. So, I have given up on the hotswaps.
- Support is the evil. You have to trade the qualify of the inner surface for your sanity, because if you use the proper support, then you will not be able to remove it!

# More photos

[![making of](pics/kbpic_small_1.jpg)](pics/kbpic_1.jpg)
[![making of](pics/kbpic_small_2.jpg)](pics/kbpic_2.jpg)
[![making of](pics/kbpic_small_3.jpg)](pics/kbpic_3.jpg)
[![making of](pics/kbpic_small_4.jpg)](pics/kbpic_4.jpg)
[![making of](pics/kbpic_small_5.jpg)](pics/kbpic_5.jpg)
[![making of](pics/kbpic_small_6.jpg)](pics/kbpic_6.jpg)
[![making of](pics/kbpic_small_7.jpg)](pics/kbpic_7.jpg)
[![making of](pics/kbpic_small_8.jpg)](pics/kbpic_8.jpg)
[![making of](pics/kbpic_small_9.jpg)](pics/kbpic_9.jpg)
[![making of](pics/kbpic_small_10.jpg)](pics/kbpic_10.jpg)
[![making of](pics/kbpic_small_11.jpg)](pics/kbpic_11.jpg)
[![making of](pics/kbpic_small_12.jpg)](pics/kbpic_12.jpg)
[![making of](pics/kbpic_small_13.jpg)](pics/kbpic_13.jpg)
[![making of](pics/kbpic_small_14.jpg)](pics/kbpic_14.jpg)
[![making of](pics/kbpic_small_15.jpg)](pics/kbpic_15.jpg)
[![making of](pics/kbpic_small_16.jpg)](pics/kbpic_16.jpg)
[![making of](pics/kbpic_small_20.jpg)](pics/kbpic_20.jpg)


# Challenges worth mentioning

In short, the build process was quite smooth. Several things are worth mentioning.

I ended up using "MX snap-in (one-way)" option for the key hole. I liked the way the switch (Cherry MX Blue) was sitting in the keyboard and I was able to remove it from this socket too, with some effort, of course. So it is not really "one-way" :) However, my right thumb did hurt a lot after pushing 70 keys in these holes. I should have used something else instead.

Soldering is easy, although it does take time. Actually, I was able to solder everything correctly from the first attempt and did not have to fix a single connection after that.

You do need to decide what to put first - diodes or the columns. I recommend the diodes. This way you will be able to push them all the way down and secure them in place when you add the column wires.

At the end, it was not that difficult at all to use regular wire to make columns. If you have a sharp scalpel-like knife, removing a couple of millimeters of the insulation is simple.

Actually the most difficult thing was to attach the wires going to the board. I decided to use the connectors instead of soldering them directly to the board. That was a good idea, because I did connect them incorrectly initially, reversing the order of the rows (or columns) on one of the halves.

Hot glue is your friend. Especially for securing the parts like reset button or TRSS socket. And Promicros themselves.

# Files

In the "resources" directory you will find the case, the bottom plate and the Promicro holder models I used to make my keyboard.

Special note about the holders. The original holders generated with the tool did not fit well my case. I had to massage the STLs a little bit (all in Tinkercad) to make them right. The box for the board was about 1mm too small, the hole for TRSS cable did not allow the cable I have to go all the way in.


# Final thoughts

I am still working on the layout that will work for me. Way too many options available from QMK :)

I am certain now that I could have a smaller keyboard.

I am not yet convinced that the bent form of Manuform is ideal for me.

My typing speed is down to something I never experienced since I was at school ;)

QMK documentation is worth reading *before* you build your keyboard, not only after.

Do not attempt to lubricate Cherry MX buttons. Not the blues, at least.

Finding decent and budget keycaps is tough, but I found a set for $17 that I liked on Amazon.

Plan for the wrist pads. I have decided not to attempt building a case with integrated wrist pad supports right away. Instead, I bought two cheap kidney-like pads and now I have cut a base for them using styrofoam. This way I can easily adjust the height, angle etc. Once I am happy, I will print something solid.

No matter what, if you like the idea and you want to try, I can guarantee you that you will enjoy building a keyboard!
