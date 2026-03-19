# Arduino Practice Toolkit

## Description
This project is a repository of practical exercises and hardware experiments using the Arduino platform. It covers a wide range of fundamental robotics and electronics concepts, from simple RGB LED manipulations to complex systems like a mobile cart controlled by motors and ultrasonic sensors for distance measurement.

## Technologies
-   **Arduino** (Hardware Platform)
-   **C/C++** (Arduino Sketch Language)
-   **Electronic Components**: LEDs, DC Motors, Buttons, Potentiometers, and LCD Displays.

## Features
-   **Lighting Systems**: Implementation of RGB color cycles and analog-controlled brightness.
-   **Motor Control**: Directional and speed control for DC motors, including autonomous "car" logic.
-   **Sensor Integration**: Distance calculation using accumulated pulses or ultrasonic logic.
-   **Visual Feedback**: Real-time data output to LCD displays, including distance metrics and simple "display games."
-   **User Interaction**: Button-triggered events to toggle lights or motor states.

## How to Run

### Prerequisites

-   **Arduino IDE** installed on your computer.
-   **Arduino Board** (Uno, Mega, or similar).
-   Required hardware components (LEDs, Motors, Jumpers, etc.).
    

### Step-by-Step Instructions

1.  **Clone or Download** the repository.
2.  **Open the Arduino IDE**.
3.  **Navigate to the desired folder** (e.g., `carrinho/motor-carrinho/`) and open the `.ino` file.
4.  **Connect your Arduino board** to your PC via USB.
5.  **Select your board and port** in the `Tools` menu of the IDE.
6.  **Click "Upload"** to compile and flash the code to the board.

## Project Structure

-   **`LED_motor_botao/`**: Basic scripts for LED colors, analog light control, and button-press logic.
-   **`aula4/` & `carrinho/`**: Advanced scripts for controlling motor-driven vehicles based on light and distance.
-   **`display_motor/`**: Integration of LCD displays with motor logic and distance calculations.
-   **`motor/`**: Focused logic for standalone DC motor operations.

## What I Learned

-   **PWM Control**: Using analog signals to vary LED intensity and motor speed.
-   **Hardware Interfacing**: Wiring and programming external peripherals like LCDs and DC motors.
-   **State Logic**: Implementing "if-then" logic to respond to physical button presses in real-time.
-   **Mathematical Modeling**: Calculating physical distance based on rotation data or sensor timing.

## Future Improvements

-   **Wireless Control**: Integrate Bluetooth or Wi-Fi modules (ESP32/HC-05) for remote operation.
-   **Autonomous Navigation**: Add obstacle avoidance logic using multiple ultrasonic sensors.
-   **Power Optimization**: Implement sleep modes for battery-operated car configurations.




