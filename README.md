[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# Gesture-Controlled Debian System with Google's MediaPipe and i3wm

## Introduction

This project combines the power of Google's MediaPipe library for gesture recognition with the efficient window management of i3wm on Debian-based systems. With this system, users can interact with their desktop environment using intuitive hand gestures, offering a novel and efficient way to control their Debian system.

[![Gesture-Controlled Debian System](https://res.cloudinary.com/marcomontalbano/image/upload/v1710108882/video_to_markdown/images/video--fe7ee2e6580ced31f4b1501092a31c11-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://raw.githubusercontent.com/zangjiucheng/GestureVision/main/demo.mp4 "Gesture-Controlled Debian System]")

## Features

- **Gesture Recognition**: Utilize MediaPipe's advanced machine learning models to accurately recognize a variety of hand gestures.
  
- **i3wm Integration**: Seamlessly control window placement, workspace switching, and other desktop actions using gestures within the i3wm environment.

- **Customizable Controls**: Personalize gesture actions according to your preferences, allowing for a tailored user experience.

- **Efficient Performance**: Benefit from the efficiency and performance of both MediaPipe and i3wm, ensuring smooth and responsive gesture-based control without compromising system resources.

- **Open-Source and Extensible**: The project is open-source, welcoming contributions to enhance functionality, add new gestures, and improve compatibility with different Debian-based systems.

## Getting Started

To get started with Gesture-Controlled Debian System, ensure you have the following prerequisites:

- Python 3 installed on your Debian-based Linux system.
- i3wm window manager installed and configured.
- A Debian-based Linux distribution (e.g., Debian, Ubuntu).

### 1. Clone the Repository

```bash
git clone https://github.com/your_username/Gesture-Controlled-Debian-System.git
```

### 2. Install Dependencies

Navigate to the project directory and install the required Python packages using pip:

```bash
cd GestureVision
pip install -r requirements.txt
```

### 3. Run the Application

Execute the main Python script to start the Gesture-Controlled Debian System:

```bash
python3 LinuxDebiani3main/main.py
```

This will launch the application, enabling gesture control within the i3wm environment. Follow the on-screen instructions or refer to the user manual for guidance on using gestures to interact with your Debian system.

### 4. Customize Gesture Actions (Optional)

If desired, you can customize gesture actions by modifying the 'Function.py' configuration file make sure it match the config with i3.

### 5. Explore and Enjoy

Experiment with different gestures and explore the capabilities of the Gesture-Controlled Debian System. We hope you find this innovative way of interacting with your desktop environment both intuitive and efficient!

If you encounter any issues or have questions, please refer to the documentation or feel free to reach out to us for assistance. Happy gesturing!

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- Our gratitude to the developers of Google's MediaPipe library and the i3wm window manager for their invaluable contributions to open-source software.

## Contact

For any questions, suggestions, or feedback, please feel free to [contact me](mailto:jiucheng.zang@proton.me).

