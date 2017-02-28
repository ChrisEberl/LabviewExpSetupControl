### National Instruments LabVIEW(R) implementation of an Experimental Setup Control based on a National Instrument FPGA A/D Board 

This is a National Instruments LabVIEW(R) implementation of an Experimental Setup Control based on a National Instrument FPGA A/D board which is still in beta status. This vi was written by Tobias Kennerknecht and can be used to control complex experimental setups by menas of an National Instruments FPGA based D/A PCIe board within a workstation. It allows for up to 8 inputs and 8 outputs with a resolution 16 bit. Relative to normal actuators, the control can be quasi realtime. The input data, e.g. from a load cell, strain sensors or others can be treated and processed on the FPGA and the output can be used to drive actuators, e.g. piezos or spindel driven motors. The data is further processed on the host computer and can saved continuously during runtime e.g. on a hard drive. A Description of a physical implementation can be found in the thesis of Tobias Kennerknecht: https://www.ksp.kit.edu/9783731502937. 

### Acknowledgment:  
* Code Author: Tobias Kennerknecht
* Involved People: Chris Eberl
* Collaborators for control software and reviewers: Thomas Straub, Sofie Burger, Matthias Funk, Stefan Slaby, Sven Bundschuh, Daniel S. Gianola, Thomas J. Balk, many others...
* Funding was provided by the German Science Foundation DFG e.g. within the independent research group grant issued to Chris Eberl between 2007-2012 at the KIT and later at the Albert-Ludwigs University Freiburg, Germany. 
  
### License

Copyright 2017 Albert-Ludwigs-University Freiburg, Germany, Chair of Micro and Materials Mechanics 

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at
http://www.apache.org/licenses/LICENSE-2.0  

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
