# FIRST Project: Design Decisions

Mandatory requirements are defined in [Reviews and Technical Requirements](guidelines/reviews-and-technical-requirements.pdf). The other reference documents, including *How to Rocketry*, provide guidance and tips.

## Airframe and Payload

- **Body tubes:** GFK laminate, 70 mm inner diameter. The larger diameter provides more space for cushioning the egg payload and helps limit flight altitude through increased aerodynamic drag.
- **Motor:** AeroTech H165R.
- **Fin can:** [3D-printed assembly](<3d models/Fin Can.step>) with an airfoil-like profile. The geometry balances aerodynamics, printability, and structural strength.

## Motor Mount and Boat Tail

- **Centering rings:** GFK.
- **Boat tail:** 3D-printed aft section attached by a printed screw thread. It also retains the motor casing; no separate aft retaining ring is used.
- **CAD:** [External thread](<3d models/Boat Tail External Thread.step>) and [internal thread](<3d models/Boat Tail Internal Thread.step>).

## Recovery and Avionics

- **Arrangement, aft to forward:** Motor mount → parachute compartment → E-Bay → nose cone with egg payload.
- **Deployment:** Flight-computer-triggered black powder charge, with the motor ejection charge as backup. Both act on the recovery compartment to separate the airframe and deploy the parachute.
- **E-Bay:** Sealed against deployment-charge fumes, with four 2 mm static pressure holes for the barometric altimeter.
- **Ignition wiring:** WAGO terminals connect the deployment charge to the flight computer; wire feedthroughs maintain the E-Bay seal.

## Materials and Design Files

- All body tubes: GFK laminate.
- Motor centering rings: GFK.
- All 3D-printed parts: PLA.
- [OpenRocket simulation](rocket_simulation.ork) and [CAD models](<3d models/>) document the current geometry and configuration.
