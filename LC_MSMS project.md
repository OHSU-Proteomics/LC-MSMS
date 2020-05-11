---
title: "LC-MS/MS Methods used in OHSU’s PSR Core"
author: "Jennifer Cunliffe"
date: "May 11, 2020"
output:
  html_document:
    css: style.css
  pdf_document: default
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

# A description of the LC and MS methods and setups that we commonly use in the PSR core

## OHSU Proteomics Shared Resource


***

![slide 1](LC-MSMS slides_final/Slide1.png)

***

![slide 2](LC-MSMS slides_final/Slide2.png)

Our high resolution mass spectrometers (Fusion and QExactive HF, from [Thermo scientific](https://www.thermofisher.com/us/en/home/clinical/clinical-translational-research/protein-analysis/mass-spectrometry-instruments.html) are coupled to [Dionex Ultimate 3000 RSLC instruments](https://www.thermofisher.com/order/catalog/product/ULTIM3000RSLCNANO#/ULTIM3000RSLCNANO). Our LC systems have 2 nano pumps (the second is only used for 2D LC methods), a loading pump, a switching valve, and an autosampler set to 4C. There is also a column oven, but we don’t use it – we heat our columns (to 40 C) using the ionization source attached to the mass spec.

***

![slide 3](LC-MSMS slides_final/Slide3.png)

We use the same elution scheme for the vast majority of our C18 analytical separations, although the gradient time can vary (typically 1 – 4 hrs). We typically use a 25 cm column, but also use a 50 cm column under certain situations.

***

![slide 4](LC-MSMS slides_final/Slide4.png)

We currently have three [Thermo scientific](https://www.thermofisher.com/us/en/home/clinical/clinical-translational-research/protein-analysis/mass-spectrometry-instruments.html) mass spectrometers in our core. The QExactive HF and the Fusion are our high resolution instruments and contain an orbitrap – they are also in higher demand. The Velos Pro contains a dual-pressure linear ion trap and is used for lower resolution studies.

***

![slide 5](LC-MSMS slides_final/Slide5.png)

_**Specifications**_  
**Mass Range**: m/z 50-6,000; **Max Resolving Power**: 240,000 @ m/z 200; **Max Scan Rate**: up to 18 Hz at resolution setting of 15,000 resolution @ m/z 200; **Mass Accuracy**: Internal: < 1 ppm RMS, External: < 3 ppm RMS, under defined conditions; **Dissociation**: In-Source CID, HCD; **Scan Functions**: FS, AIF, SIM, PRM, DIA, ddHCD; **Quad Isolation**: Step-less from full mass range down to 0.4 amu; **Polarity Switching**: One full cycle in < 1 sec (one full scan positive mode and one full scan negative mode at resolution setting of 30,000); **Multiplexing**: Up to 10 precursors/scan; **Analog Inputs**: One (1) analog input (0 - 1 V), One (1) analog (0 - 10 V).
 

***

![slide 6](LC-MSMS slides_final/Slide6.png)

_**Specifications**_  
**Mass Range**: Linear Ion Trap and Orbitrap Mass Range: Standard – m/z 50–2,000, High Mass – m/z 200–4,000, Orbitrap Extended Mass Range: Up to m/z 6000 without precursor ion selection; **Resolution**: 15,000-450,000 (FWHM) at m/z 200; **Scan Rate**: Orbitrap MSn up to 20 Hz, Ion trap MSn up to 20 Hz; **Mass Accuracy**: < 3 ppm RMS using external calibration, < 1 ppm RMS using internal calibration; **MS/MS Sensitivity of Ion Trap**: 2 μL of a 50 fg/μL solution of reserpine (100 fg total) injected at a flow of 500 μL/min will produce a minimum signal-to-noise ratio of 100:1 for the transition of the isolated protonated molecular ions at m/z 609 to the largest two product ions, m/z 397 and m/z 448, when the mass spectrometer is operated at unit resolution in the full-scan MS/MS mode, m/z 165–615. The test requires **Dynamic Range**: > 5,000 within a single scan, guaranteeing specified mass accuracy; **MS Scan Power**: MSn, for n = 1 through 10; **Thermo Scientific™ EASY-ETD™ Ion Source**: 1) Generates fluoranthene anions for electron transfer dissociation (ETD), 2) Townsend discharge ionization is extremely stable and robust, 3) Compact size, located entirely within the footprint of the instrument, 4) Active reagent ion filtering using mass-resolving quadrupole; **Thermo Scientific™ EASY-IC™ Ion Source**: 1) Generates internal calibrant ions for real-time mass calibration on every spectrum, 2) Provides <1 ppm RMS mass accuracy; **Synchronous Precursor Selection**: Up to 15 precursors per MS2 scan, for MS3 analysis only; **Multiplexing Using Ion-Routing Multipole**: Up to 10 precursors per scan using quadrupole mass filter; **Polarity Switching**: One full cycle in 1.1 sec (one full scan in positive mode and one full scan in negative mode at resolution setting of 35,000).


***

![slide 7](LC-MSMS slides_final/Slide7.png)

_**Specifications**_   
**Mass range**: 1) m/z 15–200, 2) m/z 50–2000, 3) m/z 200–4000; **Linear dynamic range**: Under typical experimental conditions, at least six (6) orders of magnitude; **Polarity switching**: 100 msec between positive and negative; **Scan power**: MSn for n = 1 through 10; **Contact closure**: Start In/Out, Start Out is programmable; **Analog inputs**: One (1) analog Input (0–1 V), One (1) analog Input (0–10 V).


***

![slide 8](LC-MSMS slides_final/Slide8.png)

This decision tree will guide you to the best LC and MS setups for your experiment.

***

![slide 9](LC-MSMS slides_final/Slide9.png)

