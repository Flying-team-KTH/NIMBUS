# NIMBUS
This is a repo for the NIMBUS-aircraft. It should contain most of the information needed to understand and operate the aircraft. Also read reports from earlier projects with NIMBUS before attempting to fly or change in any way. Start with [this](https://kth.diva-portal.org/smash/record.jsf?pid=diva2%3A1822781&dswid=8624)[^1] report from Erik Barsby and Casper Augustsson. For further reading, ask Nickolay Ivchenko (last updated 2024-03). 


## Required software

### Ground station
In order to work at any with the Ardupilot aircraft, you need a ground station application. It is higly recommended to use [Mission Planner](https://ardupilot.org/planner/index.html)[^2]. There are others, but they are not as fully equiped and have not been tested in the KTH Flying Team. It is only available for Windows. MacOS users are recommended to either get ahold of a Win-PC for the project, use the one available to the Flying Team or use Bootcamp. Should you have a M-series Mac, you could consider an emulator such as [Parallels Desktop](https://www.parallels.com/)[^3].

### [CAD-files](3D-files)
All models have been made using Autodesk Fusion360 (education licence provided for free). Files are saved here in `.m3f` format and should be updated as such. 3D-printable files in their latest version should be made available as `.stl` files. See folder `3D-files`

## Other information

### [*configuration.json*](configuration.json)
This file contains the latest config of the aircraft, with model numbers and such information that any part should be able to be changed without taking apart the plane. It is a `.json` file and shoud be formatted as such (not very difficult). If anyone knows of a good way to display it (maybe as a tree structure), please feel free to implement it. 

### [Parameter-file](NIMBUS.param)
It would be great if the latest parameters for the aricraft could be available to everyone on the Flying Team via this repo. If you are unsure about parameters, see [this website](https://ardupilot.org/planner/docs/mission-planner-configuration-and-tuning.html) and learn how to save and import parameters. If you have made an update to the parameters of the aircraft and verified that it does what you wanted, please save the parameters to a file and update the repo. Your commit should contain information on what has been changed. This is important for rollback!


[^1]: Barsby, E., & Augustsson Savinov, C. (2022). Building A Fixed Wing Autonomous UAV (Dissertation). Retrieved from https://urn.kb.se/resolve?urn=urn:nbn:se:kth:diva-323609
[^2]: Instructions and download available at https://ardupilot.org/planner/index.html
[^3]: Be aware that setup might not be straigt forward with USB-drivers and such. Parallels Desktop is a paid software and might not be worth it for you. Buy at https://www.parallels.com/ or research similar free applications. It does not have to be powerful to run Mission Planner!
