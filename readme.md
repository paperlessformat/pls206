These are Mai's code for working with JKR (Johnson-Kendall-Roberts) adhesion measurements.

The Bayesian Fitting Work of Adhesion take in a file with the Load in Newtons and a contact Radius in micromenter. It spit out a plot of a^3
versus Load with a fitting line. It also gives the Effective Modulus (E*) and the work of adhesion. 
For JKR measurements of PDMS-PDMS, your E* should be 1.0 - 2.5 MPa and your work of adhesion should be ~ 44 mJ/m^2.

The Newton Rings Approximation take an a file with the relative order of rings and the diameter of the rings in micrometers. The rings should
be from the dark rings, measuring the inner radius. It will give the approximate radius of curvature of the PDMS hemisphere in micromenters.
For JKR measurements, your radius of curvature should be 0.5 - 1.75 mm. 
