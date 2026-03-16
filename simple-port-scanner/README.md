```ruby
██████╗  ██████╗ ██████╗ ████████╗    ███████╗ ██████╗ █████╗ ███╗   ██╗███╗   ██╗███████╗██████╗
██╔══██╗██╔═══██╗██╔══██╗╚══██╔══╝    ██╔════╝██╔════╝██╔══██╗████╗  ██║████╗  ██║██╔════╝██╔══██╗
██████╔╝██║   ██║██████╔╝   ██║       ███████╗██║     ███████║██╔██╗ ██║██╔██╗ ██║█████╗  ██████╔╝
██╔═══╝ ██║   ██║██╔══██╗   ██║       ╚════██║██║     ██╔══██║██║╚██╗██║██║╚██╗██║██╔══╝  ██╔══██╗
██║     ╚██████╔╝██║  ██║   ██║       ███████║╚██████╗██║  ██║██║ ╚████║██║ ╚████║███████╗██║  ██║
╚═╝      ╚═════╝ ╚═╝  ╚═╝   ╚═╝       ╚══════╝ ╚═════╝╚═╝  ╚═╝╚═╝  ╚═══╝╚═╝  ╚═══╝╚══════╝╚═╝  ╚═╝
```

[![CyberSecurity Repository](https://img.shields.io/badge/CyberSecurity-Projects-darkred?style=flat&logo=github)](https://github.com/DogukanErzurum/CyberSecurity)
[![C++20](https://img.shields.io/badge/C++-20-00599C?style=flat&logo=cplusplus)](https://isocpp.org)
[![Linux](https://img.shields.io/badge/Platform-Linux-black?logo=linux)](https://kernel.org)
[![CMake](https://img.shields.io/badge/CMake-Build%20System-064F8C?style=flat&logo=cmake)](https://cmake.org)

> A collection of cybersecurity projects built to explore networking, security concepts and defensive tooling through hands-on development.

*This repository focuses on practical implementations rather than theory alone. Detailed explanations and walkthroughs are included within each project.*

> *Maintained by **Doğukan Erzurum***

---

# Overview

This repository is designed as a growing cybersecurity project library.

The goal is to build practical security-focused tools and experiments that help deepen understanding of:

- network protocols  
- system-level security concepts  
- defensive security tooling  
- detection and monitoring workflows  
- security-oriented software development  

Projects will be added progressively and organized by difficulty level as the repository grows.

---

# Current Project

## Simple Port Scanner

A TCP port scanning tool written in **C++** using **Boost.Asio** and **CMake**.

The project demonstrates how asynchronous networking techniques can be used to scan large port ranges efficiently while maintaining controlled concurrency.

### Core Capabilities

- TCP port scanning against remote hosts  
- Support for custom port ranges  
- Configurable scan concurrency  
- Adjustable connection timeout handling  
- Terminal output for scan results  

---

# Quick Start

Clone the repository and build the project:

```bash
git clone https://github.com/DogukanErzurum/CyberSecurity.git
cd CyberSecurity/simple-port-scanner
mkdir build && cd build
cmake ..
make
```

Run the scanner:

```bash
./simplePortScanner --target 192.168.1.1 --ports 1-1024
```

Example scans:

```bash
./simplePortScanner --target 10.0.0.1 --ports 22,80,443
./simplePortScanner --target 172.16.0.5 --ports 1-65535
```

---

# Learning Material

Each project in this repository may include a dedicated learning section explaining the concepts behind the implementation.

Typical documentation modules include:

| Module | Description |
|------|-------------|
| Overview | Introduction and prerequisites |
| Concepts | Security and networking fundamentals |
| Architecture | Design approach and system flow |
| Implementation | Code structure and walkthrough |
| Challenges | Ideas for extending the project |

---

# Project Structure

```bash
CyberSecurity/
├── simple-port-scanner
│   ├── CMakeLists.txt
│   ├── main.cpp
│   ├── src
│   ├── learn
│   └── README.md
```

Additional projects will be added over time and grouped by difficulty level.

---

# Requirements

Typical requirements for projects in this repository:

- Linux environment  
- C++20 compatible compiler  
- Boost libraries  
- CMake build system  
- Git  

---

# Purpose of This Repository

This repository is intended as a personal cybersecurity learning lab and development portfolio.

By building tools from scratch, the aim is to gain deeper insight into how security technologies work at a technical level rather than relying only on existing tools.

---

# Author

**Doğukan Erzurum**


---

