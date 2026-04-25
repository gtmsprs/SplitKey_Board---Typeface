# Day 1 - April 16th, 2026 
### Learned how to create a Proper PCB (Schematic)
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 2.1h logged
<img width="1137" height="796" alt="image" src="https://github.com/user-attachments/assets/e538af62-700e-4452-996f-738c58ad95a3" />

It took me a while to figure out how to import the right footprints and symbols, as I had been struggling to do so. But once I had it imported, I followed the instructions provided by @koeg, and kudos to her, as she made it really easy for me to follow. in the span of 2 hours, I managed to create a split key matrix and connect it to my Xiao microcontroller via the labels, and finally create a test point and battery sense. However, the footprints and symbols that I had previously imported came back to bite me in the back, as I could not properly import this into my pcb editor, so I will need to troubleshoot it sometime soon.

I recorded a timelapse of my hackpad; however the app that was provided, lapse, had not properly record my footage. Fortunately, I had been streaming at the time (https://www.twitch.tv/videos/2751697817).
and if this does not count towards creating a PCB, I will cry :(

I can also send a full video format just in case as I have also saved the stream onto my computer. My Slack ID is U08002N0XQE, so please feel free to contact me if further proof is needed. Thanks!

# Day 2 - April 17th, 2026
### PCB Editing/troubleshooting XIAO footprints and symbols
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 2.2h logged

<img width="1323" height="766" alt="image" src="https://github.com/user-attachments/assets/a2ffdf7e-095b-41c7-b66e-350f3addbf0e" />

I finally figured out what I'd been doing wrong this entire time. I had failed to import the right footprint to the symbols for both the xiao footprint and the diode footprint, plus the

What I want to add to this build is the most cheapest, but best costing materials as per part of my BOM (Bill of Materials). I will be going with the GATRON milky yellow pros, and I want to make the keyboard gatron compatiable. I also am going with the standard diode. I will debate whether I'll go with the minimal look for the keycaps, but as of right now that's not the thing that I'm focusing on.

I'm finished with the whole troubleshooting, but it took a long time to figure out, which is why I'll now proceed to work on this the next day.
https://lapse.hackclub.com/timelapse/J9anPOfhamre

# Day 3 - April 18th, 2026
### Cleaning up my Split Keyboard on PCB Editor (KiCAD)
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 4.25h logged

<img width="1631" height="760" alt="image" src="https://github.com/user-attachments/assets/41f63916-09a7-419b-bf07-23eb7d7909b9" />

So I ran into a bit of a problem again, and it's related to my original schematics. After wanting to update it again, I wanted to add a few additional buttons to the keyboard since I had more keys to spare, but now the schematics aren't getting annotated correctly. I will look at some tutorials on KiCAD to find the root of this problem.

After some troubleshooting, however, I was able to figure out the root of the problem, which was that labeling the switches and diodes ended up confusing the program and altogether making a whole bunch of errors as a result. Once I correctly labeled all of the switches and diodes correctly, it was way easier from there, allowing me to finally load the PCB back into the PCB editor.

It took a couple more hours, however, as I had to piece together all of the hotswappable switches manually to figure out what layout I wanted for this PCB to work. I decided to take on an iris swiss layout. But once I was done with one side, the other side also had to be perfectly mirrored too. And by the time I was done, it had been almost 4 hours of work, which is why I've decided i'd add the mousetraps and the actual shape of the PCB in the final PCB. I'll also post this schematic on Slack, because I want to double check incase something's wrong with how I set up the hotswappable keys.
https://lapse.hackclub.com/timelapse/J9anPOfhamre 
