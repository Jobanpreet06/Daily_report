## Daily Report
# 1st day of training
**Orientation**

Started the day with the introduction to our parent department, Computer Science and Engineering in the auditorium. Dr Priyanka introduced us with our department, about departmental library, socities and clubs, faculty. Then Dr Kiran Jyoti (Head of Deparment) gave us a brief overview about the syllabus, new pattern and the changes made to the scheme. Afterwards, we were guided to our respective labs.

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

![alt text](image.jpg)

| Directory | Description |
|-----------|-------------|
| `/`       | Root directory – the top of the file system |
| `/bin`    | Essential binary commands |
| `/boot`   | Boot loader files, including the Linux kernel |
| `/dev`    | Device files |
| `/etc`    | Configuration files for the system and applications |
| `/home`   | User home directories |
| `/lib`    | Shared libraries needed by programs in bin and sbin |
| `/media`  | Mount point for removable media |
| `/mnt`    | Temporary mount point for filesystems |
| `/opt`    | Optional software and third-party applications |
| `/proc`   | Virtual filesystem for system information (kernel, processes) |
| `/root`   | Home directory for the root user |
| `/run`    | Runtime data for processes |
| `/sbin`   | System administration binaries |
| `/srv`    | Data for services like FTP, web servers |
| `/tmp`    | Temporary files (cleared on reboot) |
| `/usr`    | User applications and files |
| `/var`    | Variable data |

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

**whereis** - Locates the binary, source, and manual files for a command.

![alt text](whereis.png)

**whatis** - Gives a one-line description of a command or program.

![alt text](whatis.png)

**pwd** - Shows the current directory path

![alt text](pwd.png)

**ASSIGNMENT**

**cp** - Copies files or directories

![alt text](cp.png)

**mv** - Moves or renames files or directories

![alt text](mv.png)

## 3rd day of training
**Bare metal installation**

Bare metal installation refers to installing an operating system (OS), software, or virtualization environment directly on the physical hardware of a server or computer, without any pre-installed OS or virtualization layer.

**VMware and virtual box**

| Feature           | VMware                              | VirtualBox                          |
|-------------------|--------------------------------------|--------------------------------------|
| Cost              | Paid (some free versions)            | Free and open-source                 |
| Performance       | Faster and more stable               | Slower, good for light use           |
| Use Case          | Best for professionals and servers   | Great for learning and testing       |
| Ease of Use       | Very polished                        | Simple and beginner-friendly         |
| Advanced Features | More enterprise tools                | Basic features                       |

**Dual boot**

Dual boot means installing two operating systems (OSes) on the same computer, so you can choose which one to use when the computer starts.

**Partitioning Schemes**

**MBR**

MBR (Master Boot Record) is an older partitioning system used on hard drives.
- Works on most old computers (BIOS systems).
- Can have up to 4 primary partitions.
- Supports drives up to 2 TB only.
  
**GPT**

GPT (GUID Partition Table) is a newer and better partitioning system used with modern computers.
- Supports more than 100 partitions.
- Works with large hard drives (over 2 TB).
- Stores multiple copies of data for safety.

**ISO**

An ISO file (or ISO image) is a copy of an entire CD, DVD, or installation disc saved as a single file. It's often used to distribute operating systems or software.

**FILE AND DIRECTORY PERMISSIONS**

Permissions control who can read, write, or execute a file or directory.

🔹**chmod**

chmod stands for change mode — it changes file or directory permissions.

Syntax: chmod +x filename.sh

**+x** changes the file to executable

![alt text](chmod.png)

🔹**chmod 444**

It sets the permissions of a file or directory to read-only for everyone:

- Owner, Group, and Others can only read the file.
- No one can modify (write) or run (execute) it.

Syntax: chmod 444 filename.sh

![alt text](wchmod444.png)

![alt text](chmod444.png)

🔹**chmod 644**

Gives permission only to the owner.

It sets the file permissions so that:

- The owner can read and write the file.
- The group and others can only read the file.
- No one has execute permission.
  
Syntax: chmod 644 filename.sh

![alt text](wchmod644.png)

![alt text](chmod644.png)

**ECHO**

echo is a command used to display text or variables to the screen or redirect them elsewhere (like into a file). It's available in Linux, Unix, Windows CMD, and many programming languages. It can be used for creating a file.

Syntax - echo text > filename.txt

![alt text](echo.png)

**REDIRECTION**

Redirection is the process of changing the flow of input or output in computing. It tells a system to send data somewhere else instead of using the default path.

Redirection lets you:

- Take input from a file instead of typing it.
- Send output to a file instead of the screen.
- Save error messages separately.

**Types of Redirection**

1. Standard Output Redirection (>)

Purpose: Sends output to a file (overwrites if it exists).

Example:

ls > files.txt

Saves output of ls to files.txt.

2. Append Output (>>)
    
Purpose: Sends output to a file without overwriting.

Example:

echo "New line" >> notes.txt

3. Standard Input Redirection (<)

Purpose: Takes input from a file instead of keyboard.

Example:

sort < names.txt

Sorts the contents of names.txt.

**PIPES**

Pipes (|) in Linux are used to connect the output of one command directly into the input of another — creating powerful command chains.

**Basic Syntax**

command1 | command2

- command1 → produces output
- command2 → takes that output as input

**How Pipes Work**

Behind the scenes:

- Each command runs in its own process.
- The stdout (standard output) of the first command is connected to the stdin (standard input) of the next command.

![alt text](pipe.png)

🔸**Wildcards**

Wildcards let you match filenames or strings with patterns. They're often used with commands like ls, cp, mv, and rm.

Examples - *.sh, file?.txt

| Wildcard | Meaning                      | Example                      |
|----------|------------------------------|------------------------------|
| `*`      | Matches zero or more characters | `*.txt` matches all `.txt` files |
| `?`      | Matches exactly one character | `file?.txt` matches `file1.txt`, `fileA.txt` |
| `[abc]`  | Matches one character listed  | `file[123].txt` matches `file1.txt`, `file2.txt`, or `file3.txt` |

**FILE COMPRESSION**

File compression is the process of reducing the size of a file by encoding its data more efficiently. This helps save disk space and makes it faster to transfer files over networks.

**How It Works:**

- Removing Redundancy: Compression algorithms look for patterns or repeated data in the file and represent them in a shorter way.
- Encoding Data: Instead of storing repeated data multiple times, the algorithm stores it once and uses references, codes, or symbols to represent repeated parts.

| Command                 | Syntax                     | Description                                                      |
|-------------------------|----------------------------|------------------------------------------------------------------|
| Compress file           | `gzip file.txt`             | Compress `file.txt` → creates `file.txt.gz`                      |
| Decompress file         | `gunzip file.txt.gz`        | Decompress `file.txt.gz` → restores `file.txt`                   |
| Compress & keep original| `gzip -k file.txt`          | Compress but **keep** original file                              |

