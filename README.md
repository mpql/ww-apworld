# Wind Waker for Archipelago

This is a mirror and guide of this [Archipelago Wind Waker](https://github.com/Dev5ter/ww-apworld) by [Dev5ter](https://github.com/Dev5ter). It's also got an [Archipelago-compatible ISO randomizer](https://github.com/Dev5ter/wwrando) ([mirror](https://github.com/mpql/AP_wwrando)) and an [Archipelago-compatible Tracker](https://github.com/Dev5ter/tww-rando-tracker) ([mirror](https://github.com/mpql/AP_tww-rando-tracker)). I tested these with a friend and they work _very_ well.

## Guide

1. Install [Archipelago](<https://github.com/ArchipelagoMW/Archipelago/releases>) if you don't already have it. Each player will want to do this.
2. Randomize your ISO like you normally would with the [wwrando tool](https://github.com/Dev5ter/wwrando/releases) ([mirror](https://github.com/mpql/AP_wwrando/releases)). Each player will want to do this. My friend and I tested with the same settings and the same seed, but I don't know that that matters. There aren't any settings for the AP yaml yet besides death-link, so I don't know if it actually supports disabling certain item types; we haven't gotten far enough yet to tell if they're just ignored. May update this later.
3. Drop the `lib` directory from this repo inside your archipelago installation's root directory. You should end up with the following directory structure:
- `<your_archipelago_root>/lib/dolphin_memory_engine/`
- `<your_archipelago_root>/lib/worlds/ww.apworld`
4. Grab the `Wind_Waker.yaml`, making a separate copy each for you and your friend(s). Change it so you have different names in each yaml; I've disabled death link by default, but feel free to turn it on if you want it. Throw everyone's yamls in Archipelago's input directory; mine is at `archipelago/input/yaml/`, but I can't recall if that is the default.
5. Launch [Dolphin](https://dolphin-emu.org/download/), load the randomized ROM you generated, start a ***new*** save file, and load into it. Link should be standing on Outset like normal. Each player will want to do this.
6. Open the Archipelago launcher, click Generate, and once that is complete, click "Host" to load up the Archipelago server, selecting the generated `AP_<numbers>.archipelago` file when it asks for it.
7. Still in the Arcipelago launcher, click "Wind Waker Client". Each player will need to open the client.
8. In the client, connect as usual:
- Type in the server IP and click connect
- If it asks, type in the server password and hit enter
- Type in slot name (player name) when it asks and hit enter -- it should say "Connected to Dolphin."

All done! Play Archipelago together as normal!

Original Readme:

---

# ww-apworld
The ww.apworld file setup for Wind Waker using Archipelago Services

# To Install (This Assumes you alread have installed Archipelago)
- Just drop the dolphin-memory-engine folder in you lib folder of your Arch install and then drop your ww.apworld file in your lib/worlds folder.
