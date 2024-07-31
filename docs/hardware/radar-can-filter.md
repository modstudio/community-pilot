# Radar CAN Filter

## **About**

Some Toyota vehicles experience limited functionality with openpilot due to the constraints of the built-in Toyota Safety Sense (TSS). To enable openpilot's longitudinal control functionality, it is necessary to filter out the adaptive cruise control (ACC) messages originating from the radar.

The Radar CAN Filter functions similarly to the SmartDSU (Driver Support Unit) by filtering out ACC messages from the vehicle’s radar. This filtering is crucial for allowing openpilot to take over longitudinal control (i.e., acceleration and braking), ensuring smoother and more effective operation of the vehicle’s autonomous driving capabilities.

For more detailed information on how the Smart DSU works, refer to the [Openpilot Wiki on Smart DSU](https://github.com/commaai/openpilot/wiki/Smart-DSU), see also [this article](sdsu.md).

## Purchase

There does not seem to be anyone currently selling the Radar CAN Filter. Check the [#hw-canfilter](https://discord.com/channels/1193296115701923900/1193296910837108856) channel on Beartech discord for updates, or reach out to tinybear with a DM.&#x20;

## Reference

{% embed url="https://github.com/commaai/openpilot/pull/28440" %}

{% embed url="https://github.com/commaai/openpilot/wiki/Toyota-Lexus" %}

{% embed url="https://github.com/Smartype/canfilter" %}
