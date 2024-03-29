
# Friday Voice Assistant  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<img src="https://image.lexica.art/full_webp/535f8a6a-f1c4-42a6-af4d-2929e41897a1" alt="Friday Logo" width="100%" height="450" />

## Table of Contents
- [Overview](#overview)
- [Why Friday?](#why-friday)
- [Features](#features)
- [Getting Started](#getting-started)
- [Code Examples](#code-examples)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [Credits](#credits)
- [License](#license)

## Overview
Friday is your personal voice assistant, drawing inspiration from `J.A.R.V.I.S in Iron Man`. It's here to assist you in various tasks and streamline your daily activities, just like Tony Stark's trusted companion.

## Why Friday?
- **Efficiency:** Simplify task management, streamline information retrieval, and interact seamlessly with your applications.
- **Inspiration:** Modeled after the iconic J.A.R.V.I.S to recreate its unparalleled functionalities.
- **Learning:** An opportunity to experiment and explore voice recognition, natural language processing, and automation.

## Features
- **Voice and Language:** Cutting-edge voice recognition and natural language processing capabilities.
- **Task Management:** Efficiently handle files, open applications, simulate keystrokes, and more.
- **Development Support:** Expert assistance tailored to VS Code and other development tasks.
- **Customization:** Configure its personality and language settings for a personalized experience.

## Getting Started
1. **Clone the repository.**
2. **Set up Dependencies:** Use `requirements.txt` to install necessary packages.
3. **Personalise User details and Assistant detail :** open `User_details.json` and modify it then open `Assistant_detail.json` and modify it
4. **Run Friday:** Execute `main.py` to launch your Friday voice assistant.

## Code Examples

### Opening Applications
```python
import os

def open_application(app_name):
    if app_name.lower() == "notepad":
        os.system("notepad.exe")
    elif app_name.lower() == "calculator":
        os.system("calc.exe")
    else:
        print("Application not supported")
```

## Roadmap
### Version 2.0 (Upcoming Release)
- Getting function my a trained `Ml model`.
- Enhance support for more applications and file types.
- Improve expert assistance for development tasks.
- Introduce customizable themes and personalities.

### Future Enhancements
- Integration with `smart home devices`.
- Advanced `natural language processing` capabilities.
- Extensive documentation and tutorials.
- `Ai` integrating 
## Contributing
Contributions and feedback are encouraged! Feel free to open issues or pull requests to enhance Friday's capabilities.

## Credits
Developed by Utkarsh Chaudhary

## License
This project is licensed under the Utkarsh Chaudhary License.
