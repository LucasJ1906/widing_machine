## DIY - Winding Machine for Outrunner Brushless Motor - In progress (90%) 

**Description:**
This repository presents a project for designing a winding machine for outrunner BLDC motors. This is a 3-axis machine: the first axis is used to rotate the stator during the winding process, the second axis is for vertical movement, and the third axis is for horizontal movement during the winding process.
![ass_001 v30](https://github.com/LucasJ1906/widing_machine/assets/37951624/287bddeb-d321-4d39-b6f6-b9f47fc642d0)
![IMG_20240505_104845](https://github.com/LucasJ1906/widing_machine/assets/37951624/d523e70c-f75c-4939-bb87-a1abb70f15e5)

**Main Technical Characteristics:**
- Motor type: Outrunner BLDC/PMSM motor (possible to wind inrunner motor with minor adjustments)
- Motor stator maximum dimensions: Diameter - 70 mm, Height - 30 mm (can accommodate larger motors with adjustments)
- Capability to perform both concentrated and distributed winding
- Utilizes NEMA 17 stepper motors, 8 mm axes, and ball screws (standard parts from 3D printer environments)
- Main parts are manufacturable using additive manufacturing (also possible with milling; contact me if you need drawings).

**Parts List:**

| Part | Qty | Description |
| --- | --- | --- |
| 001 v27 | 1 | Base of the platform which supports the motor stator that can turn with a pulley connected to stepper 1. The platform includes the motor mount of stepper 2 that enables the horizontal movement of part 007 with a belt. |
| 002 v1 | 1 | Motor stator mount system |
| 003 v2 | 1 | Motor stator adaptor part |
| 004 v4 | 4 | Linear axis 8mm * 30 mm used for vertical and horizontal movement (could be cut) |
| 005 v6 | 2 | Feet of the platform |
| 006 v4 | 1 | End of the platform, this part brings a pulley to be connected to the belt of stepper 2 for horizontal translation |
| 007 v18 | 1 | Horizontal moving platform |
| 008 v13 | 1 | Vertical moving platform |
| 009 v5 | 1 | Top of the vertical moving platform |
| 010 v5 | 2 | Belt hook attached to the horizontal moving platform (007) |
| 011 v4 | 1 | Endless screw stop-fall part |
| 012 v5 | 1 | Winding tool mounting part |
| 013 v2 | 1 | Standard Part |
| 3766N14_Fixed Alignment Linear Ball Bearing | 4 | Standard Part |
| 6624K67_Ball Screw | 1 | Standard Part |
| 8mm Mil Araba - Step v1 | 4 | Standard Part |
| 91290A079_Alloy Steel Socket Head Screw | 8 | Standard Part |
| 91502A111_Blue-Dyed Zinc-Plated Alloy Steel Socket Head Screw | 12 | Standard Part |
| Laminated stator v2 | 1 | Stator to wind |
| NEMA 17 with T5 Pulley v2 | 3 | Standard Part |
| T5 Pulley | 3 | Standard Part |
| pan cross head_am_B18.6.7M - M3 x 0.5 x 5 Type I Cross Recessed PHMS --5N | 12 | Standard Part |
| socket button head cap screw_am_B18.3.4M - 3 x 0.5 x 5 SBHCS --N | 3 | Standard Part |
| std_RS22087 v2 | 4 | Standard Part |
| std_eq_nema_17 v4 | 1 | Standard Part |

**Electronics and Software:**
The electronic setup is based on an Arduino UNO and a basic CNC shield. Please view the material list for exact references. The code will be made available soon.

**Improvements:**

*CAD:*
- Enhance positioning and position holding designs
- Improve winding wire guide for smoother wire feeding
- Reinforce winding tool to increase rigidity (currently too flexible, but works fine at low speeds)

*Software:*
- Add support for various motor configurations
- Implement auto-calibration feature for precise winding
- Develop a user-friendly interface for controlling the winding process

Coming soon:
- Detailed assembly instructions
- Video demonstration of the winding process
- Troubleshooting guide and maintenance tips
