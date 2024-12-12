# RAE Home Page
This is the homepage for Ricardo Avionics Ecosystem (RAE). This is where you will find a brief description of every repository related to RAE, as well as links for easier navigations.

## Templates

[Board Template](https://github.com/icl-rocketry/Ricardo-BoardTemplate) - Template which includes a microcontroller, power regulation and CAN bus hardware - the hardware starting point for most boards designed for use in RAE.

[OS Template](https://github.com/icl-rocketry/Ricardo-OS-Template) - Barebones firmware template - the firmware starting point for boards design for use in RAE.

## Middleware
[Backend](https://github.com/icl-rocketry/Ricardo-Backend) - Python based backend for command and data handling in the ricardo avionics ecosystem.

[Backend Apps](https://github.com/icl-rocketry/Ricardo-Backend-Apps) - Various useful utilities, scripts and applications for use with the Backend.

[Backend Stack](https://github.com/icl-rocketry/Ricardo-Backend-Stack) - Docker stack to conveniently deploy a full Ricardo Backend Stack(Backend, Command Server, Grafana) for use in operations.

[TaskHandler UI](https://github.com/icl-rocketry/TaskHandler) - UI Task handler to manage data task request handler tasks.

[Command Server](https://github.com/icl-rocketry/Ricardo-CommandServer) - Command server to send commands to the ricardo backend.

[Relay](https://github.com/icl-rocketry/Ricardo-InfluxRelay) - 


## Libraries
[iclr-hw](https://github.com/icl-rocketry/iclr-hw) - ICLR KiCAD library for 3rd party symbols and footprints.

[libriccore](https://github.com/icl-rocketry/libriccore) - Ricardo core library - core firmware framework for all RAE boards.

[librrc](https://github.com/icl-rocketry/librrc) - Ricardo rocket components - a high level abstraction of rocket components, providing two main groups, sensors and actuators.

[librnp](https://github.com/icl-rocketry/librnp) - Ricardo networking protocol - a networking library written in C++ for ricardo.

[librrp](https://github.com/icl-rocketry/librrp) - Ricardo radio library

## Boards
[PickleRick](https://github.com/icl-rocketry/Ricardo-PickleRick) - Flight controller including sensor array for state estimation, radio for live telemetry, logging and deployment pyro channels.

[Chad](https://github.com/icl-rocketry/Ricardo-Chad) - 2x Servo control board with integrated buck converter.

[Flint & Steel](https://github.com/icl-rocketry/Ricardo-FlintandSteel) - High power actuation board with continuity checking and current sensing.

[Lightning McQueen](https://github.com/icl-rocketry/Ricardo-LightningMcQueen) - Power distribution unit with two switchable rails, logic power regulation, arming and redundancy.

[Kermit](https://github.com/icl-rocketry/Ricardo-Kermit) - Data acquisiton board, with ADC and thermocouple capability.

[Stark](https://github.com/icl-rocketry/Ricardo-Stark) - Integrated engine controller unit for Thanos.

[Buckaroo](https://github.com/icl-rocketry/Ricardo-Buckaroo) - High current buck converter.

[WitcherSwitcher](https://github.com/icl-rocketry/Ricardo-WitcherSwitcher) - Power source switching board.

[Can Repeater](https://github.com/icl-rocketry/Ricardo-CANRepeater) - CAN Bus repeater, with isolation and arbitration.

[BlackBox](https://github.com/icl-rocketry/Ricardo-BlackBox) - Flight data recorder.

[Geddan](https://github.com/icl-rocketry/Ricardo-Canardboard) - Canard module control board - integrated IMU and servo output.

[Greg](https://github.com/icl-rocketry/Ricardo-Greg) - Electronic pressure regulator (E-reg) hardware and firmware.


## Forks

[SdFat](https://github.com/icl-rocketry/SdFat) - Fork of SdFat to keep config parameters the same across ricardo boards using sd card logging.

[arduino-esp32](https://github.com/icl-rocketry/arduino-esp32) - Fork of the arudino core for the esp32 for testing and bugfixes.
