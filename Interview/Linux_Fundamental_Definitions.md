# Linux Fundamental Definitions (Interview Notes)

**Bootcamp:** 180-Day Cloud Architect Bootcamp  
**Author:** Mayuresh Tripathi  
**Topic:** Linux Fundamentals - Interview Definitions

---

# 1. What is an Operating System (OS)?

## Professional Definition

An Operating System (OS) is system software that manages computer hardware and software resources, provides services to applications, and acts as an interface between the user and the computer hardware.

## Simple Definition

The Operating System is the complete software that allows users to interact with the computer while managing all hardware and software resources.

## Examples

- Windows
- Ubuntu
- Debian
- Red Hat Enterprise Linux
- macOS

---

# 2. What is the Kernel?

## Professional Definition

The Kernel is the core component of an Operating System responsible for managing hardware resources and enabling communication between software and hardware.

## Simple Definition

The Kernel is the manager of the computer. It controls CPU, RAM, storage devices, and other hardware resources.

## Responsibilities

- Process Management
- Memory Management
- CPU Scheduling
- Device Management
- File System Management
- Security & Permission Management

---

# 3. Difference Between Operating System and Kernel

| Operating System | Kernel |
|------------------|---------|
| Complete system software | Core component of the Operating System |
| Contains multiple components | One component of the Operating System |
| Provides the complete user environment | Manages hardware resources |
| Example: Ubuntu, Windows | Example: Linux Kernel, Windows NT Kernel |

---

# 4. What is the Terminal?

## Professional Definition

The Terminal is an application that provides a Command-Line Interface (CLI) through which users interact with the operating system by entering commands.

## Simple Definition

The Terminal is the application where users type commands and view the results.

## Examples

- Windows Terminal
- GNOME Terminal
- Konsole
- xterm

---

# 5. What is the Shell?

## Professional Definition

The Shell is a command-line interpreter that reads user commands, interprets them, and communicates with the Kernel to execute those commands.

## Simple Definition

The Shell understands the user's commands and passes them to the Kernel for execution.

---

# 6. What is Bash?

## Professional Definition

Bash (Bourne Again SHell) is the most widely used Linux shell. It interprets user commands and provides scripting capabilities for task automation.

## Simple Definition

Bash is the most popular Linux Shell that understands commands and automates tasks.

## Why Bash is Important

- Interprets Linux commands
- Runs Shell Scripts
- Automates repetitive tasks
- Default shell in many Linux distributions

---

# 7. What is a Shell Script?

## Professional Definition

A Shell Script is a text file containing a sequence of shell commands that are executed automatically by the Shell.

## Simple Definition

A Shell Script is a file that stores multiple Linux commands so they can be executed together.

## Example

```bash
#!/bin/bash

mkdir Project
cd Project
touch README.md
```

---

# 8. What is SSH?

## Professional Definition

SSH (Secure Shell) is a secure network protocol that allows users to remotely access and manage another computer through an encrypted command-line connection.

## Simple Definition

SSH allows you to securely control a remote computer from your own computer.

## Example

Local Laptop → AWS EC2 Server

---

# 9. What is a Package?

## Professional Definition

A Package is a bundled collection of software, libraries, configuration files, and metadata required to install and run an application.

## Simple Definition

A Package is a software bundle that contains everything needed to install and run an application.

## Examples

- Git
- Docker
- Python
- Nginx
- Google Chrome

---

# 10. What is a Package Manager?

## Professional Definition

A Package Manager is software that installs, updates, upgrades, removes, and manages software packages automatically.

## Simple Definition

A Package Manager is like an app store for Linux that manages software installation and updates.

---

# 11. What is APT?

## Professional Definition

APT (Advanced Package Tool) is the package management system used in Ubuntu and Debian-based Linux distributions for installing, updating, upgrading, and removing software packages.

## Simple Definition

APT is Ubuntu's Package Manager used to install and manage software.

## Common Commands

```bash
sudo apt update
sudo apt install git
sudo apt upgrade
sudo apt remove git
```

---

# 12. What is a Process?

## Professional Definition

A Process is an instance of a program that is currently running and being managed by the Operating System.

## Simple Definition

A Process is a program that is currently running.

## Examples

- Chrome running
- VS Code running
- Terminal running

---

# Linux Command Execution Flow

Suppose the user types:

```bash
mkdir Project
```

The execution flow is:

```text
User
   │
   ▼
Terminal
(Accepts user input)
   │
   ▼
Bash (Shell)
(Interprets the command)
   │
   ▼
Kernel
(Checks permissions and manages hardware resources)
   │
   ▼
File System / SSD
(Creates the folder)
   │
   ▼
Kernel
(Returns the result)
   │
   ▼
Bash
   │
   ▼
Terminal
(Displays output)
```

---

# Linux Architecture

```text
Operating System
│
├── Kernel
├── Shell (Bash)
├── Terminal
├── Package Manager (APT)
├── File System
├── Device Drivers
├── System Libraries
└── Applications
```

---

# Top Interview Questions

## Q1. What is an Operating System?

An Operating System is system software that manages hardware resources, provides services to applications, and acts as an interface between the user and the hardware.

---

## Q2. What is the Kernel?

The Kernel is the core component of the Operating System responsible for managing hardware resources and communication between software and hardware.

---

## Q3. Differentiate between Operating System and Kernel.

The Operating System is the complete software environment containing multiple components, whereas the Kernel is its core component responsible for hardware management.

---

## Q4. What is the Terminal?

The Terminal is an application that provides a command-line interface for interacting with the operating system.

---

## Q5. What is the Shell?

The Shell is a command interpreter that reads user commands and communicates with the Kernel to execute them.

---

## Q6. What is Bash?

Bash (Bourne Again SHell) is the most widely used Linux shell and scripting language used to interpret commands and automate tasks.

---

## Q7. What is SSH?

SSH (Secure Shell) is a secure protocol used to remotely access and manage another computer over an encrypted network.

---

## Q8. What is a Package?

A Package is a software bundle containing all the files required to install and run an application.

---

## Q9. What is a Package Manager?

A Package Manager is software that installs, updates, removes, and manages software packages automatically.

---

## Q10. What is APT?

APT (Advanced Package Tool) is Ubuntu's package manager used to manage software packages.

---

## Q11. Explain the execution flow of `mkdir Project`.

**Answer:**

User → Terminal → Bash → Kernel → File System/SSD → Kernel → Bash → Terminal → Output

---

# Quick Revision

| Concept | Remember As |
|----------|-------------|
| Operating System | Complete System Software |
| Kernel | Core Manager |
| Terminal | Command-Line Application |
| Shell | Command Interpreter |
| Bash | Most Popular Linux Shell |
| Shell Script | File containing Shell commands |
| SSH | Secure Remote Access Protocol |
| Package | Software Bundle |
| Package Manager | Software Installer |
| APT | Ubuntu Package Manager |
| Process | Running Program |

---

# Memory Formula

```text
Operating System
│
├── Kernel
├── Terminal
├── Shell (Bash)
├── Package Manager (APT)
├── Drivers
├── Libraries
└── Applications

Command Flow

User
↓
Terminal
↓
Bash
↓
Kernel
↓
Hardware
↓
Output
```

---

# Key Takeaways

- The Operating System is the complete software environment.
- The Kernel is the core component that manages hardware.
- The Terminal accepts user input.
- The Shell interprets commands.
- Bash is the most common Linux Shell.
- Shell Scripts automate repetitive tasks.
- SSH securely connects to remote systems.
- A Package is a software bundle.
- A Package Manager installs and manages software.
- APT is Ubuntu's default Package Manager.
- Every running application is called a Process.
