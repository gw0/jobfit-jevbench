# Rosalind Blackwood
Embedded / Robotics Engineer — New York, NY (Hybrid) | rosalind.blackwood@example.com | 917-555-0148 | github.com/rblackwood-robotics

## Summary
Mid-level embedded/robotics engineer, ~4 yrs, C/C++ firmware + ROS/ROS2 stacks on mobile robots and sensor rigs, comfortable across RTOS (FreeRTOS, Zephyr) scheduling/ISR work and higher-level nav/perception nodes -- basically I go from register maps to launch files depending on the week. Hybrid NYC based, prior onsite lab + remote sim work.

## Skills
- Languages: C, C++ (11/14/17), Python (tooling/scripts), some Rust (side projects)
- Robotics: ROS1 (noetic), ROS2 (foxy/humble), tf2, nav2, rviz, Gazebo/Ignition sim
- RTOS/Firmware: FreeRTOS, Zephyr, bare-metal ARM Cortex-M (STM32), interrupt-driven drivers, bootloaders
- Comms/protocols: CAN, I2C, SPI, UART, Ethernet/UDP, DDS (fastRTPS/cyclonedds)
- Tools: git, CMake, colcon/catkin, GDB/JTAG, oscilloscope + logic analyzer debugging, Docker for sim envs
- Other: sensor fusion basics (EKF), motor control/PID, unit testing (gtest), CI (Jenkins, some GH Actions)

## Experience

### Firmware/Robotics Engineer -- Halcyon Dynamics (New York, NY) | 2023 - Present
- Own firmware for differential-drive mobile base (STM32F4, FreeRTOS) -- rewrote motor control loop, cut latency ~30%
- ROS2 migration lead for nav stack (ROS1->ROS2 humble), had to redo half the launch files and tf tree, painful but done
- Wrote CAN bus driver + diagnostics layer used across 3 robot platforms
- Mentored 2 junior interns on embedded debugging (JTAG/logic analyzer workflows)
- On-call rotation for field robots, fixed a nasty watchdog reset bug that only showed up after ~14hrs runtime

### Embedded Software Engineer -- Ferrowave Robotics | 2021 - 2023
- Built sensor fusion node (IMU + wheel encoders, EKF) for indoor delivery robot, ROS1
- Zephyr RTOS port for new sensor board rev, including driver bring-up for new IMU
- Reduced boot time on custom Cortex-M7 board by rewriting bootloader stage 2
- Wrote gtest suite for control firmware, coverage went from ~20% to 65%+ (nobody had tested this before me)
- Collaborated with mech eng on encoder placement, saved a redesign cycle

### Junior Firmware Engineer -- Briarcliff Instruments | 2021 - 2021 (internship->FT briefly)
- Small embedded team, worked on I2C/SPI sensor drivers for industrial monitoring device
- Helped port legacy C codebase off an EOL microcontroller
- Basic PID tuning for a servo test rig

## Education
**B.S. Electrical Engineering** -- Rutgers University, New Brunswick, NJ | 2017 - 2021
- Senior project: autonomous line-following bot w/ custom PCB + PID control (won 2nd place dept showcase)
- Coursework: embedded systems, control theory, digital signal processing, robotics fundamentals
