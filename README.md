# SKILL LAB PRATICAL HACKATHON

## Final Project README

> **Project Weight:** 100%  
> **Team Size:** 4/3 students  
> **Project Duration:** 8 hours  
> **Total Time Available:** 32 effort-hours per team  
> **Project Type:** Playful, interactive, technology-based experience

---

# Before you begin

## Fork and rename this repository

After forking this repository, rename it using the format:

`SKILLLAB_PROR-2026-TeamName`

### Example

`SKILLLAB_PROR-2026-AuroWizards`

Do not keep the default repository name.

---

# How to use this README

This file is your team’s **working project document**.

You must keep updating it throughout the build period.  
By the final review, this README should clearly show:

- your idea,
- your planning,
- your design decisions,
- your technical process,
- your build progress,
- your testing,
- your failures and changes,
- your final outcome.

## Rules

- Fill every section.
- Do not delete headings.
- If something does not apply, write `Not applicable` and explain why.
- Add images, screenshots, sketches, links, and videos wherever useful.
- Update task status and weekly logs regularly.
- Use this file as evidence of process, not only as a final report.

---

# 1. Team Identity

## 1.1 Studio / Group Name: Axiom Works

`Project^2`

## 1.2 Team Members

| Name           | Primary Role                    | Secondary Role | Strengths Brought to the Project |
| -------------- | ------------------------------- | -------------- | -------------------------------- |
| `Vamika Kaushik` | `[Electronics / Coding / App ]` | `Documentation`  | `Documentation, Gift of Gab `|
| `Nandini Gupta`  | `[Electronics / Fabrication]`   | `[Coding]`     | `Material Handling, Hardware`    |
| `Param Anam` | `[Electronics / Coding / App ]` | `Documentation`  | `Documentation, Gift of Gab `|
| `Ruchi Ahuja`  | `[Electronics / Fabrication]`   | `[Coding]`     | `Material Handling, Hardware`    |

<img width="1280" height="960" alt="WhatsApp Image 2026-04-27 at 12 10 16 PM" src="https://github.com/user-attachments/assets/0951c388-1604-453d-b274-ccc0f6605a20" />

## 1.3 Project Title

`"Line Follower"`


"<img width="955" height="504" alt="title-card (1)_edited" src="https://github.com/user-attachments/assets/0a1e5c2c-a4f0-4559-b7ac-efb862d08250" />



## 1.4 One-Line Pitch

`A smart navigation robot that eliminates manual driving by following programmed paths using IR sensing`

## 1.5 Expanded Project Idea

This project is about an autonomous vehicle designed to detect and follow a predefined path that is usually a black line on a white surface. Our project uses
sensors and microcontrollers like shrike lite and IR sensor for various processes. The core idea of this project is to read small RC chasis with Infrared sensors that read the contrast between the line and the background. These sensors send signals to shrike lite which processes the data and sens it to LN298 motor driver which runs the motors.

This project blends concepts from robotics,embeded systems and control theory which makes it educational and practical. In future we are planning to add features like speed modes, wireless manual override via bluetooth for hybrid RC control. This project has real world relevance in places like warehouses, delivery robots and industrial transport system where line following logic is often used for navigation as it is more efficient.

---

# 2. Philosophy Fit

## 2.1 Experience, Not Social Problem

This module does **not** require your project to solve a large social problem.

You are allowed to build:

- toys,
- games,
- interactive objects,
- playful machines,
- kinetic artifacts,
- humorous devices,
- strange but delightful experiences,
- things that are entertaining to use or watch.



# 3. Inspiration

## 3.1 References

List what inspired the project.

| Source Type | Title / Link

Industrial Automation:	Automated Guided Vehicles (AGVs) in warehouses
Real-world Application:
Factory conveyor and path-guided transport systems

What Inspired You                                                                         
A line-following robot is inspired by the idea of making a machine that can move on its own without being controlled all the time. It follows a line on the ground like a guide, similar to how factory robots or delivery robots follow fixed paths. The project is made to understand how a robot can use sensors to see the path, make simple decisions, and correct its movement automatically.|

## 3.2 Original Twist