For 2D separations, the number of fractions can vary depending on the complexity and amount of peptide you have. Typically, we run anywhere from 9-18 fractions, each with a 2 hour C18 analytical separation (so 18-36 hours of analysis time). Longer analysis times usually result in increased proteome depth. The method can easily be varied for more or fewer fractions though. Please consult with the PSR to determine the best setup for your experiment.


***

![slide 10](LC-MSMS slides_final/Slide10.png)

There are two switching valves on the LC system – the 6 port autosampler valve and the 10 port switching valve. These have the same setups for 1D and 2D LC, with the exception that in the 2D LC setup, the outport on the autosampler (position 5) goes to the high pH column instead of the autosampler.

***

![slide 11](LC-MSMS slides_final/Slide11.png)

***

![slide 12](LC-MSMS slides_final/Slide12.png)

The high pH eluate from the [XBridge column](https://www.waters.com/waters/en_US/XBridge-BEH-Columns-for-High-pH-Chromatography/nav.htm?cid=513767&locale=en_US) is diluted with acidic buffer for loading onto the trap. After the 10 min loading step, the valve switches over and loads the sample onto the C18 analytical column. The loading step is longer in the 2D setup (10 min) than the 1D setup (5 min) because it adds extra time for the peptides to elute from the XBridge column, be diluted, then travel to the trap where it is retained.

***

![slide 13](LC-MSMS slides_final/Slide13.png)

After the sample leaves the LC column, it enters the mass spectrometer. Mass specs can be configured to collect data in different ways, depending on the goal of the experiment. In example 1, it starts with a full scan in the orbitrap collecting precursor ion data, then fragments the most abundant precursors (hence the name data dependent) with collision induced dissociation in the ion trap and scans the product ions. If it’s a [TMT experiment](https://github.com/OHSU-Proteomics/TMT_overview_2020), it will undergo these first two steps and then fragment the product ions using HCD, and detect the reporter ions in the orbitrap. This will be the third stage of MS, hence the name MS3. In the second example, the MS is configured for a full scan followed by PRM scans, which isolates a user-selected precursor ion (one at a time), fragments it, and the product ions from that precursor are detected in the orbitrap. In the third example, a full scan is followed by data independent acquisition (DIA), which typically isolates precursors in m/z 20-25 Da windows over a range (eg. m/z 300-1500) and fragments all of the precursors with detection by the orbitrap. 

***

![slide 14](LC-MSMS slides_final/Slide14.png)


***
![slide 15](LC-MSMS slides_final/Slide15.png)

A survey scan, or full MS, allows all of the precursor ions through the quadrupole, no fragmentation occurs, and all of the precursor ions are detected with high resolution in the orbitrap.

***
![slide 16](LC-MSMS slides_final/Slide16.png)

Information from the survey scan is used to selected precursors for isolation for DDA runs. In each MS2 scan, one precursor is selected, fragmented by either HCD or CID, and the product ions detected in the orbitrap.

***
![slide 17](LC-MSMS slides_final/Slide17.png)

As above, the first step is a MS1 survey scan. For the MS2 portion of the experiment, precursors in a m/z 20-25 Da isolation window are selected, fragmented, and the product ions detected in the orbitrap. The next m/z 20-25 Da range would then be selected, fragmented, and product ions isolated, etc., until the entire m/z range is covered. In the above cycle for m/z 300-1500, the DIA portion takes 48 scans, with a MS1 scan being performed usually every 10 scans or so. The total cycle time is ~3 sec.

***
![slide 18](LC-MSMS slides_final/Slide18.png)

In the PSR, we do most of our targeted runs on the QExactive HF instrument. The method starts with a survey scan which lets all of the precursor ions through the quadrupole and detects the precursors with high resolution in the orbitrap. In the MS2 portion of the experiment, as shown above, the quadrupole is used to isolate the target precursors of interest (one at a time), fragmentation occurs in the HCD cell, and the product ions are detected in the orbitrap with high resolution. The cycle time for this sequence is 1-2 seconds, depending how many precursor targets there are.

***
![slide 19](LC-MSMS slides_final/Slide19.png)

This slide is included for the sake of completeness, although it isn’t a detection scheme that we routinely set up in our core. SRM/MRM runs are typically performed on triple quadrupole instruments, which we no longer have in the PSR core. 
In these types of experiments, the mass spec targets specific precursor and product ions. Preliminary experiments are required to identify good transitions to monitor, since not every peptide will be detected and not every fragment ion produces good signal. SRM/MRM experiments are most successful when coupled with heavy-labeled standards.

***
![slide 20](LC-MSMS slides_final/Slide20.png)

In the PSR core we use a SPS-MS3 method to analyze our TMT samples. In the first stage of MS, precursors are detected in the orbitrap. After meeting certain selection criteria, the precursor is fragmented by collision induced dissociation (CID) in the ion trap (IT, in MS2), producing product ions. The b ions are always TMT tagged, and the y-ions are only TMT tagged if the C-terminal residue is lysine. From there, the top 10 ions are sent to the ion routing multipole (IRM) where they undergo higher energy collisional dissociation (HCD), which fragments the TMT tag releasing the reporter ions into the orbitrap for eventual detection.
Please refer to the [TMT quantitation slide deck](https://github.com/OHSU-Proteomics/TMT_overview_2020) and [an example](https://github.com/OHSU-Proteomics/squirrel_platelets_TMT_2020) for more information on TMT experiments.

***
![slide 21](LC-MSMS slides_final/Slide21.png)

Although the core routinely performs DDA, PRM and DIA type experiments, we are able to set up different MS detection schemes as well. Please consult the PSR staff if you have a different approach that you are interested in trying.

***

Thank you!
