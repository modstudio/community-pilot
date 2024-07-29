# Popular Forks

While openpilot is excellent on its own, several popular community forks enhance its functionality and support hardware like SDSU and Comma Pedal.

[Click this link](https://bderkhan.com/comma-ai-openpilot/sunnypilot-features-and-updates/openpilot-vs-sunnypilot/) to view a comparison between the different forks.

<table><thead><tr><th width="137">Name</th><th width="167">Links</th><th>About</th></tr></thead><tbody><tr><td>FrogPilot</td><td><p><a href="https://github.com/FrogAi/FrogPilot">GitHub</a></p><p><a href="https://discord.gg/frogpilot">Discord / Invite</a></p><p><a href="https://discord.com/channels/1137853399715549214/">Discord / Home</a></p></td><td>A monthly updated and 100% open-sourced fork of openpilot with clean commits dedicated to serve the openpilot community! FrogPilot is shaped by user and developer contributions, emphasizing collaborative, community-driven development to provide a bleeding-edge openpilot experience for everyone!<br><br>Install link: frogpilot.download</td></tr><tr><td>openpilot</td><td><p><a href="https://github.com/commaai/openpilot">GitHub</a></p><p><a href="https://discord.comma.ai/">Discord / Invite</a></p><p><a href="https://discord.com/channels/469524606043160576/">Discord / Home</a></p><p><a href="https://comma.ai/openpilot">Homepage</a></p></td><td>Official comma.ai openpilot repo</td></tr><tr><td>sunnypilot</td><td><p><a href="https://github.com/sunnypilot/sunnypilot">GitHub</a></p><p><a href="https://discord.gg/sunnypilot">Discord / Invite</a></p><p><a href="https://discord.com/channels/880416502577266699">Discord / Home</a><br><a href="https://www.sunnypilot.ai/">Homepage</a></p></td><td>sunnypilot is a fork of comma.ai's openpilot, an open source driver assistance system. sunnypilot offers the user a unique driving experience for over 290 supported car makes and models with modified behaviors of driving assist engagements. sunnypilot complies with comma.ai's safety rules as accurately as possible. <br><br>Install link: <a href="https://release-c3.sunnypilot.ai">https://release-c3.sunnypilot.ai</a></td></tr><tr><td>DragonPilot</td><td><a href="https://github.com/dragonpilot-community/dragonpilot">GitHub</a></td><td></td></tr></tbody></table>

## Community Features

<mark style="color:orange;background-color:yellow;">This section is a WIP!</mark>

Below are highlights of the community-supported features. Community forks include all the features of stock openpilot but add additional functionalities and the ability to fine-tune the driving experience and user interface.

<table><thead><tr><th width="335">Feature</th><th width="202">FrogPilot</th><th>SunnyPilot</th></tr></thead><tbody><tr><td>Support for Comma Pedal and SDSU</td><td>Has support</td><td>Has support</td></tr><tr><td>Separation of Lateral and Longitudinal</td><td>Always on Lateral</td><td>MADS</td></tr><tr><td>Lateral Adjustments </td><td>Multiple settings</td><td>Multiple settings</td></tr><tr><td>Automatic Lane Changes</td><td>Nudgeless lane changes</td><td>Automatic Lane Changes</td></tr><tr><td>Longitudinal Adjustments</td><td>Multiple settings</td><td>Multiple settings</td></tr><tr><td>Turn Speed Control</td><td>Vision Turn Speed Controller &#x26; Map Turn Speed Controller</td><td>Vision-based Turn Speed Control &#x26; Map-Data-based Turn Speed Control</td></tr><tr><td>Speed Limit Control</td><td>Speed Limit Controller</td><td>Speed Limit Control</td></tr><tr><td>Driving Model Selector</td><td>Yes</td><td></td></tr><tr><td>Offline maps</td><td>Offline maps</td><td>Offline OSM Maps</td></tr><tr><td>Driving UI Customizations</td><td>Multiple settings</td><td>Multiple settings</td></tr><tr><td>Developer UI</td><td>Developer UI</td><td>Developer UI</td></tr><tr><td>Device Management</td><td>Multiple settings</td><td>Multiple settings</td></tr><tr><td>Fleet Manager</td><td>Fleet Manager</td><td>Fleet Manager</td></tr></tbody></table>

### Features explained

<details>

<summary>Support for Comma Pedal and SDSU</summary>

Comma Pedal and SDSU are additional hardware that enable support for openpilot features in some older vehicles. These devices are not manufactured by comma.ai and are not supported by the stock openpilot. However, community forks do support them, allowing users to fully benefit from openpilot's features.

</details>

<details>

<summary>Separation of Lateral and Longitudinal</summary>

The ability to have lateral control (ALC/LKA) without longitudinal control (ACC/SCC) is particularly useful in challenging driving conditions. This feature allows for continued lateral assistance even when longitudinal control is not ideal. Many users appreciate the option to always keep lateral control engaged.&#x20;

</details>

<details>

<summary>Automatic Lane Changes</summary>

Change lanes without requiring a nudge on the steering wheel. Also, other adjustments can be made to when lane changes are made, for example, adding a lower limit to when a lane change would be made.&#x20;

</details>

<details>

<summary>Turn Speed Control</summary>

This feature slows the vehicle when approaching a turn and resumes the original speed once past it. Turns can be detected via vision or map data. Users can also adjust the settings to their desired driving comfort.

</details>

<details>

<summary>Speed Limit Control</summary>

Automatically adjust your speed to the posted speed limit using information from speed limit signs, map data, and the car's interface. This feature includes the ability to set an offset from the posted speed limit.

</details>

<details>

<summary>Developer UI</summary>

Display various real-time metrics, such as distance, speed, and desired following distance to your lead vehicle, on screen while driving.

</details>
