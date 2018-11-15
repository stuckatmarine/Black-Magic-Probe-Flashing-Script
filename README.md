# Black-Magic-Probe-Flashing-Script
Windows .bat script to flash .hex or .elf files to supported micro controllers via a Black Magic Probe.

SAM D20 and D21 confirmed working with SAM_BA M0 bootloader and Arduino IDE post flash.\
Also confrimed gnu debugging post flash .elf's \
Eclipse debugging, breakpoints, etc. possible with minor modifications.
Confirmed working with "Sloeber" Eclipse plugin.

## Instructions
Change line 1 to your gnu gdb.exe path\
Change to your COMX port\
Change to your filepath\\filename.hex or .elf\
Double click and run in windows explorer or via cmd\
Press q enter when done

### May also be flexed to Linux with minor changes and COM -> /dev/tty... modification
