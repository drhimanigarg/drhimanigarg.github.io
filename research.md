---
layout: default
title: Research
permalink: /research/
---

# Research

My research sits at the intersection of turbulence physics and thermal energy engineering. The common thread is high-fidelity numerical simulation — Large Eddy Simulation (LES), Direct Numerical Simulation, and VOF multiphase modelling — used to answer questions that experiments alone cannot reach.

## Turbulent heat transfer over rough and additively manufactured surfaces

Additive manufacturing (3D printing) makes it possible to build heat-exchanging components with surface textures no conventional machining can produce — but the resulting roughness changes the turbulence, the drag, and the heat transfer in ways that are still poorly understood. Using LES and DNS, we quantify how roughness height, skewness, and topography shape the near-wall flow and the Nusselt number, including conjugate heat transfer effects and medium-to-high Prandtl number fluids. This work is carried out with industrial partners such as Siemens Energy and academic collaborators at Karlsruhe Institute of Technology (Germany), Atlantic Technological University (Ireland) and Osaka Metropolitan University (Japan).

![Overview of turbulent heat transfer over rough surfaces: roughness topography, temperature roughness function, and turbulent flow structure](/assets/img/roughness-overview.jpg)
*How roughness shapes turbulent heat transfer: surface topography, the temperature roughness function, and the near-wall flow structure.*

<video autoplay muted loop playsinline controls src="/assets/img/roughness-temperature-les.mp4"></video>
*Instantaneous temperature field from our Large Eddy Simulation of turbulent flow over a rough surface.*

**Our publications on this topic:**

- H. Garg, M. Kadivar, <em>LES investigations of heat transfer in a tube with irregular roughness at moderate Prandtl numbers</em>, Int. Commun. Heat Mass Transf. 169, 2025. <a href="https://www.sciencedirect.com/science/article/pii/S0735193325013570">Read the paper</a>
- M. Kadivar, H. Garg, <em>Turbulent heat transfer over roughness: a comprehensive review of theories and turbulent flow structure</em>, Int. J. Thermofluids 26, 2025. <a href="https://www.sciencedirect.com/science/article/pii/S2666202724004075">Read the paper</a>
- H. Garg, G. Sahut, E. Tuneskog, K. Nogenmyr, C. Fureby, <em>Large Eddy Simulations of flow over additively manufactured surfaces: impact of roughness and skewness on turbulent heat transfer</em>, Phys. Fluids 36 (8), 2024. <a href="https://pubs.aip.org/aip/pof/article/36/8/085143/3307738">Read the paper</a>
- H. Garg, L. Wang, C. Fureby, <em>Heat transfer enhancement with additively manufactured rough surfaces: insights from LES</em>, Phys. Fluids 36 (2), 2024. <a href="https://pubs.aip.org/aip/pof/article/36/2/025109/3261818">Read the paper</a>
- H. Garg, L. Wang, G. Sahut, C. Fureby, <em>Large Eddy Simulations of fully-developed turbulent flows over additively manufactured rough surfaces</em>, Phys. Fluids 35 (4), 2023. <a href="https://pubs.aip.org/aip/pof/article/35/4/045145/2885307">Read the paper</a>
- H. Garg, J. Klingmann, K. Nogenmyr, A. Marin, A. Stroh, Y. Kuwata, <em>Local impact of roughness topography on heat transfer in turbulent flow over rough surfaces</em>, Turbulence, Heat and Mass Transfer, Begell House, 2025. <a href="https://www.dl.begellhouse.com/references/1bb331655c289a0a,7224fbfa56c3c688,45d63d4302ad59ab.html?year=2025">Read the paper</a>

*More work on rough-wall turbulence is ongoing — stay tuned for upcoming results!*

## Internal cooling of gas turbine blades

Matrix (lattice-structured) cooling channels are a promising alternative to conventional rib-turbulated cooling passages in turbine blades: the crossing sub-channels continuously redirect and mix the coolant, enhancing heat transfer. We investigate turbulent heat transfer and pressure loss in these geometries using both LES and RANS, aiming at design rules for the next generation of efficient, durable turbine cooling. This project is part of the <a href="https://adtherm.se/">AdTherM competence centre</a>, in which I am one of the key actors of the matrix cooling activity, working in close collaboration with KTH Royal Institute of Technology (Prof. Mihai Mihaescu and PhD student Romain Seppey) and Siemens Energy AB.