**ASSIGNMENT**

**chown**

The chown command in Linux is used to change the ownership of files or directories. It lets you set the user and/or group that owns a file.

Syntax - chown [options] new_owner[:new_group] file_or_directory

- new_owner: the username or user ID to become the new owner
- new_group (optional): the group name or group ID to become the new group owner
- file_or_directory: the file or directory to change ownership for

**To read and display the details of a person using variables**

![alt text](detailsnano.png)

![alt text](details.png)

**Multiplication table of any number**

![alt text](tablenano.png)

![alt text](table.png)

**Comaparing two variables**

![alt text](comparenano.png)

![alt text](compare.png)

🔸**Escape Characters**

Escape characters let you prevent special interpretation of characters.

Examples - \*, \$, \"

| Escape Sequence | Meaning                           | Example                                           |
|-----------------|---------------------------------|---------------------------------------------------|
| `\`             | Escape next character literally | `rm file\*.txt` deletes a file literally named `file*.txt` |
| `\\`            | Literal backslash                | `echo "C:\\Users"` outputs `C:\Users`             |
| `\n`            | Newline (in scripts or echo -e) | `echo -e "Hello\nWorld"` prints on two lines      |
| `\t`            | Tab (in scripts or echo -e)      | `echo -e "Name\tAge"` outputs a tab between words |

🔸**Quoting**

Quoting controls how the shell interprets special characters (like $, *, !, &, etc.).

Quoting is enclosing text in single (') or double (") quotes to tell the shell to treat the enclosed characters literally or with some rules, preventing special characters (like wildcards, spaces, $, !, etc.) from being interpreted by the shell.

Examples - 'literal', "$var"

| Quote Type          | Description                                                    | Example                             |
|---------------------|----------------------------------------------------------------|-----------------------------------|
| Single quotes '...'  | Preserve the literal value of all characters inside. No expansion or interpretation happens. | 'file*.txt' — wildcard * treated literally, no matching |
| Double quotes "..."  | Preserve literal characters except $, `, and \. Variables and command substitution still work. | "file*.txt" — wildcard not expanded, but $VAR will be replaced |
| No quotes           | Shell interprets special characters like wildcards, variables, etc. | file*.txt — wildcard expanded to match files |


## 4th Day of training
## HARDWARE

**What is Hardware?**

Hardware refers to the physical components of a computer system or electronic device. These are the tangible parts you can see and touch.

**Common hardware components**

| Hardware Type       | Description                                         | Examples                          |
|---------------------|-----------------------------------------------------|----------------------------------|
| Input Devices       | Devices that allow users to input data into a computer | Keyboard, Mouse, Scanner, Microphone |
| Output Devices      | Devices that output data from the computer to the user | Monitor, Printer, Speakers       |
| Processing Units    | Components that process data and execute instructions | CPU (Central Processing Unit), GPU (Graphics Processing Unit) |
| Storage Devices     | Devices used to store data permanently or temporarily | Hard Drive (HDD), Solid State Drive (SSD), USB Flash Drive |
| Memory              | Temporary storage used by the CPU to hold data and instructions | RAM (Random Access Memory), Cache |
| Motherboard         | The main circuit board that connects all hardware components | Motherboard                     |
| Power Supply Units  | Provides electrical power to all components          | PSU (Power Supply Unit)           |
| Networking Hardware | Devices that connect computers and enable communication | Network Interface Card (NIC), Router, Switch |


**Motherboard**

The motherboard is the main printed circuit board (PCB) inside a computer that connects and allows communication between all the hardware components.

**Key Functions:**

- Connects Components: Links CPU, RAM, storage devices, graphics cards, and peripherals.
- Power Distribution: Supplies power to components through power connectors.
- Communication Hub: Enables data transfer between CPU, memory, and other devices via buses and chipsets.
- Houses Slots and Ports: Contains slots for RAM, PCIe cards, and ports for USB, audio, network, etc.

![alt text](hardware.jpg)
  
**Parts of a motherboard**

| Part                 | Description & Function                                                                                   |
|----------------------|--------------------------------------------------------------------------------------------------------|
| **CPU Socket**       | The slot where the Central Processing Unit (CPU) is installed. Connects the processor to the motherboard and provides electrical contacts for data and power. Different CPUs require different socket types (e.g., LGA 1200, AM4). |
| **RAM Slots (DIMM Slots)** | Slots where memory modules (RAM) are installed. The number and type (DDR3, DDR4, DDR5) determine the system’s memory capacity and speed. These slots connect the RAM directly to the CPU via the memory controller. |
| **Chipset**          | Manages communication between the CPU, RAM, storage, and peripherals. Controls data flow and connectivity features. Modern chipsets combine Northbridge and Southbridge functions. |
| **Expansion Slots (PCIe Slots)** | Slots for adding expansion cards like graphics cards (GPUs), sound cards, network cards, or USB controllers. PCI Express (PCIe) is the standard interface, with different sizes (x1, x4, x8, x16) affecting bandwidth. |
| **Storage Connectors** | Ports where storage devices like HDDs and SSDs connect. Common types include SATA ports and M.2 slots for NVMe SSDs offering faster speeds. |
| **Power Connectors** | Connectors linking the motherboard to the power supply unit (PSU). Includes 24-pin main power and 4/8-pin CPU power connectors. |
| **BIOS/UEFI Chip**   | Memory chip containing firmware (BIOS or UEFI) that initializes hardware during startup and provides system configuration interface. |
| **CMOS Battery**     | Small battery powering CMOS memory storing BIOS settings when PC is off. Preserves system clock and configuration data. |
| **Audio Chip/Ports** | Integrated audio processing chip and connectors for sound input/output, including headphone and microphone jacks. |
| **Network Interface (Ethernet Port)** | Onboard network controller and port for wired internet connections. Some motherboards include built-in Wi-Fi modules. |
| **Cooling Fan Headers** | Connectors for system and CPU fans, allowing motherboard control over fan speeds for temperature management. |

![alt text](cpu.jpg)

**WHAT IS CACHE MEMORY?**

Cache memory is a small, very fast memory inside the CPU that stores data and instructions the CPU uses often. It helps the CPU work faster by quickly giving it the information it needs without waiting for slower main memory (RAM).

**HOW RAM IS DIFFERENT FROM CACHE MEMORY**

