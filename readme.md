# WEBBLE_JRing

This project contains a collection of HTML files for interacting with Bluetooth-enabled devices, such as the SR08 Smart Ring. These tools leverage the Web Bluetooth API to connect, discover services, and interact with Bluetooth devices.

## Project Structure

### File Descriptions

- **index.html**  
  A simple interface for connecting to the SR08 Smart Ring and reading basic data such as battery level and heart rate.

- **scan.html**  
  A general-purpose Bluetooth device scanner that lists nearby devices and their signal strength.

- **sr08.html**  
  An advanced service explorer for the SR08 J-Ring. It provides detailed information about services, characteristics, and notifications, along with a dashboard for live data updates.

- **sr08v1.html**  
  A basic version of the SR08 Service Explorer. It connects to the SR08 device and lists its services and characteristics.

- **sr08v2.html**  
  An enhanced version of the SR08 Service Explorer with improved UI and additional features like parsing known services and characteristics.

## Features

- **Bluetooth Device Scanning**  
  Use `scan.html` to discover nearby Bluetooth devices.

- **SR08 Smart Ring Support**  
  - Connect to the SR08 Smart Ring using `index.html`, `sr08.html`, `sr08v1.html`, or `sr08v2.html`.
  - Explore services and characteristics.
  - Read and display data such as heart rate, SpO2, and battery level.
  - Enable notifications for real-time updates.

## Requirements

- A modern browser with Web Bluetooth API support (e.g., Chrome, Edge, or Opera).
- Bluetooth-enabled devices such as the SR08 Smart Ring.

## Usage

1. Open the desired HTML file in a browser.
2. Follow the on-screen instructions to connect to a Bluetooth device.
3. Interact with the device to explore services, read data, or enable notifications.

### Example: Connecting to the SR08 Smart Ring

1. Open `sr08.html` in your browser.
2. Click the "Connect to SR08" button.
3. Select your SR08 device from the list of available devices.
4. Explore the services and characteristics or view live data updates.

## Notes

- Ensure that Bluetooth is enabled on your device.
- Some features may require specific permissions or device configurations.
- The Web Bluetooth API is not supported on all browsers or platforms.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
