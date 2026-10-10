# Cosine Effect and Velocity Measurement

## Overview
This repository contains the documentation, data, and analysis for an experimental physics investigation exploring the impact of the **cosine error (or cosine effect)** on velocity measurements obtained from ultrasonic motion detectors. 

Originally intended to utilize an HB100 Doppler microwave radar and Arduino setup, the methodology was pivoted to use a **Vernier Motion Detector 2** paired with **Vernier Logger Pro 3** to examine angular dependence in a controlled laboratory setting.

---

## Research Question
> *To what extent does the angle of incidence between a moving object and the motion sensor affect the measured velocity?*

---

## Key Experimental Details

* **Independent Variable:** Angle of incidence of the ultrasound beam ($0^\circ, 5^\circ, 10^\circ, 15^\circ, 20^\circ, 25^\circ, 30^\circ$), altered in fixed increments using printed protractor paper[cite: 7, 8, 17].
* **Dependent Variable:** Measured speed calculated via the cosine effect formula and manual distance-time processing[cite: 7, 19].
* **Controlled Variables:** 
  * Constant velocity of a LEGO train cart maintained via a microcontroller motor module[cite: 7, 8, 13].
  * Dimensions and foil-wrapping of the reflecting object to maintain consistent reflectivity[cite: 7, 8, 14].
  * Linear motion along the track toward the motor[cite: 8].
* **Apparatus & Materials:** 
  * Vernier Motion Detector 2 (ultrasonic sensor operating at 40 measurements/second)[cite: 8, 9, 10].
  * Vernier Logger Pro 3 software[cite: 11].
  * LEGO train set modified with cotton balls and an aluminum-foil-wrapped cylindrical reflector from a pen to minimize extraneous cross-sectional reflections[cite: 13, 14, 15].
  * Large umbrella screen used to block background disturbances[cite: 16].

---

## Summary of Findings

* **Theoretical Deviation:** The investigation observed that measured velocity decreased with a decreasing angle of incidence (increasing cosine value), which diverged from the standard theoretical cosine error model ($v_{measured} = v_{actual} \cdot \cos(\theta)$)[cite: 5, 25, 28].
* **Statistical Analysis:** A low percentage error (~3%) was found between predicted and observed values when compared to the baseline $0^\circ$ speed[cite: 24, 25].
* **Correlation Strength:** A moderate-to-low correlation ($R^2 \approx 0.49$) indicated considerable data scatter and numerical noise[cite: 24, 25].
* **Error Sources:** Identified systematic and random errors include unverified terminal velocity convergence over the short track length, limitations in sensor resolution/undisclosed software smoothing algorithms, and multi-surface reflection from the apparatus[cite: 25, 26, 27, 28].

---

## Document Structure
The full academic report is available in this repository under [Cosine Effect and Velocity.pdf](Cosine%20Effect%20and%20Velocity.pdf), covering:
1. **Introduction & Background Information** (Velocity kinematics and Cosine Error)[cite: 2, 3, 4, 5]
2. **Methodology & Variables**[cite: 2, 6, 7]
3. **Materials** (HB100 Radar, Vernier Motion Detector 2, Logger Pro, Train Set, Screen)[cite: 2, 8, 9, 11, 13, 16]
4. **Procedure & Recorded Data**[cite: 2, 17, 18, 20]
5. **Data Processing & Uncertainties** (IQR outlier removal, protractor/velocity uncertainties, graphing)[cite: 2, 20, 21, 22, 23, 24]
6. **Analysis & Conclusion** (Systematic/random errors, real-world ADAS implications, and personal reflection)[cite: 2, 25, 26, 27, 28, 29]

---

## Author & Context
* **Subject:** Physics (Group 4: Experimental Sciences)
* **Word Count:** ~3,476 words