| Feature           | RAM (Random Access Memory)                             | Cache Memory                                     |
|-------------------|--------------------------------------------------------|--------------------------------------------------|
| **Speed**         | Slower than cache memory                               | Much faster than RAM                             |
| **Location**      | On the motherboard                                     | On or very close to the CPU                      |
| **Purpose**       | Stores data and programs currently in use              | Stores frequently accessed data/instructions     |
| **Size**          | Larger (e.g., 8GB, 16GB)                               | Smaller (KB to a few MB)                         |
| **Cost**          | Cheaper per MB/GB                                      | More expensive per MB                            |
| **Access Time**   | Higher (in nanoseconds)                                | Very low (a few nanoseconds)                     |
| **Volatility**    | Volatile (data lost when power is off)                 | Volatile as well                                 |
| **Managed By**    | Controlled by the operating system                     | Managed automatically by the CPU hardware        |

**HOW RAM IS DIFFERENT FROM HARD DISK**

| Feature           | RAM (Random Access Memory)                            | Hard Disk (HDD/SSD)                              |
|-------------------|-------------------------------------------------------|--------------------------------------------------|
| **Speed**         | Much faster                                            | Slower compared to RAM                           |
| **Location**      | On the motherboard                                     | Connected via SATA/NVMe interface                |
| **Purpose**       | Temporarily stores data currently in use              | Permanently stores OS, software, and files       |
| **Size**          | Smaller (typically 8GB to 64GB)                       | Larger (typically 256GB to several TBs)          |
| **Cost**          | More expensive per GB                                 | Less expensive per GB                            |
| **Access Time**   | Very low latency (nanoseconds)                        | Higher latency (microseconds to milliseconds)    |
| **Volatility**    | Volatile (loses data when power is off)              | Non-volatile (retains data without power)        |
| **Data Retention**| Temporary                                              | Permanent                                        |
| **Managed By**    | Managed by the operating system                       | Managed by file system and OS                    |

**REGISTERS**

Registers are tiny, super-fast storage locations inside the CPU. They hold data and instructions that the CPU is currently working on. Registers are the fastest type of memory because they are directly part of the processor.

- Very small storage inside the CPU
- Store data the CPU needs immediately
- Faster than cache and RAM
- Used to perform calculations and operations quickly

## 5th day of training
## PC & Network Troubleshooting

**GPU** 

GPU stands for **Graphics Processing Unit**. It’s a special processor designed to handle graphics and images, like in video games, videos, and 3D rendering.

- Works alongside the CPU
- Great at doing many tasks at once (parallel processing)
- Speeds up drawing images, videos, and animations
- Also used for AI, machine learning, and scientific calculations

**Common issues and Problems in PC**

**Partitioning of Hard Disk**

Partitioning of Hard Disk means dividing a physical hard disk into separate sections called partitions. Each partition works like a separate drive, allowing you to organize data better, install multiple operating systems, or separate system files from personal files.

| Partition Type       | Description                                                   | Limitations                      |
|----------------------|---------------------------------------------------------------|---------------------------------|
| **Extended Partition**| A special partition that can hold multiple logical partitions.| Only one extended partition per disk. |
| **Logical Partition** | Partitions created inside the extended partition.             | Allows more than 4 partitions on a disk. |

**Shortcut key for Help is F11**

**CAUSES AND FIXES OF SLOW SPEED OF PC**

| Cause                              | Description                                      | Fix / Solution                                  |
|-----------------------------------|------------------------------------------------|------------------------------------------------|
| **Too Many Startup Programs**     | Programs launching automatically slow boot time| Disable unnecessary startup apps via Task Manager or System Settings |
| **Low Disk Space**                 | Hard drive almost full, affecting performance  | Free up space by deleting unwanted files or uninstalling apps |
| **Malware or Virus**               | Malicious software consumes resources          | Run a full antivirus scan and remove threats   |
| **Outdated Software or Drivers**  | Old versions can cause slowdowns or conflicts  | Update OS, drivers, and software regularly      |
| **Too Many Background Processes** | Multiple apps running simultaneously            | Close unnecessary programs via Task Manager    |
| **Fragmented Hard Drive (HDD only)** | Files scattered across disk, slowing access   | Run disk defragmentation tool (not needed for SSD) |
| **Insufficient RAM**               | Not enough memory for running apps               | Upgrade RAM or close unused applications        |
| **Overheating**                   | CPU/GPU throttling due to heat                   | Clean fans, improve cooling, or replace thermal paste |
| **Old Hardware**                  | Aging components slower than current software demands | Upgrade hardware components (CPU, RAM, SSD)    |

**SYSTEM SCANNING AND DEFRAGMENTATION**

**Optimization**

Optimization means making your computer or software work faster and more efficiently. It involves cleaning up unnecessary files, fixing errors, managing startup programs, and adjusting settings so everything runs smoothly.

By optimizing your system, you can improve speed, reduce crashes, and get better overall performance.

**System Scanning** is the process where your computer checks itself for errors, malware, or other issues. It helps find and fix problems like viruses, corrupted files, or system glitches, keeping your PC safe and running smoothly.

**Defragmentation** is the process of organizing files on your hard drive so they are stored in one place instead of scattered around. This makes your computer read and write files faster, improving overall performance. Note that defragmentation is useful for traditional hard drives (HDDs) but not needed for solid-state drives (SSDs).

**Scheduled Optimization**

Scheduled Optimization is setting your computer or device to automatically perform maintenance tasks at regular times—like cleaning up junk files, defragmenting the disk, or scanning for errors—without you having to do it manually.

This helps keep your system running smoothly and fast without interrupting your work.

**Why Install an Antivirus Scanner?**

- Protects Your Computer: Detects and removes viruses, malware, spyware, and other harmful software that can damage your files or system.
- Prevents Data Theft: Stops hackers and malicious software from stealing your personal information like passwords, bank details, and documents.
- Keeps System Running Smoothly: Removes unwanted programs that slow down your computer or cause crashes.
- Safeguards Against New Threats: Regular updates help protect you from the latest viruses and cyberattacks.

**Printer Problems and Solutions**

| Problem                     | Cause                                    | Solution                                           |
|-----------------------------|------------------------------------------|--------------------------------------------------|
| **Printer Not Printing**     | Printer offline or not connected         | Check cables/connections, turn on printer, set as default device |
| **Paper Jam**                | Paper stuck inside printer                | Open printer and carefully remove jammed paper   |
| **Poor Print Quality**       | Low ink/toner, dirty print head           | Replace ink/toner, clean the print head           |
| **Printer is Slow**          | High-resolution settings or busy print queue | Lower print quality settings, clear print queue   |
| **Driver Issues**            | Outdated or missing drivers                | Update or reinstall printer drivers                |
| **Unable to Connect Wireless**| Wi-Fi or network problems                  | Restart router, reconnect printer to network      |
| **Error Messages on Printer**| Hardware or software fault                  | Check error code in manual or reset printer       |
| **Blank Pages Printed**      | Empty ink cartridge or clogged nozzles    | Replace cartridge or clean nozzles                 |

**Benefits of Updates**