![Heat transfer coefficient and pressure ratio along a matrix cooling channel: LES with four subgrid models compared with the experiments of Bunker at Re = 24100](/assets/img/matrix-htc-validation.jpg)
*Quantitative validation: heat transfer coefficient and pressure ratio along the matrix channel from our LES with four subgrid-scale models, compared with the experiments of Bunker (Re = 24 100).*

<video autoplay muted loop playsinline controls src="/assets/img/matrix-lambda2-les.mp4"></video>
*λ₂ vortical structures inside the matrix sub-channels, from our Large Eddy Simulations.*

The work has now also entered the laboratory: our experimental campaign has started, with a test rig up and running at Siemens Energy where we will conduct heat transfer measurements on different 3D-printed matrix cooling geometries, tightly coupled with high-fidelity simulations.

![The matrix cooling test rig at Siemens Energy](/assets/img/matrix-test-rig.jpg)
*The matrix cooling test rig, ready and running at Siemens Energy.*

**Our publications on this topic:**

- H. Garg, R. Seppey, M. Mihaescu, C. Fureby, <em>Turbulent Heat Transfer in Lattice-Structured Matrix Cooling Channels</em>, GT2026-177503, ASME Turbo Expo 2026, accepted in the Journal of Turbomachinery (ASME).
- R. Seppey, H. Garg, M. Mihaescu, <em>Numerical Investigation of Heat Transfer Rates and Pressure Drop in a Matrix Channel for Turbine Blade Internal Cooling</em>, GT2026-176392, ASME Turbo Expo 2026.
- E. Naversten, F. Maletzke, N. Rignell, H. Garg, <em>Steady-state RANS investigation of turbulent heat transfer in matrix cooling channels for gas turbine blades</em>, Case Studies in Thermal Engineering 82, 2026. <a href="https://www.sciencedirect.com/science/article/pii/S2214157X2600465X">Read the paper</a>

*A lot more is coming on this topic — stay tuned!*

## Elastic turbulence and viscoelastic flows

At micro scales, inertia is too weak to generate turbulence — but adding small amounts of elastic polymer to a liquid triggers *elastic turbulence*, a chaotic flow state that dramatically enhances mixing and heat transfer. Building on my PhD work on particle-laden elastic turbulence, we study viscoelastic flows in serpentine microchannels and their potential for cooling and lab-on-a-chip applications.

## Hydrogen technologies and multiphase flow

Water management inside proton exchange membrane (PEM) fuel cells and bubble dynamics in alkaline electrolyzers are two-phase flow problems that decide the efficiency and lifetime of hydrogen energy devices. We perform pore-scale simulations of gas diffusion layers, dynamic contact angle modelling for droplet transport, and channel-scale two-phase studies. This theme is supported by the Hains Foundation project *Hydrogen as a Catalyst for Climate-Neutral Fuels*, and much of the PEM fuel cell work below formed the PhD thesis of my student <a href="https://portal.research.lu.se/en/persons/danan-yang/">Danan Yang</a>, who defended in August 2025.

<video autoplay muted loop playsinline controls src="/assets/img/pemfc-water-generation.mp4"></video>
*Why water management matters: water is continuously generated inside an operating fuel cell — too little dries the membrane, too much floods the pores and blocks the reactant gas.*

![Computational geometry: gas channel and gas diffusion layer assembly, with stochastically reconstructed fibrous GDL microstructures of varying fiber diameter compared with the Freudenberg H2315 material](/assets/img/pemfc-gdl-geometry.jpg)
*Our computational playground: the gas channel–gas diffusion layer (GC–GDL) assembly, and stochastically reconstructed fibrous GDL microstructures with varying fiber diameter, compared against the real Freudenberg H2315 material.*

