# Digital Clock

A digital clock designed and simulated using **Logisim**.

The project displays **hours, minutes, and seconds** using digital logic circuits and seven-segment displays.

## Overview

The clock is built using counters, logic gates, and seven-segment displays. Each time unit is handled separately and connected to the next unit through the required counting logic.

The project was implemented completely in Logisim as a practical application of digital logic and sequential circuits.

## Main Components

* **Clock signal** – Provides the timing signal for the circuit.
* **Counters** – Used to count seconds, minutes, and hours.
* **4-bit counters** – Used as part of the counting circuits.
* **Logic Gates** – Control the counting limits and reset conditions.
* **Seven-Segment Displays** – Display the current time.
* **Wiring** – Connects the different stages of the clock.

## Clock Structure

The clock is divided into three main sections:

```text
       ┌──────────────┐
       │    Clock     │
       │    Signal    │
       └──────┬───────┘
              │
              ▼
       ┌──────────────┐
       │   Seconds    │
       │    Counter   │
       └──────┬───────┘
              │
              ▼
       ┌──────────────┐
       │    Minutes   │
       │    Counter   │
       └──────┬───────┘
              │
              ▼
       ┌──────────────┐
       │     Hours    │
       │    Counter   │
       └──────────────┘
```

Each section is connected to the next one so that the clock advances continuously.

## Display

The current values of:

* Hours
* Minutes
* Seconds

are displayed using seven-segment displays.

The circuit also uses logic gates to detect the required counting limits and generate the appropriate reset/carry signals.

## Features

* Digital time display
* Hours, minutes, and seconds
* Counter-based design
* Seven-segment displays
* Clock-driven operation
* Logic-based reset and carry signals
* Built entirely using digital logic components

## Software

**Logisim**

The complete digital clock was designed and simulated using Logisim.


<img width="1366" height="768" alt="Screenshot 2026-08-24 034950" src="https://github.com/user-attachments/assets/ef9efca6-8a5e-4796-a26d-07c07dc1b61f" />


## Project Structure

The Logisim project contains circuits for:

* Main clock
* 4-bit counter
* 4-bit sensing/counting logic
* Wiring
* Logic Gates
* Multiplexers
* Arithmetic components
* Input / Output

## Purpose

This project was developed to practice the design of sequential digital circuits and understand how counters and logic gates can be combined to create a functional digital clock.

## Author

**Mohamed Abdelmonem**
