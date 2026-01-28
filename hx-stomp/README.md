# HX Stomp Configurations

Please read the root [README](../README.md) for how to use. You will need to download the configurations your interested in, rename them and copy them to the correct folder, which the [README](../README.md) advices on.

## Unintended switches

Sometimes I don't use all footswitches, but as the root [README](../README.md) mentions, my device errors if all switches aren't configured.

As such, I'll mark the unintended / unused switches with a "*" and set it to toggle tuner.

## looper.txt

This configuration helps you utilise the looper within the HX Stomp. I always felt the looper was rather hard to use or too simplistic. Thankfully the MIDI commands we can send to the HX Stomp can help us create our own loop footswitches. 

You will need to add one of the loopers to a block within the HX Stomp. I tested the simple looper and it works great for this.

Default Name: 'HLOO'

Functions:
- Switch 1 - Stop / Play
- Switch 2 - Reverse / Forward
- Switch 3 - Half / Full Speed
- Switch A - Looper Record / Play
- Switch B - Looper Overdub / Play Block
- Switch C - * Toggle Tuner *


## navigation.txt

This configuration helps you navigate around your stomp to manage footswitches and snapshots. It's super handy if your stomp is on your pedalboard but hidden, or hard to reach.

Default Name: 'HNAV'

Functions:
- Switch 1 - Previous Preset
- Switch 2 - Next Preset
- Switch 3 - Toggle Tuner
- Switch A - Snapshot 1
- Switch B - Snapshot 2
- Switch C - Snapshot 3