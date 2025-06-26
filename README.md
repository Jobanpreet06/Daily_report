# Daily Report
## 1st day of training
**Orientation**

Starting the day with the introduction to our parent department, Computer Science and Engineering in the auditorium. Dr Priyanka introduced us with our department, about departmental library, socities and clubs, faculty. Then Dr Kiran Jyoti (Head of Deparment) gave us a brief overview about the syllabus, new pattern and the changes made to the scheme. Afterwards, we were guided to our respective labs.

**Introduction to linux:**
Linux was developed by a person named Linus in 1991. Linux is a powerful, open source operating system.

*Linux is preferred over windows due to its numerous features:*

Open Source & Free

Stability & Reliability

Provides Security

Run efficiently

Developer Friendly

**Difference between Linux and Windows**
| Features | Linux | Windows |
| :---: | :---: | :---: |
| Cost | Usually free | Paid license required |
| Source code | Open source(free to access) | Not an open source |
| Security | It is more secure as admin password is required | It is not secure as there is a risk of viruses |
| Stability | Very stable | Can be less stable |
| Customizability | Linux offers extensive customization options, allowing users to modify everything from the desktop environment to the core components | Windows provides limited customization compared to Linux, with more rigid control over the core structure and functionalities |

**Installing Linux Operating System**

It include installation of three softwares:

*Steps:-*

1.Oracle Virtual Machine https://download.virtualbox.org/virtualbox/7.0.20/VirtualBox-7.0.20-163906-Win.exe 

*Oracle virtual box is a powerful, open-source virtualization software that allows users to run multiple operating systems on a single machine, making it ideal for development, testing, and deployment.Thus, it is installed first as it enables users to run operating systems such as Windows , macOS, Linux.*

2.Microsoft Visual C++ https://download.visualstudio.microsoft.com/download/pr/40b59c73-1480-4caf-ab5b-4886f176bf71/D62841375B90782B1829483AC75695CCEF680A8F13E7DE569B992EF33C6CD14A/VC_redist.x64.exe

3.Ubuntu 24.04.2 https://login.gndec.ac.in/ubuntu-24.04.2-desktop-amd64.iso

4.After installing Oracle virtual machine and Microsoft Visual C++, install Ubuntu 24.04.02.

5.Set Up Ubuntu in VirtualBox:

    Open VirtualBox

    Click New > Name: e.g., Ubuntu VM

    Select the path of Ubuntu in iso image

    Set:
            Type: Linux
            Version: Ubuntu (64-bit)
    
    Enter the username and password

    Set the required memory space and processors

**Product based companies:**

- Develop and sell their own products
- Earn from selling/licensing products
- Google, Microsoft, Adobe, Apple
- Own and maintain their own codebase

**Service based companies:**

- Provide services or solutions to other businesses
- Earn from client contracts
- Infosys, TCS, Wipro, Accenture
- Work on client-owned codebases

**Startups:**

- Startups are newly established companies aiming to solve problems with innovative solutions.
- They focus on rapid growth and scalability, often with limited resources.
- Common goal: grow fast, get acquired, or go public

**Career Opportunities Using Linux**

1. System Administrator

2. DevOps Engineer

3. Cloud Engineer

4. Linux Administrator

5. Cybersecurity Analyst

6. QA/Test Engineer

7. Database Administrator

8. Software Developer

**Booting**

Booting is the process of starting up a computer and loading the operating system (OS) into the computer's memory so that it can be used. When you turn on a computer, it performs a series of steps to prepare the hardware and software for use.

**Types of Booting**

1.Cold Booting (Hard Booting)

This happens when you turn on the computer from a completely powered-off state. Examples include Linux and MacOS.

2.Warm Booting (Soft Booting)

This happens when you restart the computer without turning off the power completely. Examples include Windows.

## 2nd day of training

In today's class, we learnt about:

**Kernel**

The kernel is the core part of an operating system. It acts as a bridge between the computer hardware and the software applications. The kernel manages system resources such as the CPU, memory, and input/output devices, ensuring that programs run smoothly and efficiently.

![alt text](shell.png)

**Shell**

The shell is a user interface that allows you to interact with the operating system. It takes commands from the user and tells the OS what to do.

**Types of Shells**

bash: Enhanced sh with more features, widely used on Linux.

sh: Basic Unix shell, mainly for scripting and compatibility.

zsh: Feature-rich, highly customizable shell popular among power users.

fish: User-friendly shell with smart features and easy syntax.

**Categories of Shells:**

- Command-Line Shell: You type text commands (like in Windows Command Prompt or Linux Terminal).
- Graphical Shell: You use graphical elements like icons and menus (like Windows Explorer or macOS Finder).

**File System Structure (/, /home, /etc, /var etc)**

The root directory, represented by a single slash /, is the top-level directory of the entire Linux file system hierarchy. All files and directories branch out from this root directory.

![alt text](linux-file-system-tutorial-1.png)

| Directory | Description |
|-----------|-------------|
| `/`       | Root directory – the top of the file system |
| `/bin`    | Essential binary commands (e.g., `ls`, `cp`) |
| `/boot`   | Boot loader files, including the Linux kernel |
| `/dev`    | Device files (e.g., hard drives, USBs) |
| `/etc`    | Configuration files for the system and applications |
| `/home`   | User home directories (e.g., `/home/user`) |
| `/lib`    | Shared libraries needed by programs in `/bin` and `/sbin` |
| `/media`  | Mount point for removable media (e.g., USB drives) |
| `/mnt`    | Temporary mount point for filesystems |
| `/opt`    | Optional software and third-party applications |
| `/proc`   | Virtual filesystem for system information (kernel, processes) |
| `/root`   | Home directory for the root user |
| `/run`    | Runtime data for processes |
| `/sbin`   | System administration binaries (e.g., `shutdown`, `reboot`) |
| `/srv`    | Data for services like FTP, web servers |
| `/tmp`    | Temporary files (cleared on reboot) |
| `/usr`    | User applications and files (e.g., `/usr/bin`, `/usr/lib`) |
| `/var`    | Variable data (e.g., logs, mail, print spool files) |

**Commands**

Commands are instructions you type into the terminal to tell the computer to perform specific tasks like managing files, running programs, or checking system status.

**ls** - Lists files and directories

![alt text](t.jpg)

**whoami** - Displays the username of the current user.

![alt text](whoami.png)

**date** - Displays the current date and time of the system.

![alt text](date.png)

**cd** - Changes the current directory

![alt text](cd.png)

**mkdir** - Creates a new directory

![alt text](mkdir.png)

**cat** - Displays contents of a file

![alt text](cat.png)

**touch** - creates empty files or updates the modification time of existing files.

![alt text](touch.png)

**cp** - Copies files or directories

![alt text](cp.png)

**mv** - Moves or renames files or directories

![alt text](mv.png)

**whereis** - Locates the binary, source, and manual files for a command.

![alt text](whereis.png)

**whatis** - Gives a one-line description of a command or program.

![alt text](whatis.png)

**pwd** - Shows the current directory path

![alt text](pwd.png)