- Improved Security: Updates patch vulnerabilities that hackers could exploit.  
- Bug Fixes: They fix software errors and glitches for smoother performance.  
- New Features: Updates often add new tools and functionalities.  
- Better Compatibility: Ensure your software works well with new hardware and other programs.  
- Performance Enhancements: Updates can speed up software and make it more efficient.  
- Stability Improvements: Reduce crashes and unexpected errors.  
- Compliance: Keeps software up to date with industry standards and regulations.  

## PC Hardware Troubleshooting

**Blue Screen of Death (BSOD)**

Blue Screen of Death (BSOD) and Why It Happens
BSOD is an error screen shown by Windows when the system encounters a serious problem it cannot fix on its own. It stops everything to prevent damage.

![alt text](bsod.jpg)

**Why BSOD happens:**

- Faulty or incompatible hardware (like bad RAM or hard drives)
- Driver problems (corrupted or outdated drivers)
- Software bugs or corrupted system files
- Overheating or hardware failures
- Malware or virus infections
- Conflicts between software and hardware

When BSOD occurs, Windows shows an error code to help identify the problem.

**System crash analysis**

System crash analysis is the process of investigating why a computer suddenly stops working or restarts unexpectedly. The goal is to find the cause and fix it to prevent future crashes.

**How it’s done:**

- Check error messages or codes shown during the crash.
- Review system logs using tools like Event Viewer.
- Analyze crash dump files with utilities such as BlueScreenView or WinDbg.
- Look for recent changes in hardware, software, or drivers that might have caused the crash.
- Run hardware diagnostics to check for failing components.
  
**Fixes usually involve:**

- Updating or rolling back drivers.
- Removing problematic software.
- Repairing corrupted system files.
- Replacing faulty hardware.

**ASSIGNMENT**

**BIOS/UEFI Settings and POST Errors**

**BIOS/UEFI Settings**

- **BIOS (Basic Input/Output System)** and **UEFI (Unified Extensible Firmware Interface)** are firmware interfaces between your computer’s hardware and operating system.
- They initialize hardware components during startup and provide runtime services for the OS.
- BIOS is older; UEFI is newer with more features like faster boot, secure boot, and support for large drives.
- Users can access BIOS/UEFI to configure system settings such as boot order, hardware settings, and security options.

**POST Errors**

- **POST (Power-On Self-Test)** is a diagnostic test run by BIOS/UEFI at startup to check hardware health.
- If POST detects issues, it shows error messages or beep codes.
- Common POST errors include:
  - **No display:** Could be GPU or monitor issue.
  - **Beep codes:** Indicate hardware faults (RAM, CPU, GPU).
  - **Error messages:** Like “Keyboard error” or “Boot device not found.”
- Troubleshooting POST errors involves checking hardware connections, reseating components, or replacing faulty parts.

# 6th day of training

**What is Safe Mode?**

Safe Mode is a special way to start your computer with only the most important programs and drivers running.
It helps you fix problems by stopping any extra software that might be causing trouble, like viruses or faulty programs.

**Why Use Safe Mode?**

- To remove viruses or malware that won’t let you delete them normally
- To uninstall software or drivers causing crashes
- To fix errors when your computer won’t start properly

**How to Start Safe Mode (Windows)**

- Hold Shift and click Restart on your computer.
- Choose Troubleshoot > Advanced Options > Startup Settings > Click Restart.
- Press 4 (for Safe Mode) or 5 (for Safe Mode with Internet).

**What Are Recovery Tools?**

Recovery Tools help fix your computer if it won’t start properly or if something is broken.
Recovery Tools are special tools in Windows that help you fix bigger problems — like when your PC won’t start, or system files are broken.

**Common Recovery Tools:**

- Startup Repair – Fixes boot problems.
- System Restore – Goes back to an earlier time when your PC worked.
- Command Prompt – Lets you type commands to fix problems.
- Reset This PC – Reinstalls Windows (you can keep or remove your files).

**How to Access Recovery Tools**

**Windows:**

Restart > Hold Shift + click Restart > Choose Troubleshoot or

Restart and press F8 or F11 on some PCs

**Mac:**

Restart and hold Command + R during boot

**What is OS Repair?**

OS Repair means fixing the software that runs your computer — called the Operating System (OS). For most PCs, this is Windows.

When the OS has problems (like crashes, errors, or slow performance), OS repair tools help find and fix these problems so your computer works well again.

**Common Methods:**

    SFC (System File Checker)
    
    sfc /scannow → Scans & fixes corrupted system files.

    DISM Tool (Deployment Image Servicing and Management)
    
    DISM /Online /Cleanup-Image /RestoreHealth → Repairs Windows image.

    Windows Recovery Environment (WinRE)
    
    Access through boot menu or recovery drive.

**Why might you need OS repair?**

- Your computer is freezing or crashing
- You get error messages or blue screens
- Windows doesn’t start properly
- Programs don’t open or keep closing
- Files or settings are missing or broken

**How does OS repair work?**

- It checks important system files and replaces damaged or missing ones.
- It can restore Windows to an earlier, healthy state.
- It can fix startup problems so Windows boots correctly.
- If needed, it can reset or reinstall Windows without deleting your personal files.

**Virus malware**

Viruses and malware are harmful programs that can mess up your computer, steal your information, or slow everything down.

They can come from fake websites, email attachments, pop-up ads, USB drives, or bad software.

**Symptoms and basic removal steps**

| Virus/Malware Symptoms                 | Basic Removal Steps                                 |
|--------------------------------------|----------------------------------------------------|
| Computer is very slow or freezes      | Restart computer in *Safe Mode*                   |
| Many pop-up ads appear                | Uninstall strange or unknown programs               |
| Programs crash or close by themselves | Run a full scan with antivirus (e.g., Malwarebytes)|
| Browser homepage changes or redirects | Clear browser history and reset browser settings    |
| Files or folders missing or strange   | Delete temporary files (temp, %temp%, prefetch)|
| Antivirus turns off or won’t update   | Check and disable suspicious startup programs       |
| New programs appear you didn’t install| Restart computer normally after cleaning            |
| Friends get emails/messages from you  | Keep antivirus updated and avoid suspicious links   |

**What Are Plug-ins?**

Plug-ins are small software add-ons that you can install to add new features or functions to a program or app.

**Where Are Plug-ins Used?**

- Web browsers (like Chrome or Firefox) use plug-ins or extensions to block ads, translate pages, or play videos.
- Photo or video editors use plug-ins to add new effects or filters.
- Music players or games can use plug-ins for extra sounds or tools.

**What is a Backup?**

A backup is a copy of your important files and data saved somewhere safe — like on another drive or in the cloud.

It helps you recover your files if something bad happens, like your computer breaking or a virus deleting data.

**Why Backup?**

