# Mission 3 — Understand the Operating System

## 1. Task / objective

Explore the operating system, running processes, storage, paths and file permissions. Understand and explain the major responsibilities of an operating system.

## 2. Work completed

- Inspected macOS system information using Terminal.
- Checked filesystem capacity and storage usage.
- Learned about running processes and Process IDs (PID).
- Studied absolute paths and relative paths.
- Learned file permissions: read, write and execute.
- Studied six major operating-system responsibilities.
- Reviewed how the operating system connects users, applications and hardware.

### System information observed

| Property | Observation |
|---|---|
| Operating system | macOS |
| Version | 27.0.1 |
| Build version | 26A434 |
| Filesystem size reported | 926 GiB |
| Available space reported | 807 GiB |
| Data volume used | 94 GiB |
| Data volume capacity used | 11% |

## 3. Commands / tools used

| Command / tool | Purpose |
|---|---|
| `sw_vers` | Displays macOS version and build information. |
| `df -h` | Displays filesystem capacity and storage usage in human-readable units. |
| `ps aux` | Displays a snapshot of running processes. |
| `head -10` | Displays the first ten lines of input. |
| `pwd` | Displays the current working directory. |
| `ls -l` | Displays detailed file information, including permissions. |
| Terminal | Used to inspect operating-system information. |
| VS Code | Used to maintain mission documentation. |

## 4. My understanding

An operating system manages computer hardware and software resources and provides an environment for applications to run.

A process is an instance of a program that is currently running. Each process has a Process Identifier (PID), which helps the operating system identify it.

Storage commands help inspect filesystem capacity and usage. The `df -h` command displays total size, used space, available space and capacity.

An absolute path describes the complete location of a file, while a relative path describes its location in relation to the current working directory.

File permissions control access:
- Read (`r`): Allows reading a file.
- Write (`w`): Allows modifying a file.
- Execute (`x`): Allows executing a program or accessing a directory.

The six major responsibilities of an operating system are:

1. **Process management:** Manages running programs and CPU time.
2. **Memory management:** Allocates and manages RAM.
3. **Device management:** Controls communication with hardware devices.
4. **File management:** Organises and manages files and directories.
5. **User interface / shell:** Provides ways for users to interact with the computer.
6. **Security and permissions:** Controls access to files and system resources.

The operating system acts as an intermediary between users, applications and hardware.

## 5. Difficulties faced

No major difficulties.

## 6. How I resolved them

Used Terminal commands to inspect system information and storage. Reviewed operating-system concepts and command purposes to understand the results.

## 7. Evidence / files

- `mission-03-operating-system/README.md`
- macOS system information observed using `sw_vers`.
- Filesystem information observed using `df -h`.
- Notes covering processes, paths, permissions and operating-system responsibilities.

## 8. Commit details

To be updated after committing and pushing this mission to GitHub.