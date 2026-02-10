# about

This project enable the user to connect and read/write their UART signals via USBC.

Feel free to read more about the design and use process [here](https://substack.com/home/post/p-186289458)

## PCB electronics design

In [`TOP-V2`](./TOP-V2), the KiCad files for the project schematic and layout are available, which enable BOM, Gerber, and Centroid generation for manufacture and assembly.

![schematic](./images/0_schematic.png)

![layout](./images/1_layout.png)

Also the footprints and revelent 3D models needed to generate `.step` files for freeCAD housing design...

![3d model](./images/2_stp_model.png)

## PCB 3D-printed enclosure

In [`ENCLOSURE`](./ENCLOSURE), the freeCAD source files that enable us to generate a `.stl` - and therefore enable 3D-printed housing for the PCB

![initial](./images/3_stl_model_initial.png)

![final](./images/4_stl_model_final.png)

![packaged](./images/5_packaged.jpg )