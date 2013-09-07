Arduino-MPPT
============

Used on PLC for solar portable vaccine refridgerator Afia, a project undertaken by LIGTT (LBNL Institute of Globally Transformative Technologoies) at the Lawrence Berkeley National Laboratories in Berkeley, CA.

Algorithm must perform the following:
	- measure and log temperatures from 14 thermistors on a pre-set interval
	- determine a power setting to run pumps for thermoelectric modules using the available solar power
	- run the maximal power point tracking (MPPT) algorithm for optimizing power drawn from solar panels
	- go into a low-power setting overnight and when not recording data

