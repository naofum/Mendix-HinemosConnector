# Mendix-HinemosConnector

This module supports job execution which scheduled using NTT DATA Hinemos batch job scheduler.

Hinemos is a job scheduler like SOS JobScheduler, HITACHI JP-1, FUJITSU Systemwalker. About Hinemos, see. https://www.hinemos.info/

you can exec batch job like this. curl http://localhost:8080/rest/batchcallerws/v1/exec?microflow=batch.BatchA

## Dependencies
* CommunityCommons module


## Installation
* Import the module **HinemosConnector** in your project (from the Mendix AppStore or by downloading and exporting the module from this project)

- Create custom trap in the Hinemos.
- Create jobs in the Hinemos


## Configuration
- customize constants and others as your needed.


## License
- This module Licensed under the Apache License 2.0


## Version history
- 2.0.0 Convert to Mx 8.0.0
- 0.0.1 first functions for Hinemos connector implemented

