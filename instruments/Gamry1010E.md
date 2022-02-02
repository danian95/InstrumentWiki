---
title: Gamry Interface 1010E
description: Potentiostat/galvanostat/ZRA capable of operating in bipotentiostatic mode
published: true
date: 2022-01-30T16:00:04.110Z
tags: electrochemistry, potentiostat
editor: markdown
dateCreated: 2022-01-19T15:33:31.606Z
---

# Electrochemical Analysis

There are two Interface 1010E potentiostats in the chemistry department. In order to run bipotentiostatic measurements, they need to be interfaced to one another. See Dr. McCurry for details.

## Procedures {.tabset}

### Familiarization

#### Procedure

 1. Make sure the power is on to the potentiostat. (Look for the power LED)
 2. Attach the potentiostat leads to the calibration "cell" (the circuit board
    looking thing). If there are alligator clips attached to the leads, you can
    pull them off. Just make sure to grip the colored portion of the banana jack
    and **not** the wire. The colors of the appropriate leads are screen printed
    on the circuit board. **Be absolutely sure that you are connected the leads
    to the appropriate positions.** It's good practice to connect them in order
    of Counter > Reference > Working.
 3. Open the Gamry Framework software.
 4. Go to Experiment > Physical Electrochemistry > Cyclic Voltammetry
 5. Set the parameters as follows:
     * Initial E (V): 0
     * Scan Limit 1 (V): 0.5
     * Scan Limit 2 (V): -0.5
     * Final E (V): 0
    All other defaults should be good to use.
 6. Click OK. If it complains about the calibration, ignore it for now. If it
    asks to replace a file, click Yes.
 7. When the scan is complete (in not very apparent text, it says "Experiment
    done" in the bottom left of the open window), press 'F2' on the keyboard.
 8. Disconnect all leads from the calibration cell and attach the alligator
    clips. Note that the reference lead (white) uses a specific clip.
 9. Find the electrochemical cell to the right of the computer. Electrodes have
    already been immersed in this saturated NaCl solution. Attach the orange
    clip to the copper post on the electrode furthest to the right. Attach the
    red clip to the orange clip. Attach the white clip to the electrode furthest
    to the left (white wire). Attach the blue clip to the center electrode.
    Attach the green clip to the blue clip.
10. Make sure that none of the alligator clips are touching each other
    (excluding the blue/green and orange/red pairs) or anything conductive.
11. Repeat the CV, but this time, name your file (Output File) RCV-NaCl.DTA.
12. When complete (remember to press F2), disconnect all electrodes, close Gamry Framework, and turn
    off the potentiostat.
13. Open Gamry Echem Analyst.
14. Click the open button on the toolbar and select both RCV.DTA and
    RCV-NaCl.DTA. You can hold down Ctrl on the keyboard while clicking to
    select multiple files. Open them separately.
15. Use the data to answer the questions below and close the software when you
    are finished.

#### Questions

 1. What is the slope of the resulting line for the calibration cell?
 2. Does the slope make sense provided the values on the calibration cell?
 3. How does the shape of the curve for the saturated NaCl differ from the first
    run?
 4. If we were to model our electrochemical cell with an equivalent circuit
    diagram, what components might we need to mimic the aqueous solution of
    NaCl? Consider how current is changing with respect to voltage.


### Voltammetry {.tabset}

#### CV

#### LSV

#### ASV

### Amperometry {.tabset}

#### test

### Impedance

## Data Analysis

The easiest way to visualize data before exporting to a figure is to work up the data in Gamry Echem Analyst.

## External Links

- [Gamry Application Notes](https://www.gamry.com/application-notes/)
{.links-list}
