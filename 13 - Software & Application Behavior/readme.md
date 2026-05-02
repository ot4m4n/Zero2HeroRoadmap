# Software & Application Behavior

> **Goal:** Understand how applications run, log, fail, and what to instrument.
> **Prerequisites:** 03, 05/06.
> **Estimated time:** 10–15 h

## 📚 Free resources

- [Brendan Gregg — Performance & Tracing (free site)](https://www.brendangregg.com/)
- [strace / ltrace tutorials — RedHat blog](https://www.redhat.com/en/blog)
- [Process Explorer & Sysinternals docs](https://learn.microsoft.com/en-us/sysinternals/)

## ✅ Checkpoint — you're ready to move on when:

- You can attach strace/Process Monitor to a misbehaving binary and read the output.

---

## 📂 Syllabus

## 📁 How Software Works
- What is software: binary vs interpreted
- Runtime environments and dependencies
- Compilation vs interpretation
- Software architecture: monolithic vs microservices
- How operating systems load and execute programs
- DLLs and shared libraries
- Process lifecycle: creation, execution, termination
- Threads vs processes
- Software update mechanisms
- Software packaging and installers (e.g., MSI, EXE, Deb, RPM)

## 🔍 Application Behavior Analysis
- Understanding behavior vs code
- Static vs dynamic analysis
- Resource usage (RAM, CPU, Disk, Network)
- Memory allocation patterns
- File system interactions
- Registry interactions (Windows)
- Network connections and outbound calls
- Common logging behaviors
- Interprocess communication (IPC)
- Crash and exception handling

## 🧪 Testing & Instrumentation
- Using Sysinternals Suite (ProcMon, ProcExp, TCPView)
- Dependency Walker, PE Studio
- Monitoring file and registry access
- Tracking process trees and child processes
- Debuggers overview (x64dbg, WinDbg, GDB)
- API call tracing and hooking
- Environment sandboxing and behavior isolation
- Event Viewer and Application Logs

## 🧰 Configuration & Tuning
- Software configuration files and flags
- Feature toggles
- Licensing mechanisms
- Telemetry and analytics opt-out
- Startup behaviors and autostart mechanisms
- Handling corrupted config states

## 🏗 Examples of Software Types
- System-level tools (e.g., drivers, services)
- User-facing applications (e.g., browsers, mail clients)
- Background services and daemons
- CLI tools vs GUI software
- Web-based apps (client-server model)
- Mobile apps (Android/iOS architecture)
