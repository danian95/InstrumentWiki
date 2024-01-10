---
title: Gamry Interface 1010E
description: Potentiostat/galvanostat/ZRA capable of operating in bipotentiostatic mode
published: true
date: 2022-04-27T17:28:46.340Z
tags: electrochemistry, potentiostat
editor: markdown
dateCreated: 2022-01-19T15:33:31.606Z
---

# Electrochemical Analysis

There are two Interface 1010E potentiostats in the chemistry department. In order to run bipotentiostatic measurements, they need to be interfaced to one another. See Dr. McCurry for details.

## Procedures {.tabset}

### Familiarization

#### Procedure

 1. Make sure the power to the potentiostat is on. The switch is on the back of the instrument, so you will have to reach around to locate it. (Look for the power LED)
 2. Attach the potentiostat leads to the calibration "cell" (the circuit board looking thing). If there are alligator clips attached to the leads, you can pull them off. Just make sure to grip the colored portion of the banana jack and **not** the wire. The colors of the appropriate leads are screen printed on the circuit board. **Be absolutely sure that you are connected the leads to the appropriate positions.** It's good practice to connect them in order of Counter (red,orange clips) > Reference (white clip) > Working (blue, green clips). The Counter is the electrode with the long wire, the reference electrode is the clear tip stored in the solution vial (MR-5275) with a white lid. The platinum working electrode is the solid black electrode.
 3. Open the Gamry Framework software.
 4. Go to Experiment > Physical Electrochemistry > Cyclic Voltammetry
 5. Set the parameters as follows:
     * Initial E (V): 0
     * Scan Limit 1 (V): 0.5
     * Scan Limit 2 (V): -0.5
     * Final E (V): 0
    All other defaults should be good to use.
 6. Click OK. If it complains about the calibration, ignore it by pressing run anyways. If it asks to replace a file, click Yes.
 7. When the scan is complete (in not very apparent text, it says "Experiment done" in the bottom left of the open window), press 'F2' on the keyboard.
 8. Disconnect all leads from the calibration cell and attach the alligator clips. Note that the reference lead (white) uses a specific clip.
 9. Find the electrochemical cell to the right of the computer. Electrodes have already been immersed in this saturated NaCl solution. Attach the orange clip to the copper post on the electrode furthest to the right. Attach the red clip to the orange clip. Attach the white clip to the electrode furthest to the left (white wire). Attach the blue clip to the center electrode. Attach the green clip to the blue clip.
10. Make sure that none of the alligator clips are touching each other (excluding the blue/green and orange/red pairs) or anything conductive.
11. Repeat the CV, but this time, name your file (Output File) RCV-NaCl.DTA.
12. When complete (remember to press F2), disconnect all electrodes, close Gamry Framework, and turn off the potentiostat.
13. Open Gamry Echem Analyst.
14. Click the open button on the toolbar and select both RCV.DTA and RCV-NaCl.DTA. You can hold down Ctrl on the keyboard while clicking to select multiple files. Open them separately.
15. Use the data to answer the questions below and close the software when you are finished.




### Voltammetry {.tabset}

Most voltammetric measurements make use of a device called a potentiostat, which is capable of applying a controlled potential to a working electrode and measuring the current that passes as a result of electron transfer to solution species of interest. The potentiostat contains many internal circuits that allow it to function in this capacity. The circuits generate and measure potentials and currents.

#### CV
1. Once desired solutions are prepared, fill the electrochemical cell (shot glass) ~ 3/4th full with the blank, add the small stirbar, & place on the silver shelf. Slide the shelf under the covering with holes for the electrodes and turn on the magnetic stirring. (black switch to the right of the cell)
2. Remove all oxygen from solution by bubbling nitrogen gas through the electrochemical cell for 3-5 minutes
-**NOTE**: make sure the nitrogen gas is causing the solution to bubble quite rapidly, but not enough to spill any solution
3. While the solution is bubbling, power on the Gamry Potentiostat. The switch is in the back, kind of on the bottom right if you are looking at the front of the machine. 
4. Go to Experiment > Physical Electrochem > Cyclic Voltammetry
5. Set the desired parameters:
	* Test ID: The name of the experiment.
 * Set the scan parameters as follows:
    	 - Initial E (V): 0.8
    	 - Scan Limit 1 (V): -0.12
    	 - Scan Limit 2 (V): 0.8
     	 - Final E (V): 0.8
       - all the previous scan parameters are vs Eref
 	 * Output file: The name of the file created.
 	 * Electrode Area: Will give current (*i*) if the area is set to 1. It will give current density (*j*) if the actual area is provided.
   * Set scan limits: The range of voltages that will be scanned.
   * Scan Rate: The speed at which scans are done. (20mV/s)
   * Step Size: The distance in between which measurements are taken. (2mV)
   * Cycles: How many times each point is measured (1 Cycle)
   * Max Current: Maximum current allowed (To start, set to auto)
   * Eq Time: Time potentiostat waits before measurement (set to 0 normally, but 10s is recommended)
   * 1/E Range Mode: Fixed
   * Expected max V: Maximum voltage anticipated (10V)
   * Sampling mode: Set to noise reject
   * All tick boxes should be unchecked
6. Once bubbling is completed (the instructions say purge with nitrogen for 10 minutes, but 3 should suffice... it's a small "toothpick holder") remove the tube from the solution, but leave it blowing nitrogen gas over the solution with minimal ripples so no oxygen gets back in.
7. Insert the electrodes and connect the alligator clips in the following order:
	* Counter electrode: Always connect the "sensor" clip closest to the electrode
 	 * Reference electrode
   * Working electrode: Always connect the "sensor" clip closest to the electrode 
8. Ensure the electrodes are not touching. The cell is small and the clips can slide as the wires settle. 
9. Turn off the magnetic stirring. This will create waves in your data in the diffusion limited current region of your CV.
8. Once parameters are set, click "OK" at the top of the screen and take a background scan. You should see this run take place with no peaks.
		*If there are peaks, you will need to polish the working electrode   with Micropolish Alumina. If the peaks in your blank are not resolved, the WE may require sonication.
9. Once run is complete, press F2 on the keyboard and continue further runs. (Remember, each time the solution is swapped, you must bubble through with nitrogen gas and stir for at least 3 minutes).
10. The reference electrode should be washed between runs with deionized water, though this electrode must always remain wet as to not clog the pourous glass with the formation of crystals. 

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
