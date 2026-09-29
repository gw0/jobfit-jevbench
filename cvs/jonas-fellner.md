# Jonas Fellner
Berlin, Germany (remote) | jonas.fellner@example.com | +49 176 5550193 | github.com/jfellner-robotics | linkedin.com/in/jonasfellner

## Summary
Junior Embedded/Robotics Engineer, ~1 yr experience building firmware and ROS nodes for small mobile robots and sensor rigs. Comfortable across the stack from bare-metal C on microcontrollers up to ROS1/ROS2 nav & perception nodes, plus RTOS task scheduling (FreeRTOS, Zephyr). Based in Berlin, open to remote/hybrid, fast learner, ships fast and fixes what breaks.

## Skills
- **Languages:** C, C++ (11/14/17), Python (scripting/tooling), some Rust (hobby)
- **Robotics:** ROS1 (noetic), ROS2 (humble/foxy), tf2, URDF, rviz, Gazebo/Ignition sim, MoveIt (basic)
- **RTOS/Embedded:** FreeRTOS, Zephyr RTOS, STM32 (HAL + bare metal), Arduino/Teensy, ESP32
- **Comms/protocols:** I2C, SPI, UART, CAN bus, MQTT, DDS (fastrtps)
- **Tools:** Git, Docker, CMake, colcon/catkin, PlatformIO, JTAG/SWD debugging, oscilloscope & logic analyzer
- **Other:** basic control theory (PID), Kalman filter (studied, implemented small demo), Linux (Ubuntu, Yocto exposure)

## Experience

### Junior Robotics Engineer — Nordlicht Robotics GmbH, Berlin
*Mar 2025 – Present*
- wrote + maintained ROS2 nodes for a warehouse AMR prototype (lidar + odometry fusion), reduced localization drift complaints from ops team significantly
- ported motor control loop from Arduino prototype to STM32F4 running FreeRTOS, hit real time deadlines that the old bare-metal loop kept missing under load
- built CI pipeline (colcon + docker) so nightly builds actually build, before that people just... didn't test
- debugged flaky CAN bus comms between motor controller and main compute board — turned out to be termination resistor issue, learned a lot about signal integrity the hard way
- documentation, some. wrote onboarding doc for new interns re: ROS workspace setup

### Embedded Systems Intern — Kesselring Mechatronik, Potsdam
*Jun 2024 – Feb 2025*
- assisted senior eng with firmware for small greenhouse sensor nodes (ESP32, MQTT telemetry)
- implemented basic I2C driver for humidity/temp sensor cluster, added to shared driver lib
- helped migrate a legacy bare-metal project to Zephyr RTOS, mostly just moved GPIO init code around and fixed the inevitable breakage
- soldering, a LOT of soldering. also learned to actually use a multimeter properly
- attended trade fair (Hannover) as booth support, explained the sensor demo to visitors

## Education
**B.Sc. Mechatronics / Embedded Systems** — Technische Hochschule Wildau
*2021 – 2024*
- thesis: "Low-latency sensor fusion for a two-wheeled balancing robot using FreeRTOS" — grade: gut (2.0)
- relevant coursework: microcontroller programming, control systems, digital signal processing, robotics I/II
- student robotics club (member 2022-2024) — built line-following + small ROS-based rover for competitions, placed 3rd regional 2023