What makes your project original?
What makes this project original is that it goes beyond a basic line-following robot. Instead of only moving automatically on a fixed path, it also includes Bluetooth control, which allows the user to manually operate the robot whenever needed. This gives the system flexibility to switch between automatic and manual modes depending on the situation. In addition, the project focuses on better engineering design by separating the motor power supply from the control circuit, which improves stability and reduces common issues like resets or interruptions. By combining sensors, motor control, and wireless communication in a single system, the project becomes more practical, reliable, and closer to real-world robotic applications rather than just a simple beginner-level model.


---

# 4. Project Intent

## 4.1 User Journey 

Describe exactly how a user will use the project.Make it a story
**Response:**  
Its early morning in a small warehouse in smallville,trucks have just finished unloading boxes of medicines and electronics. All of them need to be sorted by the end of the day. Instead of a large automated system this warehouse uses a line follower which is nibble and cna lift heavy loads. This robot is designed for making internla transport easy and quick. 
A worker named Rohan switches it on.The robot sits at a marked starting point on the floor, right next to a loading station. A thin black tape line runs across the warehouse floor like a guiding path, splitting into branches that lead to different zones dispatch, cold storage, packing, and returns. Rohan places items on the robot and now the robot starts to begin with a switch activted by rohan. It doesn’t need a remote control for direction. Instead, its sensors constantly read the black line beneath it. The warehouse floor becomes its map, and the line becomes its instructions.
A forklift passes nearby. The robot pauses for a split second to stabilize its reading, then continues once the path is clear. It doesn’t get confused, because its system is simple and reliable: follow the line, correct errors instantly, keep moving.
At one point, the path curves sharply near a storage rack. The robot slows down automatically to maintain balance, then regains speed on the straight section. The package remains steady on top. within a few minutes the robot completes its job and rohan resets it.
the warehouse is fully sorted within hours saving time and labour
                                                  |



---

# 5. Definition of Success

## 5.1 Definition of “Usable”

For our RC Line Follower robot, “usable” means that the system is not just working in ideal conditions, but is practical, reliable, and easy to operate in real-world or near-real-world environments where line-based navigation is required.

A usable RC Line Follower always:
1.Easy Operation
The user should be able to start and use the robot with minimal effort—typically by switching it ON or selecting a mode. No complex setup or technical adjustments should be required during normal use.

2. Reliable Line Detection
The robot must consistently detect and follow the black line on different surfaces without frequent errors, even when there are curves, junctions, or slight lighting changes.

3. Stable Movement Under Load
It should move smoothly while carrying a small payload (like a parcel or object) without losing balance or deviating from the path.

4. Correct Decision-Making at Junctions
If the path includes splits or turns, the robot should correctly follow the intended route based on pre-programmed logic or sensor input without manual intervention.

5. Minimal Human Intervention
Once started, the system should operate autonomously until it reaches its destination, requiring human input only for start, stop, or mode selection.

6. Consistency Across Repeated Runs
The robot should perform the same task multiple times with similar accuracy and timing, proving it is dependable rather than случай (random) in behavior.

7. Safe and Controlled Operation
The movement should be controlled enough to avoid collisions, sudden jerks, or instability, making it safe for use in indoor environments like labs, warehouses, or model industrial setups.


## 5.2 Minimum Usable Version

What is the smallest version of this project that still delivers the core experience?

  The smallest version of this is a 4-wheel IR-sensor robot that follows a single closed black line loop autonomously using basic left-right correction logic.


## 5.3 Stretch Features

What features are nice to have but not essential?

Some of the nice to have non essential features are:
1.PID Control:
Makes movement smoother and reduces zig-zagging on curves.
2.Speed control:
Allows slow turns and fast straight movement
3.Gradual acceleration/deceleration:
Prevents jerky starts and stops.
4.Junction detection and decision logic
Choosing left/right/straight at splits.
5.Multiple path memory or routing logic
Following different pre-set routes.
6.Start/stop markers on the track
Detecting special zones using sensor patterns.

---

# 6. System Overview

## 6.1 Project Type

Check all that apply.

- [x] Electronics-based

- [x] Mechanical

- [x] Sensor-based

- [ ] App-connected

- [x] Motorized

- [ ] Sound-based

