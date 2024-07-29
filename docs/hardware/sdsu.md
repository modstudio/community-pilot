# SDSU

## About

Older Toyota/Lexus vehicles have limited functionality with openpilot due to the limitations in of the built in Driver Support Unit (DSU). For openpilot's longitudinal functionality to work, the DSU must be unplugged.

### Challenges

Unplugging the DSU can cause several issues:

* CAN errors, potentially disabling autopilot entirely.
* Disabling Automatic Emergency Braking (AEB).

### Solutions

This can be resolved in one of two ways

<table><thead><tr><th width="202">Option</th><th width="311">Explanation</th><th>Purchase</th></tr></thead><tbody><tr><td>C-SDSU / SmartDSU</td><td>A device that sits between your DSU and the powertrain CAN bus of Toyota vehicles and filters the traffic between them, enabling openpilot longitudinal control without removing AEB.</td><td><a href="https://shop.tlbb.ca/products/copy-of-c-sdsu-smartdsu-for-toyota-openpilot-2-day-rush">Beartech</a></td></tr><tr><td>Smartened DSU</td><td>A DSU that is "smartened" to accomplish the same as the above without an additional device</td><td>Contact Erich Moraga (dm on comma discord server)<br><a href="https://discord.com/channels/469524606043160576/532179801474203649/687669433145229385">Link to discord post</a></td></tr></tbody></table>

### SmartDSU Installation&#x20;

1. Locate the DSU in your vehicle
2. Remove the harness from the DSU, plug it into the SDSU
3. Plug the harness from the SDSU into the DSU
4. Insure sure you have a fork installed that supports the SDSU like FrogPilot or sunnypilot

#### Locating the DSU

<table><thead><tr><th width="153">Model</th><th width="283">Location</th><th>Links</th></tr></thead><tbody><tr><td>Lexus ES</td><td>Behind the glove compartment</td><td><a href="https://youtu.be/njlkA-RWzjg?si=wiAEws1p0ojcF1p1&#x26;t=370">YouTube → Beat-Sonic → Removing the glove compartment 1</a><br><a href="https://youtu.be/P01pwrMV5EY?si=8Xev3G6XFegFNKKq&#x26;t=292">YouTube → Beat-Sonic → Removing the glove compartment 2</a></td></tr><tr><td>Lexus IS</td><td>Above the driver's right knee when seated in the driver's seat</td><td></td></tr><tr><td>Lexus RX</td><td>Behind the glove compartment</td><td><a href="https://www.reddit.com/r/Comma_ai/comments/12y0n7k/please_help_lexus_rx350_2019_dsu/">Reddit → Access DSU</a></td></tr><tr><td>Toyota Corolla</td><td>Through the glove compartment behind the head unit</td><td></td></tr></tbody></table>

## Reference

Links to code and information regarding the SDSU

<table><thead><tr><th width="349">Link</th><th>Info</th></tr></thead><tbody><tr><td><a href="https://github.com/commaai/panda">GitHub → comma.ai → panda → master</a></td><td>Comma code related to the the SDSU</td></tr><tr><td><a href="https://github.com/wocsor/panda/tree/smart_dsu?tab=readme-ov-file">GitHub → Kevin Roscom → panda → smart_dsu branch</a></td><td>Fork of comma panda code with info and code supporting the SDSU</td></tr><tr><td><a href="https://github.com/RetroPilot/panda/tree/master/board/smart_dsu">GitHub → Retropilot → panda/board /smart_dsu</a></td><td>Up to date version of the above SDSU code</td></tr><tr><td><a href="https://discord.com/channels/1193296115701923900/1193296608390021150">Discord → Beratech → #hw-sdsu</a></td><td>Info regarding Beartech SDSU</td></tr></tbody></table>
