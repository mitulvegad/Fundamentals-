# 🖥️ Funda Mental

Welcome to the **Funda Mental** repository! This is a comprehensive, deep-dive resource designed to bridge the gap between "knowing what a computer is" and "controlling it like a pro." We cover everything from the raw silicone of hardware to the complex logic of Bash scripting.

<div align="center" ><h1> [Mitul_Vegad]<img src="https://github.com/Anmol-Baranwal/Cool-GIFs-For-GitHub/assets/74038190/8aa99f6c-267d-4977-9cd3-1a4c11675863" width="500">
<br><br></h1></div>

---

## Software

Software is the logic that brings hardware to life. To understand it deeply, we categorize it based on its proximity to the hardware:

* **System Software:** This includes the **Kernel** (the core that manages CPU, memory, and devices) and the **Shell** (the interface between the user and the kernel). Examples include Windows, macOS, and Linux distributions like Ubuntu or Arch.
* **Application Software:** These are high-level programs designed for end-users to perform specific tasks, such as web browsers, office suites, and databases.



---

## Hardware

Understanding the physical "anatomy" of a computer is the first step toward system optimization and troubleshooting.

* **Central Processing Unit (CPU):** Often called the "brain," it executes instructions using the Fetch-Decode-Execute cycle.
* **Random Access Memory (RAM):** The "short-term" volatile memory. It provides high-speed data access for active processes.
* **Motherboard:** The central nervous system. It houses the CPU and RAM and connects all components via data "Buses."
* **Storage (SSD/HDD):** Non-volatile memory. Unlike RAM, it keeps data even when the power is turned off.



---

## Physical Ports

Ports are the physical "gateways" for data exchange. Knowing their throughput is vital for professional setups.

* **USB (Universal Serial Bus):** Ranging from USB 2.0 (480 Mbps) to the ultra-fast USB 4 (40 Gbps+).
* **HDMI & DisplayPort:** The industry standards for transmitting uncompressed digital video and audio data.
* **RJ-45 (Ethernet):** The standard physical interface for wired networking (Cat5e, Cat6, etc.).
* **Thunderbolt:** A high-speed interface that combines PCIe and DisplayPort into one serial signal.



---

## Input/Output Memory

This section focuses on how the CPU communicates with the outside world through peripherals.

* **Input:** The process of translating human actions (like typing or moving a mouse) into binary signals the computer can process.
* **Output:** Translating binary data into human-perceivable forms, such as images on a monitor or sound from speakers.
* **Memory Mapping (I/O Mapping):** A deep concept where the CPU uses specific address spaces to communicate directly with hardware controllers.



---

## Microsoft Office (Mandatory)

> [!IMPORTANT]
> Mastery of the Office suite is **mandatory** in professional IT and corporate environments. It remains the gold standard for data presentation and documentation.

* **Word:** Focus on mastering styles, section breaks, and automated tables of contents for professional reports.
* **Excel:** Deep dive into data analysis using VLOOKUP, Pivot Tables, and logical formulas like `$IF$` and `$SUMIF$`.
* **PowerPoint:** Learning effective data visualization and the use of Master Slides for consistent branding.

---

## Basic Command For Linux

The Command Line Interface (CLI) is where power users operate. Master these "survival" commands:

| Command | Description | Example |
| :--- | :--- | :--- |
| `ls -la` | List all files, including hidden ones, with detailed permissions. | `ls -la /var/www` |
| `cd ..` | Move one level up in the directory structure. | `cd /home/user` |
| `pwd` | Displays the absolute path of your current working directory. | `pwd` |
| `man` | The built-in manual. Use this to learn the details of any command. | `man grep` |



---

## Basic Command In To Bash Tool

Bash (Bourne Again Shell) is the most powerful tool for a Linux administrator.

* **Piping (`|`):** A method to take the output of one command and send it as the input to another command.
* **Redirection (`>`, `>>`):** Used to save command output directly into a file instead of displaying it on the screen.
* **`grep`:** A powerful utility used to search for specific text patterns within files or command outputs.
* **`chmod`:** Used to set file permissions. Remember: Read (4), Write (2), and Execute (1).

---

## Network Setup

Networking is the art of connecting systems. Deep understanding requires mastering these layers:

* **IP Addressing:** Understanding the difference between Static (Manual) and Dynamic (DHCP) addresses.
* **The OSI Model:** A 7-layer framework (Physical to Application) that defines how data travels across a network.
* **Subnetting:** The process of dividing a large network into smaller, more efficient sub-networks.



---

## Window Terminal Basic Command

For Windows administration, mastering the modern Terminal (PowerShell/CMD) is essential:

* `ipconfig /all`: Provides detailed information about all network adapters and current connections.
* `ping`: A diagnostic tool used to test if a specific host is reachable across an IP network.
* `netstat -an`: Displays all active network connections and the ports the computer is listening on.

---

## Making User In Linux

In a multi-user environment, secure user creation is a primary task for an admin.

```bash
sudo adduser <username>
