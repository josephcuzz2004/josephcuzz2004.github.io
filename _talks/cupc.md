---
title: "Feedback System for Laser Intensity Stabilization"
collection: talks
type: "Conference Oral Presentation"
permalink: /talks/cupc
venue: "University of British Columbia"
date: 2024-10-26
location: "Vancouver, British Columbia, Canada"
---

[More information here](https://cupc.cap.ca/2024-attendee-information/2024-student-presentations/)

We have constructed a feedback system for stabilizing the intensity of diode lasers for experiments in precision metrology. The system uses an analog circuit to generate a correction signal that regulates an acousto-optic 
modulator (AOM) so as to stabilize the output power of the laser. A portion of the light diffracted by the AOM is incident on a photodetector. The signal from this photodetector is compared to a setpoint 
voltage using a subtractor, where the output is then amplified and integrated with a time constant that can be as small as 100 μs. The resulting signal controls a radio frequency (RF) attenuator that
modulates a voltage-controlled oscillator driving the AOM. In this scheme, if the laser power fluctuates, the RF signal to the AOM changes so as to stabilize the laser intensity. We have also 
constructed a sample and hold module that engages the feedback loop when a control (TTL) pulse is applied and disengages the feedback when the control pulse is off. With the feedback engaged, we
find that the laser intensity can be stabilized on time scales ranging from 100 μs to 20 ms. The standard deviation of the intensity fluctuations is typically reduced by more than a factor of 3. We find
a similar reduction in laser intensity fluctuations when the feedback loop is operated with the sample and hold module, suggesting that our results can be extended to pulsed laser experiments.

[View the slides (PPTX)]({{ '/files/JOSEPH_CUZZUPOLI_SLIDES (1).pptx' | relative_url }})

