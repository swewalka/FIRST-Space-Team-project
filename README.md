# TU Space Team FIRST Project: TEAM Schubkraftverweigerer

Welcome to the repository for our FIRST (First Introduction to Rockets and Space Team) project. This repository contains the structural designs, flight simulations, and engineering decisions for our four-person team's mid-power model rocket.

## Project Overview
The objective of this project is to design, manufacture, and launch a model rocket that strictly complies with the TU Space Team's technical requirements. The rocket is engineered to fly on an AeroTech H238T solid rocket motor while maintaining a simulated altitude of under 600 meters and ensuring a safe descent using a redundantly deployed recovery system.

## Repository Structure

* `guidelines/` - Contains the official FIRST project documentation.
  * `reviews-and-technical-requirements.pdf` - Core project constraints and review checklists.
  * `how-to-rocketry-UoF.pdf` - Best practices for manufacturing and component integration.
  * `flightsimulation_guide` - A detailed Document about the basic physics of rocketry and flight simulation. 
* `design_decisions.md` - Detailed architectural breakdown of our airframe, E-Bay, and recovery system layout.
* `rocket_layout.svg` - Visual schematic of the rocket's internal layout and separation points.
* `team_schubkraftverweigerer_simulation.ork` - The primary OpenRocket flight simulation file. 

## Key Engineering Constraints
* **Motor:** AeroTech H238T (29mm)
* **Target Altitude:** ≤ 600m
* **Stability Margin:** 1 - 2 calibers (strictly > 0.1 * rocket length)
* **Recovery:** Main parachute deployed at apogee via flight computer, backed up by a mechanical engine ejection charge

## Getting Started
Note: If you have never worked on (model) rockets before it is highly recommended to read ![this](guidelines/flightsimulation_guide.pdf) guide on Rocketry and flight simulation. 

To view and modify the rocket simulation:
1. Download and install [OpenRocket](https://openrocket.info/).
2. Open the `.ork` file located in the root of this repository.
3. Reference `design_decisions.md` and `rocket_layout.svg` to understand the structural rationale behind the selected dimensions, component masses, and the stacking order.