# ELF Loader with Demand Paging

![C](https://img.shields.io/badge/C-11-blue)
![Systems](https://img.shields.io/badge/Systems-Programming-orange)
![ELF](https://img.shields.io/badge/Executable-ELF_format-green)

A minimal ELF loader implementing demand paging with SIGSEGV handling for memory allocation. Measures page faults and internal fragmentation during execution.

## Key Features
- 🖥️ On-demand page allocation via `mmap`
- ⚡ SIGSEGV handler for transparent page fault handling
- 📊 Tracks performance metrics:
  - Page fault counts
  - Memory allocations
  - Internal fragmentation
- 🔍 Supports 32-bit ELF executables

## Code Structure
