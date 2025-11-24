# MIMO Gain Visualizer

An interactive web-based visualization tool for understanding MIMO (Multiple Input Multiple Output) antenna gain through phase alignment.

## Features

- **2x2 and 4x4 MIMO Configurations**: Switch between different antenna configurations
- **Interactive Phase Control**: Adjust phase differences between antennas with a slider
- **Real-time Visualization**: See how individual signals combine to create constructive or destructive interference
- **Gain Calculation**: View the actual gain in dB based on phase alignment
- **Animation Controls**: Animate phase changes or loop continuously

## How It Works

This visualizer demonstrates how multiple antennas transmitting the same signal can add together:
- When waves are **in-phase**, they combine constructively and increase signal strength
- When waves are **out-of-phase**, they partially or completely cancel each other out

The maximum theoretical gain for N antennas is 10×log₁₀(N) dB when all signals are perfectly in phase.

## Usage

Simply open `index.html` in a web browser. No additional setup or dependencies required!

## Live Demo

Visit the live demo at: **[mimoviz.com](https://mimoviz.com)**

