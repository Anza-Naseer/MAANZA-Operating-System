🖥️ MAANZA – Terminal-Based Operating System Simulation
MAANZA is a fully terminal-based, multitasking Operating System simulation developed in C++ as part of our final term project for the Operating Systems Lab – Spring 2025.
It is designed to simulate how a real OS manages processes, memory, resources, and scheduling techniques in a controlled user/kernel mode environment.
🚀 Features
🔧 System Initialization
User inputs system specs:

RAM size (e.g., 2GB)

Hard Disk capacity (e.g., 256GB)

Number of CPU cores (e.g., 8)

Displays custom OS name "MAANZA" on boot using sleep animation.

🧩 Multitasking Environment
Supports 15+ independent tasks/applications.

Each task is a separate process launched via exec (no function calls).

Memory/resource request-response mechanism between OS and tasks.

If insufficient memory, task is safely terminated.

📜 User & Kernel Modes
User Mode:

Launch, minimize, switch between tasks.

Kernel Mode:

Force close/delete processes.

Manage system memory and resources.

🧠 Process & Memory Management
Simulated RAM and Hard Drive.

Tasks request memory and get assigned space.

Resources are freed upon task termination.

Simulates process states: Ready, Running, Blocked, Terminated.

⚙️ Process Scheduling
Multicore support with:

Multilevel Queue Scheduling

Semaphores

Mutual Exclusion

Condition Variables

Simulated Context Switching between tasks.

🔄 Interrupt Handling
Manual interrupts move a task to Blocked state.

Tasks resume execution once interrupt is resolved.

💻 Task Management
Launch tasks from a menu.

Options to Minimize, Close, or Switch tasks.

Multitask freely across apps like in real OS.

📅 Startup Tasks
Auto-launch utilities (Clock, Calendar) on OS boot.

💾 File Storage
Tasks like Notepad support auto-save to simulated HDD.

File system simulation includes Create, Move, Copy, Delete, and File Info.

🧠 OS Concepts Implemented
✅ Multitasking

✅ Process Creation (exec)

✅ RAM & HDD Resource Allocation

✅ Threads & Synchronization

✅ Context Switching

✅ User/Kernel Mode Isolation

✅ Interrupt Handling

✅ Multilevel Queue Scheduling

✅ Semaphores, Mutexes, Condition Variables
