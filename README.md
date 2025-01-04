<<<<<<< HEAD
# IP_Address_Generator_Tool
=======
# IP Address Converter Tool

A user-friendly GUI tool for IP address calculations and subnet planning, perfect for network administrators and IT professionals.

![IP Address Converter Tool Main Interface](screenshots/Screenshot%202025-01-04%20190814.png)

![IP Address Converter Tool Results](screenshots/Screenshot%202025-01-04%20190848.png)

## ✨ Features

- 🔢 Input IP address in octet format (e.g., 192.168.1.0)
- 🎯 Specify subnet mask (0-32)
- 💻 Calculate required IP addresses based on number of devices
- 📊 Automatic subnet calculations
- 📝 Display detailed subnet information
- 🌐 Show network and broadcast addresses
- 📋 List available IP ranges for each subnet
- 🎨 Modern and intuitive graphical interface

## 🚀 Quick Start Guide

### Method 1: Direct Download
1. Download the latest release from: [IP Address Converter v1.0.0](https://github.com/Moatasem-Official/IP_Address_Generator_Tool/releases/tag/v1.0.0)
2. Extract the ZIP file
3. Run `IP_Address_Converter.exe`

### Method 2: Run from Source
1. Clone the repository:
   ```bash
   git clone https://github.com/Moatasem-Official/IP_Address_Generator_Tool.git
   cd IP_Address_Generator_Tool
   ```

2. Make sure you have Python 3.8+ installed

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:
   ```bash
   python ip_converter_gui.py
   ```

## 🚀 Installation

### Prerequisites
- Python 3.8 or higher
- pip (Python package installer)

### Steps

1. Download the tool:
   ```bash
   git clone https://github.com/Moatasem-Official/IP_Address_Generator_Tool.git
   cd IP_Address_Generator_Tool
   ```

2. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   
   # On Windows:
   .\venv\Scripts\activate
   
   # On Linux/Mac:
   source venv/bin/activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 📝 How to Use

1. Start the application:
   ```bash
   python ip_converter_gui.py
   ```

2. Enter your IP information:
   - Type the IP address in the four octet fields (default: 192.168.1.0)
   - Enter the subnet mask (default: 24)
   - Specify the number of devices needed

3. Click "Generate" to calculate

4. View the results:
   - Required IP addresses
   - Optimal subnet mask
   - Network details
   - Available IP ranges
   - Network and broadcast addresses

## 📝 Example Usage

1. Planning a small office network:
   - IP Address: 192.168.1.0
   - Current Subnet Mask: 24
   - Number of Devices: 50
   
   The tool will calculate the optimal subnet to accommodate your devices while maintaining network efficiency.

2. Dividing a network into subnets:
   - Enter your network details
   - The tool will show you all possible subnets with their ranges

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

Created by MOATASEM

## 🆘 Support

If you encounter any issues or need help:
- Open an issue on [GitHub](https://github.com/Moatasem-Official/IP_Address_Generator_Tool/issues)
- Star the repository if you find it useful! ⭐

## 📊 Version History

- v1.0.0 (2024) - Initial release
  - Basic IP conversion functionality
  - GUI interface
  - Subnet calculations
>>>>>>> 816a850 (Initial commit: Add IP Address Generator Tool files)
