# Runnig Linux on a IBM Thinkpad 600E

Is it possible to run a modern Linux on a
24 years old (1999) Thinkpad 600E?

Yes it is!

## Working

| Distro                                  | Version | Kernel | X Server    | CD Image
| --------------------------------------- | ------- | ------ | ----------- | -------------------------------------------------------------------------------------------------------------------------
| [Tiny Core](http://tinycorelinux.net)   | 14.0    | 6.1    | tinyx 1.2   | [CorePlus-14.0.iso](http://tinycorelinux.net/14.x/x86/release/CorePlus-14.0.iso)
| [Alpine](https://www.alpinelinux.org/)  | 3.17    | 5.15   | Xorg 21.1   | [alpine-standard-3.17.3-x86.iso](https://dl-cdn.alpinelinux.org/alpine/v3.17/releases/x86/alpine-standard-3.17.3-x86.iso)
| [antiX](https://antixlinux.com/)        | 22      | 4.9    |             | [antiX-22_386-core.iso](https://sourceforge.net/projects/antix-linux/files/Final/antiX-22/antiX-22_386-core.iso/download)
| [Ubuntu](https://ubuntu.com)            | 6.06    | 2.6    | Xorg 7.0    | [ubuntu-6.06.1-alternate-i386.iso](https://old-releases.ubuntu.com/releases/6.06.2/ubuntu-6.06.1-alternate-i386.iso)
| [DSL](http://www.damnsmalllinux.org)    | 4.4.10  | 2.4    | XFree86 4.2 | [dsl-4.4.10.iso](https://distro.ibiblio.org/damnsmall/current/dsl-4.4.10.iso)

## Not working

| Distro    | Version    | Problems
| --------- | ---------- | ----------------------------------
| Ubuntu    | 4.10       | Kernel panic on boot
| Arch 32   | 2023.03.02 | Stops with blinking cursor on boot
| Void      | 5.19       | requires SSE2
| Debian    | 12         | requires SSE2 and PAE

## Hardware Specs

- CPU: Mobile Pentium II 366 MHz
- GPU: Neomagic MagicMedia256AV with 2.5MB
- RAM: 128 MB
- Display: 13" TFT / 1024x786
