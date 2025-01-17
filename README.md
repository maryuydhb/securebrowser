# SecureBrowser

## Overview

SecureBrowser is a Python application that provides a secure browsing environment by isolating internet activities from the rest of the Windows system. It achieves this by utilizing Windows Sandbox technology to create a temporary and isolated environment for web browsing.

## Features

- **Isolation**: Runs the browser in a Windows Sandbox to ensure that browsing activities do not affect the main system.
- **Temporary Environment**: Uses temporary directories which are cleaned up after the browsing session ends.
- **Easy to Use**: Start and stop the secure browser with simple commands.

## Requirements

- Windows 10 Pro, Enterprise or Education with Windows Sandbox enabled.
- Python 3.x installed on your system.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/SecureBrowser.git
    ```
2. Navigate to the project directory:
    ```bash
    cd SecureBrowser
    ```
3. Install necessary Python dependencies (if any).

## Usage

1. Run `secure_browser.py` using Python:
    ```bash
    python secure_browser.py
    ```
2. The program will start the secure browser in a sandboxed environment.
3. Press `Enter` in the console to stop the Secure Browser.
4. The application will automatically clean up temporary files upon exit.

## Limitations

- Requires Windows Sandbox, which is only available on certain editions of Windows 10.
- The sandbox environment is reset after each session, meaning no data is saved between sessions.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with your improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
```

Note: The above code is a conceptual representation and assumes the existence of Windows Sandbox on the system. Actual implementation might require adjustments based on system capabilities and specific requirements.