# RETRO/OS

**An experimental 64-bit operating system built from scratch.**

Developed by **Signal&Noise Co.**

## About

RETRO/OS is an independent hobby operating system project targeting the x86-64 architecture. Its kernel is written in C17 and x86-64 assembly, without using the Linux kernel or another existing OS kernel.

The project combines retro-inspired visual design with modern 64-bit system architecture.

## Development status

- **v0.1.0** — First stable development milestone: framebuffer console
- **v0.2.0** — Work in progress: GDT, IDT, CPU exceptions, RTC and panic screen
- **Next milestones** — Hardware interrupts, APIC and timer support

## Technology

- Architecture: x86-64
- Languages: C17 and x86-64 Assembly
- Bootloader: Limine
- Toolchain: Clang/LLVM and LLD
- Testing: QEMU

## Downloads

Public test builds will be available in the GitHub Releases section.

## Testing

RETRO/OS is experimental software. We recommend testing releases in QEMU or another compatible virtual machine. Do not use it on production hardware.

## Source code

Development currently takes place in a private Forgejo repository. This public repository is intended for binary releases, documentation and testing information. Source code is not currently published here.

## Feedback

Bug reports and testing feedback are welcome through GitHub Issues.

---

**Signal&Noise Co. — Technical Culture.**
