# HotWheelzBMSMonitor

Real-time telemetry interface for a solar race car, combining battery diagnostics, CAN-bus communication and live camera feedback.
Originally developed as a collaborative/team project.
This repository showcases my contributions and project documentation for portfolio purposes.

## My Contributions

- Designed and programmed the driver-monitor GUI
- Implemented real-time telemetry display
- Integrated CANbus sensor data and camera feed
- Created technical/system documentation

## Technologies

Python • Tkinter • Raspberry Pi • CANbus

## Original Team Repository

This project was developed collaboratively through the Solar Race Car Team and remains under active development.

🔗 [Original Repository](https://github.com/Jazzy-girl/HotWheelzTelemetry/tree/main)

# HotWheelz Telemetry

Code for

- sending data from the car (Raspberry Pi) to the pit (Arduino->Laptop)
- displaying and analyzing data in a native python app pit-side
- displaying backup camera and necessary data to the driver in a native python app car-side

## Telemetry Documentation Artifacts

[Telemetry Project / Documentation](https://docs.google.com/document/d/1JleDLJ7EduALBelWgs0jYR1E61BF-kjRYm0OXcnqzK4/edit?tab=t.0)

# Developers

Divna Mijić  
Ryanne Wilson  
Matthew Cornell  
Gem Martinage  
Natu Benyam Demeke  
Max Young

# Necessary Installs

can
cantools
tkinter

# How to import:

## 1. Install cantools (Python CAN library)

### Linux

sudo apt install python3-can

### Windows

pip install can (maybe?)

### Macbook (if using Homebrew)

1. Firstly, install python if you don't already have it

```bash
brew install python
```

2. Then, install python-can and cantools via pip:

```bash
pip3 install python-can cantools
```

## 2. Install tkinter (GUI library)

### Linux

```bash
sudo apt install python3-can
```

### Windows

```bash
pip install can (maybe?)
```

### Macbook (if using Homebrew)

```bash
 brew install python-tk
```

Unless you are using avirtual machine, your laptop will likely complain. To bypass this issue and force install tkinter locally on yoru computer run the following:

```bash
pip3 install --break-system-packages python-can cantools
```

## 3. Install opencv

By running this command, you are installing dependencies needed to use the Raspberry Pi camera

### Virtual Machine

```bash
???
```

### Linux

```bash
sudo apt install python3-can
```

### Windows

```bash
pip install can (maybe?)
```

### Macbook (if using Homebrew)

```bash
 brew install python-tk
```

## 4. Running

Just run the ReceivingDataCode.py as you normally would, a display window will open with simple GUI
