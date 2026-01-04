# General-Accretion-Disk-Solver
This notebook computes the innermost stable circular orbit (ISCO), specific angular momentum, specific energy, and angular velocity for timelike particles in arbitrary spacetimes, including those with an external magnetic field. Within the Novikov-Thorne framework, it then calculates the accretion disk's energy flux density, temperature, and thermal luminosity.

It is noteworthy that rotating black hole spacetimes with an external magnetic field are often non-integrable, rendering analytical expressions for particle motion unavailable and posing a challenge for computing Novikov-Thorne accretion disk properties. This notebook overcomes this obstacle by constructing interpolation functions to obtain discrete data of particle motion, thereby establishing a viable method for calculating Novikov-Thorne accretion disks in non-integrable spacetimes.

For further details, please refer to the code comments or the following arXiv article:

Influence of the external electromagnetic field on the properties of the Novikov-Thorne accretion disk in Kerr spacetime, arXiv: 2507.14599.