- Protect important photos, documents, and files
- Restore your data if your computer crashes
- Avoid losing work or memories

**How to Backup**

- Copy files manually to an external hard drive or USB
- Use built-in backup tools like:
  
      Windows: File History or Backup and Restore
  
      Mac: Time Machine
- Use cloud services like Google Drive, OneDrive, or Dropbox

**Backup Tips**

- Backup regularly (once a week or more)
- Keep backups in a safe place
- Test your backups sometimes to make sure they work

**What is an RJ45 Connector?**

An RJ45 connector is a plastic plug used to connect Ethernet cables to computers, routers, or switches.

It’s the most common type of connector for network cables.

**What Does It Look Like?**

- It looks like a bigger version of a phone plug (RJ11).
- Has 8 metal pins inside that connect to 8 wires inside the Ethernet cable.

**What Does It Do?**

- It allows devices to connect to a wired network.
- Sends data between your computer and other devices over the network.

**How Is It Used?**

- You crimp (attach) an RJ45 connector onto the end of an Ethernet cable.
- Then plug it into the Ethernet port on your device.

**What is an Ethernet Cable?**

An Ethernet cable is a wire that connects your computer or device to a router, modem, or network switch.

It helps devices talk to each other and access the internet.

**What is a Crimping Tool?**

A crimping tool is a special hand tool used to attach RJ45 connectors (the plugs) to the ends of Ethernet cables.

It “crimps” or presses the metal pins inside the connector onto the wires inside the cable to make a strong, secure connection.

**RJ connector wire color combinations**

![alt text](colorrj.png)

## 7th day of training
## Networking Basics

**Host**

Host refers to any device that connects to a network and can send or receive data. This includes:

**Examples of Hosts:**

- Computers (laptops, desktops)
- Servers
- Smartphones
- Tablets
- Printers
- IoT devices (smart TVs, smart thermostats, etc.)

![alt text](host.png)

**Client**

A client is a device or software that initiates communication with a server to access services or resources.

**Examples:**

- A web browser (like Chrome) requesting a web page.
- An email app checking your inbox.
- A mobile app fetching data from a server.

**Server**

A server is a device or program that waits for requests and then responds with data or services.

**Examples:**

- A web server hosting a website.
- A file server storing and sharing files.
- A database server handling data queries.

**What is a Network?**

A network is a group of two or more computers or devices connected together so they can communicate and share resources.

**IP Address**

- An IP address uniquely identifies a device on a network.
- It enables devices to communicate with each other.

**Unique and Universal Properties**

- **Uniqueness:**  
  - Public IPs are **globally unique**.  
  - Private IPs are unique **only within their private network** but can be reused elsewhere.

- **Universality:**  
  - IP addressing standards ensure every device worldwide can be identified in networks.

| IP Type     | Usage                  |
|------------|------------------------|
| Public     | Accessing the Internet |
| Private    | Internal Network Use   |

**IPv4 and IPv6**

| Feature         | IPv4                       | IPv6                            |
|-----------------|----------------------------|--------------------------------|
| Address Length  | 32 bits                    | 128 bits                       |
| Address Format  | Dotted decimal (e.g., 192.168.1.1) | Hexadecimal, colon-separated (e.g., 2001:0db8::1) |
| Address Space   | ~4.3 billion addresses    | Vast (3.4×10^38 addresses)      |
| Header Complexity | Simple                    | More complex, improved features |
| Deployment      | Widely used                | Growing adoption, future-proof  |

![alt text](ipv4ipv6.jpg)

**NOTATIONS**

**Decimal Notation**
- Uses **base 10** number system (digits 0–9).
- Most common in everyday life.
- Example: `192`, `168`, `1`, `1` in IPv4 address `192.168.1.1`.

**Binary Notation**
- Uses **base 2** number system (digits 0 and 1).
- Computers operate using binary internally.
- Each decimal number in an IPv4 address corresponds to an 8-bit binary number.
- Example:  
  - Decimal `192` = Binary `11000000`  
  - Decimal `168` = Binary `10101000`  
  - Decimal `1` = Binary `00000001`

**CLASSFUL ADDRESSING**

Classful addressing is an early way of dividing IPv4 addresses into fixed categories called classes based on the first few bits of the address.

**Network and Host**

Network: The part of an IP address that identifies the specific network a device belongs to.

Host: The part of the IP address that identifies the specific device (computer, printer, etc.) on that network.

**Example:**

In the IP address 192.168.1.10 with subnet mask 255.255.255.0:

Network part: 192.168.1

Host part: 10

**Prefix and Suffix**

Prefix: Another name for the network portion of the IP address. Often expressed with CIDR notation, e.g., /24 means the first 24 bits are the network prefix.

Suffix: Refers to the host portion of the IP address — the bits left over after the prefix that identify the device.

*In clasful addressing, address space is divided into 5 classes: A, B, C, D, E. Each occupies some part of address space.*

![alt text](ip.jpg)

**SUBNETTING**

Subnetting is the process of dividing a larger IP network into smaller, more manageable subnetworks (subnets).

![alt text](subnet.webp)

| Class | Address Range               | Starting Bits | Default Subnet Mask    | Number of Networks | Hosts per Network | Purpose / Theory                                                                                     |
|-------|-----------------------------|---------------|-----------------------|--------------------|-------------------|----------------------------------------------------------------------------------------------------|
| A     | 0.0.0.0 – 127.255.255.255  | 0             | 255.0.0.0 (/8)        | 128                | ~16 million      | Designed for very large networks with many hosts, such as large ISPs or multinational corporations. |
| B     | 128.0.0.0 – 191.255.255.255| 10            | 255.255.0.0 (/16)     | 16,384             | ~65,000          | Suitable for medium-sized networks like universities or large businesses.                           |
| C     | 192.0.0.0 – 223.255.255.255| 110           | 255.255.255.0 (/24)   | Over 2 million     | 254              | Intended for small networks, such as small offices or home networks.                               |
| D     | 224.0.0.0 – 239.255.255.255| 1110          | N/A                   | N/A                | N/A              | Reserved for multicast addressing, allowing data to be sent to multiple devices simultaneously.    |
| E     | 240.0.0.0 – 255.255.255.255| 1111          | N/A                   | N/A                | N/A              | Reserved for experimental use and research, not used in general networking.                        |

**SUBNET MASK**

A subnet mask is a 32-bit number used to divide an IP address into network and host parts.

**Purpose**

- It determines which part of the IP address refers to the network and which part refers to the host.
- Helps routers and devices identify the subnet to which an IP belongs.

**Format**

- Written in the same format as an IPv4 address (four decimal octets).
- Example: `255.255.255.0`

**Network IP (Network Address)**

- The network IP identifies the specific subnet.
- It is the first address in the subnet.
- All host bits are set to 0.
- Not assigned to any device.
  
