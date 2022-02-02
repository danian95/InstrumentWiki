---
title: Agilent 8890 GC-MS
description: Agilent 8890 GC with 7000D MS
published: true
date: 2022-01-30T15:58:49.092Z
tags: gas chromatography, chromatography, mass spectrometry
editor: markdown
dateCreated: 2022-01-13T19:22:29.951Z
---

# Agilent 8890 GC-MS
The Agilent 8890 GC is interfaced to a 7000D triple quadrupole mass analyzer. A PAL autosampler is installed capable of liquid, headspace, and SPME sample introduction.

- [:calendar: Calendar *View the current instrument schedule*](https://instrumentschedule.com/fom/viewonly?eid=2338&p=t1KelxxGan)
- [:book: Manuals *View instrument documentation*](https://huskiesbloomu.sharepoint.com/:f:/s/chem/Eo8ei4C4hEBPtwPJfns7mI0BiMMpSgB_ErzjQQ6LtRDLvw?e=fuEzIz)
{.links-list}

![gcms.png](/gcms.png =50%x)

## General Usage
> If using the PAL, be sure that the correct attachment is installed. {.is-info}

## Familiarization

### Procedure

 1. The GC-MS must remain under high vacuum, so it is **always on**. Open the Agilent GCQQQ software.
 2. Go to Method > Load Method and find butterscotch.M.
 3. Click the big arrow at the top of the screen.
 4. Type your name in under Operator Name. For Data Path, click Browse. Save your data under D:/MassHunter/GCMS/1/data/practice. Name your data file something fun and interesting.
 5. Take a look at the sample racks above the GC-MS. We'll be using the Butterscotch extract which is already loaded in one of the trays. Find it! Note that the trays have numbers corresponding to the individual vials, but also numbers corresponding to the racks present. Two rows of racks are numbered 1-3. The racks on the left are correct. The racks on the right are actually racks 4-6. On the computer, type in the vial number for the Butterscotch Extract and select the correct rack from the dropdown (making sure that you translate 1 to 4, 2 to 5, and 3 to 6).
 6. OK and run method!
 7. It may appear as if nothing is happening at all as it warms up. Please be patient. The PAL autosampler will play some tunes right before it's about to move.
 8. Once the run is complete, open the Qualitative Analysis software. Find your data file and open it. If nothing has changed, it should automatically identify all of the peaks in your data.
 9. Once you're finished looking at the software, you may close it.
10. If you are the last person using the GC-MS, go to Method and load the standby.M method (just look through the drop down menu as it should have recently been used).

### Questions

 1. We operated the GC-MS in "headspace" mode which means it just pulls off the vapor at the top of the sample without actually dipping into the liquid. Knowing that, what was the purpose of the incubation/shaking chamber?
 2. Were all of your peaks well resolved?
 3. Name 3 compounds that were identified by the software. Compare that to the list of ingredients on the original bottle. How does what you found differ from the label on the bottle?
 4. Can you determine which compound is most concentrated based on this run? How or why not?

### Procedure {.tabset}

#### Loading a Saved Method

Go to File

#### Building a New Method

## Shutdown

> When finished using the instrument, be sure to set the method to **standby.M**.
{.is-warning}
