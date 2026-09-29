# Paulo Winkler
Embedded Systems / Robotics — Principal Engineer | São Paulo, Brazil (Remote) | paulo.winkler@example.com | +55 11 98212-4471

## Summary
16 yrs building firmware & robotics stacks, from bare-metal drivers to full ROS2 nav stacks running on fleets of AGVs. Comfortable owning the HW/SW boundary, RTOS scheduling, safety-critical stuff (IEC 61508 exposure, not certified myself though). Led teams up to 9 engineers across 3 employers, mostly logistics robotics & industrial automation. Remote-first since 2019 — distributed teams across EU/US timezones, no problem.

## Skills
- Languages: C (embedded, MISRA-ish), C++11/14/17, some Python for tooling/sim, bash
- RTOS: FreeRTOS, Zephyr, VxWorks (legacy project only), also hand-rolled a cooperative scheduler on Cortex-M0 way back (2011-ish, don't judge)
- ROS / ROS2 — led Foxy->Humble migration twice, tf2, nav2, a bit of MoveIt
- Comms: CAN/CANopen, EtherCAT, Modbus, UART/SPI/I2C obviously, some UDP multicast for sensor fusion nodes
- Toolchains: gcc/arm-none-eabi, CMake (heavy user), Yocto (basic), gdb/JTAG/openocd, Bazel (briefly, hated it honestly)
- Sim: Gazebo/Ignition, a little Webots
- misc: git, Jenkins, some Docker but only for CI runners, not the actual embedded target lol

## Experience

### Principal Robotics Engineer — Vantara Robotics Ltda (São Paulo)
2020 – Present
- architected the motion-control + localization stack for a warehouse AGV fleet (~40 units deployed across 3 customer sites)
- migrated ROS1->ROS2 (Foxy then Humble) across the whole fleet with near-zero downtime, staged rollout
- built a custom real-time layer on FreeRTOS for the motor controllers, replaced a vendor blob that kept faulting under load
- mentored 4 engineers, ran the on-call rotation for 2 yrs
- cut field failure rate by ~35% (mix of watchdog redesign + better CAN bus error handling, hard to attribute exactly which mattered more)

### Senior Embedded Engineer, Robotics — Mecatrônica Sul Sistemas
2013 – 2020 (~7 yrs, some overlap w/ contract work not listed here)
- owned firmware for pick-and-place industrial arms, C on STM32F4/F7, later moved some targets to Zephyr
- integrated ROS (industrial_core era) for higher-level task planning talking down to our custom motor drivers over EtherCAT
- built the CI/HIL rig — bunch of Jetsons + real motor benches wired up, caught a lot of regressions before the customer did
- also maintained the VxWorks legacy line for a while, one client insisted on it, painful

### Firmware Engineer — Cronos Automação Industrial
2010 – 2013
- entry-ish role, bare metal C on 8/32-bit MCUs (started on 8051 believe it or not, then AVR, then ARM)
- wrote bootloader + OTA-ish update mechanism over serial for field devices (no internet on these, just techs w/ laptops)
- first real RTOS exposure here (uC/OS-II) — also first real exposure to priority inversion, learned that one the hard way

## Education
- BSc Electrical Engineering — Universidade Presbiteriana Mackenzie, São Paulo (2005-2010, took an extra year, worked part-time through most of it)
- assorted: FreeRTOS vendor training (2015), ROS2 migration workshop, online (2021)