Example: For subnet `192.168.1.0/24`, network IP is `192.168.1.0`.

**Broadcast IP (Broadcast Address)**

- The broadcast IP is used to send messages to all devices on the subnet.
- It is the last address in the subnet.
- All host bits are set to 1.
- Not assigned to any device.

Example: For subnet `192.168.1.0/24`, broadcast IP is `192.168.1.255`.

**CIDR (Classless Inter-Domain Routing)**

- CIDR notation represents the network prefix length.
- Written as IP address followed by a slash and number of bits in the network part.
- Example: `192.168.1.0/24` means the first 24 bits are network bits.

**Example: Subnetting a /24 into /26**

| Parameter            | Value                   |
|----------------------|-------------------------|
| Original Network     | 192.168.1.0/24          |
| New Subnet Mask      | 255.255.255.192 (/26)   |
| Number of Subnets    | 4                       |
| Hosts per Subnet     | 62                      |
| Network IP (Subnet 1)| 192.168.1.0             |
| Broadcast IP (Subnet 1)| 192.168.1.63           |

**ASSIGNMENT**

**Broadcast, Multicast, Unicast** 

| Feature              | Unicast                                          | Broadcast                                         | Multicast                                         |
|----------------------|-------------------------------------------------|--------------------------------------------------|--------------------------------------------------|
| *Definition*       | One-to-one communication                          | One-to-all communication                          | One-to-many communication                         |
| *Recipients*       | Single specific device                            | All devices on the network                         | A specific group of devices that joined the group|
| *Efficiency*       | Efficient, only one receiver                      | Inefficient, all devices receive data             | Efficient, only interested receivers get data    |
| *Use Case Examples*| Web browsing, file transfer, email               | ARP requests, DHCP discovery                       | IPTV, video conferencing, stock ticker updates   |

**MAC Address**

A MAC address (short for Media Access Control address) is a unique number given to every device that connects to a network (like your phone, laptop, or Wi-Fi router).

**Example:**

A MAC address looks like this:

    00:1A:2B:3C:4D:5E

Each device has its own MAC address, and it's usually built into the hardware (like the Wi-Fi card).

**What is DNS?**

- DNS stands for Domain Name System.
- It’s like the phonebook of the internet.
- It translates website names (like google.com) into IP addresses (like 172.217.10.46) that computers use to find each other.

**Why do we need DNS?**

- Humans find it easier to remember names like facebook.com than long numbers (IP addresses).
- Computers need IP addresses to communicate.
- DNS helps bridge that gap by translating names into numbers instantly

**Default Gateway**

A default gateway is like the door your device uses to go outside your local network (like your home Wi-Fi) to reach the internet or other networks.

**How it Works?**

- Your computer wants to go to Google.
- It sends the request to the default gateway.
- The gateway/router sends it to the internet to find Google.

# 8th day of training

**DHCP**

DHCP (Dynamic Host Configuration Protocol) is a network management protocol used to automatically assign IP addresses and other network configuration settings to devices on a network, allowing them to communicate effectively.

**Commands**

**ping**

The ping command is used to test the connectivity between your computer and another device (host) on a network. It helps determine if the host is reachable and measures the response time.

In networking, ping is a command-line utility that uses the ICMP (Internet Control Message Protocol) to test the reachability of a host on an IP network and measure the round-trip time (RTT) for packets sent from the source to the destination.

**Syntax:** ping website_address

Example: ping www.gndec.com

To Exit: Press Ctrl + C in the command prompt/terminal.

![alt text](cmdp.png)

**64 bytes**

In the context of the ping command, "64 bytes" refers to the size of the ICMP Echo Reply packet received from the destination host. It indicates that the system received 64 bytes of data, which includes both the ICMP header (8 bytes) and the payload (typically 56 bytes).

**Loopback Address (127.0.0.1)**

A loopback address is a special IP address used to test network functionality on your own computer — it routes traffic back to the local machine.

**Key Details**

IPv4 Loopback: 127.0.0.1

IPv6 Loopback: ::1

Also known as localhost

**Purpose**

Test if your TCP/IP stack is working

Verify if services are running locally

Develop and test network applications without needing a physical network

**Traceroute**

traceroute is a network utility that shows the route (path) packets take from your computer to a destination host by listing all intermediate routers (hops) along the way. It helps diagnose where delays or network failures occur.

**Command Syntax:**

Linux/macOS:

    traceroute [options] <destination>

Windows (command is tracert):

    tracert [options] <destination>
    
**Example:**

    traceroute google.com
    
or on Windows:

    tracert google.com

- *** (Asterisks) in Output: It indicates that the router at that hop did not reply.

**ipconfig**

A command-line tool used in Windows to display and manage the IP configuration of network interfaces.

**ifconfig**

A command-line utility used in Linux/Unix/macOS to configure, control, and display network interfaces.

**Purpose:**

Both commands show network settings like:

- IP address
- Subnet mask
- Default gateway
- 
They can also be used to enable/disable interfaces or renew DHCP leases.

**Basic Syntax:**

Windows (ipconfig):

    ipconfig [options]
    
Linux/macOS (ifconfig):

    ifconfig [interface] [options]

**What is Ethernet?**

Ethernet is a popular wired networking technology used to connect devices within a local area network (LAN), enabling communication and data sharing.

**How it Works:**

- Plug one end of an Ethernet cable into your PC's network port.
- Plug the other end of the cable into a modem or router.
- Your PC can now communicate over the network and access the internet.

**Where It’s Used:**

- Home networks to connect PCs, printers, and smart devices.
- Business offices for reliable and secure LAN connections.
- Data centers for fast, stable connections between servers and storage.
- Industrial environments where robust, wired communication is critical.

**Ethernet vs Wi-Fi**

| Feature           | Ethernet                          | Wi-Fi                           |
|-------------------|---------------------------------|--------------------------------|
| Connection Type   | Wired                            | Wireless                       |
| Speed             | Typically 100 Mbps to 10 Gbps+  | Typically 54 Mbps to 1-2 Gbps+ |
| Reliability       | Very reliable, low interference | Less reliable, subject to interference |
| Latency           | Low latency                     | Higher latency due to wireless overhead |
| Security          | More secure (physical access required) | Wireless security protocols (WPA2/WPA3) |
| Mobility          | Limited to cable length         | High mobility, supports device movement |
| Setup Complexity  | Requires cables and ports       | Easier setup, no cables needed |
| Cost              | Usually lower per device        | May require access points and more infrastructure |
| Common Usage      | Offices, data centers, gaming   | Homes, public hotspots, mobile devices |
| Range             | Limited by cable length (~100m max) | Varies (up to ~100m indoors, more outdoors) |


 **Ethernet vs Wi-Fi vs LAN vs WAN**

 | Term     | What It Is                        | Connection Type       | Typical Use                        |
