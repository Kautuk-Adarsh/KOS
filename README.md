# KOS — Kautuk's Operating System

KOS is a fully custom operating system built from scratch, targeting the x86-64 architecture.  
No Linux. No Windows. No borrowed foundation. Every component — from the boot sector to the shell — is written by hand.

---

## What this is

KOS is a long-term, ground-up OS development project. The goal is a functional, bootable operating system that real people can download and run.

Built with: x86 Assembly (bootloader) and C (kernel and beyond).  
Development environment: WSL2 + GCC + NASM + QEMU.

---

## Current Status

> 🔧 **Phase 1 in progress — Bootloader**

- [ ] Phase 1 — Bootloader (x86 real mode, BIOS boot, kernel loading)
- [ ] Phase 2 — Minimal kernel (protected mode, memory map, console output)
- [ ] Phase 3 — Memory management (paging, heap allocator)
- [ ] Phase 4 — Interrupts and hardware (IDT, PIC, keyboard, timer)
- [ ] Phase 5 — Process management (scheduling, context switching)
- [ ] Phase 6 — File system (VFS, custom filesystem)
- [ ] Phase 7 — Shell and userland (syscalls, shell, user programs)

---

## No libraries. No shortcuts.

Every line of code in KOS is written from scratch. No libc. No external runtime dependencies. If it runs on KOS, someone wrote it for KOS.

---

## Follow the build

This repository is the live development log. Commits are made at every meaningful milestone. If you want to watch an OS get built from the ground up, star the repo and check back.

Issues, feedback, and technical discussion are welcome.

---

## Running KOS

> Instructions will be added once the first bootable image is ready.

---

*KOS is a work in progress. It will take time. That is the point.*