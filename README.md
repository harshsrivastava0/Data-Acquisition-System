# Data-Acquisition-System
A data acquisition system (DAQ for short) created for Team Defianz Racing wherein we take data from various sensors and display them on dashboard screen as well as the pit screen.


## Table of Contents
- [Sensors](#sensors)
- [Data](#data)
- [Credits](#credits)

## Sensors
We use the following sensors:
1. Motor Controller: DTI HV 500 LC (https://drivetraininnovation.com/webshop/inverters/dti-hv-500-liquid-cooled)
[mc]!(https://drivetraininnovation.com/_next/image?url=https%3A%2F%2Fwp.drivetraininnovation.com%2Fwp-content%2Fuploads%2F2022%2F10%2FHV-500-LC-AC-side.jpg&w=3840&q=75)



2. Battery Management System(BMS): BMS Orion 2 (https://www.orionbms.com/products/orion-bms-standard)
[bms]!(https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.NSqE4HeM6PPir5RTsKeRygHaHa%26pid%3DApi&f=1&ipt=c23257c23c20e77985ccd94606b7e78ffb879d359620200bc12e52137b779ce8&ipo=images)



3. Mass Flow rate Sensor (MFR)
[mfr]!(https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.0dcQG2wKK-bv4eLM9ceW3gHaHa%26pid%3DApi&f=1&ipt=5b196ff0dcd807fe3c39f2efe95099984d3a28e329520079a665c0925c0a8606&ipo=images)



## Data
We fetch the following data:
From Motor Controller: Motor Temperature, Motor Controller Temperature, ERPM, Throttle
From BMS: Accumulator current, Accumulator Voltage, State of charge, Highest temperature of a cell in the battery, lowest temperature of a cell in the battery
From MFR: Speed of the fluid in the cooling system tubes (unit: L/minute)


## Credits