- [ ] Light-based

- [ ] Screen/UI-based

- [x] Fabricated structure

- [ ] Game logic based

- [x] Installation

- [ ] Other:

## 6.2 High-Level System Description

Explain how the system works in simple terms.

Include:

- input,
- processing,
- output,
- physical structure,
- app interaction if any.

Input:
The system receives input from IR sensors placed at the front of the robot. These sensors detect the black line on the surface by sensing the difference between black and white areas.
Processing:
The microcontroller reads the sensor signals and decides the movement of the robot. If both sensors detect the line, the robot moves forward. If one sensor moves off the line, the controller adjusts motor speed to correct the direction and bring the robot back on track.
Output:
The output is the movement of the robot. The DC motors respond to the controller’s signals by moving the wheels left, right, or forward, allowing the robot to follow the line.
Physical Structure:
The system is built on a small chassis that holds the motors, wheels, sensors, battery, and controller. The sensors are placed at the front for accurate line detection, and the motors are fixed to the sides for movement control.
App Interaction (if any):
In the basic version, there is no app involved. The robot works autonomously based on pre-programmed instructions. (Optional advanced versions may include Bluetooth or mobile app control, but it is not required for core operation.)

## 6.3 Input / Output Map

| System Part                              | Type            | What It Does                                                               |


---

# 7. Sketches and Visual Planning

## 7.1 Concept Sketch

Add an early sketch of the full idea.

**Insert image below:**  
`[Upload image and link here]`

Example:

```md

```



## 7.2 Labeled Build Sketch

Add a sketch with labels showing:

- structure,
- electronics placement,
- user touch points,
- moving parts,
- output elements.

**Insert image below:**  
`[Upload image and link here]`
<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/95637f31-b4e7-4427-a9e1-4b63fbeb0ac5" />

## 7.3 Approximate Dimensions

| Dimension        | Value   |
| ---------------- | ------- |
| Length           | `18 cm` |
| Width            | `15 cm` |
| Height           | `10cm`  |
| Estimated weight | `500 g` |

---

# 8. Electronics Planning

## 8.1 Electronics Used

| Component                 | Quantity | Purpose                               |
| ------------------------- | --------:| ------------------------------------- |
| `[ESP32]`                 | `1`      | `[Main controller]`                   |
| `[L298N Motor Driver]`    | `1`      | `[Control Motors]`                    |
| `[BO Motors]`             | `2`      | `[Rotate wheels]`                     |
| `[Buck Converter]`        | `1`      | `[Power ESP32]`                       |
| `[Li Ion Battery Pack]`   | `2`      | `[Power]`                             |
| `[Projector]`             | `1`      | `[Display obstacles]`                 |
| `Camera (Webcam / Phone)` | `1`      | `[Tracks car position using markers]` |

## 8.2 Wiring Plan

Describe the main electrical connections.

**Response:**  
`The ESP32 is connected to the motor driver (L298N) using four GPIO pins (18,19; 22,23) to control motor direction (IN1, IN2, IN3, IN4). Two PWM-capable pins (ENA and ENB; 25 and 26) are connected to control the speed of each motor.

The motors are connected to the output terminals of the motor driver. The motor driver is powered directly by the battery pack (higher voltage), while the ESP32 receives regulated 5V from the buck converter.

All components share a common ground to ensure stable operation. The projector and camera are connected to the laptop, which handles tracking and game logic separately.`

## 8.3 Circuit Diagram

Insert a hand-drawn or software-made circuit diagram.

**Insert image below:**  
`[Upload image and link here]`
<img width="867" height="1156" alt="" src="" />


# 9. Power Plan

| Question         | Response                                                                                                                                          |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Power source     | `Battery (Li-ion pack)`                                                                                                                           |
| Voltage required | `~6–8.4V for motors (via driver), stepped down to 5V for ESP32 (buck converter)`                                                                  |
| Current concerns | `Motors can draw high current under load, which may cause voltage drops affecting ESP32 and WiFi stability`                                       |
| Safety concerns  | `Avoid over-discharging Li-ion batteries, ensure proper voltage regulation, prevent short circuits, and secure wiring to avoid loose connections` |

---

# 10. Software Planning

