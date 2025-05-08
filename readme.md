# SR08 J-Ring Service Explorer

A web-based tool for exploring Bluetooth Low Energy (BLE) services and characteristics on the SR08 J-Ring device. Connect, discover, and read all available services and characteristics, including heart rate, SpO2, and battery information.

---

## ⚠️ Important: Enable Experimental Web Bluetooth

To use this tool, you must enable the experimental **Web Bluetooth** feature in your browser settings.

- **For Chrome:**  
  1. Go to `chrome://flags/#enable-experimental-web-platform-features`
  2. Enable it.
  3. Restart your browser.

Other Chromium-based browsers may have similar settings.

---

## Features

- Connect to the SR08 J-Ring via Web Bluetooth
- Discover all available GATT services and characteristics
- Read and display values for known characteristics (Heart Rate, Battery Level, Device Name, etc.)
- Subscribe to notifications for real-time updates
- User-friendly log and notification display

---

## Usage

1. Open `Jring.html` in a supported web browser (such as Chrome or Edge with Web Bluetooth enabled).
2. Click **Connect to SR08** and select your SR08 J-Ring device.
3. Explore the discovered services and characteristics.
4. View logs and notifications in the provided panels.

---

## Requirements

- A compatible browser with [Web Bluetooth API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Bluetooth_API) support
- Experimental Web Bluetooth feature enabled (see above)
- SR08 J-Ring device

---

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.