# milo-cnc
linuxcnc configuration files for Milliniem Machinces Milo running Mesa 6i25, Gecko G540 drivers and Stepper Online EV200 vfd

This Milo is driven by quadcore intel system with a Pci Mesa FPGA connected to a Gecko G540 driver set and a C11G BOB for additional io. The spindle is a 2.2kw water-cooled Zhong Hua Jiang brand Manufactured by the Chanzhou Huajiang Electric Appliance Company. The spindle is controlled by a VFD sold by StepperOnline under the model name EV200-2200G-S2 and manufactored by the Ausenist Co. Spindle control is done with Modbus RTU.

Running the C11G connected to the 6125 required special firmware that was provided by the Mesa company. 
