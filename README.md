SKILL LAB PRATICAL HACKATHON

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


## 1.2 Team Members

| Name           | Primary Role                    | Secondary Role | Strengths Brought to the Project     |
| -------------- | ------------------------------- | -------------- | --------------------------------     |
| `Vamika Kaushik` | `[Electronics / Coding / App ]` | `Documentation`  | `Documentation, Gift of Gab `    |
| `Nandini Gupta`  | `[Electronics / Fabrication]`   | `[Coding]`       | `Material Handling, Hardware`    |
| `Param Anam`     | `[Electronics / Coding / App ]` | `Documentation`  | `Documentation, Gift of Gab `    |
| `Ruchi Ahuja`    | `[Electronics / Fabrication]`   | `[Coding]`       | `Material Handling, Hardware`    |

<img width="1280" height="960" alt="WhatsApp Image 2026-04-27 at 12 10 16 PM" src="https://github.com/user-attachments/assets/0951c388-1604-453d-b274-ccc0f6605a20" />

## 1.3 Project Title



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
IR sensorx2                                  Sensor            Detects Black Line 
Dc Motorx2                                   Motor             Moves Robot
L298Ns                                       Motor Driver      Controls Motor Power (bridge between motor and microcontroller)                 
Jumper Wires                                 Support           Electrical connection
Shrike Lite                                  Microcontroller   Reads sensor inputs and sends commands to motors
Battery 3.7V                                 Power Supply      Gives power to system       
Battery Holder                               Support           Hold battery securely
RC body                                      Support           Projct Body
Ultrasonic Sensor                            Sensor            Object Detection
---

# 7. Sketches and Visual Planning

## 7.1 Concept Sketch


<img width="1536" height="1024" alt="WhatsApp Image 2026-04-27 at 3 10 09 PM (2)" src="https://github.com/user-attachments/assets/3bfce7b2-13c7-4003-9c12-7350ea98d3fe" />
```



## 7.2 Labeled Build Sketch

<<img width="918" height="1169" alt="WhatsApp Image 2026-04-27 at 3 40 19 PM_edited" src="https://github.com/user-attachments/assets/d71f648b-1600-45c7-8dcc-6bd8847231a0" />
/>

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
| `[Shrike Lite]`           | `1`      | `[Main controller]`                   |
| `[L298N Motor Driver]`    | `1`      | `[Control Motors]`                    |
| `[DC Motors]`             | `2`      | `[Rotate wheels]`                     |
| `[Battery Holder]`        | `1`      | `[Holds Battery]`                       |
| `[9V Battery]`            | `2`      | `[Power]`                             |

## 8.2 Wiring Plan
1. Power Connections:
The battery supplies power to the motor driver and microcontroller.
A common ground (GND) is shared between all components to ensure proper signal flow.

2. Sensor Connections:
The IR sensors are connected to the microcontroller input pins.
They send HIGH/LOW signals based on line detection.

3. Microcontroller Connections:
Acts as the central unit.
Receives input from sensors and sends control signals to the motor driver.

4. Motor Driver Connections:
Connected between the microcontroller and motors.
Receives signals from the controller and controls motor direction and speed.

5. Motor Connections:
Two DC motors are connected to the motor driver outputs.
Left and right motors operate independently for turning.



## 8.3 Circuit Diagram

<![Uploading image.png…]()
/>


# 9. Power Plan

| Question         | Response                                                                                                                                          |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Power source     | `9V Battery`                                                                                                                                      |                              
| Voltage required | `3.3 to 5V for strike lite`                                                                                                                       |
| Current concerns | `Speed is very high,+5V was connected to GND and grounds were not shared between battery and pico `                                                                                                                              |
| Safety concerns  | `Using Pwm to set speed levels,Wires have been reconnected,Grounds are shared`                                                                                                                   |

---

# 10. Software Planning

## 10.1 Software Tools

| Tool / Platform                | Purpose                                        |
| ------------------------------ | ---------------------------------------------- |
| `[C++]`                        | `Control Shrike Lite`                          |
| `[Arduino IDE]`                | `Recieve input,feed output to the motor driver'|
| `[Fusion/Blender/Illustrator]` | `[Prototyping structure]`                      |
|                                |                                                |

## 10.2 Software Logic

Describe what the code must do.

Startup Behavior:
When powered ON, the system initializes all pins, sensors, and motor driver. The robot may pause briefly or indicate readiness before starting movement.