## 10.1 Software Tools

| Tool / Platform                | Purpose                                        |
| ------------------------------ | ---------------------------------------------- |
| `[MicroPython]`                | `Control ESP32`                                |
| `[Python/PyGame/OpenCV]`       | `Track markers, game logic, create projection` |
| `[Fusion/Blender/Illustrator]` | `[Prototyping structure]`                      |
|                                |                                                |

## 10.2 Software Logic

Describe what the code must do.

Include:

- startup behavior,
- input handling,
- sensor reading,
- decision logic,
- output behavior,
- communication logic,
- reset behavior.

**Response:**  
`

- **Startup behavior:**  
  The ESP32 initializes motor pins, PWM control, and starts a WiFi access point with a web server. The laptop initializes camera input, tracking system, and projection mapping.
- **Input handling:**  
  Movement commands are received from the laptop (pygame sends http requests)
- **Sensor reading:**  
  The camera continuously captures frames, and OpenCV detects ArUco markers to determine the car’s position and orientation.
- **Decision logic:**  
  The system maps the car’s position into a virtual coordinate system and checks for nearby obstacles or collisions. If movement is valid, the command is allowed; if not, it is blocked or replaced with a feedback action (like a slight shake).
- **Output behavior:**  
  The ESP32 drives the motors using PWM signals to control speed and direction. The projector displays the updated game environment, including obstacles, targets, and feedback visuals.
- **Communication logic:**  
  The laptop sends HTTP requests (e.g., `/forward`, `/left`) to the ESP32 over WiFi. The ESP32 parses these commands and executes motor actions.
- **Reset behavior:**  
  If no command is received within a short timeout, the ESP32 stops the motors. The game resets when a level is completed or restarted.`

## 10.3 Code Flowchart

Insert a flowchart showing your code logic.

Suggested sequence:

- start,
- initialize,
- wait for input,
- read input,
- decision,
- trigger output,
- repeat or reset,
- error handling.

**Insert image below:**  
<img width="1600" height="1200" alt="image" src="" />
<img width="1600" height="1200" alt="image" src="" />




# 11. Bill of Materials

## 11.1 Full BOM

| Item                             | Quantity | In Kit? | Need to Buy? | Estimated Cost | Material / Spec               | Why This Choice?          |
| -------------------------------- | --------:| ------- | ------------ | --------------:| ----------------------------- | ------------------------- |
| `[ESP32]`                        | `1`      | `Yes`   | `No`         | `0`            | `38 Pin ESP32`                | `[To control components]` |
| `[Motor Driver]`                 | `[1]`    | `[Yes]` | `[No]`       | `0`            | `[LN296]`                     | `[To drive both motors]`  |
| `[DC Motors and wheel]`          | `[2]`    | `[No]`  | `[Yes]`      | `[150]`        | `[BO Motors and 6 cm wheels]` | `[high torque motors]`    |
| `[Buck Converter]`               | `[1]`    | `[No]`  | `[Yes]`      | `[75]`         |                               |                           |
| `[Li-ion batteries with holder]` | `[1]`    | `[No]`  | `[Yes]`      | `[200]`        |                               |                           |

## 11.2 Material Justification

Explain why you selected your main materials and components.

**Response:**  
`DC motors (BO motors) were chosen instead of servos or steppers because the system requires continuous rotation for movement rather than precise angular control (Previously, we were considering using steppers as we were planning on tracking movement on the ESP using its relative position from an origin, but since we're using a camera now, this is not required). A motor driver (L298N) was used to allow bidirectional control and speed variation using PWM.`


## 11.3 Items You chose

| Item                 | Why Needed               | Purchase Link | Latest Safe Date to Procure | Status       |
| -------------------- | ------------------------ | ------------- | --------------------------- | ------------ |
| `BO Motors + Wheels` | `Drive system for car`   | `robu.in`     | `15th April`                | `[Received]` |
| `Buck Converter`     | `Stable power for ESP32` | `local store` | `before testing`            | `[Received]` |
| `Li-ion Batteries`   | `Portable power`         | `local store` | `before testing`            | `Recieved`   |

## 11.4 Budget Summary

