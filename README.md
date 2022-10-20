# LT3233 Computational Linguistics

## Computer Architecture

- Kernel
- CPU
- RAM (memory)

The other devices/components:

- External storage (hard disk drive)
- Peripheral devices (key board, monitor, printer, …);
- A system bus (=“info highway”) for connection to all devices (incl. RAM + external storage):
control_cmd{data@address} (in a fashion like a postman delivering a package)

Everything is sent to & received from the databus.

## System Bus

Every device (incl. the memory) is “hung” onto this system bus.

## Machine codes -> programming languages

Machine codes are not readable by most people without a codebook providing all machine codes of a particular processor in use (e.g., x86, x86-32 and x86-64)

Each usually as a triple: OpCode oparand1, operand2

For engineering purpose, such codes (usually in mnemonics called assembly language) have to be re-organized into various kinds of more readable program languages, like C/C++, Perl, Python, Java, etc.

This is why we need to compile our programs (source codes) into such machine codes for the machine to run.
