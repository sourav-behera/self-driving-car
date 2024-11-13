# Autonomous Driving Agent using Udacity Self Driving Simulator
This project uses a Convolutional Neural Network (CNN) to predict steering angles in a self-driving car simulation. The model is trained on data from the Udacity Self-Driving Car Simulator, which you’ll need to download and set up to run in autonomous mode.

## Prerequisites

- Python 3.6 or later
- Git
- Virtualenv

## Getting Started

### 1. Download the Udacity Self-Driving Car Simulator

Download the simulator from the [Udacity GitHub repository](https://github.com/udacity/self-driving-car-sim) or the [direct download link](https://github.com/udacity/self-driving-car-sim/releases).

Run the downloaded application to start the simulator and familiarize yourself with its environment. You’ll use this simulator in autonomous mode after setting up the project.

### 2. Setting up the project

Use Git to clone this repository onto your local machine:

```bash
git clone https://github.com/udacity/self-driving-car-sim
cd self-driving-car
python -m venv .venv
./.venv/bin/activate
pip install -r requirements.txt
```
### Running the model
Make sure you are in the /src folder before running the model
```bash
cd src/
python drive2.py model.py
```
This will startup the server. After starting the server launch the simulator in autonomous mode selecting the track 1
