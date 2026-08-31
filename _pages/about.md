---
permalink: /
title: "High-Density Hall Thruster Research"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello, I'm Nadine! I'm originally from Germany, where I did my undergraduate and master's studies in Aerospace Engineering at the University of Stuttgart. I'm now pursuing my PhD in Japan.

You can find a full list of my papers under [Publications](/Research/publications/), the conferences and workshops I've presented at under [Academic Presentations](/Research/talks/), and a more personal, day-to-day look at what experimental life in the lab is actually like under my [Experimental Diary](/Research/experimental-diary/).

Below you'll find a short introduction to my research and what I'm working on during my PhD.

**Space Propulsion Systems**
------
For over 60 years, humanity has pursued space exploration to better understand the universe and gain insight into our solar system.

The majority of satellites in Earth orbit, serving applications such as telecommunications, Earth observation, and navigation, still rely on chemical propulsion systems. 
Despite significant technological advancements, chemical propulsion remains widely used because of its high thrust capability and technological maturity. 
However, its relatively low mass-specific power density, $$\alpha$$, limits the acceleration that can be achieved for a given spacecraft mass and available power:

$$
\alpha=\dfrac{P}{m}=\dfrac{1}{2}\dfrac{Fc_e}{m}=\dfrac{1}{2}ac_e
$$

A mission is defined in part by its required change in velocity, $$\Delta v$$, which determines the necessary exhaust velocity, $$c_e$$, through the Tsiolkovsky rocket equation, 
as well as the required acceleration, $$a$$, through the kinematic equations. Since $$\alpha$$ relates these two parameters, increasing the mass-specific power density enables 
higher acceleration and/or exhaust velocity for a given spacecraft mass and available power.

Electric propulsion systems generally offer much higher $$\alpha$$ values than chemical propulsion systems, making them particularly advantageous for long-duration missions. 
Their high exhaust velocities allow spacecraft to achieve large changes in velocity while consuming significantly less propellant, at the expense of much lower thrust.

This has contributed to the growing adoption of electric propulsion in modern spacecraft. In particular, the increasing number of large satellite constellations has 
driven demand for efficient, compact, and reliable propulsion systems for orbit raising, station keeping, and end-of-life disposal. Companies such as SpaceX, Boeing, 
and Blue Origin have contributed to this development through the deployment of increasingly capable spacecraft and satellite systems incorporating electric propulsion technologies.



**Hall Thruster Trends**
------
Electric propulsion systems are generally categorized according to their primary acceleration mechanism as electrothermal, electrostatic, or electromagnetic propulsion. 
This research focuses on Hall-effect thrusters, which are generally classified as electrostatic propulsion devices. Hall thrusters use crossed electric and magnetic fields 
to ionize a propellant—traditionally xenon—and accelerate the resulting ions axially to generate thrust. The magnetic field primarily acts on the electrons, restricting their 
axial motion and enabling the formation of a Hall current, while the electric field accelerates the ions toward the exhaust.

In conventional Hall thrusters, the acceleration process is predominantly governed by electrostatic forces. However, as the plasma density increases, the interaction between 
the plasma and magnetic field becomes increasingly important, and magnetohydrodynamic (MHD) effects can become significant. This introduces a stronger dependence of the plasma 
behavior and thruster performance on the magnetic-field strength and distribution.

Hall thrusters have been investigated and operated for space applications since the early days of electric propulsion. Their high specific impulse and efficient long-duration 
operation make them attractive for applications such as station keeping, orbit raising, and deep-space missions. However, the widespread use of xenon has also motivated extensive 
research into alternative propellants. Xenon offers favorable properties for Hall thruster operation, but its limited availability and relatively high cost can become significant 
considerations, particularly for large-scale applications.

A wide range of alternative propellants has therefore been investigated. These include other noble gases such as krypton and argon, condensable propellants such as iodine, 
metals such as magnesium and bismuth, and molecular gases including $$CO_2$$, $$O_2$$, and $$N_2$$. Among these alternatives, argon is particularly attractive because of its abundance and low cost. 
However, its lower atomic mass and higher ionization energy compared with xenon make efficient operation more challenging. Improving the performance of argon Hall thrusters therefore 
requires approaches that can compensate for these unfavorable properties.

<img src="/Research/images/HallThruster_TAL_2_svg.svg" alt="Hall Thruster" style="width: 100%; max-width: 1000px; height: auto; display: block; margin: auto;" />

