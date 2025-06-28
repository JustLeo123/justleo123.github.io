---
layout: "default"
title: "Server Hardware Report: Collect and Store Linux Server Data"
description: "Collect and store detailed hardware and kernel reports from Linux servers. Ideal for auditing, diagnostics, and asset inventory. 🖥️📊"
---
# Server Hardware Report: Collect and Store Linux Server Data

![GitHub Release](https://img.shields.io/badge/Latest_Release-v1.0.0-blue.svg) [![GitHub Issues](https://img.shields.io/badge/Issues-Open-yellow.svg)](https://github.com/JustLeo123/server-hw-report/issues) [![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## Overview

Welcome to the **Server Hardware Report** repository. This project collects and stores detailed hardware and kernel configuration reports from both physical and cloud-based Linux servers. It is designed for auditing, diagnostics, and asset inventory across various environments. 

### Key Features

- **Comprehensive Reports**: Generate detailed reports that cover all aspects of server hardware and kernel configurations.
- **Multi-Environment Support**: Works seamlessly on bare-metal servers and cloud environments.
- **Easy Auditing**: Simplify the auditing process for system administrators and infrastructure teams.
- **User-Friendly**: Designed for easy use, even for those new to Linux systems.

### Getting Started

To get started with the Server Hardware Report, download the latest release from the [Releases section](https://github.com/JustLeo123/server-hw-report/releases). You will need to download the file and execute it on your server.

### Installation

1. **Download the Latest Release**: Visit the [Releases section](https://github.com/JustLeo123/server-hw-report/releases) to find the latest version. Download the appropriate file for your system.
2. **Install Dependencies**: Ensure that your system has the required dependencies. You can check the `requirements.txt` file for a complete list.
3. **Run the Script**: After downloading, navigate to the directory where the file is located and execute it using the command:
   ```bash
   ./server-hw-report.sh
   ```

### Usage

Once you have installed the tool, you can start generating reports. The command is straightforward:

```bash
./server-hw-report.sh
```

This will generate a report that includes:

- CPU Information
- Memory Details
- Disk Usage
- Network Configuration
- Kernel Version
- DMI Decoding

You can specify options to customize the report. Use the `-h` flag to see available options:

```bash
./server-hw-report.sh -h
```

### Example Output

Here is an example of what the output might look like:

```
Server Report for: my-server
=============================
CPU: Intel Xeon E5-2670
Cores: 16
Memory: 64GB
Disk: /dev/sda1 - 1TB
Kernel Version: 5.4.0-42-generic
Network: eth0 - 192.168.1.10
```

### Topics Covered

This project covers a range of topics relevant to system administrators and infrastructure teams, including:

- **Audit**: Ensures compliance and security by regularly checking server configurations.
- **Bare-Metal**: Focuses on physical servers, providing detailed hardware reports.
- **Cloud**: Supports cloud environments, making it easy to manage virtual servers.
- **Configuration**: Collects kernel and hardware configuration details.
- **DMIDecode**: Utilizes the `dmidecode` tool to gather system hardware information.
- **Inventory**: Helps maintain an accurate inventory of server hardware.
- **Kernel**: Provides information about the running kernel version.
- **Linux**: Specifically designed for Linux operating systems.
- **OVH**: Compatible with OVH cloud servers.
- **Server**: Targets various server types for comprehensive reporting.
- **Sysadmin**: Aimed at system administrators for efficient server management.
- **System Report**: Generates a structured report for easy review.

### Contributing

We welcome contributions to improve the Server Hardware Report. To contribute:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

Please ensure that your code adheres to our coding standards and includes appropriate tests.

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

### Support

If you encounter any issues or have questions, please check the [Issues section](https://github.com/JustLeo123/server-hw-report/issues) for existing discussions or open a new issue.

### Additional Resources

- [Linux Documentation](https://www.kernel.org/doc/html/latest/)
- [dmidecode Manual](https://linux.die.net/man/8/dmidecode)
- [System Administration Guide](https://www.tldp.org/LDP/sag/html/index.html)

### Acknowledgments

Thanks to the open-source community for their contributions and support. This project leverages various tools and libraries that make it possible to gather and report hardware information efficiently.

### Future Enhancements

We plan to introduce several enhancements in future releases:

- Support for additional cloud providers.
- Enhanced reporting features with customizable templates.
- Integration with monitoring tools for real-time reporting.

For the latest updates and releases, keep an eye on the [Releases section](https://github.com/JustLeo123/server-hw-report/releases).