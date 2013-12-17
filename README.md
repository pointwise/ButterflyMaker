# ButterflyMaker
A Glyph script that converts H topology structured blocks into O-H (butterfly) topologies. 

![ScriptImage](https://raw.github.com/pointwise/ButterflyMaker/master/TkGUI.png)

## Selection
Upon starting the script, all currently available structured blocks will be listed in the selection box on the left. Before the script can be run, structured block(s) must be selected for conversion. Blocks may be selected through the provided list box. Alternatively, blocks may be selected interactively by using the "Click to Select Interactively" button. Block Groups are also listed in the selection box (with prefix GROUP); however, if the group contains unstructured blocks, only the structured blocks will be operated upon.

## Topology Options
I, J, K, or ALL: Direction of conversion. Specify the structured block's face that will receive butterfly topology.

H Region 3D Scaler: Specify a 3D vector used to scale the butterfly topology. The third component is only used when "All" is set for the direction.

Propagate Topology: If this option is checked, then the butterfly topology will propagate to any structured block that is adjacent to the selected block in the specified direction (I, J, or K). This option is not available when direction is set to "All".

Preview: Preview butterfly topology before it is created.

## Disclaimer
Scripts are freely provided. They are not supported products of
Pointwise, Inc. Some scripts have been written and contributed by third
parties outside of Pointwise's control.

TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, POINTWISE DISCLAIMS
ALL WARRANTIES, EITHER EXPRESS OR IMPLIED, INCLUDING, BUT NOT LIMITED
TO, IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
PURPOSE, WITH REGARD TO THESE SCRIPTS. TO THE MAXIMUM EXTENT PERMITTED
BY APPLICABLE LAW, IN NO EVENT SHALL POINTWISE BE LIABLE TO ANY PARTY
FOR ANY SPECIAL, INCIDENTAL, INDIRECT, OR CONSEQUENTIAL DAMAGES
WHATSOEVER (INCLUDING, WITHOUT LIMITATION, DAMAGES FOR LOSS OF BUSINESS
INFORMATION, OR ANY OTHER PECUNIARY LOSS) ARISING OUT OF THE USE OF OR
INABILITY TO USE THESE SCRIPTS EVEN IF POINTWISE HAS BEEN ADVISED OF THE
POSSIBILITY OF SUCH DAMAGES AND REGARDLESS OF THE FAULT OR NEGLIGENCE OF
POINTWISE.
	 

