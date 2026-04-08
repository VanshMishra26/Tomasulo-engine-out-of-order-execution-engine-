# Tomasulo Engine: Explainer & Simulator

## Overview
In modern computer architecture, waiting for data is a major bottleneck. The Tomasulo algorithm, designed in 1967 for the IBM 360/91, elegantly solves this through dynamic scheduling and out-of-order execution, ensuring the processor never stalls unnecessarily. 

This project brings this complex, microscopic process to life. It is a comprehensive, browser-based tool designed to make computer architecture accessible, split into two main components: an **Animated Explainer** and a **cycle-accurate Simulator**.

## Features
* **Animated Explainer:** Interactive, visual breakdowns that teach the core concepts of dynamic scheduling, reservation stations, and the Common Data Bus (CDB).
* **Cycle-Accurate Simulator:** A fully functional engine to test custom instruction sequences, processing them out-of-order and reflecting exact architectural clock cycles.
* **Real-Time Visualization:** Watch instructions in real-time as they are issued, executed, and written back, with live updates to registers and reservation station states.
* **Browser-Based:** Completely accessible via the web with zero installation required.

## Getting Started

### Prerequisites
Since this is a browser-based tool, all you need is a modern web browser (Chrome, Firefox, Edge, Safari).

### Installation & Setup
1. Clone the repository:
   ```bash
   git clone [https://github.com/VanshMishra26/tomasulo-engine.git](https://github.com/VanshMishra26/tomasulo-engine.git)
