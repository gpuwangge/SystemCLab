# What is SystemC
![Windows](https://img.shields.io/badge/Windows-passing-brightgreen)

SystemC is a language built in standard C++ to model Hardware.   
https://systemc.org/overview/systemc/#systemc
# What is SystemC Lab
SystemC Lab is sandbox with SystemC/TLM example code based on:  
https://www.accellera.org/downloads/standards/systemc
## Build
Open SystemC_examples.sln or tlm_examples.sln in build-msvc/ with Visual Studio(2019 or later) and build  
## Structure
### libs/ 
SystemC.lib 
(build from systemc-2.3.4, Visual Studio 2019, Debug, x64)
### src/   
include files for SystemC.lib 
### sysc/
SystemC example source codes
### tlm/   
TLM example source codes 
## How to rebuild SystemC.lib
If for some reason you want to rebuild SystemC.lib (ex: x86), this is the step:  
In the SystemC/TLM download webpage, download core zip file, such as:  
Core SystemC Language and Examples (.zip) 2022-12-01  
After unzip file, open msvc10/, click SystemC.sln and build  
build libs are here: msvc10\SystemC\x64\Debug
## Visual Studio 2022 Compatibility
This project is created with Visual Studio 2019  
If open with Visual Studio 2022, a window will pop up to ask for upgrading Platform Toolset from v142 to v143  
The project should build fine  