| Budget Item           | Estimated Cost              |
| --------------------- | ---------------------------:|
| Electronics           | `[400]`                     |
| Mechanical parts      | `[200]`                     |
| Fabrication materials | `[0 (Available on campus)]` |
| Purchased extras      | `[0]`                       |
| Contingency           | `[300]`                     |
| **Total**             | `[900]`                     |

## 11.5 Budget Reflection

If your cost is too high, what can be simplified, removed, substituted, or shared?

**Response:**  

---

# 12. Planning the Work

## 12.1 Team Working Agreement

Write how your team will work together.

Include:

- how tasks are divided,
- how decisions are made,
- how progress will be checked,
- what happens if a task is delayed,
- how documentation will be maintained.

**Response:**  


## 12.2 Task Breakdown

| Task ID | Task                    | Owner    | Estimated Hours | Deadline     | Dependency | Status |
| ------- | ----------------------- | -------- | ---------------:| ------------ | ---------- | ------ |
| T1      | `[Finalize concept]`    | `[Both]` | `2`             | `1st April`  | `None`     | `Done` |


## 12.3 Responsibility Split

| Area                 | Main Owner | Support Owner |
| -------------------- | ---------- | ------------- |
| Concept              | `[Gopal]`  | `[Kader]`    |
| Electronics          | `[]`       | `[]`     |
| Coding               | `[]`       | `[]`     |
| Mechanical build     | `[]`       | `[]`    |
| Testing              | `[]`       | `[]`    |
| Documentation        | `[]`       | `[]`     |

---

# 13. 2 hour Milestones

## 13.1 8-hour Plan

### Bi Hour 1 — Plan and De-risk

Expected outcomes:

- [x] Idea finalized
- [x] Core interaction decided
- [x] Sketches made
- [x] BOM completed
- [x] Purchase needs identified
- [ ] Key uncertainty identified
- [x] Basic feasibility tested

### Bi Hour 2 — Build Subsystems

Expected outcomes:

- [x] Electronics tests completed
- [ ] CAD / structure planning completed
- [ ] App UI started if needed
- [x] Mechanical concept tested
- [x] Main subsystems partially working

### Bi Hour 3 — Integrate

Expected outcomes:

- [x] Physical body built
- [x] Electronics integrated
- [x] Code connected to hardware
- [ ] App connected if required
- [x] First playable version exists

### Bi Hour 4 — Refine and Finish

Expected outcomes:

- [x] Technical bugs reduced
- [x] Playtesting completed
- [x] Improvements made
- [x] Documentation completed
- [x] Final build ready

## 13.2  Update Log

| Week   | Planned Goal   | What Actually Happened | What Changed   | Next Steps     |
| ------ | -------------- | ---------------------- | -------------- | -------------- |
| Week 1 | `[Write here]` | `[Write here]`         | `[Write here]` | `[Write here]` |
| Week 2 | `[Write here]` | `[Write here]`         | `[Write here]` | `[Write here]` |
| Week 3 | `[Write here]` | `[Write here]`         | `[Write here]` | `[Write here]` |
| Week 4 | `[Write here]` | `[Write here]`         | `[Write here]` | `[Write here]` |

---

# 14. Risks and Unknowns

## 14.1 Risk Register

| Risk                                                            | Type         | Likelihood | Impact   | Mitigation Plan                                                                       | Owner                |
| --------------------------------------------------------------- | ------------ | ---------- | -------- | ------------------------------------------------------------------------------------- | -------------------- |
| WiFi connection between laptop and ESP32 becomes unstable       | `Technical`  | `Medium`   | `High`   | Keep ESP32 close, ensure stable power supply, reduce network load, add fail-safe stop | `[Gopal]`           |


## 14.2 Biggest Unknown Right Now

What is the single biggest uncertainty in your project at this stage?

**Response:**  


---

# 15. Testing 

## 15.1 Technical Testing Plan

| What Needs Testing     | How You Will Test It                                                                 | Success Condition                                                                                    |
| ---------------------- | ------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------- |
| `[Wifi connection]`    | `[Check if motor spins via app button]`                                              | `[Both motors accurately respond to wifi signals]`                                                   |
                       |
## 15.2 Testing and Debugging Log

