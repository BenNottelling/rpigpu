# Overview

Experimental WDDM driver for Raspberry Pi. You might want to check out the [webpage](http://rpidrivers.bennottelling.com/gpu/discretehybrid/) for it to see the most recent tests performed

![Build status](https://ci.appveyor.com/api/projects/status/gw8dxlvha99pm9u6?svg=true)

## Goals
Support [hybrid rendering systems](https://docs.microsoft.com/en-us/windows-hardware/drivers/display/using-cross-adapter-resources-in-a-hybrid-system)
Basic tiled texture support to help windows feel snappier
DirectX 9 support, to build off of eventually

## Installing / Testing

Download one of the [releases](https://github.com/BenNottelling/rpigpu/releases), usually the newest is better
Run the `prerun.bat` file, this will prepare settings and configurations currectly for how the driver is intended to be tested as, then right click `Ros.inf` and select install