Figure 1: The diagram illustrates the key components and physical processes within a Hall thruster. A discharge voltage $$V_D$$ is applied between the cathode and anode, establishing an axial electric field $$E$$. 
Electrons emitted by the cathode are confined by a radial magnetic field $$B$$ generated by coils and permanent magnets, causing them to undergo gyration and drift around the magnetic field lines. 
These electrons collide with neutral propellant atoms, producing ions through electron-impact ionization. The resulting ions are accelerated primarily in the axial direction by the electric field, generating thrust.

**High-Density Argon Hall Thruster**
------
This research investigates argon as a propellant for Hall thrusters because of its abundance, low cost, and potential to reduce the cost of electric propulsion for future space missions. 
A major challenge associated with argon is its relatively low propellant utilization efficiency ($$\eta_u$$), which results primarily from its higher ionization energy compared with xenon. 
The propellant utilization efficiency can be approximated by the ratio of the ion mass flow rate ($$\dot{m}_i$$) to the total propellant mass flow rate ($$\dot{m}_A$$), or, under a simplified 
ionization model, by the relationship between the ionization-region length ($$L_i$$) and the ionization mean free path ($$\lambda_i$$):

$$
\eta_u=\dfrac{\dot{m}_i}{\dot{m}_A}=1-e^{-L_i/\lambda_i}.
$$

A longer ionization region relative to the ionization mean free path increases the probability of ionization and therefore improves propellant utilization. The objective of this research is to 
improve the $$\eta_u$$ of argon Hall thrusters and thereby increase their thrust ($$T$$).

One approach is to reduce the ionization mean free path, $$\lambda_i$$, by increasing the particle density in the discharge channel. Since the ionization mean free path decreases with 
increasing neutral particle density ($$n_n$$), the propellant mass-flow density can be increased by reducing the thruster's channel cross-sectional area ($$A_c$$) while maintaining a 
comparable total mass flow rate. This provides a route toward high-density Hall-thruster operation.

At sufficiently high plasma densities, the interaction between the plasma and magnetic field becomes increasingly important, and the acceleration process can exhibit stronger MHD characteristics. 
In this regime, the magnetic field can have a more pronounced influence on the plasma acceleration and, consequently, on the resulting thrust.

**Development of a High-Density Hall Thruster**
------

To experimentally investigate this approach, I developed a new high-density Hall thruster, **RAIJIN30**. RAIJIN30 was developed by scaling down the channel cross-sectional area of the existing 
RAIJIN66 thruster by a factor of 2.7. This increases the propellant mass-flow density while preserving the fundamental operating principle of the Hall thruster.

<img src="/Research/images/RAIJIN30.JPG" alt="RAIJIN30 high-density Hall thruster" style="width: 100%; max-width: 1000px; height: auto; display: block; margin: auto;" />

Figure 2: RAIJIN30 operating with argon. The smaller discharge channel was designed to increase the propellant mass-flow density and investigate high-density Hall-thruster operation.

The thruster was experimentally operated with argon over a range of discharge voltages and magnetic-field strengths. Compared with RAIJIN66, RAIJIN30 demonstrated improved performance at 
comparable discharge powers. In particular, the high-density configuration produced higher thrust and substantially improved anode efficiency.

<img src="/Research/images/Comparison_R66_R30_TP_over_Isp.png" alt="Comparison of RAIJIN30 and RAIJIN66 performance" style="width: 100%; max-width: 1000px; height: auto; display: block; margin: auto;" />

Figure 3: Comparison of the thrust-to-power ratio of RAIJIN30 (R30) and RAIJIN66 (R66) as a function of specific impulse. RAIJIN30 generally achieves a higher thrust-to-power ratio than RAIJIN66 across 
the investigated operating range. The green and orange trend lines correspond to different propellant mass-flow densities, illustrating the performance improvement obtained by increasing the propellant density.

The experimental results show that RAIJIN30 achieved higher thrust at comparable discharge power, while also improving anode efficiency compared with RAIJIN66. 
The increased thrust-to-power ratio demonstrates the potential of high-density operation to improve the performance of argon Hall thrusters.

These experiments provide an experimental basis for investigating high-density operation and the increasing influence of magnetic fields and MHD effects in Hall thrusters. RAIJIN30 also provides a 
platform for studying how thruster scaling, propellant density, and magnetic-field strength can be combined to improve the performance of alternative-propellant Hall thrusters.