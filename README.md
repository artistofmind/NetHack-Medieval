# NetHack Medieval

### Contents

1. [Introduction](https://github.com/artistofmind/NetHack-Medieval/blob/main/README.md#1-introduction)
2. [Instructions](https://github.com/artistofmind/NetHack-Medieval/blob/main/README.md#2-intsructions)
3. [Why This Project](https://github.com/artistofmind/NetHack-Medieval/blob/main/README.md#3-why-this-project)
4. [Looking Forward](https://github.com/artistofmind/NetHack-Medieval/blob/main/README.md#3-looking-forward)

---

## 1. Introduction

Presenting _NetHack Medieval_: a complete tileset for NetHack 3.6.7, with unique icons for nearly everything. These tiles actually convey more information than the original ASCII; and since they’re made with vector graphics of a single color each, the result is as clean & crisp as any font. 😎 Every weapon, tool, potion etc. looks distinct, yet still “of a piece” with other items of that type — so you can tell what everything is at a glance. It’s designed to be legible when viewing the whole map at once, yet there’s enough detail here to provide a rich experience when viewing one room at a time — win / win! (Who said you couldn’t have your cake and eat it, too? 😛)

Based on _NetHack Modern_ by Tower Hufham, this set likewise uses graphics from the open-source repository [Game-icons.net](https://game-icons.net), by Delapouite, Lorc, Caro Asercion, et al., modified slightly by yours truly. (For example, the Hawaiian shirt began as a polo shirt from that site; I extended the button flap and added flowers. I also gave the ettin a second head. Because ettins are two-headed giants, as every Monty Python fan knows. 😉 *“All right, not biscuits. But let’s kill him anyway!”*)

---

## 2. Instructions

To install, simply unzip to your NetHack program directory, and add the following line to the <code>.nethackrc</code> file in your user folder:

> OPTIONS=tile_file:NetHack Medieval 64x-367.bmp,tile_width=64,tile_height=64

(Replacing “64” with any other size as appropriate.) NetHack is 80 tiles wide when fit to screen, so simply divide your screen width by 80 to get the size you need for the game to render at 1:1. FYI:

- 1080p (1920 w) = 24x
- 1440p (2560 w) = 32x
- 4k (3840 w) = 48x
- 5k (5120 w) = 64x
- 8k (7680 w) = 96x
- 10k (10240 w) = 128x

I have provided all of the above, which I believe covers most standard screens. If you need something unusual, simply resize the 10k tiles using a high-quality resampler, like the Lanczos filter in the free program IrfanView. (Divide the target width by 40, and there’s your tile size. 🙂)

---

## 3. Why This Project

I was using NetHack Modern when I noticed it had several flaws. For example:

- No two purple tiles were the same color (just really close).
- Some icons were identical to others. E.g. you couldn’t tell a master lich from an arch-lich, or a baby worm from an adult one. You also couldn’t tell an open door from a doorway, so sometimes I tried closing a door that wasn’t there. 😊
- Some icons were clearly just placeholders. E.g. unicorns & ki-rins were only regular horses.
- Some icons were missing altogether. E.g. there was no unique stethoscope or lockpick.
- Rays & explosions merely repeated one tile each, regardless of direction.
- Statues were simply a copy-paste of the first section converted to grayscale. This meant their values differed wildly, with e.g. statues of white monsters still appearing white, and red ones looking blacker than “black” — making it hard to tell if something even was a statue!
- Some tiles were simply incorrect. E.g. the Chromatic Dragon was an @ symbol; the quadrupeds were mostly crocodile heads; the corpses of puddings & oozes looked more alive than before they were killed (the “glob” gains a face); and the “strange monster” was accidentally duplicated after the statues. (One tile too many.)
- The tiles labeled “96x” were actually 128x.

Etc. (By no means a comprehensive list! Heh.)

Game-icons.net has also added lots of content in the last 10 years. So while I set out simply to rectify some of these issues, I ended up redoing the entire thing from scratch. The result has little in common with _NetHack Modern_, despite getting most artwork from the same source; hence I’ve called this spinoff _NetHack Medieval_, instead. (Well, back in the day art tended to be more intricate, while most Modern art is comparatively simple; so I reckon the name change is only appropriate. 🤷)

FWIW, Fandom’s [map of the default tileset](https://nethack.fandom.com/wiki/Tileset#Default_tileset) is incomplete, and their [list of tiles](https://nethack.fandom.com/wiki/List_of_vanilla_NetHack_tiles) is slightly out of order. To be sure mine were exactly right, I tested everything myself in game, using the latest version of NetHack. All of this research & editing took me about a month, so you’re welcome!

---

## 4. Looking Forward

I originally had unique tiles for all the gems (including worthless ones); all four bags and gray stones; the real & fake amulets of Yendor; both flutes, harps, whistles, candles, lamps; the cornuthaum & dunce cap. The amber stone even had a fossilized mosquito in it. 🙂 Alas, this caused my tiles to contain spoilers! (You could identify those items just by looking at them.) So I had to build in some redundancy, as in every other tileset out there. 😕

Perhaps a future version of NetHack will always show the first icon till an item is identified, and only then change it? Or else randomize the tiles assigned to those items, as with potions & wands? . . . As it is, it’s weird having separate slots for all these things when you can’t actually use them. 🤨 I also found a bug, whereby the aquamarine stone sometimes gets assigned the sapphire’s icon, depending on whether it’s called a green or blue gem in that particular session of the game. (So, even when that tile is unique, it sometimes doesn’t get used, and one of the others is used twice.)

Game-icons.net also has some pictures I really wanted to use, but couldn’t. For instance, they have an image specifically for holy water. It would be so cool if a future version of NetHack has three different “clear potion” tiles, defaults to the uncursed one and only changes when it’s identified as either blessed or cursed. If and when that day comes, I am ready to update this set accordingly. 🙂

Likewise, it would be nice if wand rays could be bi-directional along each axis, but I’d need twice as many tile slots to achieve that. (As it is, they always read from West–East / South–North.) I guess it’s safe to say _NetHack Medieval_ isn’t just complete, it’s more-than-complete: there would be even more variety if it were allowed!

Be assured I will keep this tileset up to date for as long as I’m alive and able. So when a new version of NetHack adds more tiles, so will I. 🙂

Cheers!  
JAK from CA, USA  
2025
