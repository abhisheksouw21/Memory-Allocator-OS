# Memory-Allocator-OS

A Windows Forms simulator for contiguous memory allocation in operating systems.
It lets you define memory holes, add and remove processes, compare allocation
strategies, and compact memory visually.

<p align="center">
  <img src="screenshots/3.png?raw=true" alt="Memory allocator simulator" />
</p>

## Features

- First-fit, best-fit, and worst-fit allocation strategies
- Configurable initial memory holes
- Visual process allocation map
- Process deallocation by double-clicking its block
- Memory compaction

## Getting started

The project targets **.NET Framework 4.0** and is intended to run on Windows.

1. Open `memory-allocator-gui-app/memory-allocation-gui-app.csproj` in Visual Studio.
2. Build the project.
3. Run the `memory-allocation-gui-app` Windows application.

Set a positive memory size, add one or more holes, then choose an allocation
strategy before adding processes.

## Project resources

- [Source code](memory-allocator-gui-app/)
- [Screenshots](screenshots/)
- [Project documentation](os-memory-allocator-documentation.pdf)

## License

This project is distributed under the [MIT License](LICENSE).
