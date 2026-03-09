# Semiconductor Basics

**Course Name:** [Analog electronics 1]  
**Assignment Title:** Assignment 2.1 – Semiconductor Basics  
**Student Name:** [MD Mehrab Hasan Rafy]  
**Student ID:** [s2515903]  
**Tools Used:** ChatGPT, GitHub
## Real Diode Task

**Diode Name:** 1N4148  
**Manufacturer:** ON Semiconductor  
**Application:** Fast switching in signal and digital circuits
## Ideal vs Real Diode Comparison

The ideal diode model and the real diode model behave differently in the DC sweep simulation. The ideal diode turns on immediately when it is forward biased, so it does not show a noticeable turn-on voltage drop. In contrast, the practical 1N4148 diode requires about 0.6 V to 0.7 V before significant current begins to flow.

The current behavior is also different. In the ideal model, current starts abruptly once the diode is on. In the real diode model, the current increases gradually and then rises rapidly as the voltage reaches the forward conduction region. This reflects the actual physical behavior of semiconductor diodes.

Ideal models are still useful because they make circuit analysis easier and help explain the basic operation of a circuit. They are often used in introductory analysis and quick design calculations. However, ideal models become inaccurate when the actual voltage drop, power loss, or exact current behavior matters. In real circuits, practical diode models are better because they more closely match how real components behave.
