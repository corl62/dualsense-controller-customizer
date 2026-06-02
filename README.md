# DualSense Controller Customizer

A web-based utility tool that harnesses the power of the PS5 DualSense controller's advanced features including haptic feedback, adaptive triggers, motion controls, and touch pad interaction.

## Features

- **Haptic Feedback**: Create and customize vibration patterns with different intensities and durations
- **Adaptive Triggers**: Control trigger resistance and tension for immersive gameplay
- **Motion Controls**: Visualize and interact with accelerometer and gyroscope data in real-time
- **Touch Pad Detection**: Detect and respond to touch pad interactions
- **Real-time Controller Status**: Monitor all controller inputs and sensors
- **Custom Presets**: Save and load your favorite controller configurations
- **Button & Stick Mapping**: See live input from all buttons and analog sticks

## Getting Started

1. Clone the repository
   ```bash
   git clone https://github.com/corl62/dualsense-controller-customizer.git
   cd dualsense-controller-customizer
   ```

2. Open `index.html` in a modern web browser (Chrome, Edge, Firefox)

3. Connect your DualSense controller to your computer

4. Press any button on the controller to connect and start using the tool

### Browser Requirements

- Chrome/Chromium 78+
- Edge 79+
- Firefox 55+
- Must support the Gamepad API

## Project Structure

```
├── index.html              # Main HTML file with UI structure
├── css/
│   └── styles.css          # Complete styling and layout
├── js/
│   ├── main.js             # Main application logic and initialization
│   ├── gamepad.js          # Gamepad API wrapper and input detection
│   ├── haptics.js          # Haptic feedback controller
│   ├── triggers.js         # Adaptive triggers controller
│   ├── motion.js           # Motion controls visualization
│   └── ui.js               # UI update functions
└── README.md
```

## How to Use

### 1. **Connect Your Controller**
   - Open the tool in your browser
   - Connect your DualSense controller via USB or Bluetooth
   - Press any button to initiate connection

### 2. **Haptic Feedback**
   - Use the haptic feedback panel to create custom vibration patterns
   - Adjust intensity and duration
   - Save presets for later use

### 3. **Adaptive Triggers**
   - Configure left and right trigger resistance
   - Set trigger tension profiles
   - Test in real-time

### 4. **Motion Controls**
   - View accelerometer and gyroscope data
   - See real-time motion visualization
   - Monitor sensor values

### 5. **Input Monitoring**
   - Watch all button presses in real-time
   - See analog stick positions
   - Track touch pad interactions

## API Documentation

### Gamepad API
The project uses the standard Gamepad API to detect controller inputs and access extended features.

### Haptic Feedback
Implements vibration patterns using the gamepad's vibrate capabilities.

### Adaptive Triggers
Controls trigger resistance through WebXR or proprietary APIs (browser-dependent).

### Motion Controls
Accesses accelerometer and gyroscope data through the Gamepad API's extended properties.

## Browser Support

| Feature | Chrome | Firefox | Safari | Edge |
|---------|--------|---------|--------|------|
| Gamepad API | ✅ | ✅ | ⚠️ | ✅ |
| Haptic Feedback | ✅ | ✅ | ❌ | ✅ |
| Motion Controls | ✅ | ⚠️ | ⚠️ | ✅ |
| Adaptive Triggers | ⚠️ | ❌ | ❌ | ⚠️ |

## License

MIT License - See LICENSE file for details

## Contributing

Feel free to open issues and submit pull requests!

## Resources

- [MDN Gamepad API Documentation](https://developer.mozilla.org/en-US/docs/Web/API/Gamepad_API)
- [W3C Gamepad Specification](https://w3c.github.io/gamepad/)
- [DualSense Controller Documentation](https://www.playstation.com/en-us/accessories/dualsense-wireless-controller/)

## Support

For issues, questions, or feature requests, please open an issue on the GitHub repository.
