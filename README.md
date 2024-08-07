<div align="center">

# Shock Collar OSC Bridge

[![Generic badge](https://img.shields.io/github/downloads/jellejurre/Shock-Collar-OSC-Bridge/total?label=Downloads)](https://github.com/jellejurre/Shock-Collar-OSC-Bridge/releases/latest)
[![Generic badge](https://img.shields.io/badge/License-MIT-informational.svg)](https://github.com/jellejurre/Shock-Collar-OSC-Bridge/blob/main/LICENSE)
[![Generic badge](https://img.shields.io/badge/Unity-2019.4.31f1-lightblue.svg)](https://unity3d.com/unity/whats-new/2019.4.31)
[![Generic badge](https://img.shields.io/badge/SDK-AvatarSDK3-lightblue.svg)](https://vrchat.com/home/download)

Connect Liindys Shock Collar to your Pishock or Openshock shockers!

### ⬇️ [Download Latest Version](https://github.com/jellejurre/Shock-Collar-OSC-Bridge/releases/latest)

</div>

# Features

This controller works as a bridge between Liindys Shock Collar and VRCOsc or ShockOSC with a list of preset values for intensity and duration.

Note: Hold mode isn't supported. It will shock with the previously set values.

# Usage

- Buy and install Liindys Shocker System as per their instructions.
- Import the latest unity package from the [Releases Page](https://github.com/jellejurre/Shock-Collar-OSC-Bridge/releases/latest)
- Use VRCFury or the Avatar 3.0 Manager to install the `ShockOSCBridgeFX` controller.
  - If using the Avatar 3.0 Manager, make sure to remove the   `0` postfixes from the merged parameters before merging.
![Untitled](https://github.com/user-attachments/assets/952ec517-1252-463f-a6d8-2fbf732395e5)
  - So remove the “ 0” above from those fields.
- Change the ShockCollarOSCBridge/Intensity1-5 and ShockCollarOSCBridge/Duration1-5 values to your liking, Intensity goes from 0 to 100, Duration goes from 1 to 10 in full seconds.

From here on your install route depends on if you’re using PiShock software shockers or OpenShock software shockers.

# Pishock route
- Install VRCOSC from [here](https://github.com/VolcanicArts/VRCOSC).
- Enable the PiShock module at the bottom by clicking on the big gray checkbox.
![Untitled(1)](https://github.com/user-attachments/assets/68074cca-92e7-45b5-ae0f-b5ec75b4bddb)
- Click on the gear icon at the right of this module to enter the settings page.
- Enter your username and API Key, and set up a Shocker with a name and a sharecode.
- Create a group with your shocker(s) in it. Make sure this group is group 0 as this controller will only shock group 0.

# OpenShock route
- Install ShockOSC from [here](https://github.com/OpenShock/ShockOSC).
- Log in with your OpenShock account. It should automatically find your OpenShock shockers.

Note: The asset will shock all your active OpenShock shockers.
