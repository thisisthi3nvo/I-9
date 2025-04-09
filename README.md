# I-9

## Stepper Motor Control with MQTT Integration
This project demonstrates how to control a stepper motor using Adafruit Crickit and integrate it with the MQTT messaging protocol. The motor responds to specific MQTT messages, enabling external event-driven motor control.

## Features
Stepper Motor Control: Supports forward, backward, and oscillating movements.

MQTT Integration: Listens for messages on a specific topic to trigger motor actions.

Real-Time Response: Executes commands immediately upon receiving MQTT messages.

## Requirements
### Hardware
Adafruit Crickit Hat for Raspberry Pi
Stepper Motor

### Software
Python 3.7+

## Usage
Run the Stepper Motor Controller
The run_stepper.py script listens for MQTT messages and controls the motor based on received commands.

### Supported Commands:
FORWARD: Rotates the motor clockwise for one full revolution.

BACKWARD: Rotates the motor counter-clockwise for one full revolution.

OSCILLATE: Moves the motor back and forth for 5 seconds.

