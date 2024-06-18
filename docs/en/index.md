# 
<img src="img/easycal_header.svg" alt="header" width="400"/>

## What is VSE EasyCal?

#### Motivation
The EasyCal software was developed in companion with the Cal.flow to perform flowmeter calibrations with high accuracy. The main focus of this system is keeping the calibration setup and procedure as simple as possible for the end user. 

#### VSE Cal.flow
The Cal.flow is an external USB Device that is attached to a PC to perform signal measurements and calculations of two attached flowmeters. Hardware specifications of the device can be found [here](calflow.md).

#### Main features
EasyCal offers the following main features:

* Highly accurate flowrate/frequency measurement of two flowmeters (ratio counting method)
* Calibration of DUT (device under test) flowmeter using reference principle
* Automatic calculation of error and reproducibility
* Generation of PDF calibration reports with full documentation and customer logo
* Export of results as excel sheet for maximum value precision in futher calculations
* Guided flow adjustment with steadyness check
* Live graph of flowrate for both flowmeters
* Master Linearisation with up to 24 points
* Modular and preset-based configuration of calibration procedure
* Integration of VSE flowmeter data for fast value lookup
* Calibration point template generator
* Advanced settings like calibration time and hysteresis limits

## Structure

This documentation is structured into the following main chapters:

* [Basics](basics.md) for connecting the hardware correctly and how the software works
* [Calibration setup](program.md) describes how a calibration is configured
* [Calibration procedure](procedure.md) shows how the calibration procedure is performed 
* [Cal.flow](calflow.md) explains the hardware features and specifications of the Cal.flow
* [FAQs](faqs.md) shows how to solve the commonly asked questions and problems

## Hardware requirements

The PC running the EasyCal software should meet the following minimum hardware requirements:

* 2 GHz processor (x64) or faster
* 64-bit Windows installation
* 512 MB RAM or more
* Graphics card with DirectX11 support
* 100 MB free hard disk space
* Screen resolution: at least 1440x900 px
* USB 2.0 interface or better
* Optional internet connection for update check

## License info

Disclaimers and license information of used software components can be found in the [About](about.md) section.