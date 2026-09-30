# FlowCompute: A Cross-Platform OpenFOAM Client

FlowCompute is an open-source graphical client for OpenFOAM. Available for Windows and Linux, it lets you create cases, generate meshes, configure simulations, and launch OpenFOAM tools without relying on the command line. FlowCompute can execute in three ways:

* Run in Linux while OpenFOAM runs locally
* Run in Windows while OpenFOAM runs in WSL
* Run in Linux or Windows while OpenFOAM runs on a remote system

Released under the GNU Lesser General Public License (LGPL), FlowCompute is free to use, modify, and distribute. The complete source code is available on [Github](https://github.com/FlowComputeClient/flowcompute).

![The FlowCompute Graphical User Interface](images/flowcompute.gif)

## Video Demonstrations

The following YouTube videos demonstrate FlowCompute in action:

* [Linux demonstration](https://youtu.be/2V0Cg_nVLG0) - Runs a transient simulation with compressible flow
* [Windows demonstration](https://youtu.be/r2RV39VZIRo) - Runs a steady-state simulation with incompressible flow

## Features and Capabilities

The client streamlines case management by generating dictionary files based on user input. Powerful wizards guide users through creating case folders, customizing the meshing process, and configuring the simulation. When all the dictionary files have been created, OpenFOAM utilities can be launched using buttons.

Important features include:

* **Multi-language support** - The FlowCompute interface can display text in English, German, French, Italian, Japanese, Korean, Portuguese (Brazilian), Swedish, and Chinese (Simplified)
* **High-performance rendering** - Utilizing a custom Vulkan rendering pipeline, the interface will accurately display surfaces and OpenFOAM meshes
* **Configuration wizards** - Easily generate case files, mesh configuration files, and simulation files
* **Text editors** - Natively edit and update dictionary files with syntax coloring and error checking
* **Utility access** - Instantly launch OpenFOAM utilities using dialogs and buttons
* **Data validation** - Automatically ensure that dictionary files are formatted correctly

---
&copy; 2026 FlowCompute LLC &dash; All rights reserved
