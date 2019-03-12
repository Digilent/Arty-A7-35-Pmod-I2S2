Arty A7-35 Pmod I2S2 Demo
==============
 
Description
--------------
This project is a Vivado demo using the Arty A7-35's switches and the Pmod Port JA with the Pmod I2S2 , written in Verilog. It creates a pass-through from Line-In to the Line-Out jack. 
The audio data coming through this passthrough is scaled by the number of switches on the FPGA that are closed. All switches open means that the data stream will be muted.
All switches closed means that the data stream will be at full volume. The audio volume scales linearly between these two points. You can reset the demo by using the RESET Button.
In addition, headphones or speakers and an audio input source (such as a personal computer) are also required.

Requirements
--------------
* **Arty A7-35**: To purchase a Arty A7-35, see the Digilent [Store](https://store.digilentinc.com/arty-a7-artix-7-fpga-development-board-for-makers-and-hobbyists/)
* **Pmod I2S2**: To purchase a Pmod I2S2, see the Digilent [Store](https://store.digilentinc.com/pmod-i2s2-stereo-audio-input-and-output/)
* **Vivado 2018.2 Installation**: To set up Vivado, see the [Installing Vivado and Digilent Board Files Tutorial](https://reference.digilentinc.com/vivado/installing-vivado/start).
* **MicroUSB Cable**
* **Headphones or speakers**
* **Audio input source (such as a personal computer)**

Demo Setup
--------------
1. Download and extract the most recent release ZIP archive from this repository's [Releases Page](https://github.com/Digilent/Arty-A7-35-Pmod-I2S2/releases).
2. Open the project in Vivado 2018.2 by double clicking on the included XPR file found at "\<archive extracted location\>/vivado_proj/Arty-A7-35-Pmod-I2S2.xpr".
3. In the Flow Navigator panel on the left side of the Vivado window, click **Open Hardware Manager**.
4. Plug a Arty A7-35 into the computer using a MicroUSB cable.
5. In the green bar at the top of the Vivado window, click "Open target". Select "Auto connect" from the drop down menu.
6. In the green bar at the top of the Vivado window, click "Program device".
7. In the Program Device Wizard, enter "\<archive extracted location\>vivado_proj/Arty-A7-35-Pmod-I2S2\vivado_proj\Arty-A7-35-Pmod-I2S2.runs\impl_1/top.bit" into the "Bitstream file" field. Then click **Program**.
8. The demo will now be programmed onto the Arty A7-35. See the Introduction section of this README for a description of how this demo works.

Next Steps
--------------
This demo can be used as a basis for other projects, either by adding sources included in the demo's release to those projects, or by modifying the sources in the release project.

Check out the Arty A7-35's [Resource Center](https://reference.digilentinc.com/reference/programmable-logic/arty-a7/start) to find more documentation, demos, and tutorials.

For technical support or questions, please post on the [Digilent Forum](https://forum.digilentinc.com).

Additional Notes
--------------
For more information on how this project is version controlled, refer to the [Digilent Vivado Scripts Repository](https://github.com/digilent/digilent-vivado-scripts)