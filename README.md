# Apple-IIcx-PSU-ATX-Adapter
Apple Mac IIcx PSU ATX Adapter

![ATX Adapter PCB](/docs/PSU%20Adapter%202.png?)
 
The PSU in these old computers suffer with age, particularly the Rifa capacitors which have a tendency to explode.
The general consensus seems to be that it isn't worth trying to repair them as this is likely to only extend their life by a few years.
I therefore decided to replace the guts of the PSU with a mini ATX PSU but there are a couple of issues with hooking it up:
1) The Apple PSU has a special connector to the logic board allowing the PSU to be plugged in as a unit.
2) The ATX PSU does not have direct provision for the soft start capability.
3) Many ATX units don't have a monitor A/C pass-through

I decided to design this PCB to solve all of these issues. It is designed to connect to the power plug from the mains input unit, pass AC power 
to the ATX board, get DC power back via the ATX connector and use the logic board plug and wires from the old PSU.

The ATX PSU I have used is from FSP Group Inc. Model FSP270-60LE as this has comparable power output capabilities.

I have also designed a mounting plate for the ATX PCB which can be 3D printed.

See files in Docs for the schematic and details of the build.
