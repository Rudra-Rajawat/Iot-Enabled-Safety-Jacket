# Iot-Enabled-Safety-Jacket
# IoT Enabled Smart Safety Jacket

!! [Smart Safety Jacket]

This project showcases an IoT enabled Smart Safety Jacket that utilizes various sensors to provide enhanced safety features. The jacket incorporates the following sensors: MQ2 gas sensor, MAX30100 heart rate sensor, DHT11 temperature and humidity sensor, and an ESP32 development board. The data collected from these sensors is then displayed on the Blynk cloud platform, allowing users to monitor and analyze the information remotely.

## Features

- **MQ2 Gas Sensor**: Detects the presence of harmful gases in the surrounding environment and alerts the wearer.
- **MAX30100 Heart Rate Sensor**: Measures the wearer's heart rate, enabling real-time monitoring and early detection of abnormalities.
- **DHT11 Temperature and Humidity Sensor**: Monitors the ambient temperature and humidity to ensure optimal comfort and safety.
- **ESP32 Development Board**: Serves as the central hub for collecting data from the sensors and connecting to the Blynk cloud platform.
- **Blynk Cloud**: Provides a user-friendly interface to visualize and track the collected sensor data remotely.

## Getting Started

### Prerequisites

To replicate this project, you will need the following hardware components:

- Smart Safety Jacket (with sensors and ESP32 board integrated)
- USB cable for ESP32 board
- Internet connection
- Arduino IDE

### Installation

1. Clone this repository to your local machine:

   ```
   https://github.com/Rudra-Rajawat/Iot-Enabled-Safety-Jacket.git
   ```

2. Connect the ESP32 board to your computer using the USB cable.

3. Install the required dependencies by running the following command:

   ```
   pip install -r requirements.txt
   ```

4. Open the `config.py` file and enter your Blynk cloud credentials:

   ```python
   BLYNK_AUTH = 'your_blynk_auth_token'
   ```

5. Upload the necessary code to the ESP32 board using the Arduino IDE or any other preferred method.

6. Power on the Smart Safety Jacket and ensure it is connected to the internet.

7. Launch the Blynk app on your mobile device and start monitoring the sensor data remotely.

## Usage

Once the Smart Safety Jacket is up and running, you can use the Blynk app to view and analyze the collected sensor data. The app provides various widgets to display sensor readings, such as gauges, graphs, and notifications. Additionally, you can set thresholds and triggers to receive alerts for specific conditions.

## Contributing

Contributions to this project are welcome. If you encounter any issues or have suggestions for improvements, please submit a pull request. Alternatively, you can open an issue and describe the problem or feature request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

We would like to express our gratitude to the developers of the libraries and frameworks used in this project. Their contributions greatly facilitated the implementation of the Smart Safety Jacket.

- [Blynk](https://blynk.io/)
- [Arduino](https://www.arduino.cc/)
- [Adafruit Industries](https://www.adafruit.com/)

## Contact

If you have any questions or inquiries about this project, please contact us at [RUDRARAJAWAT001@gmail.com](mailto:RUDRARAJAWAT001@gmail.com).

Happy hacking!
