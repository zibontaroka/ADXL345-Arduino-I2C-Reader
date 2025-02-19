<<<<<<< HEAD
# ADXL345 Accelerometer Data Reader

This project demonstrates how to use the ADXL345 accelerometer sensor with an Arduino to read acceleration data along the X, Y, and Z axes. The sensor communicates via I2C, and the data is printed to the Serial Monitor for visualization.

## Features
- Reads acceleration data from the ADXL345 sensor.
- Outputs X, Y, and Z axis values in raw format scaled for a ±2g range.
- Uses I2C communication to interact with the ADXL345 sensor.

## Components Needed
- Arduino (Uno, Nano, or any compatible board)
- ADXL345 Accelerometer
- Jumper wires
- Breadboard (optional)

## Circuit
- Connect the **VCC** of the ADXL345 to **5V** on the Arduino.
- Connect the **GND** of the ADXL345 to **GND** on the Arduino.
- Connect **SDA** to **A4** (for Uno) or the corresponding SDA pin on other boards.
- Connect **SCL** to **A5** (for Uno) or the corresponding SCL pin on other boards.

## Code Explanation
1. The program begins by initializing I2C communication with the ADXL345 sensor.
2. It then enables the measurement mode of the sensor.
3. In the `loop()` function, the accelerometer data is read from the sensor's registers.
4. The data is processed and printed to the Serial Monitor.

## Usage
1. Upload the code to your Arduino.
2. Open the Serial Monitor at **9600 baud rate**.
3. View the accelerometer data along the X, Y, and Z axes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
=======
# ADXL345-Arduino-I2C-Reader
This repository contains an Arduino-based project for reading acceleration data from the ADXL345 sensor using I2C communication. The code initializes the sensor, retrieves raw X, Y, and Z axis values, scales them for a ±2g range, and prints the output to the Serial Monitor.
>>>>>>> 7aad63b56fe646f5e48617cdc31f39230dbc3836
