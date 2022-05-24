Chicken Gas Nuclear Thermal Rockets
=========

This patchset allows using liquid ammonia in NTRs. Liquid Ammonia requires
smaller tanks for the same propellant mass, boils at higher temperature, which
saves cryostat electricity usage. And gives higher thrust in NTRs.

It is mainly for players who want to use beautiful mods of Nertea, but do not 
want their game to be too technical and number-y like [Interstellar extended][3].

As a bonus, mass and thrust of those engines are patched with SMURFF 
factors, if the mod is installed.

[Dennis Nikitaev][1] featured in [project rho][2] predicts that ammonia 
propellant would result in 2x more thrust at 41% Isp. KSP-IE uses 1.4x thrust 
and 63% Isp. As a compromise, this patchset uses 1.6-1.7x thrust and 60% Isp.

[1]: https://web.archive.org/web/20220120112222/https://nets2021.ornl.gov/wp-content/uploads/gravity_forms/12-b63a96649a525ab5aa39d607840d9d9f/2021/04/In-Situ-Propellant-for-NTP-Engines.pdf
[2]: http://www.projectrho.com/public_html/rocket/enginelist2.php
[3]: https://forum.kerbalspaceprogram.com/index.php?/topic/172026-*

Nerv and Cherenkov NTRs featuring LH2/LF switching are converted to LH2/NH3.

The Neptune, Scylla and Poseidon LA-NTRs are stripped of their oxidizer 
augmented mode and given NH3 modes instead. The Stubber was left unmodified.

The Deliverance lightbulb rocket has been extended with ammonia mode.

The patches can be easily extended to other engines if desired
just by adding another part name in the PART line.

Lastly, LqdAmmonia configuration has been added to procedural liquid tank,
if Rational Resources is not installed.

Due to incompatibility of ModuleSystemHeatFissionEngine with B9 based fuel 
switching, more than two modes can't be added and in-flight switching can't be 
disabled. Players looking for more propellant choices can look into 
Interstellar. There are other interesting propellants, but Ammonia is the least 
proplematic of them in terms of corrosion, sooting, reactivity, and 
performance.

Requires: CRP,
[KerbalAtomics](https://spacedock.info/mod/710/Kerbal%20Atomics).

Recommends:
[Procedural Parts](https://forum.kerbalspaceprogram.com/index.php?/topic/204080-*/),
[Rational Resources](https://forum.kerbalspaceprogram.com/index.php?/topic/184875-*/).

Supports: [SMURFF](https://forum.kerbalspaceprogram.com/index.php?/topic/117992-*/).

By Veronika Kerman
