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

<table><thead><tr><th width="189">Model</th><th></th></tr></thead><tbody><tr><td>Lexus IS</td><td>Above the driver's right knee when seated in the driver's seat</td></tr><tr><td>Lexus ES</td><td>Behind the glove box </td></tr><tr><td>Toyota Corolla</td><td>Through the glove box behind the head unit</td></tr></tbody></table>

## Reference

{% embed url="https://github.com/wocsor/panda/tree/smart_dsu?tab=readme-ov-file" %}

{% embed url="https://github.com/commaai/openpilot/wiki/Smart-DSU" %}
