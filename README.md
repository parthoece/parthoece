# Partho Adhikari

**Software Engineer — Equipment Software · Machine Vision · Smart Manufacturing**

Based in Taiwan. I develop software for **high-precision manufacturing equipment, automated inspection systems, and factory integration**.

My work sits at the boundary between **equipment hardware, algorithms, operator applications, vision systems, and manufacturing infrastructure**. I build and integrate C#/.NET equipment applications, machine-vision components, industrial device interfaces, manufacturing data flows, and algorithm modules used in production equipment.

A recurring part of my work is integrating **MATLAB-developed algorithms packaged as C++ DLLs into C# equipment software**, together with industrial cameras, lighting systems, barcode readers, databases, and third-party equipment interfaces.

My engineering focus includes:

* **Equipment software:** C#/.NET, Windows desktop applications, HMI/operator workflows, machine states, device SDK integration, diagnostics, fault handling, testing, and production troubleshooting
* **Machine vision & inspection:** AOI, industrial cameras, image acquisition, lighting, defect detection, computer vision, and inference integration
* **Manufacturing integration:** equipment data, traceability, MES-style workflows, PostgreSQL, event-driven systems, APIs, and industrial interfaces
* **Reliability & architecture:** hardware abstraction, simulation, fault injection, recovery behavior, observability, automated testing, and maintainable system boundaries

Primary technologies include **C#, .NET, C/C++, Python, SQL, MATLAB, PostgreSQL, Docker, PyTorch, ONNX, OpenCV/vision tooling, and Git-based CI/CD**.

## Selected Engineering Systems

### Virtual Multi-Axis Motion Control Platform

[**multiaxis-motion-sim**](https://github.com/parthoece/multiaxis-motion-sim)

Software-in-the-loop virtual commissioning environment for industrial machine-control software. The system models deterministic XYZ motion, equipment states, inspection workflows, operator cancellation, abnormal conditions, fault recovery, persistence, and replaceable motion-controller backends.

Built around C#/.NET and WPF with deterministic simulation, grblHAL integration, automated tests, architecture checks, and runtime diagnostics.

### Virtual Smart Motion Cell

[**virtual-smart-motion-cell**](https://github.com/parthoece/virtual-smart-motion-cell)

Open-source reference implementation of a software-defined industrial machine cell.

The platform combines a headless .NET machine runtime, motion abstraction, operator HMI, Three.js digital twin, OPC UA, MES integration, traceability, observability, fault injection, restart recovery, and automated integration testing.

The architecture explores modular machine-control software with explicit separation between domain behavior, application orchestration, infrastructure, industrial protocols, and operator interfaces.

### Fabiq Smart Factory

[**fabiq-smart-factory**](https://github.com/parthoece/fabiq-smart-factory)

Reference implementation of an event-driven MES/IIoT platform for manufacturing operations.

The system connects simulated equipment events with Apache Kafka, ASP.NET Core services, PostgreSQL manufacturing history, operational APIs, anomaly detection, React dashboards, Prometheus/Grafana observability, and Docker-based deployment.

It explores production visibility, equipment events, downtime, OEE, traceability, and extensible factory-system integration.

### Cyber-Physical Systems Testbed

[**CPS_testbed**](https://github.com/parthoece/CPS_testbed)

Docker-based industrial cyber-physical testbed integrating simulated processes, PLCs, HMIs, system logging, network capture, fault generation, and reproducible anomaly-detection experiments.

The research built on this environment included a two-stage operational-technology anomaly-detection approach achieving a **99% F1-score**.

## Background

I hold an **M.S. in Electrical Engineering and Computer Science** from **National Yang Ming Chiao Tung University (NYCU), Taiwan**.

My graduate and independent work has included industrial anomaly detection, computer vision, OT cybersecurity, and AI-assisted investigation systems. One computer-vision project achieved **95% mAP at 30 FPS** for real-time safety-helmet detection using YOLOv8l.

## Contact

**[Email](mailto:parthoece23@gmail.com)**