| Date          | Problem Found                         | Type         | What You Tried                                | Result               | Next Action                                    |
| ------------- | ------------------------------------- | ------------ | --------------------------------------------- | -------------------- | ---------------------------------------------- |
| `18th April`  | `Car not balancing properly`          | `Mechanical` | `Add low-friction caster support to one side` | `Worked`             | `improve caster structure`                     |


## 15.3 Playtesting Notes

| Tester      | What They Did                        | What Confused Them                    | What They Enjoyed                         | What You Will Change                          |
| ----------- | ------------------------------------ | ------------------------------------- | ----------------------------------------- | --------------------------------------------- |
| `Gopal` | `Tried navigating through obstacles` | `Some obstacles ewren't clear enough` | `Liked projection + real car interaction` | `Add a slight red highlight around obstacles` |


---

# 16. Build Documentation

## 16.1 Fabrication Process

Describe how the project was physically made.

Include:

- cutting,
- 3D printing,
- assembly,
- fastening,
- wiring,
- finishing,
- revisions.

**Response:**  
`The fabrication process involved designing, manufacturing, assembling, and refining both the physical structure and electronic integration of the system.`

`Design (CAD Modeling):
The initial model was created using CAD software, where components were designed based on the actual dimensions of the electronic parts. This ensured accurate fitting and minimized errors during assembly.
Cutting (Laser Cutting):
The designed parts were fabricated using laser cutting techniques. Sheets were cut precisely according to the CAD model to create the structural base and mounts for components.`

`Components were fixed using adhesives and mechanical supports. Certain parts were intentionally kept modular (not permanently fixed) to allow easy replacement and modification of electronics.
Surface Finishing:
Some parts were sanded to smooth rough edges after cutting. Sawdust mixed with adhesive was used to fill gaps and uneven edges, improving structural finish. The final structure was then painted for better aesthetics and durability.`

`Environment Setup (Dark Room Fabrication):
To enhance projection visibility, a controlled dark environment was created using Z-boards, paper sheets, and bedsheets. This minimized external light interference and improved projection clarity.
Revisions and Iterations:
Multiple adjustments were made throughout the process, including refining alignment, improving structural stability, repositioning components, and optimizing the interaction between the physical car and projected environment.`

## 16.2 Build Photos

Add photos throughout the project.

Suggested images:

- early sketch,
- prototype,
- electronics testing,
- mechanism test,
- app screenshot,
- final build.
- <img width="960" height="1280" alt="WhatsApp Image 2026-04-24 at 9 46 02 AM (1)" src="https://github.com/user-attachments/assets/74baa570-5770-483e-be6d-d2f03386e37c" />





# 17. Final Outcome

## 17.1 Final Description

Describe the final version of your project.

**Response:**  


## 17.2 What Works Well



## 17.3 What Still Needs Improvement


## 17.4 What Changed From the Original Plan

How did the project change from the initial idea?

**Response:**  


---

# 18. Reflection

## 18.1 Team Reflection

What did your team do well?  
What slowed you down?  
How well did you manage time, tasks, and responsibilities?

**Response:**  


## 18.2 Technical Reflection

What did you learn about:

- electronics,
- coding,
- mechanisms,
- fabrication,
- integration?

**Response:**  


## 18.3 Design Reflection

What did you learn about:

- designing ,
- delight,
- clarity,
- physical interaction,
- understanding,
- iteration?

**Response:**  


## 18.4 If You Had One More hour

What would you improve next?

**Response:**  

` `

---

# 19. Final Submission Checklist

Before submission, confirm that:

- [x] Team details are complete
- [x] Project description is complete
- [x] Inspiration sources are included
- [x] Sketches are added
- [x] BOM is complete
- [x] Purchase list is complete
- [x] Budget summary is complete
- [x] Mechanical planning is documented if applicable
- [ ] App planning is documented if applicable
- [x] Code flowchart is added
- [x] Task breakdown is complete
- [x] Weekly logs are updated
- [x] Risk register is complete
- [x] Testing log is updated
- [x] Playtesting notes are included
- [x] Build photos are included
- [x] Final reflection is written
<img width="1131" height="1600" alt="image" src="" />

---


---


