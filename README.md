
# Industial Control Trainer LabVIEW GUI :computer:

LabVIEW GUI for the Bytronic ICT3 (Industrial Control Trainer)

## Requirements

- **[LabVIEW]** 2016 or greater
- Ni DAQ Unit
- Bytronic [ICT3] Educational Unit

## Abstract

The use of automation technology in the world is widespread and a growing field.  Automation is used everywhere from software tasks to physical tasks. The ICT3 platform is a typical representation of an industrial automation setup. The objective of this project is to use LabVIEW to develop an efficient and robust, fully automated controller for the [ICT3] setup to asssemble widgets.

The method used for the base controller was an event programming structure. The Graphical User Interface, GUI was designed for ease of use and short learning-time. At every clock-cycle, all the sensors where polled for data. When the right sequence of data was read, the corresponding actuator action and program data were executed and updated respectively.

On an average test cycle, the system was able to reach an accuracy of 100% on sorting pegs and rings, _**95%**_ on assembling a ring and peg, _**99%**_ in sensing which part passes through the Quality Assurance area, and a _**100%**_ in the Rejection area. The system also is able to save and load a **csv** file of its outputs using LabVIEW's file I/O funcatinality. The project demostrated how LabVIEW can be used to program a complex controller to automate the ICT3 platform and generate its runtime results in a csv file.

## License

License can be found in [LICENSE](/LICENSE)

[LabVIEW]: http://www.ni.com/en-ca/shop/labview.html
[ICT3]: http://www.bytronic.net/product/industrial-control-trainer-ict3/
