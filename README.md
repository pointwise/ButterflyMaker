# ButterflyMaker
Copyright 2021 Cadence Design Systems, Inc. All rights reserved worldwide.

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
This file is licensed under the Cadence Public License Version 1.0 (the "License"), a copy of which is found in the LICENSE file, and is distributed "AS IS." 
TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, CADENCE DISCLAIMS ALL WARRANTIES AND IN NO EVENT SHALL BE LIABLE TO ANY PARTY FOR ANY DAMAGES ARISING OUT OF OR RELATING TO USE OF THIS FILE. 
Please see the License for the full text of applicable terms.
