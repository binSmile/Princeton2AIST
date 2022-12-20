# AnySpectrometr2AIST
 Simple TCP server for simulating LabRAM's answers. It tested with Princeton spectrometer and AIST-NT program.
 
 
## SpecServer_LV.py
 TCP server, which wait connection on 1234 port and simulate answers of "AFMServer 0.6.3". Such answers provide LabRAM (Horiba Jobin Yvon) with LabSpec v4 software. 
 It is compatible with AIST-NT software (tested on 3.5.115 version).
 
 This server wait connection from AIST-NT and do spectrum measurements by TCP-query to another server.
 
## Simple TCP - Server - Princeton.vi
 
 This is LabView TCP server for Princeton spectrometer. This program wait  connection in 2234 port, do measurements and answers with spectrum

## AIST-Dialog-example.txt
The example of dialog during mapping 2x2 between AIST and LabRAM