# CAN filter

## **About**

Some Toyota vehicles have limited functionality with openpilot due to the limitations in of the built in Toyota Safety Sense (TSS). For openpilot's longitudinal functionality to work, the ACC messages coming from the radar must be filtered out.

This works the same way the SmartDSU filters out the ACC messages from the DSU for models with a DSU, [see this article](sdsu.md) with more information regarding that.

## Purchase

There does not seem to be anyone currently selling the CAN filter. Check the [#hw-canfilter](https://discord.com/channels/1193296115701923900/1193296910837108856) channel on Beartech discord for updates, or reach out to tinybear with a DM.&#x20;

## Reference

{% embed url="https://github.com/commaai/openpilot/pull/28440" %}

{% embed url="https://github.com/commaai/openpilot/wiki/Toyota-Lexus" %}

{% embed url="https://github.com/Smartype/canfilter" %}