|----------|---------------------------------|----------------------|----------------------------------|
| Ethernet | Wired network technology         | Cable (RJ45)         | Reliable, fast local connections |
| Wi-Fi    | Wireless network technology      | Radio waves          | Wireless local & mobile devices  |
| LAN      | Local Area Network (small area)  | Wired or wireless    | Home, office networks            |
| WAN      | Wide Area Network (large area)   | Various (Internet, leased lines) | Connects multiple LANs over long distances |

# 9th day of training
# INTRODUCTION TO HTML

HTML stands for HyperText Markup Language. It is the standard language used to create and design web pages. HTML provides the basic structure for web content by using tags and elements.

**Key Points:**

HyperText: Refers to the ability to link to other web pages.

Markup Language: Uses tags to "mark up" content for display in web browsers.

**Basic Structure of an HTML Document:**

    <!DOCTYPE html>
    <html>
      <head>
        <title>My First Web Page</title>
      </head>
      <body>
        <h1>Welcome to HTML</h1>
        <p>This is a paragraph.</p>
      </body>
    </html>

| **Part**         | **Purpose**                                              |
|------------------|----------------------------------------------------------|
| `<!DOCTYPE html>`| Declares HTML5 document type to the browser              |
| `<html>`         | Root of the HTML document                                |
| `<head>`         | Contains page info (not shown on page) like title/meta   |
| `<title>`        | Sets the page title (shown in browser tab)               |


**Common HTML Tags:**

- `<h1> to <h6>`: Headings
- `<p>`: Paragraph
- `<a>`: Link
- `<img>`: Image
- `<ul>, <ol>, <li>`: Lists
- `<div>, <span>`: Layout and grouping

**Purpose:**

HTML is the foundation of all web pages. It works with CSS (for styling) and JavaScript (for interactivity) to create modern websites.


# 10th day of training
# BASIC HTML TAGS

**1. Heading Tags (`<h1>` to `<h6>`)**

- Used to define headings or titles on a web page.
- `<h1>` is the largest/most important, and `<h6>` is the smallest/least important.

![alt text](heading.png)

**2. Paragraph Tag (`<p>`)**

- Used to define a block of text as a paragraph.

![alt text](paragraph.png)

**3. List Tags (`<ul>`, `<ol>`, `<li>`)**

- Used to create lists.
- `<ul>` = unordered list (bullets)
- `<ol>` = ordered list (numbers)
- `<li>` = list item

![alt text](list.png)

**4. Image Tag (`<img>`)**

- Used to display images.
- It’s a self-closing tag.
- Requires src (image URL or path) and alt (alternative text) attributes.

![alt text](img.png)

**5. Anchor Tag (`<a>`)**

- Used to create hyperlinks.
- The href attribute specifies the destination URL.

![alt text](links.png)

# 11th day of training
# FORM AND INPUT TYPES
The `<form>` tag is used to create an HTML form for user input. A form can include input fields like text boxes, checkboxes, radio buttons, and buttons to submit or reset data.

**Common Attributes:**

- action: URL where the form data is sent after submission.
- method: HTTP method (usually "get" or "post").

**Example:**

    <form action="/submit" method="post">
      <!-- form inputs go here -->
    </form>

![alt text](form.png)

**`<input>` Tag**

The `<input>` tag is used to create interactive fields in a form. The type of input is defined using the type attribute.

**Common Input Types:**

| Input Type | Purpose                                  | Example Syntax                              |
|------------|------------------------------------------|---------------------------------------------|
| `text`     | Single-line text input                   | `<input type="text">`                       |
| `password` | Hides characters (for passwords)         | `<input type="password">`                   |
| `email`    | Validates email format                   | `<input type="email">`                      |
| `number`   | Numeric input only                       | `<input type="number">`                     |
| `checkbox` | Select one or more options               | `<input type="checkbox">`                   |
| `radio`    | Select one option from a group           | `<input type="radio" name="gender">`        |
| `submit`   | Submit the form                          | `<input type="submit">`                     
| `button`   | A clickable button (no submit default)   | `<input type="button" value="Click">`       |

**Examples:**

![alt text](radio.png)

![alt text](checkboxes.png)

# Semantic HTML
Semantic HTML uses elements that clearly describe their meaning in both the code and to the browser and developer. Instead of using generic `<div>` and `<span>` tags, semantic tags like `<header>`, `<footer>`, and `<article>` provide meaningful structure.


**1. `<header>`**

The `<header>` element represents the top section of a page or a section, usually containing a logo, title, or navigation links.

**Example:**

    <header>
      <h1>My Blog</h1>
      <nav>
        <a href="/">Home</a>
        <a href="/about">About</a>
      </nav>
    </header>

**2. `<footer>`**

The `<footer>` element defines the bottom section of a page or a section, usually containing contact info, copyright, or links.

**Example:**

    <footer>
      <p>&copy; 2025 My Blog. All rights reserved.</p>
    </footer>

**3. `<nav>`**

The `<nav>` element is used to define a navigation menu — links to different parts of the site or other pages.

**Example:**

    <nav>
      <ul>
        <li><a href="/">Home</a></li>
        <li><a href="/services">Services</a></li>
        <li><a href="/contact">Contact</a></li>
      </ul>
    </nav>

**4. `<section>`**

The `<section>` element represents a thematic grouping of content, typically with a heading. It’s used to divide the page into meaningful areas.

**Example:**

    <section>
      <h2>About Us</h2>
      <p>We are a team of passionate developers.</p>
    </section>

**5. `<article>`**

The `<article>` element is used for independent, self-contained content like a blog post, news article, or forum post.

**Example:**

    <article>
      <h2>How to Learn HTML</h2>
      <p>HTML is the foundation of web development...</p>
    </article>

# 12th day of training
# BASIC STYLING IN HTML
**CSS (Cascading Style Sheets)**

CSS is used to style HTML elements — changing fonts, colors, layout, spacing, etc. There are 3 main ways to apply CSS:

- Inline CSS – directly inside an HTML tag
- Internal CSS – in a `<style>` block in the `<head>` section
- External CSS – in a separate .css file

**CSS Properties Used:**

| Property           | Description               | Example                     |
| ------------------ | ------------------------- | --------------------------- |
| `color`            | Text color                | `color: red;`               |
| `background-color` | Background color          | `background-color: yellow;` |
| `font-size`        | Size of the font          | `font-size: 20px;`          |
| `text-align`       | Alignment of text         | `text-align: center;`       |
| `margin`           | Space outside the element | `margin: 10px;`             |
| `padding`          | Space inside the element  | `padding: 10px;`            |
| `font-family`      | Font type                 | `font-family: Arial;`       |



**1. Inline CSS**

Inline CSS is applied using the style attribute directly inside an HTML tag.

