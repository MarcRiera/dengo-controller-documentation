## Adapters and hacks

Besides the official compatibility, it is possible to use unofficial adapters, tools and hacks to use controllers with games which is unsupported officially.

### Converter tool by Autotraintas

[Autotraintas](https://autotraintas.hariko.com) has created a tool that makes it possible to use nearly any Densha de GO! controller with the PC versions of the games. This includes the classic console controllers (USB adapter required) and the USB controllers for the PlayStation 2. The tool patches the game memory on the fly to reflect the input from the controller.

### PlayStation 2 cheat codes for PlayStation 1 controllers

While **Densha de GO! 3** and **Densha de GO! Shinkansen** officially support the original (non-USB) PlayStation 1 controllers, **Densha de GO! Ryojouhen**, **Densha de GO! Professional 2** and **Densha de GO! Final** are only compatible with USB controllers. Via cheat codes, it is possible to use the original PlayStation 1 controllers on real hardware, either with retail discs or via OPL.

The codes emulate a Type 2 controller. You will need to connect the controller as follows:

- Port 1: Dualshock or Dualshock 2 (D-pad, **SELECT**)
- Port 2: PlayStation 1 controller (handles and buttons, **SELECT** is mapped to **D**)

Each game requires a specific cheat code:

- [Densha de GO! Ryojouhen](controller-cheat_ryojouhen.txt)
- [Densha de GO! Professional 2](controller-cheat_pro2.txt)
- [Densha de GO! Professional 2 (Taito Best)](controller-cheat_pro2best.txt)

For retail discs, the codes can be loaded with [ps2rd](https://github.com/mlafeldt/ps2rd) or [Cheat Device](https://github.com/root670/CheatDevicePS2). If you are using OPL, it already includes ps2rd and you just need to copy the codes and enable cheats.

### Input plugins for BVE Trainsim/OpenBVE

BVE Trainsim and OpenBVE both support **input plugins**, which allow expanding the controllers compatible with the program.

BVE Trainsim requires installing external input plugins, depending on the controller:

- [Classic controllers](http://blog.livedoor.jp/hase_6809/archives/1249844.html) (USB adapter required)
- [DGG-255/DGOC-44U](http://www.konkyu.net/DenGoControllerInterface.aspx)
- [OHC-PC01](http://www.konkyu.net/SanYingControllerInterface.aspx)

OpenBVE includes built-in input plugins for all official Densha de GO! controllers (except TCPP-20017) and OHC-PC01. They can be enabled and configured in the program's settings. Note that a USB adapter is required for classic controllers.