Input Handling:
The code continuously checks inputs from the IR sensors to detect the position of the line under the robot.

Sensor Reading:
IR sensors provide HIGH/LOW signals depending on whether they detect the black line or white surface. These readings are updated in real time.

Decision Logic:
Based on sensor values:

Both sensors on line → move forward
Left sensor off line → turn left
Right sensor off line → turn right
Both off line → stop or search for line

Output Behavior:
The microcontroller sends signals to the motor driver to control motor direction and speed, resulting in forward movement or turning.

Communication Logic:
In the basic version, no external communication is required.

Reset Behavior:
On reset or restart, the system reinitializes and begins from the starting condition, ready to follow the line again.`

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
| `[Shrike Lite]`                  | `1`      | `Yes`   | `No`         | `[379]`        | ``                            | `[To control components]` |
| `[ Motor Driver]`                | `[1]`    | `[Yes]` | `[No]`       | `[91]`         | `[L298N]`                     | `[To drive both motors]`  |
| `[DC Motors and wheel]`          | `[2]`    | `[Yes]` | `[No]`       | `[100]`        | `[BO Motors and 6 cm wheels]` | `[high torque motors]`    |
| `[Battery Holder]`               | `[1]`    | `[Yes]` | `[No]`       | `[40]`         |                               | `[to hold the batteries]` |
| `[3.7V Batteris]`                | `[2]`    | `[Yes]` | `[No]`       | `[75]`         |                               | `[Power Supply]`          |
| `[jumper wirse]`                 | `[40]`   | `[No]`  | `[Yes]`      | `[40]`         |                               | `[Electrical Connections]`| 
| `[IR Sensor]`                    | `[2]`    | `[Yes]` | `[No]`       | `[300]`        |                               | `[Path Detection]`        |
| `[Ultrasonic Sensor]`            | `[1]`    | `[No]`  | `[Yes]`      | `[65]`         |                               | `[Object Detection]`      |
| `[Purchased Extras]`             [ `[3]`    | `[No]`  | `[Yes]`      | `[800]'        |                               | `[Vehicle Body]`          |
| **Total**                                                            | `[1890]`       |


## 11.2 Material Justification
 
Explain why you selected your main materials and components.
1. Microcontroller (Control Unit)
We selected a microcontroller board because it is:
Easy to program and widely supported
Capable of real-time sensor reading and motor control
Affordable for student-level projects
It acts as the brain of the system, making all movement decisions quickly and efficiently.

2. IR Sensors
IR sensors were chosen because:
They can clearly detect contrast between black and white surfaces
They are low-cost and highly reliable for line tracking
They respond quickly, enabling real-time corrections
They form the core input system of the robot.

3. Motor Driver (L298N)
We used a motor driver because:
Microcontrollers cannot directly power motors
It allows control of direction and speed for two DC motors
It is cheap, widely available, and easy to interface
It acts as the bridge between logic and motion.

4. DC Motors
DC motors were selected because:
They are simple, durable, and easy to control
Suitable for low-speed robotic movement
Cost-effective for small-scale robotics
They provide the physical movement of the robot.

5. Chassis (Frame Structure)
We used a lightweight chassis because:
It holds all components in a stable structure
It reduces weight for better movement efficiency
It is easy to assemble and modify
It forms the physical foundation of the robot.

6. Power Source (Battery)
A battery was chosen because:
It provides portable and stable power supply
Supports continuous operation without external connection
Easy to replace or recharge
It ensures the robot remains self-contained and mobile.


## 11.3 Budget Reflection

If your cost is too high, what can be simplified, removed, substituted, or shared?

Our cost is cheaper compared to big machines but even if its not affordable to all as our product is to be bought in bulk we can remodel the rc body using 3D printed bodies or a cheaper base for the rc body 
---

# 12. Planning the Work

## 12.1 Team Working Agreement

The project work will be mainly divided based on skills and interest. One member will handle hardware assembly whereas the other will focus on the software part.Documentation and report writing will be shared between teammates.

1.Decision Making:
All major decisions will be made through group discussion. If there is disagreement, the team will decide based on testing results and majority agreement.

2.Progress Checking:
Progress will be reviewed regularly during short team meetings. Each member will report what they have completed, what is pending, and any issues faced. A simple checklist or timeline will be used to track milestones like “chassis completed,” “sensor working,” and “final testing done.”

