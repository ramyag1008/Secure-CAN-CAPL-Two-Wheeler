Secure CAN CAPL Implementation for Two-Wheeler ECUs

Overview
This repository contains CAPL source files associated with the security-aware Classical CAN communication architecture for two-wheeler Electronic Control Units (ECUs).

CAPL Source Files
1. ABS_Mux.can — ABS multiplexed communication.
2. Diagnostic_Mux.can — Diagnostic communication.
3. EMS_MUX.can — Engine Management System communication.
4. IC_MUX.can — Instrument Cluster communication.
5. Keyless_Mux.can — Keyless ECU communication.
6. Lighting_Mux.can — Lighting ECU communication.

Purpose
The files support the CANoe implementation and evaluation of ECU communication, message multiplexing, and associated signal-processing functions.

Usage
Open the relevant CAPL files within a compatible Vector CANoe project configured with the corresponding CAN database (DBC). Configure the network and ECU nodes according to the project setup before running the simulation.

Implementation Scope
Refer to the individual CAPL files for the functions implemented. The presence of a source file does not necessarily mean that all proposed security mechanisms, including complete ASCON cryptographic processing or authenticated selective wake-up, have been implemented and validated.

Research Context
These files support the implementation documentation for the project on security-aware multiplexed Classical CAN communication for two-wheeler ECUs.
