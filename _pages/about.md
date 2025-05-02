---
permalink: /
title: "High-Density Hall Thruster Research"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

**Space Propulsion Systems**
------
For over 60 years, humanity has pursued space exploration to better understand the universe, and gain insights into our solar system. The majority of satellites in Earth orbit, primarily serving purposes such as telecommunications, Earth observation, and navigation. Despite technological advancements, most satellites in orbit (approximately 60–70%) still rely on chemical propulsion systems, which are relatively inefficient due to their limited mass-specific power density $$\alpha$$:

$$\alpha=\dfrac{P}{m}=\dfrac{1}{2} \dfrac{Fc_e}{m}=\dfrac{1}{2} ac_e$$

Defining a mission involves determining the required change in velocity $$\Delta v$$ , which in turn defines the necessary exhaust velocity $$c_e$$  through the Tsiolkovsky rocket equation and the required acceleration $$a$$  via the kinematic equation. Given these constraints, the only parameter that can simultaneously increase both $$c_e$$  and $$a$$ is $$\alpha$$ . Electric propulsion systems typically exhibit higher $$\alpha$$  values, making them especially advantageous for long-duration missions due to their lower propellant consumption and higher specific impulse. In recent years, there has been a clear trend toward the utilization of electric propulsion, driven in part by advances from companies such as SpaceX, Boeing, and Blue Origin. They have made significant progress in deploying satellite constellations and spacecraft utilizing electric propulsion technologies.


**Hall Thruster Trends**
------
Electric propulsion systems are generally categorized into three types: thermoelectric acceleration, electrostatic acceleration, and magnetohydrodynamic (MHD) acceleration. This research focuses on Hall-effect thrusters, which are typically considered as electrostatic acceleration devices. These thrusters use the Hall effect by utilizing electric and magnetic fields to ionize a propellant—typically xenon—and accelerate the resulting ions to generate thrust. In high-density Hall thrusters, the strong interaction between electric and magnetic fields can give rise to additional MHD effects, with more dependency of performance from the magnetic field.

Hall thrusters have been in use since the early days of space exploration. Despite their advantages—such as high specific impulse and efficient long-term operation—their broader application in large-scale missions has been limited, primarily due to the high cost and limited availability of xenon gas. As a result, significant research in the field has focused on identifying alternative propellants. These include other noble gases such as krypton and argon, condensable options like iodine, metals such as magnesium and bismuth, and even molecular gases including CO₂, O₂, and N₂. However, to date, no propellant has proven to be a fully viable substitute for xenon [2].

![HallThruster](/images/HallThruster_TAL_svg.svg)
<img src="../images/HallThruster_TAL_svg.svg" alt="Hall Thruster" style="max-width: 100%; height: auto;" />



This study investigates the use of argon as a propellant, due to its abundance, low cost, and potential to make space travel more economically accessible. A major drawback of argon, however, is its low propellant utilization efficiency ($$\eta_u$$), which can be approximated by the ratio of the ion mass flow rate ($$\dot{m}_i$$) to the total propellant mass flow rate ($$\dot{m)_a$$), or alternatively, by the relationship between the ionization region length ($$L_i$$) and the ionization mean free path ($$\lambda_i$$), as shown below:

$$ \eta_u=\dfrac{\dot{m}_i}{\dot{m}_A}=1-e^{(-L_i/λ_i)}.$$

The objective of this research is to improve the $$\eta_u$$  of Argon Hall thrusters and, in doing so, increase the resulting thrust ($$T$$). This is pursued by decreasing $$\lambda_i$$ , which can be achieved by increasing the plasma density ($$n_e$$). The proposed approach involves reducing the thruster's channel cross-sectional area ($$A_c$$), thereby increasing the neutral particle density ($$n_n$$). This increase in density is expected to shift the thruster operation further into the MHD regime, enhancing the influence of the magnetic field and making the thrust more strongly dependent on the electromagnetic force.
...
