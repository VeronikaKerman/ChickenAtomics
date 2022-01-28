Chicken Gas Nuclear Thermal Rockets
=========

This patchset allows using liquid ammonia in NTRs. Liquid Ammonia requires
smaller tanks for the same propellant mass, boils at higher temperature, which
saves cryostat electricity usage. And gives higher thrust in NTRs.

It is mainly for players who want to use beautiful mods of Nertea, but do not 
want their game to be too technical and number-y like Interstellar ex.

Dennis Nikitaev predicts that ammonia propellant would result in 2x more thrust 
at 41% Isp. KSP-IE uses 1.4x thrust and 63% Isp. As a compromise, this patchset 
uses 1.6-1.7x thrust and 60% Isp.

All multimode NTRs featuring LH2/LF switching are converted to LH2/NH3.

The Neptune, Scylla and Poseidon LA-NTRs are stripped of their oxidizer 
augmented mode and given NH3 modes instead.

The Deliverance lightbulb rocket has been extended with ammonia mode.

The two later patches can be easily extended to other engines if desired
just by adding another part name in the PART line.

Lastly, LqdAmmonia configuration has been added to procedural liquid tank,
if Rational Resources is not installed.

Due to incompatibility of ModuleSystemHeatFissionEngine with B9 based fuel 
switching, more than two modes can't be added and in-flight switching can't be 
disabled. Players looking for more propellant choices can look into 
Interstellar. There are other interesting propellants, but Ammonia is the least 
proplematic of them in terms of corrosion, sooting, reactivity, and 
performance.

Requires: CRP, KerbalAtomics.

Recommends: Procedural Parts, Rational Resources.

Supports: SMURFF.
