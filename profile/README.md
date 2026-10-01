<div align="center">

# AEROVEX

**Unified 3D Simulation, Digital Twin & Mission Operations Platform for Autonomous Robotics**

[![Website](https://img.shields.io/badge/Website-aerovex.net-0ea5e9?style=flat-square&logo=google-chrome&logoColor=white)](https://aerovex.net)
[![Status](https://img.shields.io/badge/Platform-Active%20Development-34d399?style=flat-square)](https://aerovex.net)
[![License](https://img.shields.io/badge/License-Proprietary%20%2F%20Enterprise-a855f7?style=flat-square)](https://aerovex.net)

<p align="center">
  <em>Bridging visual robotics design, high-fidelity physics simulation, and real-world hardware teleoperation across aerial, ground, and multi-domain autonomous systems.</em>
</p>

---

</div>

## 🌐 Overview

**Aerovex** is an end-to-end 3D robotics simulation, digital twin, and mission orchestration ecosystem. It empowers engineers, autonomous vehicle developers, and robotics operators to design, simulate, test, and deploy complex autonomous systems in a unified spatial environment.

From visual kinematic modeling and digital twin world generation to real-time hardware-in-the-loop (HITL/SITL) testing and high-frequency telemetry analytics, Aerovex provides the complete software stack for next-generation robotics engineering.

---

## 🏛️ Flagship Platforms & Engines

<table>
  <thead>
    <tr>
      <th>Platform / Engine</th>
      <th>Discipline</th>
      <th>Primary Role</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b><a href="https://github.com/aerovexhq/aerovex">Aerovex Workstation</a></b></td>
      <td>Workstation Platform</td>
      <td>Unified 3D geospatial digital twin, Cesium terrain, CAD studio, and mission planner.</td>
    </tr>
    <tr>
      <td><b><a href="https://github.com/aerovexhq/chronos">Chronos</a></b></td>
      <td>Physics & Multi-World Sim</td>
      <td>High-throughput multi-world 6-DOF simulation kernel, 8 dynamics solvers & aerodynamics.</td>
    </tr>
    <tr>
      <td><b><a href="https://github.com/aerovexhq/kestrel">Kestrel</a></b></td>
      <td>Avionics & Autopilot</td>
      <td>Hard real-time embedded flight control OS, 24-state EKF & multi-vehicle guidance.</td>
    </tr>
    <tr>
      <td><b><a href="https://github.com/aerovexhq/phonon">Phonon</a></b></td>
      <td>Circuit & EDA Simulation</td>
      <td>Physically rigorous electro-thermal circuit simulator and transistor-level SPICE solver.</td>
    </tr>
    <tr>
      <td><b><a href="https://github.com/aerovexhq/axiom">Axiom</a></b></td>
      <td>Silicon & Digital EDA</td>
      <td>High-performance in-RAM HDL engine, Cranelift JIT simulator & silicon telemetry.</td>
    </tr>
    <tr>
      <td><b><a href="https://github.com/aerovexhq/sonon">Sonon</a></b></td>
      <td>Acoustics & Voice</td>
      <td>Minimalist robotics-aimed acoustic DSP, few-shot phrase spotting & streaming speech engine.</td>
    </tr>
    <tr>
      <td><b><a href="https://github.com/aerovexhq/vexview">Vexview</a></b></td>
      <td>Linux Studio Utility</td>
      <td>Minimalist media & video studio inspector, stream trimming & image editing engine.</td>
    </tr>
    <tr>
      <td><b><a href="https://github.com/aerovexhq/vexrec">Vexrec</a></b></td>
      <td>Linux Studio Utility</td>
      <td>Screen and audio recording with Wayland PipeWire, loopback audio & camera PiP.</td>
    </tr>
    <tr>
      <td><b><a href="https://github.com/aerovexhq/appify">Appify</a></b></td>
      <td>Desktop Packaging</td>
      <td>Convert any web application into a high-performance native desktop app with Rust backend.</td>
    </tr>
  </tbody>
</table>

---

## ⚡ Core Capabilities


<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🤖 Visual Robotics & Kinematics</h3>
      <ul>
        <li><b>Visual SDF / URDF Authoring:</b> Interactive tree-based and 3D viewport robot modeling with real-time SDF XML sync.</li>
        <li><b>Kinematic Chains & Joint Constraints:</b> Full joint hierarchy configuration with real-time physics and joint animation playback.</li>
        <li><b>Sensor & Actuator Fusion:</b> Integrated IMU, GPS, LiDAR, optical cameras, and control surface modeling.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🌍 3D Geospatial Digital Twins</h3>
      <ul>
        <li><b>Global Terrain & Photogrammetry:</b> Planetary 3D geospatial engine with sub-meter terrain elevation and custom tiled imagery.</li>
        <li><b>Environmental & Dynamic Weather:</b> Configurable atmospheric conditions, wind vector simulation, and lighting models.</li>
        <li><b>Cross-Engine World Export:</b> Native export to Gazebo worlds, FlightGear scenery, and X-Plane DSF packages.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🛰️ Autonomous Mission Operations</h3>
      <ul>
        <li><b>Multi-Agent Mission Planner:</b> 3D waypoint creation, terrain-following trajectories, and geofencing.</li>
        <li><b>Autonomous Path Generation:</b> Smart survey grids, spline smoothing, and real-time obstacle avoidance boundaries.</li>
        <li><b>Live Teleoperation & Tracking:</b> Low-latency multi-vehicle command-and-control with dynamic camera tracking.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🔌 Multi-Engine SITL & HITL</h3>
      <ul>
        <li><b>Autopilot Integration:</b> Native zero-config SITL orchestration for ArduPilot (ArduCopter, ArduPlane, Rover, Sub) and PX4.</li>
        <li><b>MAVLink & ROS Ecosystem:</b> High-speed MAVLink telemetry sockets, MAVProxy console integration, and ROS/ROS2 bridges.</li>
        <li><b>Hardware-in-the-Loop:</b> Serial, UDP, and TCP connections to physical autopilots and embedded robotics controllers.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📊 Deep Telemetry & Log Analytics</h3>
      <ul>
        <li><b>Interactive PID Tuning:</b> Real-time frequency response visualization and automated PID loop analyzer.</li>
        <li><b>Blackbox Log Playback:</b> High-resolution DataFlash (.bin) and telemetry (.tlog) synchronized 3D mission replay.</li>
        <li><b>Multi-Metric Telemetry Graphs:</b> Real-time and historical charting with millisecond time-cursor synchronization.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>☁️ Cloud Collaboration & Extensibility</h3>
      <ul>
        <li><b>Spatial Team Synchronization:</b> Multi-user concurrent editing of worlds, models, and flight plans in real time.</li>
        <li><b>In-App Scripting Engine:</b> Sandboxed Python (Pyodide) and TypeScript/JavaScript execution environments.</li>
        <li><b>Cross-Platform Native Desktop:</b> Ultra-lightweight secure launcher with native high-performance workstation client.</li>
      </ul>
    </td>
  </tr>
</table>

---

## 🚀 Getting Started & Contact

- 🌐 **Web Portal & Documentation**: [aerovex.net](https://aerovex.net)
- 📧 **Enterprise & Support**: [founder@aerovex.net](mailto:founder@aerovex.net)

---

<div align="center">
  <sub>© 2026 Aerovex. All rights reserved.</sub>
</div>
