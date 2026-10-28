# Engineering screening

Starting requirement sets for engineering roles. Each set is longer than a screen should be: keep the five to seven requirements the work actually depends on, rewrite them in your own words and delete the rest.

## How to use

1. Pick the role set closest to the opening. Add the work-values set if those behaviours matter for the team.
2. Remove requirements the work does not need. Move background that is only helpful down to nice to have.
3. Complete the evidence column for every requirement you keep: what in a CV, application or work example would show it.
4. Calibrate the kept requirements with [screening-calibration.md](screening-calibration.md) before reviewing live applications.

Tool, language and vendor names are examples. Accept equivalent experience unless the stack genuinely requires the named tool.

## Robotics / software engineer

### Software fundamentals

| Requirement | Priority | Evidence to look for |
| --- | --- | --- |
| Writes production code in Python and C++ | preferred | Projects or roles naming both languages, not just coursework |
| Applies object-oriented design | preferred | Code samples or descriptions of class or module boundaries |
| Uses version control and has had code reviewed by others | preferred | Team projects, pull requests, open-source contributions |
| Recognises and applies common design patterns | nice to have | Named patterns tied to a problem they solved |

### Robotics software

| Requirement | Priority | Evidence to look for |
| --- | --- | --- |
| Has written ROS 2 nodes and launch files | hard | ROS 2 projects with their own nodes, not only tutorials |
| Has built something larger than a single-file program | preferred | Multi-module projects, packages or services |
| Integrates open-source components | nice to have | Libraries adopted, wrapped or patched |

### Perception, navigation and control

| Requirement | Priority | Evidence to look for |
| --- | --- | --- |
| Has worked on computer vision, navigation or control software | preferred | Projects naming the problem and their part in it |
| Knows a navigation stack or behaviour trees (e.g. Nav2) | nice to have | Configured or extended a navigation or task-orchestration framework |
| Has fused localisation sources (GNSS, IMU, odometry) | nice to have | State-estimation work with named sensors |

### Systems and ownership

| Requirement | Priority | Evidence to look for |
| --- | --- | --- |
| Builds and runs software on Linux | hard | Daily Linux development, deployment to Linux targets |
| Has debugged on real hardware, not only in simulation | preferred | Field tests, lab work, physical robot or device projects |
| Uses containers and robotics tooling (e.g. Docker, Foxglove) | nice to have | Containerised builds, recorded data inspection |

## Embedded / mechatronics engineer

### Embedded software

| Requirement | Priority | Evidence to look for |
| --- | --- | --- |
| Writes embedded C or C++ | hard | Firmware projects with named targets |
| Has worked with a real-time operating system | preferred | Tasks, scheduling or timing constraints described |
| Uses version control | preferred | Repositories, team firmware projects |

### Electronics and protocols

| Requirement | Priority | Evidence to look for |
| --- | --- | --- |
| Programs microcontrollers (e.g. ESP32, STM32, RP2040) | hard | Boards named alongside what the firmware did |
| Uses bus protocols such as I2C, SPI and CAN | preferred | Peripherals or devices integrated over a named bus |
| Has integrated sensors and actuators hands-on | preferred | Physical builds, test rigs, wiring and bring-up |
| Knows serial or industrial protocols (UART, Modbus, RS-485) | nice to have | Industrial equipment or legacy device integration |

### PCB design

| Requirement | Priority | Evidence to look for |
| --- | --- | --- |
| Has designed a PCB | preferred | Named design tool and board purpose |
| Has taken a PCB through manufacturing | nice to have | Ordered, assembled and debugged a board; problems named |

### Motor and actuator control

| Requirement | Priority | Evidence to look for |
| --- | --- | --- |
| Has tuned motors or drives with closed-loop feedback | preferred | Steppers, servos or AC drives with encoders; tuning described |
| Has configured an industrial drive or motor controller (e.g. a VFD) | nice to have | Parameter setup on industrial equipment |

### Systems and safety

| Requirement | Priority | Evidence to look for |
| --- | --- | --- |
| Builds and runs software on Linux | preferred | Linux tooling, host-side scripts, single-board computers |
| Has debugged hardware outside their own desk setup | preferred | Field, lab or customer-site debugging |
| Follows electrical safety practice around mains power | preferred | Protective devices, emergency stops, safety procedures named |
| Has basic ROS 2 experience | nice to have | Any ROS 2 node or launch file, even a simple one |

## Work values (any role)

These are rarely visible in a CV. Screen lightly, then ask every candidate the same interview questions about them.

| Requirement | Priority | Evidence to look for |
| --- | --- | --- |
| Ownership: carries work end to end, including integration | preferred | Delivered a feature or system through to use, not only a part |
| Autonomy: makes informed decisions and then communicates them | preferred | Decisions they made alone and how they told others |
| Pragmatism: delivers the core quickly, then refines | preferred | Examples of scoping down or shipping a first version |
| Communication: clarifies the task before, during and after the work | preferred | Written explanations, questions asked, handovers |
| Documentation: leaves work others can understand without them | preferred | READMEs, design notes, diagrams |

## Practical conditions

Mark these hard only when the condition is confirmed and the reason is written down in [hiring-intake.md](hiring-intake.md).

| Requirement | Priority | Evidence to look for |
| --- | --- | --- |
| Can work at the stated location and schedule | Complete here | Stated in the application or confirmed in a screening call |
| Can start by the stated date | Complete here | Stated in the application or confirmed in a screening call |

## Motivation and reflection questions

**Application question:** What do you know about our work, and why does this role interest you?

**Written reflection** (100–150 words each; pick three to five):

- What work are you most proud of, and why?
- Which mistake do you most regret, and what changed afterwards?
- What was hard for you to learn, and how did you get through it?
- When have you been happiest at work, and why?
- When have you been unhappiest at work, and why?
- Who has mentored you, and what did you learn?
- Who have you mentored, and what did you learn from them?
- Which qualities do you most value in colleagues?

The reflection questions are adapted from Bryan Cantrill, [Assessing software engineering candidates](https://bcantrill.dtrace.org/2018/10/05/assessing-software-engineering-candidates/) (2018).

## Confirm before use

- [ ] Five to seven requirements remain, each tied to the work.
- [ ] Hard requirements are few and each has a written reason.
- [ ] Named tools are required only where equivalents genuinely would not do.
- [ ] The evidence column is complete for every requirement.
- [ ] Work-values questions are the same for every candidate.
- [ ] The requirements were calibrated with [screening-calibration.md](screening-calibration.md).

## Limits and decision boundaries

These documents support human review. Agreement does not make a criterion fair, lawful or accurate. Vendor observations are not certification or proof of production quality. Do not publish filled-in worksheets containing candidate or internal business data. The agenda and worksheets are working documents, not claims about application features.

[code-sample-review.md](code-sample-review.md) · [README](README.md)
