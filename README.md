# MIDI Captain Config

This repo contains config files for paint audio's MIDI Captain. You can find details about the midi footswitch details on their [website](https://paintaudio.com/).

I am not sponsered, or a contact on behalf of paint audio.

You are free to use these config files are your own risk.

## Tested Devices

- MIDI Captain MINI 6 Controller

## How To Use

- Plug your MIDI Captain into your computer via USB.
- Turn it one whilst pressing Footswitch 1.
- A device should be recognised on bootup.
    - On Windows it shows as a D drive for me.
- Download a config txt file you want.
- Copy any of the config text files into the subfolder "supersetup".
- Rename the text file as pageX.txt where "X" is the page.
    - For example: "page0.txt".

Feel free to change the configurations to suit. I've included common configurations I actively use. Please note the tested devices. You may need to adjust configurations if you have a similar, smaller, or larger device.

## GOTCHAS!

It's been my experience that you must account for every footswitch! If you don't you'll see boot errors. Maybe I'm doing something wrong. 

Sometimes I (or you!) don't need all footswitches. As such I'll likely add a "dummy" one that does something that I didn't actually intend, just to fill the slots. These will be explained in the individual folders and READMEs. 

If you edit any of the configurations make sure that:
- Every configuration in this repo has 'globalsetup', which is only required for 'page0.txt'. Delete from 'globalsetup' to the 'page' section if you use as a different page number.
- page_name is in uppercase letters  and has less than or equal to 4 characters.

**I'll update the more I spot**

## Why Does This Exist?

I found the device quite complex to use initially. The manual isn't that intuitive and if you get the config wrong you'll likely see python boot errors. 

It may just end up as backup configurations for myself but I'll be leaving this public in case others find this useful.