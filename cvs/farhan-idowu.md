# Farhan Idowu
London, UK (hybrid) | farhan.idowu@example.com | +44 7700 900512 | github.com/fidowu-robotics

## Summary
Embedded/Robotics engineer, 8 yrs, C/C++ down to the metal + ROS/ROS2 up top, comfortable owning a system end to end - bootloader, RTOS scheduling, sensor drivers, nav stack integration. Have shipped stuff on actual robots (warehouse AMRs, a delivery bot pilot, industrial arms) not just sim. Strong on real-time constraints & debugging weird hardware timing issues at 2am. Also do a bit of PCB bring-up when needed although not primary skill.

## Skills
- **Languages:** C, C++ (11/14/17), Python (tooling/scripts), some Rust (evaluating for driver layer)
- **RTOS:** FreeRTOS, Zephyr, VxWorks (legacy project), task scheduling, priority inversion debugging, interrupt latency tuning
- **Robotics:** ROS1 (Noetic), ROS2 (Foxy/Humble), Nav2, tf2, MoveIt, URDF/Xacro, sensor fusion (EKF/UKF via robot_localization)
- **Comms/protocols:** CAN bus, SPI, I2C, UART, EtherCAT, DDS/RTPS tuning
- **Tooling:** JTAG/SWD debugging, oscilloscope + logic analyzer work, GDB, Valgrind, static analysis (cppcheck, clang-tidy)
- Git, CI (Jenkins + some Github Actions), Docker for dev environments, basic Linux kernel module familiarity
- Simulation: Gazebo, occasionally Webots

## Experience

### Senior Robotics Engineer — Northgate Autonomy (London) | 2022-Present
- lead firmware + middleware integration for warehouse AMR fleet (~40 units deployed), reduced localization drift by tuning EKF params and fixing a nasty encoder overflow bug that was causing position jumps every ~6 hrs
- migrated control stack ROS1->ROS2, had to rewrite most of the custom message defs, took 5 months longer than planned because of DDS discovery issues on the warehouse wifi
- introduced FreeRTOS-based motor controller firmware replacing bare-metal loop, cut control loop jitter significantly
- mentoring 2 junior engineers, running architecture reviews
- on-call rotation for fleet, fixed several field failures remotely via OTA patches

### Embedded Software Engineer — Thackeray Systems Ltd (Cambridge, remote-ish) | 2019-2022
- worked on industrial robotic arm controller (6-DOF), safety-rated motion planning interfacing w/ MoveIt
- wrote CAN bus driver stack for joint controllers, debugged intermittent bus-off errors that only happened under vibration (turned out to be a grounding issue, not software - wasted 3 weeks on this before figuring that out)
- built diagnostics/logging system for field units, black-box style recorder for crash analysis
- ported subsystem from VxWorks to Zephyr as cost-cutting measure

### Firmware Engineer — Bramfield Dynamics (Reading) | 2017-2019
- entry-mid level role, worked on sensor board firmware (IMU + LIDAR interface board)
- C firmware for STM32 parts, SPI/I2C drivers, some low level DMA config
- helped build automated hw-in-loop test rig, caught a bunch of regressions before they hit customers
- first exposure to ROS here, built basic driver nodes publishing sensor data

## Education
**MEng Electronic & Electrical Engineering** — Imperial College London, 2013-2017
- Final year project: real-time obstacle avoidance on a small differential-drive robot (ROS1 + basic SLAM)

**A-Levels:** Maths, Further Maths, Physics — Woodgrange Sixth Form, London

## Other
- occasional speaker at London ROS meetup
- contributed a couple small PRs to robot_localization pkg (bug fixes, nothing major)
