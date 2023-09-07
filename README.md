# Autonomous Car Track Challenge

## Project Overview

The project aims to design an autonomous car that combines principles from electrical-electronics engineering (EEE) and computer engineering (CoE). This car should be able to navigate a predefined track, identify simple signs, and make decisions based on those signs. The project involves the use of mathematical models and artificial intelligence (AI) approaches, leveraging libraries like OpenCV.

### Track and Signs

- The track consists of a 50 cm wide road with white-colored lines on both sides.
- Four signs are used on the track:
  1. Bus Stop Sign (D): For passengers on/offloading.
  2. Left Sign: Indicates a left turn.
  3. Right Sign: Indicates a right turn.
  4. Stop Sign: Signals the car to stop permanently.

### Autonomous Car Behavior

- The autonomous car should start within 10 seconds of being in front of the track.
- It must complete the track without crossing the white lines on the sides.
- The car should identify and react to the signs as follows:
  - Bus Stop Sign (D): Stops for 30 seconds on first encounter and 20 seconds on subsequent encounters.
  - Left Sign: Executes a left turn.
  - Right Sign: Executes a right turn.
  - Stop Sign: Permanently stops the car.

## Implementation

The implementation involves:
1. Developing mathematical models for car movement and sign detection.
2. Using AI approaches, especially the OpenCV library, for sign recognition.
3. Ensuring the car follows the track and reacts appropriately to signs.