<div class="video-pair">
  <video autoplay muted loop playsinline controls src="/assets/img/pemfc-gdl-sim1.mp4"></video>
  <video autoplay muted loop playsinline controls src="/assets/img/pemfc-gdl-sim2.mp4"></video>
</div>
*Two-phase flow in GC–GDL assemblies: liquid water invading the fibrous gas diffusion layer and emerging into the gas channel, from our VOF simulations.*

**Our publications on this topic:**

- D. Yang, H. Garg, M. Andersson, <em>A framework for stochastic reconstruction of gas diffusion layers with enhanced fiber morphology modulation and additive incorporation</em>, Mater. Today Commun. 53, 2026. <a href="https://www.sciencedirect.com/science/article/pii/S2352492826006926">Read the paper</a>
- D. Yang, M. Andersson, H. Garg, <em>Pore-scale numerical investigation of water-gas flow and heat transport in gas diffusion layers with varying fiber/additive content and hydrophobicity</em>, Int. J. Heat Mass Transf., 2025. <a href="https://www.sciencedirect.com/science/article/pii/S0017931025011949">Read the paper</a>
- D. Yang, M. Andersson, H. Garg, <em>Effect of fiber curvature on gas diffusion layer two-phase dynamics of a proton exchange membrane fuel cell</em>, Int. J. Hydrogen Energy 85, 2024. <a href="https://www.sciencedirect.com/science/article/pii/S0360319924036966">Read the paper</a>
- D. Yang, P. Fortin, H. Garg, M. Andersson, <em>The influence of bipolar plate hydrophobicity on performance and durability of a proton exchange membrane fuel cell</em>, Int. J. Hydrogen Energy 95, 2024. <a href="https://www.sciencedirect.com/science/article/pii/S0360319924034700">Read the paper</a>
- D. Yang, S. Beale, H. Garg, M. Andersson, <em>Two-phase fluid dynamics in proton exchange membrane fuel cells: counter-flow liquid inlets and gas outlets at the electrolyte-cathode interface</em>, J. Electrochem. Soc. 171 (10), 2024. <a href="https://iopscience.iop.org/article/10.1149/1945-7111/ad7d3d">Read the paper</a>
- D. Yang, H. Garg, M. Andersson, <em>Numerical investigation on two-phase flow pressure drop in cathode channels of proton exchange membrane fuel cells</em>, ECS Trans. 114 (5), 2024. <a href="https://iopscience.iop.org/article/10.1149/11405.0577ecst">Read the paper</a>
- D. Yang, H. Garg, M. Andersson, <em>Numerical simulation of two-phase flow in gas diffusion layer and gas channel of proton exchange membrane fuel cells</em>, Int. J. Hydrogen Energy 48 (41), 2023. <a href="https://www.sciencedirect.com/science/article/pii/S0360319923000162">Read the paper</a>
- D. Yang, H. Garg, S. B. Beale, M. Andersson, <em>Numerical reconstruction of proton exchange membrane fuel cell gas diffusion layer</em>, ECS Trans. 112, 2023. <a href="https://iopscience.iop.org/article/10.1149/11204.0049ecst">Read the paper</a>

## Applied thermal engineering

Beyond fundamental studies, we apply CFD to practical energy systems: solar dryers for food preservation, cooling strategies for industrial processes (Crafoord and Kempe foundation projects), cavitation in hydraulic machines, and premixed flame dynamics with conjugate heat transfer in combustors.

---

## Funding

Current and recent research grants:

- **Hains Foundation** — *Hydrogen as a Catalyst for Climate-Neutral Fuels: Advancing Efficiency in the Energy Transition* (PI, 1.75 MSEK, 2025)
- **Crafoord Foundation** — *Advanced cooling strategies and flow-induced heat transfer enhancement for industrial processes* (PI, 1 MSEK, 2025)
- **Kempestiftelserna** — *Advanced Cooling Strategies and Flow-Induced Heat Transfer Enhancement for Industrial Processes* (Co-PI, two-year postdoc scholarship, 2025)
- **Vinnova** — *Advanced Computing for Sustainable Thermal Management in Industry (AdTherM)* competence centre (co-applicant, 109 MSEK consortium, 2023)
