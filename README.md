<div align="center">

# Amine Bensaid

### Software Engineer building developer tools, autonomous systems, and full-stack products

I work across the software stack—from static analysis and web platforms to ROS 2, embedded controllers, and cloud-connected IoT systems.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Amine_Bensaid-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amine-bensaid/)
[![Email](https://img.shields.io/badge/Email-Contact_me-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:mohamedamine.bensaid@insat.ucar.tn)
[![CV](https://img.shields.io/badge/CV-View_PDF-24292F?style=flat-square&logo=readthedocs&logoColor=white)](./Amine%20Bensaid.pdf)

</div>

---

## About me

I am an Embedded Systems Engineering student at **INSAT** in Tunisia with experience building open-source developer tools, production web platforms, distributed robotics software, embedded control systems, and IoT applications.

My work spans several layers of engineering:

- Designing static-analysis and visualization tools for ROS 2 developers
- Building full-stack products with Next.js, NestJS, PostgreSQL, and TypeScript
- Developing autonomous navigation and distributed communication with ROS 2 and micro-ROS
- Connecting embedded devices to cloud services and real-time dashboards
- Turning competition prototypes into reliable systems that operate under real constraints

## Projects

### 01 — ROS 2 Inspector

**Open-source static architecture analysis and policy enforcement for ROS 2 workspaces.**

I created a Python CLI that analyzes ROS 2 source code without requiring the workspace to be built or executed. It scans supported Python, C++, interface, and launch-file patterns to construct an evidence-backed model of packages, nodes, deployments, topics, services, actions, and dependencies.

The tool provides:

- Python AST and Tree-sitter C++ analysis
- Python, XML, and YAML launch-file inspection
- Package, node, topic, service, action, and interface discovery
- Mermaid, DOT, JSON, YAML, and interactive HTML output
- Architecture audits and YAML-based policy validation for CI
- Content-fingerprinted incremental analysis
- Explicit diagnostics for unresolved or dynamic behavior
- Automated tests, type checking, linting, packaging, and release workflows

`Python` `Tree-sitter` `NetworkX` `Typer` `Rich` `Pytest` `Mypy` `GitHub Actions`

[Source code](https://github.com/aminebensaid66/ros2_inspector) · [Documentation](https://ros2-inspector-theta.vercel.app/) · [PyPI](https://pypi.org/project/ros2inspector/)

---

### 02 — ROS 2 Inspector for VS Code

**A native workspace architecture explorer powered by ROS 2 Inspector.**

I built a companion VS Code extension that brings the analyzer's architecture model into the editor. It includes a searchable Architecture Explorer, interactive communication and dependency graphs, Problems integration, source navigation, policy validation, and automatic refresh on relevant file changes.

The extension is workspace-trust aware, runs the analyzer without shell interpolation, performs no telemetry or runtime network requests, and supports local and remote development environments.

`JavaScript` `VS Code API` `Webviews` `CSP` `Node.js`

[Source code](https://github.com/aminebensaid66/ros2_inspector_vscode)

---

### 03 — TRI-UP Platform

**E-learning, collaborative production, and logistics management for artisan associations.**

I contributed across a multi-role platform connecting association hubs, staff, trainers, trainees, training programs, products, and customer production orders.

My work included:

- Product-aware matching between orders and eligible artisan associations
- Atomic production-order transitions and concurrency safeguards
- Secure direct-to-object-storage media and image uploads
- Adaptive HLS video playback with signed URLs
- Authentication, invitations, password recovery, and account workflows
- PostgreSQL and Prisma connection, query, and timeout tuning
- API request tracing, safer logging, and reliability improvements
- Frontend error handling, navigation, mobile behavior, and quality enforcement
- Automated unit, integration, browser, and production-oriented performance tests

The wider system includes Redis-backed services, BullMQ background jobs, media processing, push notifications, role-based access control, CI pipelines, and deployment tooling.

`Next.js` `React` `NestJS` `PostgreSQL` `Prisma` `Redis` `BullMQ` `MinIO` `Cloudflare R2` `TypeScript`

> Collaborative organization project. The production repository is private.

---

### 04 — EUROBOT 2026 Autonomous Robotics System

**A distributed, competition-grade software stack for a fully autonomous robot.**

As a ROS 2 developer with **AEROBOTIX INSAT**, I worked on the robot's software architecture, navigation, embedded communication, real-time control, and operator tooling.

The system combined:

- ROS 2 Jazzy nodes deployed on a Raspberry Pi 5
- Hybrid A* path planning and autonomous navigation
- Lidar-based perception and obstacle avoidance
- Task scheduling and multi-system coordination
- micro-ROS communication with STM32 and ESP32 controllers
- Serial and UDP communication across heterogeneous devices
- PID-based closed-loop actuator and motor control
- A Flask and ROSBridge dashboard for strategy control, simulation, monitoring, and telemetry
- Linux `systemd` services for competition reliability

**Results:** 1st place in the Tunisian qualifications · 2nd place in the international accumulation phase · 5th place overall at the EUROBOT 2026 Finals in France

`ROS 2 Jazzy` `Python` `C++` `micro-ROS` `Hybrid A*` `Flask` `ROSBridge` `STM32` `ESP32` `Raspberry Pi`

---

### 05 — NXP Cup Autonomous Lane-Following Robot

**Real-time visual lane tracking and embedded closed-loop vehicle control.**

I designed and implemented software for an autonomous vehicle using a Teensy 4 microcontroller, Pixy2 camera, wheel encoders, and NXP components. The control stack combined visual lane input with PID-based motor regulation for accurate trajectory and speed control.

I also developed practical testing and debugging tools, including an ESP32 WebSocket controller for operating the vehicle independently of the camera during hardware validation.

**Results:** 1st place in Tunisia · Only Tunisian team qualified for the 2025 international finals in the Netherlands

`Embedded C++` `PID Control` `Teensy 4` `Pixy2` `ESP32` `WebSockets` `Encoders`

[Project repository](https://github.com/aminebensaid66/NXP-CUP-FINALS)

---

### 06 — Orange IoT Monitoring and Control Platform

**An end-to-end IoT system for monitoring and regulating microalgae pools.**

During a four-month internship at **Orange Digital Center Tunisia**, I contributed across embedded firmware, cloud communication, backend services, and user interfaces.

The system included real-time sensor acquisition, automated actuator control, closed-loop pool regulation, AWS IoT Core and MQTT telemetry, remote command execution, and web and touchscreen monitoring interfaces. I worked in an Agile team using Jira.

`Embedded C` `Python` `Flask` `AWS IoT Core` `MQTT` `REST APIs` `WebSockets`

---

### 07 — Robot Control Mobile Application

**Cross-platform monitoring and remote control for a four-wheel autonomous robot.**

I built a Flutter application that communicates with a robot over Bluetooth Low Energy. It supports remote commands, speed adjustment, real-time telemetry, and live visualization of encoder-based odometry.

`Flutter` `Dart` `BLE` `Real-time Telemetry` `Odometry`

---

### 08 — ChatGPT Prompt Runner

**A local Electron desktop application for organizing and running reusable browser-automation workflows.**

The application combines an Electron main process with a statically exported Next.js interface. It uses isolated IPC APIs for filesystem access, native folder selection, project management, workflow filtering, and command generation without requiring a local web server.

`Electron` `Next.js` `React` `TypeScript` `IPC` `macOS`

[Project repository](https://github.com/aminebensaid66/chatGPT.com-Automation-GUI)

## Experience

| Role | Organization | Focus |
|---|---|---|
| **IoT Software Engineer Intern** | Orange Digital Center Tunisia | Embedded firmware, AWS IoT, MQTT, Flask, monitoring interfaces |
| **ROS 2 Developer** | AEROBOTIX INSAT | Autonomous navigation, distributed robotics, embedded communication, dashboards |
| **Full-Stack Contributor** | TRI-UP | Platform architecture, backend reliability, matching, media, performance, testing |

## Achievements

- **2nd place**, EUROBOT 2026 international accumulation phase, France
- **5th place overall**, EUROBOT 2026 international finals, France
- **1st place**, EUROBOT 2026 Tunisian qualifications
- **1st place nationally**, NXP Cup Tunisia
- **International finalist**, NXP Cup 2025, Netherlands

## Technical stack

| Domain | Technologies |
|---|---|
| **Languages** | Python, C, C++, TypeScript, JavaScript, Dart, Java, SQL |
| **Developer tooling** | AST analysis, Tree-sitter, CLI design, VS Code extensions, static analysis |
| **Frontend & mobile** | Next.js, React, Tailwind CSS, Flutter, Electron |
| **Backend & data** | NestJS, Flask, PostgreSQL, Prisma, Redis, BullMQ, REST, WebSockets |
| **Robotics** | ROS 2, micro-ROS, Hybrid A*, SLAM, Navigation2, EKF, PID, Gazebo |
| **Embedded & IoT** | STM32, ESP32, Teensy 4, Raspberry Pi, FreeRTOS, AWS IoT Core, MQTT |
| **Infrastructure** | Linux, Docker, GitHub Actions, MinIO, S3-compatible storage, systemd |
| **Protocols** | I2C, SPI, UART, CAN, Serial, UDP, BLE, HTTP, MQTT |

## Current interests

- Developer tools that make complex software architectures easier to understand
- Reliable robotics software and communication across heterogeneous systems
- Backend architecture, distributed systems, and production performance
- Open-source engineering and tools with practical developer workflows

---

<div align="center">

### Let's build something useful

I am open to collaboration and software engineering opportunities involving developer tools, robotics, embedded systems, or full-stack products.

[LinkedIn](https://www.linkedin.com/in/amine-bensaid/) · [Email](mailto:mohamedamine.bensaid@insat.ucar.tn) · [CV](./Amine%20Bensaid.pdf)

</div>
