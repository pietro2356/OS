# Basic OS project

## Table of Contents

- [About](#about)
- [Requirements](#requirements)
- [Getting Started](#getting_started)
- [Usage](#usage)
- [License](LICENSE)

## About <a name = "about"></a>

Con questo piccolo progetto vorrei apprendere la struttura di quello che è un OS di base.

## Requirements <a name = "requirements"></a>

* **GNU/Linux** - I am using GNU/Kali Linux 2017 i386 distribution .
* **Assembler** - I am using GNU Assembler(gas) to instruct the bootloader for loading the starting point of our kernel.
* **GCC** - GNU Compiler Collection a cross compiler. A newer version of GCC. I am using 7.2.0 version of GCC. The most important thing.
If you use old version you may face multiboot header not found error.
* **Xorriso** - A package that creates, loads, manipulates ISO 9660 filesystem images.(man xorriso)
* **grub-mkrescue** - Make a GRUB rescue image, this package internally calls the xorriso functionality to build an iso image.
* **QEMU** - Quick EMUlator to boot our kernel in virtual machine without rebooting the main system.

## Getting Started <a name = "getting_started"></a>

Per avviare il tutto basta eseguire il file ***run.sh*** nella cartella ***KernelBasic*** così:

```console
sudo ./run.sh
```
or
```console
sh run.sh
```

### Prerequisites

What things you need to install the software and how to install them.

```console
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running.

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo.

## Usage <a name = "usage"></a>

Add notes about how to use the system.
