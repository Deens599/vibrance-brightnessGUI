# Changes in this repo

This fork implements Windows 11's SDR Content Brightness controls alongside the existing NVIDIA/AMD Digital Vibrance controls. Due to the limitations and very limited documentation of the SDR Content Brightness API, only the primary monitor will be affected regardless of the settings.

These settings seem to be completely disconnected from the slider in the Display settings, so if anything bugs out, just go to Settings -> System -> Display -> HDR and click on the slider, it should retain the same value as before using this program.

### Not tested on:
1. AMD hardware
2. SDR-only setups
3. Setups with more than one HDR monitor

### Credits:
1. MaloW for C# code for controlling SDR Content Brightness (https://stackoverflow.com/questions/74594751/controlling-sdr-content-brightness-programmatically-in-windows-11)
2. juv for making vibranceGUI

# Original README

# vibranceGUI

VibranceGUI is a Windows Utility written in C# that automates NVIDIAs Digitial Vibrance Control and AMDs Saturation for Games, e.g. Counter-Strike: Global Offensive by utilizing native graphic card driver APIs. 

As of 18th April 2015, vibranceGUI also fully supports AMD graphic cards. Prior to that, vibanceGUI was developed to support NVIDIA graphic cards only. 

Note that NVIDIA Laptop GPUs are not supported because their drivers do not contain the needed functionality.
Intel did not publish an API for their integrated GPUs and are not supported. 

More information and binary download available at: http://vibrancegui.com/

## Compiling

When compiling, make sure to compile for x86 target platform.  

## Contributing

Every contribution is greatly appreciated. Do not hesitate to submit every issue and pull request that comes to your mind.

## Contact

NVIDIA support: https://twitter.com/juvlarN
  
AMD support: https://twitter.com/juRiiir3

`Please do not add either of us at Steam to ask questions about vibranceGUI. Thank you.`
