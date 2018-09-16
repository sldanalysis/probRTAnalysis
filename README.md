# Probabilistic State-Based RT-Analysis of SDFGs on MPSoCs with Shared Memory Communication
This repository provides our UPPAAL models used for our research paper.

UPPAAL stratego 4.1.20 _and_ 4.1.20-4 required for analysis. If 4.1.20 does not work, please use 4.1.20-4 and vice versa.

Use the ClassicTA.xml with UPPAAL-SMC queries for a uniform distribution of execution times.
For normal distribution edit the STA.xml to call the Normal-Function (commented out).
By default, STA.xml uses our time distribution we proposed in the paper.
