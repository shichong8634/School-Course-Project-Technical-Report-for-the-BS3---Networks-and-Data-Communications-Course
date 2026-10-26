# School-Course-Project-Technical-Report-for-the-BS3---Networks-and-Data-Communications-Course
A theoretical analysis and visualization of the Shannon–Hartley theorem and the Nyquist maximum data rate model.
Overview

This project investigates how bandwidth, signal levels, and signal-to-noise ratio (SNR) affect the theoretical transmission limits of communication channels.

The analysis compares two fundamental models in data communications:

Nyquist model: Estimates the maximum data rate of an ideal, noiseless channel.

Shannon model: Estimates the theoretical channel capacity of a noisy channel.

Numerical calculations and two-dimensional plots are used to examine the relationships between the relevant channel parameters.

## Objectives

Study the mathematical formulations of the Nyquist and Shannon models.

Analyse the effects of bandwidth and signal levels on the Nyquist maximum data rate.

Examine the effects of bandwidth and SNR on Shannon channel capacity.

Visualize the calculated relationships using line charts.

Compare the assumptions and theoretical limits of the two models.

## Mathematical Models

1. Nyquist Maximum Data Rate
2. Shannon Channel Capacity

## Methodology
The analysis uses selected theoretical parameter values.

Nyquist Model

Bandwidth: 1,000–10,000 Hz, in increments of 1,000 Hz

Signal levels: 2, 4, 8, 16, and 32

Shannon Model

Bandwidth: 1,000–10,000 Hz

SNR: 0–40 dB

The corresponding data rates and channel capacities are calculated using the equations above. The results are organized in spreadsheets and visualized using OriginPro 2024b.

## Key Findings

Under the Nyquist model, the theoretical maximum data rate increases linearly with bandwidth when the number of signal levels is fixed.

Increasing the number of signal levels increases the Nyquist data rate logarithmically.

Under the Shannon model, channel capacity increases linearly with bandwidth at a fixed SNR.

Channel capacity increases with SNR according to the logarithmic Shannon relationship when SNR is expressed as a linear ratio.

The two models describe different theoretical limits and rely on different channel assumptions.

## Repository Structure



## Tools

Microsoft Excel — numerical data organization and calculation

Origin 2024 — scientific plotting and visualization

## Limitations

This project presents theoretical calculations based on mathematical models and selected parameter values. It does not include measurements from physical communication equipment or empirical network throughput tests. Actual system performance may be affected by noise, interference, coding overhead, and implementation constraints.

## Academic Context

This project was developed as part of the Networks and Data Communications coursework in the BSc Computing Science programme at Griffith College Dublin.

## References

Not yet finished; currently consulting reference materials.