3.Delay Handling:
If any task is delayed, other team members will assist to complete it. The workload may be redistributed temporarily to ensure the project stays on schedule. Priority will be given to critical tasks like coding and wiring.

4.Documentation Maintenance:
All work will be documented continuously. This includes circuit diagrams, code updates, testing results, and changes made during development. A shared file will be maintained so that all members have access to the latest version of the project details.

## 12.2 Task Breakdown

| Task ID | Task                    | Owner    | Estimated Hours | Deadline     |  Status |
| ------- | ----------------------- | -------- | ---------------:| ------------ |  ------ |
     1        hardware               vamika           5hours         27 april     complete
     2        software               nandini          2hour          27 april     complete
     3        documentation          param            8hours         27 april     complete
     4        report or ppt          ruchi            2hours         27 april     complete
     5        video                  all              40mins         27 april     complete


## 12.3 Responsibility Split

| Area                 | Main Owner | Support Owner |
| -------------------- | ---------- | ------------- |
| Concept              | `[Nandini]`| `[Vamika]`    |
| Electronics          | `[Ruchi]   | `[Param]`     |
| Coding               | `[Nandini]`| `[Vamika]`    |
| Mechanical build     | `[Vamika]` | `[Nandini]`   |
| Testing              | `[Ruchi]`  | `[Param]`     |
| Documentation        | `[Param]`  | `[Ruchi]`     |

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
- [x] Key uncertainty identified
- [x] Basic feasibility tested

### Bi Hour 2 — Build Subsystems

Expected outcomes:

- [x] Electronics tests completed
- [x] CAD / structure planning completed
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

| hour   | Planned Goal   | What Actually Happened       | What Changed       | Next Steps     |

   1      Topic decision    Many topics were discussed    Topic Finalized       Mapping
   2      Mapping           Basic map was created         Easy to begin         circuit configuration
   3      Circuit Config    All connections were made     Pinconfig was wrong   correcting the pin config
   4      Correction        All connections were right    No more errors        code uploadation
   5      Coding            Code was built and uploaded   Code had errors       error correction
   6      corrections       code was corrected            all erros resolved    testing
   7      testing           project was tested            breadboard was        alternate solution
                                                          overloading the
                                                          project
   8      End               breadboard no longer in use   project is ready      pitching and presenting

# 14. Risks and Unknowns

## 14.1 Risk Register

| Risk                                                            | Type         | Likelihood         | Impact                      | Mitigation Plan                                                 | Owner                |
Ultrasonic sensor drew more power    vamika                        hardware       due to high voltage  circuit shutsdown sometimes  we found an alternate use for                                                                                                                                      breadboard


## 14.2 Biggest Unknown Right Now

What is the single biggest uncertainty in your project at this stage?

rc car works even without power supply sometimes after it is done testing

# 15. Testing 

## 15.1 Technical Testing Plan

| What Needs Testing     | How You Will Test It                                     | Success Condition|
| IR Sensors             | We have used black tape to make a pathway for our RC car | 90% |


## 15.2 Testing and Debugging Log

| Date          | Problem Found                         | Type         | What You Tried                                | Result               | Next Action|
 27 april        breadboard was overloading the project   hardware        tried different power supplies                 did not matter         stopped using                                                                                                                                                     bread board

## 15.3 Playtesting Notes

| Tester      | What They Did                        | What Confused Them                    | What They Enjoyed                         | What You Will Change                          |
| ----------- | ------------------------------------ | ------------------------------------- | ----------------------------------------- | --------------------------------------------- |



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

Cutting:
The chassis base and mounting parts were cut to the required size using acrylic sheets or lightweight board material. Openings were made for motors, sensors, and wiring paths to ensure proper fitting of components.

Assembly:
All mechanical components like motors, wheels, and chassis frame were assembled first. The IR sensors were mounted at the front in a fixed position for accurate line detection, and the battery holder was placed securely on the base.

Wiring:
All electronic connections were made according to the circuit plan. The microcontroller, motor driver, sensors, and motors were carefully connected using jumper wires, ensuring correct polarity and proper grounding.

Finishing:
Loose wires were organized and tied neatly to avoid interference with moving parts. The overall structure was checked for balance, and the wheels were tested for smooth rotation.

Revisions:
After initial testing, minor adjustments were made such as sensor repositioning, wire corrections, and motor calibration. These revisions improved line tracking accuracy and overall performance.

## 16.2 Build Photos






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


