# Crazyflie Firmware  [![CI](https://github.com/bitcraze/crazyflie-firmware/workflows/CI/badge.svg)](https://github.com/bitcraze/crazyflie-firmware/actions?query=workflow%3ACI)

This project contains the source code for the firmware used in the Crazyflie range of platforms, including the Crazyflie 2.X and the Roadrunner.
NHR: Firmware is modified to allow streaming of a control vector [ang_rate_roll, ang_rate_pitch, ang_rate_yaw, thrust], which is fed to an adaptive INDI controller. 
This INDI controller takes commands from a MPC controller running on a seperate entity.


### Crazyflie 1.0 support

The 2017.06 release was the last release with Crazyflie 1.0 support. If you want
to play with the Crazyflie 1.0 and modify the code, please clone this repo and
branch off from the 2017.06 tag.

## Building and Flashing
See the [building and flashing instructions](https://github.com/bitcraze/crazyflie-firmware/blob/master/docs/building-and-flashing/build.md) in the github docs folder.


## Official Documentation

Check out the [Bitcraze crazyflie-firmware documentation](https://www.bitcraze.io/documentation/repository/crazyflie-firmware/master/) on our website.

## Generated documentation

The easiest way to generate the API documentation is to use the [toolbelt](https://github.com/bitcraze/toolbelt)

```tb build-docs```

and to view it in a web page

```tb docs```

## License

The code is licensed under LGPL-3.0