**Example:**

    <p style="color: blue; font-size: 18px;">This is blue text with a font size of 18px.</p>

**OUTPUT:**

![alt text](inline.png)

**2. Internal CSS**

Internal CSS is placed inside a <style> tag within the <head> of the HTML document. It allows you to style multiple elements at once.

**Example:**

    <!DOCTYPE html>
    <html>
    <head>
      <title>Internal CSS Example</title>
      <style>
        body {
          background-color: #f4f4f4;
          font-family: Arial, sans-serif;
        }
        h1 {
          color: darkgreen;
          text-align: center;
        }
        p {
          color: #333;
          font-size: 16px;
          margin: 20px;
        }
      </style>
    </head>
    <body>
      <h1>Welcome to My Website</h1>
      <p>This paragraph is styled using internal CSS.</p>
    </body>
    </html>

**OUTPUT:**

![alt text](internal.png)

**3. External CSS**

External CSS is written in a separate file (e.g., style.css) and linked to your HTML file. This is the best practice for styling large or multi-page websites, because it keeps content (HTML) and design (CSS) separate.

**How to Link:**

In the `<head>` section of your HTML file:

    <link rel="stylesheet" href="style.css">

**Example:** index.html

    <!DOCTYPE html>
    <html>
    <head>
      <title>External CSS Example</title>
      <link rel="stylesheet" href="style.css">
    </head>
    <body>
      <h1>Welcome to My Website</h1>
      <p>This is styled using external CSS.</p>
    </body>
    </html>

**Example:** style.css

    body {
      background-color: #e0f7fa;
      font-family: Verdana, sans-serif;
    }

    h1 {
      color: navy;
      text-align: center;
    }

    p {
      color: #555;
      font-size: 18px;
      padding: 10px;
    }

**OUTPUT:**

![alt text](external.png)

# 13th day of training
# Introduction to Git and Version Control
**What is Git?**

Git is a version control system that helps you track changes in your code over time. It allows multiple people to collaborate, revert to previous versions, and manage code history efficiently.

**Why Git is Open Source**

Git is open source so anyone can use, modify, and improve it freely. This openness helps millions collaborate, making Git reliable and widely adopted.

**Why Future Coders Must Learn Git**

Git is essential because it helps you track code changes, work with others smoothly, and showcase your projects. Almost every software job requires Git skills, especially for contributing to open source and team projects.

**What is Version Control?**

Version control is a system that tracks changes to files (usually code) over time. It lets you save different versions, so you can:

- Go back to earlier versions if something breaks
- Compare changes between versions
- Work together with others without overwriting each other’s work

**Types**

**1. Local Version Control**

- Keeps track of changes on your own computer.
- Simple, but risky if your computer fails.

**2. Distributed Version Control**

- Every user has a full copy of the project history.
- Examples: Git, Mercurial.
- Safer and great for collaboration.

**Git Architecture**

**1. Working Directory**

- Your local folder where you edit files.
- Contains the actual project files.

**2. Staging Area (Index)**

- A place where you prepare (stage) changes before committing.
- You choose which changes to include in the next commit.

**3. Git Repository (Local Repo)**

- Stores all commits and the full history of your project locally.
- Contains metadata and objects like commits, trees, and blobs.

**4. Remote Repository**

- A shared version of the repository hosted on servers (e.g., GitHub, GitLab).
- Used to collaborate and push/pull changes between team members.

![alt text](archi.jpg)

**COMMANDS**

**1. Go to GitHub and create a new repository.**

![alt text](repo1.png)
![alt text](repo.png)

**2. Copy the repository HTTPS clone link.**

![alt text](http.png)

**3. Open Git Bash.**

**4. Clone the Repository.**

**What is git clone?**

- Git clone is a Git command used to create a local copy of a remote repository (usually from GitHub or another Git server).

**5. Check if you got the repository cloned on your local drive using ls.**

**6. Move inside the direcotry by cd repository_name.**

**7. Again, check the content inside your repository.**

![alt text](code1.png)

**8. Check status of the repository by git status.**

**What is git status?**

- Git status is a Git command used to display the current state of the working directory and staging area. It tells you what changes have been staged, what changes are not staged, and which files aren’t being tracked by Git.

**9. If the response id 'Up to date', you are good to move forward.**

**10. Create a new file by touch file_name.html.**

**11. Open the file by nano file_name.html, write html code and save it.**

![alt text](nanoo.png)

**12. Add by: git add file_name.html**

**What is git add?**

- Git add is a Git command used to stage changes (new, modified, or deleted files) so they are included in the next commit.

**13. Git push origin main:**

**What is git push origin main?**

- Git push origin main is a Git command used to upload your local commits from the main branch to the remote repository named origin (usually GitHub).
- It directs and you get asked to authorize Git Credential Manager, which securely saves GitHub login credentials for pushing/pulling code.

![alt text](ss1.png)

**14. Now, Click on 'Authorize git-ecosystem'.**

![alt text](ss2.png)

![alt text](ss3.png)

**15. To commit: git commit -m "message".**

**What is git commit -m?**

- Git commit -m is a Git command that saves (or commits) your staged changes and includes a message describing what you’ve done.

![alt text](code2.png)

**16. Now you can see the file in your repository.**

![alt text](html.png)

# 14th day of training
# BRANCHING AND MERGING

**What is Branching in Git?**

Branching means creating a separate version of your project so you can work on changes without messing up the main version.

**Why use branches?**

- Try out new features or ideas
- Fix bugs without affecting the main code
- Work in teams on different tasks at the same time

**To create a new branch**

    git branch branch-name

To create and switch to it at the same time:

    git checkout branch-name
    
![alt text](code141.png)

**Practical demonstration for branching**

**git push -u origin branch_name**

Pushes the local branch named branchname to the remote repository called origin and sets it as the upstream branch for easier future pushes and pulls.

| Part           | Explanation                                                                                  |
|----------------|----------------------------------------------------------------------------------------------|
| `git push`     | Uploads your local commits to the remote repository.                                         |
| `-u` or `--set-upstream` | Sets the specified remote branch as the default upstream branch for the current local branch. Enables simpler future pushes and pulls. |
| `origin`       | The name of the remote repository you're pushing to. By default, `origin` refers to the main remote. |
| `branchname`   | The name of the local branch you want to push to the remote repository.                      |

The command:

    git checkout branchname

is used to switch to an existing branch named branchname in a Git repository.

![alt text](code142.png)

![alt text](txt1.png)

![alt text](txt2.png)

**Merging**

Merging in Git combines the changes from one branch into another. Typically, you:

- Switch to the branch you want to merge into (often main or develop).
- Run the merge command with the name of the branch you want to merge from.


![alt text](merge.png)

# 15th day of training
# QUIZ AND CAREER COUNSELLING
