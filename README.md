# PLC-Based Automated Conveyor Control System

## Overview

A simulated automated conveyor control system developed using OpenPLC and Ladder Diagram programming.

The project demonstrates fundamental industrial automation concepts including conveyor control, product detection, production counting, inspection-position detection, production limits, motor fault monitoring, fault latching, and manual fault reset.

## Objectives

- Learn PLC programming fundamentals
- Implement industrial conveyor control logic
- Work with digital inputs and outputs
- Implement production counting
- Implement control interlocks
- Implement fault detection and recovery
- Understand basic manufacturing automation logic

## System Features

- Start/stop conveyor control
- Motor seal-in logic
- Emergency-stop interlock
- Product detection
- Product counting
- Counter reset
- Production-limit control
- Inspection-position detection
- Motor fault detection
- Fault latching
- Manual fault reset
- Conveyor running status

## Technology

- OpenPLC Editor
- Ladder Diagram (LD)
- PLC simulation

## System Flow

Operator Controls
→ PLC Control Logic
→ Conveyor Motor

Product Sensor
→ Product Detection
→ Production Counter

Inspection Sensor
→ Inspection Position Status

Motor Fault
→ Fault Detection
→ Fault Latching
→ Manual Reset
→ Controlled Restart

## Testing

All implemented functions were tested in the PLC simulation environment.

| Test | Result |
|---|---|
| Start/Stop | PASS |
| Emergency Stop | PASS |
| Product Detection | PASS |
| Product Counting | PASS |
| Counter Reset | PASS |
| Production Limit | PASS |
| Inspection Detection | PASS |
| Motor Fault | PASS |
| Fault Latching | PASS |
| Fault Reset | PASS |
| Controlled Restart | PASS |

## Limitations

This project is a PLC simulation and does not use physical conveyor hardware, sensors, or motors.

The motor fault is represented by a simulated Boolean input.

The emergency-stop behavior is implemented in the simulated control logic. A real industrial machine would normally use a safety-rated emergency-stop circuit or safety PLC.

## Future Improvements

- Connect real PLC I/O
- Add physical sensors and actuators
- Add HMI interface
- Add robotic pick-and-place
- Add machine-vision inspection
- Add production-data logging
- Add predictive-maintenance monitoring

## Author
Ryhan
