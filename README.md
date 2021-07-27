<h1>Modular Synthesis as an Educational Tool </h1>

<h2>Introduction</h2>
This repository documents my contributions to my Senior Design Capstone project at LSU: Modular Synthesis as an Educational Tool. As a cosponsor of this project, my team set out to create a mixed analog and digital modular synthesizer to be used alongside courses such as Electronics, Signals and Systems, and Digital Signal Processing. Our system strives to be a physical and tangible example of applications of concepts learned in these courses.

- University: LSU
- Year: Fall 2020 & Spring 2021
- Team: 80
- Members:
  - Rafael Alvarez
  - Keri Grevemvberg
  - Taylor LeBlanc
  - Tarik Lopez
  - Kyle Sellers
- Courses: EE 4810 and 4820

<h2> Table of Contents </h2>

 - System Overview
   - My Contribution
 - Digital Multi-Effects (DME)
   - Overview
   - Hardware
   - Software
 - Wireless Control Module (WCM)
   - Overview
   - Hardware
   - Software (Mobile App)
   - Software (Embedded)


<h2>System Overview</h2>
The final system consists of 7 synthesizer modules, a power supply, and a wooden case. The modules included are:

- <strong>Voltage Controlled Oscillator (VCO)</strong> : Generates basic waveforms and allows users to manipulate fundamental frequency
- <strong>Voltage Controlled Filter (VCF)</strong> : High and Low Pass filters allow users to filter out frequency content from frequency rich signals
- <strong>Digital Multi-Effects (DME)</strong> : Processes incoming audio with various digital effects via DSP algorithms
- <strong>Level Control Module (LCM)</strong> : Brings output voltage from other modules down to appropriate level for analysis via National Instruments MyDAQ or active speakers
- <strong>Envelope Generator (EG)</strong> : Produces a control voltage Attack Decay (AD) or Attack Release (AR) envelope for use in manipulating other modules.
- <strong>Sequencer (SEQ)</strong> : Produces repeating pattern of control voltages to create melodies and rhythms
- <strong>Wireless Control Module (WCM)</strong> : Allows users to wireless control parameters via control voltages from a mobile application

<h3>My Contribution</h3>
As the Computer Engineer of the team, my responsibilities were to create the Digital Multi-Effects (DME) and the Wireless Control Module (WCM). Material for each can be found in their respective folders.

<h2>Digital Multi-Effects (DME)</h2>
<h3>Overview</h3>
The Digital Multi-Effects processes a mono audio signal with one of four programmed effects: Distortion, Bitcrusher, Delay, or Reverb. Parameters for each of these effects can be manipulated by a physical knob on the module, or via a control voltage (CV) from another module.
<h3>Hardware</h3>
The design for the DME module is based on the Electro-smith Daisy Patch: 

[Link](https://www.electro-smith.com/daisy/patch)

[Schematic](https://github.com/electro-smith/Hardware/tree/master/reference/daisy_patch)

<h3>Software</h3>

<h2>Wireless Control Module (WCM)</h2>
<h3>Overview</h3>

<h3>Hardware</h3>


<h3>Software (Mobile App)</h3>

<h3>Software (Embedded)</h3>
