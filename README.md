ML-Based Design & Optimization of Bandpass Frequency Selective Surfaces (FSS)
This repository contains the design, simulation, and machine learning optimization of a high-selectivity Bandpass Frequency Selective Surface (FSS) tailored for C-band RADAR applications.
Project Overview
  The project focuses on developing a spatial filter that allows specific frequencies (6–8 GHz) to pass with near-zero loss    while reflecting out-of-band signals. By utilizing a Slot-Cut Polygonal Loop unit cell, the design achieves high resonance   stability and polarization insensitivity, making it ideal for stealth technology and RADAR Cross Section (RCS) management.
Key Features
  Miniaturized Unit Cell: Compact 10 x 10 mm footprint (approx. lambda/4 at 7 GHz), eliminating unwanted grating lobes.
  High-Performance Substrate: Utilizes Rogers RO3203 (ceramic-filled PTFE) to prevent thermal runaway and dielectric           breakdown in high-power RADAR environments.
  ML Optimization: Features a simplified structural design specifically optimized for deployment on standard hardware,         reducing variable complexity for training.
  High Precision: The ML-predicted response achieves an impressive error margin of only 0.5% compared to full-wave EM          simulations.
Machine Learning Integration
  To overcome the computational intensity of traditional EM solvers, this project employs a machine learning model to          predict the S11 response. This allows for:
                    Rapid Design Iteration: Instantly predicting performance based on physical dimensions.
                    Manufacturing Tolerance: Designing structures that remain stable despite minor etching errors.
                    Future ScopeActive FSS: Integrating PIN diodes or Varactors for real-time frequency tuning to counter                        frequency-hopping RADAR.
                    Hybrid Absorbers: Incorporating resistive elements to act as Radar Absorbent Material (RAM) at higher                        frequency bands (X or Ku).
