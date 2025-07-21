# Proximity Radar for FiveM

Simple client-side script for FiveM that displays nearby players within a configurable radius.  
Shows player server ID and distance above their heads in 3D text.

## Features

- Detects players within a configurable radius (default 50 meters)  
- Displays player server ID and precise distance  
- Lightweight and easy to use  
- Pure client-side script (no server-side permissions needed for local/private servers)  

## Installation

1. Clone or download this repository.  
2. Place the folder `proximity_radar` into your FiveM `resources` directory.  
3. Add the following line to your server config (`server.cfg`):

   ```plaintext
   ensure proximity_radar
## Restart your server or start the resource manually via the console:

ensure proximity_radar

Usage
Once started, the script will automatically display the IDs and distances of nearby players (within 50 meters) above their heads in-game.

You can modify the detection radius by editing the radarRadius value in client.lua.

Notes
This script is intended for private or local servers where you have control.

On public servers, you need admin permission to add and start resources.

The script is client-side and lightweight for minimal performance impact.

License
This project is open-source and free to use under the MIT License.
