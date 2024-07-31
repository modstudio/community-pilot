# Popular Forks

While openpilot is excellent on its own, several popular community forks enhance its functionality and support hardware like SDSU and Comma Pedal.

[Click this link](https://bderkhan.com/comma-ai-openpilot/sunnypilot-features-and-updates/openpilot-vs-sunnypilot/) to view a comparison between the different forks.

<table><thead><tr><th width="137">Name</th><th width="167">Links</th><th>About</th></tr></thead><tbody><tr><td>FrogPilot</td><td><p><a href="https://github.com/FrogAi/FrogPilot">GitHub</a></p><p><a href="https://discord.gg/frogpilot">Discord / Invite</a></p><p><a href="https://discord.com/channels/1137853399715549214/">Discord / Home</a></p></td><td>A monthly updated and 100% open-sourced fork of openpilot with clean commits dedicated to serve the openpilot community! FrogPilot is shaped by user and developer contributions, emphasizing collaborative, community-driven development to provide a bleeding-edge openpilot experience for everyone!<br><br>Install link: frogpilot.download</td></tr><tr><td>openpilot</td><td><p><a href="https://github.com/commaai/openpilot">GitHub</a></p><p><a href="https://discord.comma.ai/">Discord / Invite</a></p><p><a href="https://discord.com/channels/469524606043160576/">Discord / Home</a></p><p><a href="https://comma.ai/openpilot">Homepage</a></p></td><td>Official comma.ai openpilot repo</td></tr><tr><td>sunnypilot</td><td><p><a href="https://github.com/sunnypilot/sunnypilot">GitHub</a></p><p><a href="https://discord.gg/sunnypilot">Discord / Invite</a></p><p><a href="https://discord.com/channels/880416502577266699">Discord / Home</a><br><a href="https://www.sunnypilot.ai/">Homepage</a></p></td><td>sunnypilot is a fork of comma.ai's openpilot, an open source driver assistance system. sunnypilot offers the user a unique driving experience for over 290 supported car makes and models with modified behaviors of driving assist engagements. sunnypilot complies with comma.ai's safety rules as accurately as possible. <br><br>Install link: <a href="https://release-c3.sunnypilot.ai">https://release-c3.sunnypilot.ai</a></td></tr><tr><td>DragonPilot</td><td><a href="https://github.com/dragonpilot-community/dragonpilot">GitHub</a><br><a href="https://github.com/dragonpilot-community">English Overview</a></td><td><p>This fork is focused on Toyotas and Lexus with secondary attention given to Honda and Hyundai. All of the upstream vehicle are supported.<br><br>Install links:</p><p>Comma 3: <a href="https://smiskol.com/fork/dp">https://smiskol.com/fork/dp</a><br>Comma 2: <a href="https://smiskol.com/fork/dp/release2">https://smiskol.com/fork/dp/release2</a></p></td></tr></tbody></table>

## Community Features

Below are highlights of the community-supported features. Community forks include all the features of stock openpilot but add additional functionalities and the ability to fine-tune the driving experience and user interface. FrogPilot, sunnypilot and DragonPilot all support most of these in one way or another. Features that are exclusive to one of the forks have been indicated in the chart below.&#x20;

<table><thead><tr><th width="335">Feature</th><th>Summary</th></tr></thead><tbody><tr><td><strong>Hardware support</strong></td><td></td></tr><tr><td>⭐️ Support for Comma Pedal and SDSU</td><td>Support for community created hardware enabling stop and go and full support for older vehicles </td></tr><tr><td><strong>General</strong></td><td></td></tr><tr><td>⭐️ Separation of Lateral and Longitudinal</td><td>Users can choose to let the system handle steering while managing speed themselves or vice versa.</td></tr><tr><td>⭐️ Vehicle Specific</td><td>Features related to specific vehicles such as custom tunings, software and hardware support.</td></tr><tr><td><strong>Lateral</strong> </td><td></td></tr><tr><td>⭐️ Automatic Lane Changes</td><td>Supports nudgeless lane changes, allowing the vehicle to change lanes automatically without requiring a nudge from the steering wheel.</td></tr><tr><td>⭐️ Always on Lateral</td><td>Breaking does not cancel lateral control enabling lateral to remain engaged in most driving conditions.</td></tr><tr><td>⭐️ Lateral Tuning</td><td>Extensive settings to fine-tune the vehicle’s lateral control. Users can adjust the steering ratio, lane departure sensitivity, and other parameters to suit their driving preferences</td></tr><tr><td><strong>Longitudinal</strong></td><td></td></tr><tr><td>⭐️ Turn Speed Control</td><td>Vision and map based turn speed controller to slow the vehicle while taking a curve and then resume normal speed after the curve.</td></tr><tr><td>⭐️ Speed Limit Control</td><td>Set the speed based on map and road sign data</td></tr><tr><td>⭐️ Following Distance Profiles</td><td>Offers different acceleration modes (e.g., Eco, Normal, Sport)</td></tr><tr><td>⭐️ Traffic Mode (FP)</td><td>Tailored towards driving in traffic </td></tr><tr><td>⭐️ Longitudinal Tuning</td><td>Customizable settings for managing the vehicle's acceleration and braking.</td></tr><tr><td><strong>Navigation</strong></td><td></td></tr><tr><td>⭐️ Offline maps</td><td>Offline maps allow the navigation and map based features to function without a internet connection or comma prime subscription.</td></tr><tr><td><strong>Driving Model</strong></td><td></td></tr><tr><td>⭐️ Driving Model Selector</td><td>Users can choose from different driving models to match their driving preferences and conditions.</td></tr><tr><td>⭐️ Dynamic Experimental Mode</td><td>Enable experimental mode under specific criteria and conditions</td></tr><tr><td><strong>UI</strong></td><td></td></tr><tr><td>⭐️ Driving UI Customizations</td><td>Users can adjust visual elements such as lane colors, path edges, and display metrics to suit their preferences.</td></tr><tr><td>⭐️ Alerts and Notifications</td><td>Customize which alerts are displayed and additional alerts.</td></tr><tr><td>⭐️ Developer UI</td><td>Provides real-time metrics and insights for developers including detailed information about the vehicle’s state, sensor data, and system health.</td></tr><tr><td>⭐️ Custom Themes and Sounds (FP)</td><td>Offers various custom themes and sound effects for a personalized driving experience.</td></tr><tr><td>⭐️ Multi-Language Interface (DP)</td><td>Fully supports multiple languages including English, Simplified/Traditional Chinese, Japanese, Korean, French, Portuguese, and German.</td></tr><tr><td><strong>Device</strong></td><td></td></tr><tr><td>⭐️ Device Management</td><td>Comprehensive device management settings, allowing users to control power management, software updates, data logging, and more.</td></tr><tr><td>⭐️ Fleet Manager</td><td>Device management and data access from the browser.</td></tr></tbody></table>

### Features explained

<details>

<summary>Support for Comma Pedal and SDSU</summary>

**Overview**

This feature provides support for additional hardware such as the Comma Pedal and Smart DSU (Driver Support Unit), enhancing the system's capabilities for adaptive driving and providing more flexibility in controlling vehicle dynamics, particularly for Toyota vehicles.

**Key Features**

1. **Comma Pedal Support**:
   * **Throttle Control**: Allows for manual or automated throttle adjustments, providing smoother acceleration and deceleration. This feature is particularly useful for older vehicles that may not have built-in adaptive cruise control (ACC).
   * **Compatibility**: Supports a wide range of car models by integrating the Comma Pedal for enhanced driving control.
2. **Smart DSU (Driver Support Unit) Support**:
   * **ACC Control Integration**: The Smart DSU filters out specific messages from the stock DSU, allowing openpilot to take over longitudinal control (acceleration and braking) while retaining automatic emergency braking (AEB). This integration enables more reliable and responsive ACC behavior in Toyota vehicles.
   * **Maintaining AEB**: By using the Smart DSU, the AEB functionality remains active even when openpilot manages the ACC, ensuring enhanced safety features are not compromised.
   * **Improved ACC Performance**: Enables openpilot to manage ACC, providing smoother and safer driving experiences, especially in stop-and-go traffic situations.
   * **Compatibility with Toyota Vehicles**: Designed to work seamlessly with various Toyota models equipped with DSUs, ensuring optimal integration and performance.

**Benefits**

* **Improved Vehicle Control**: Utilizing the Comma Pedal provides better control over acceleration and deceleration, enhancing the driving experience and safety.
* **Enhanced ACC Performance**: With Smart DSU support, users benefit from improved ACC functionality, providing more precise and reliable speed and distance management.
* **Broad Compatibility**: Both forks support a wide range of vehicle models, making these enhancements accessible to a larger user base.

These features ensure that users can take full advantage of their vehicle's capabilities and the openpilot system, providing smoother control, better ACC performance, and enhanced overall driving experience.

</details>

<details>

<summary>Separation of Lateral and Longitudinal</summary>

**Overview**

This feature provides support the separation of lateral (steering) and longitudinal (acceleration and braking) control, enhancing customization and safety in vehicle management.

**Key Features**

1. **Independent Control Modes**:
   * **Lateral Control Only**: Manages steering while the vehicle's stock ACC handles acceleration and braking. This mode is useful for vehicles where openpilot does not yet support full longitudinal control.
   * **Longitudinal Control Only**: Manages acceleration and braking while the vehicle's native systems handle steering. This can be particularly useful in cases where the vehicle's native systems are more reliable for certain driving conditions.
2. **Always-On Lateral Control**:
   * **Continuous Steering**: Enables lateral control to remain active even when the driver is manually controlling acceleration and braking. This feature ensures consistent lane-keeping and steering assistance.
3. **User-Defined Control**:
   * **Customization**: Users can enable or disable either lateral or longitudinal control based on preferences and driving conditions. This flexibility allows for a more tailored driving experience.
4. **Adaptive Configurations**:
   * **Safety and Comfort**: Configurations can be adjusted to prioritize either safety or comfort, depending on the vehicle’s capabilities and user preferences.

**Benefits**

* **Improved Safety**: Precise management of each control type reduces risks and enhances vehicle safety.
* **Increased Flexibility**: Allows users to customize their driving experience by selecting the appropriate control mode.
* **Broader Compatibility**: Supports a wider range of vehicles, including those not fully integrated with both control types.

These features ensure users can leverage the full capabilities of the openpilot system, providing enhanced safety, flexibility, and compatibility.

</details>

<details>

<summary>Lateral Adjustments</summary>

**Overview**

Lateral Adjustments in openpilot refer to the control and customization of the vehicle's steering behavior. These adjustments are crucial for ensuring the vehicle stays centered in its lane and handles curves and turns smoothly. FrogPilot, SunnyPilot, and DragonPilot all offer extensive options for fine-tuning lateral control.

**Key Features**

1. **Always-On Lateral Control**:
   * **Continuous Steering**: Enables the system to maintain lateral control even when the driver is manually controlling acceleration and braking. This ensures consistent lane-keeping and steering assistance. (FP, SP, DP)
   * For more details, refer to the "Separation of Lateral and Longitudinal Control" section.
2. **Nudgeless Lane Changes**:
   * **Lane Detection**: Allows for lane changes without the need for a steering nudge, relying instead on lane detection to ensure safe transitions. This feature enhances the ease and safety of lane changes. (FP, DP)
3. **Dynamic Lane Profiles**:
   * **Auto Lane Switching**: Automatically switches between laneful and laneless modes based on lane recognition confidence. This provides optimal lane-keeping performance in varying road conditions. (SP, DP)
4. **Custom Steering Ratios**:
   * **Fine-Tuning Steering Response**: Allows users to adjust the vehicle's steering ratio to achieve the desired responsiveness and handling characteristics. This is particularly useful for optimizing performance in different driving scenarios. (FP, DP)
5. **Pause Lateral on Brake**:
   * **Conditional Lateral Control**: Temporarily disables lateral control when the brake pedal is pressed, resuming it upon release. This feature ensures safety and driver control during braking. (FP, DP)
   * For more details, refer to the "Separation of Lateral and Longitudinal Control" section.
6. **Lateral Metrics Visualization**:
   * **Real-Time Metrics**: Displays metrics such as steering angle, torque, and lane position on the driving UI. This helps users monitor and understand the vehicle’s lateral control performance. (FP, SP, DP)
   * For more details, refer to the "Developer UI" section.
7. **Precise Turn Handling**:
   * **Turn Desires**: Uses advanced algorithms to manage the vehicle’s speed and steering angle for precise handling of turns, ensuring smooth and accurate navigation through curves. (FP, DP)
8. **Customizable Path Widths and Colors**:
   * **Visual Customization**: Allows users to adjust the width and color of lane lines and path edges on the driving UI, enhancing visibility and personal preference. (FP, DP)
   * For more details, refer to the "Driving UI Customizations" section.

**Benefits**

* **Enhanced Safety**: Precise control over the vehicle’s steering behavior reduces the risk of lane departure and improves overall driving safety. (FP, SP, DP)
* **Improved Comfort**: Smooth and accurate steering adjustments provide a more comfortable driving experience, especially on winding roads and during lane changes. (FP, SP, DP)
* **Customization**: Extensive customization options allow users to tailor the vehicle’s lateral control to their specific driving style and preferences. (FP, SP, DP)

These features ensure that users benefit from a robust and flexible lateral control system, providing enhanced safety, comfort, and customization in their driving experience.

</details>

<details>

<summary>Automatic Lane Changes</summary>

**Overview**

Support for automatic lane changes, enhancing the driving experience by enabling smoother and safer lane transitions.

**Key Features**

1. **Automatic Lane Change Activation**:
   * **Turn Signal**: Initiate lane changes by engaging the turn signal. The system checks for obstacles and initiates the lane change when safe.
   * **Steering Nudge**: Some implementations may require a slight nudge on the steering wheel to confirm the lane change. This feature ensures that the driver is aware and consenting to the maneuver.
2. **Obstacle Prevention**:
   * **Blind Spot Monitoring (BSM)**: Integrates with the vehicle's blind spot monitoring system to prevent lane changes when obstacles are detected in the adjacent lane, enhancing safety.
3. **Customizable Timer**:
   * **Lane Change Delay**: Users can set a timer to delay the automatic lane change operation once the turn signal is activated. This allows for more control and customization of the lane change process.&#x20;

**Benefits**

* **Enhanced Safety**: The integration of blind spot monitoring ensures that lane changes are only initiated when it is safe to do so, reducing the risk of collisions.&#x20;
* **Improved Convenience**: Automatic lane changes make highway driving more comfortable by reducing the need for manual steering inputs, allowing the driver to focus more on monitoring traffic conditions.
* **Customizable Experience**: The ability to set a delay timer and use steering nudges provides users with options to tailor the lane change behavior to their preferences.

These features ensure a safer and more comfortable driving experience, leveraging advanced automation to manage lane changes effectively.

</details>

<details>

<summary>Longitudinal Adjustments</summary>

**Overview**

Longitudinal Adjustments refer to the enhancements and additional features beyond the stock openpilot's capabilities for managing acceleration and braking. These adjustments are crucial for maintaining safe following distances, optimizing speed control, and ensuring smooth driving dynamics.

**Key Features**

1. **Following Distance Profiles**:
   * **Customizable Following Distance**: Allows users to set different following distance profiles (e.g., long, normal, short) to adjust the gap between their vehicle and the lead vehicle.
   * **Dynamic Adjustment**: Automatically adjusts the following distance based on traffic conditions and driving speed.
2. **Acceleration Profiles**:
   * **Mode Selection**: Offers different acceleration modes (e.g., Eco, Normal, Sport) to match the driver's preference for fuel efficiency or performance.
   * **Smooth Transition**: Ensures smooth acceleration and deceleration transitions to improve passenger comfort and vehicle stability.
3. **Map-based Longitudinal Control**:
   * **Speed Limit Adjustments**: Utilizes map data to adjust the vehicle's speed based on the detected speed limits of the road.
   * **Curvature Management**: Slows down the vehicle when approaching curves or turns based on map data to ensure safe handling.
4. **User-Defined Speed Limits**:
   * **Custom Speed Settings**: Allows users to set custom speed limits for different driving conditions, ensuring that the vehicle adheres to user-defined speed preferences.
5. **Manual Override**:
   * **Gas Pedal Access**: Enables the driver to manually control acceleration by pressing the gas pedal while the system is engaged, providing more control over the vehicle's speed when necessary.
   * **Brake Pedal Override**: Temporarily disables the system’s control when the brake pedal is pressed, resuming control upon release.
6. **Alerts and Notifications**:
   * **Lead Car Alerts**: Notifies the driver when the lead car starts moving after a stop, helping to reduce reaction time and improve traffic flow.
   * **Turn Speed Alerts**: Warns the driver if the system detects a speed that exceeds safe limits for upcoming turns.

**Benefits**

* **Enhanced Safety**: Maintains safe following distances and adapts to traffic conditions, reducing the risk of collisions.
* **Improved Comfort**: Smooth acceleration and deceleration provide a more comfortable ride for passengers.
* **Fuel Efficiency**: Customizable acceleration profiles can help optimize fuel consumption based on driving preferences.
* **Driver Control**: Manual override options allow the driver to take control when needed, enhancing flexibility and safety.

These features ensure that users benefit from a robust and flexible longitudinal control system, providing enhanced safety, comfort, and customization in their driving experience.

</details>

<details>

<summary>Turn Speed Control</summary>

**Overview**

Turn Speed Control enhances safety and comfort by automatically adjusting the vehicle's speed based on road conditions, particularly when approaching curves or turns.

**Key Features**

1. **Vision-based Turn Speed Control**:
   * **Vision Path Predictions**: Utilizes camera data to predict the appropriate speed for navigating through turns. This ensures that the vehicle slows down for curves based on real-time visual information.
2. **Map-Data-based Turn Speed Control:**
   * **Map Curvature Data**: Uses pre-downloaded map data to determine the curvature of upcoming roads and adjusts the vehicle's speed accordingly. This method provides additional context to ensure safe speed limits are adhered to during turns. (FP, SP)
3. **Integration with Longitudinal Control**:
   * **Smooth Speed Adjustments**: Both vision and map-based turn speed control methods are integrated with the vehicle’s longitudinal control system, allowing for seamless speed adjustments without driver intervention. (FP, SP)

**Benefits**

* **Enhanced Safety**: Automatically adjusting speed based on road curvature reduces the risk of accidents caused by excessive speed in turns.
* **Improved Comfort**: Provides a smoother driving experience by ensuring consistent and appropriate speed adjustments during turns.
* **Increased Accuracy**: The combination of vision-based and map-based data ensures accurate and reliable speed control, adapting to both real-time conditions and pre-known road information.

These features enhance the overall driving experience by combining real-time vision data with pre-existing map information to provide safe and efficient speed adjustments when navigating turns.

</details>

<details>

<summary>Speed Limit Control</summary>

**Overview**

Speed Limit Control feature automatically adjusts the vehicle's speed to comply with speed limits detected through various methods. This enhances driving safety and helps drivers adhere to legal speed limits.

**Key Features**

1. **Vision-based Speed Limit Control**:
   * **Speed Limit Signs Detection**: Utilizes the vehicle’s camera system to detect and read speed limit signs. This information is then used to adjust the vehicle’s speed accordingly.
2. **Map-based Speed Limit Control**:
   * **OpenStreetMap Data**: Uses pre-downloaded map data from OpenStreetMap to determine speed limits on various road segments. This is particularly useful in areas where speed limit signs may be sparse or absent.
3. **User-Defined Speed Offset**:
   * **Speed Limit Offset**: Allows drivers to set a speed offset (e.g., 5 mph over the speed limit) to accommodate personal driving preferences while still adhering to safety regulations.
4. **Hybrid Approach**:
   * **Combined Vision and Map Data**: Integrates both vision-based and map-based data to provide the most accurate and reliable speed limit control. This ensures that the system can adapt to real-time changes in speed limits as well as predefined speed limits from map data.

**Benefits**

* **Enhanced Safety**: Automatically adjusting speed to comply with speed limits reduces the risk of speeding violations and enhances overall road safety.
* **Driver Convenience**: Reduces the cognitive load on the driver by automating speed adjustments, allowing them to focus more on the road and less on speed monitoring.
* **Accurate Speed Compliance**: The combination of vision and map data ensures that the vehicle adheres to the most accurate and current speed limits, even in the absence of visible signs.

These features ensure that users benefit from a robust and reliable Speed Limit Control system, providing enhanced safety, convenience, and compliance with traffic laws.

</details>

<details>

<summary>Dynamic Experimental Mode</summary>

**Overview**

Dynamic Experimental Mode in openpilot forks like FrogPilot and SunnyPilot enables the system to intelligently switch between experimental and default driving modes based on specific driving conditions. This feature optimizes the driving experience by applying the most suitable mode for different scenarios.

**Key Features**

1. **Automatic Mode Switching**:
   * **Conditional Activation**: Automatically activates Experimental Mode under several conditions such as approaching intersections, turns, slower vehicles, or specific road features like curves and stop signs.
   * **Optimal Driving Experience**: Maintains Default Mode for highway driving to ensure smooth and efficient performance, while Experimental Mode handles more complex urban driving tasks.
2. **Enhanced Urban Driving**:
   * **Stop Sign and Traffic Light Handling**: Slows down and stops at stop signs and traffic lights, ensuring safer navigation in city environments.
   * **Tight Turn Management**: Uses Experimental Mode to handle tight turns and sharp curves more effectively.
3. **Dynamic Adjustments**:
   * **Adaptive Speed Control**: Adjusts the vehicle's speed dynamically based on detected road conditions, such as reducing speed for tight turns or intersections.
   * **Smooth Transition**: Seamlessly switches between Experimental and Default modes without driver intervention, ensuring a fluid driving experience.

**Benefits**

* **Enhanced Safety**: Improves safety by applying the most suitable driving mode for different scenarios, particularly in complex urban environments.
* **Improved Comfort**: Provides a smoother driving experience by dynamically adjusting speed and handling based on real-time conditions.
* **Increased Efficiency**: Optimizes performance by using Default Mode for highway driving and Experimental Mode for city driving, ensuring the best of both worlds.

These features ensure a safer, more comfortable, and efficient driving experience by intelligently adapting to various driving conditions.

</details>

<details>

<summary>Offline maps</summary>

**Overview**

Both forks of openpilot include comprehensive offline maps features designed to enhance the navigation and driving experience without requiring continuous internet connectivity. Utilizing OpenStreetMap (OSM) data, these features allow users to download map data locally and leverage various functionalities based on the offline maps.

**Key Features**

1. **Offline Navigation**: Users can download map data from OpenStreetMap, enabling navigation without an internet connection. (FP, SP)
2. **Speed Limit Control**: The downloaded map data allows the system to adjust the vehicle's speed according to the speed limits embedded within the OSM data. (FP, SP)
3. **Road Name Display**: Road names are displayed directly from the offline maps, providing users with essential information during their drive. (FP)
4. **Regular Updates**: The systems receive frequent updates to ensure that the offline maps feature remains current and reliable, benefiting from community contributions and continuous improvement. (FP)
5. **Enhanced Driving Assist**: Integrates vision-based turn speed control and speed limit adjustments based on offline map data to enhance driving safety and convenience. (SP)
6. **Automated Speed Adjustments**: Utilizes offline data to automatically adjust the vehicle's speed, ensuring compliance with local speed limits and improving overall driving safety. (FP, SP)

These features ensure that users have access to reliable and efficient navigation, significantly enhancing the autonomous driving experience even in offline scenarios.

</details>

<details>

<summary>Driving UI Customizations</summary>



#### Driving UI Customizations

**Overview**

Both FrogPilot and SunnyPilot forks of openpilot offer extensive driving UI customizations, allowing users to tailor the display to suit their preferences and needs. These customizations enhance the driving experience by providing relevant information in a user-friendly manner.

**Key Features**

1. **Visual Enhancements**:
   * **Lane Path Colors**: Customize lane path colors to display real-time lane models and engagement status, with options to indicate different modes like laneful, laneless, and experimental.
   * **Compass and FPS Counter**: Add a compass that rotates according to the driving direction and an FPS counter to monitor system performance. (FP)
   * **Custom Map Styles**: Integrate 3D buildings and full-screen maps for a more expansive and detailed navigation view.
2. **Dynamic Information Display**:
   * **Vehicle Metrics**: Display various metrics such as distance, speed, and following distance to the lead vehicle. These can be toggled to show CPU and GPU monitoring or RAM and storage usage.
   * **Blind Spot Monitoring**: Visualize blind spot warnings and other critical alerts directly on the driving screen.
3. **Interactive Elements**:
   * **Tap-to-Toggle**: Enable interactive elements where users can tap on specific UI components to toggle between different metrics or display modes, such as switching between CPU and GPU usage or RAM and storage monitoring. (FP)
   * **Customizable Paths**: Adjust the width and color of lane lines, path edges, and road UI elements based on specific driving statuses like navigation, lateral control, or experimental mode. (FP)
4. **Alerts and Notifications**:
   * **Event Markers**: Mark significant events such as lane changes, obstacle detection, and speed adjustments. Custom alerts can be set for various driving conditions and statuses.
   * **Turn Signal and Brake Indicators**: Show when turn signals are active or when the vehicle is braking, providing clear visual cues for the driver.
5. **Personalization Options**:
   * **Themes and Sounds**: Customize the UI with various themes (e.g., Tesla theme, holiday themes) and sound effects. Users can request additional themes through community channels. (FP)
   * **Steering Wheel Icons**: Customize steering wheel icons to match user preferences or specific themes. (FP)

**Benefits**

* **Enhanced User Experience**: Tailoring the UI to individual preferences enhances the overall driving experience, making it more intuitive and enjoyable.
* **Improved Safety**: Customizable visual alerts and indicators help drivers stay aware of their vehicle’s status and surroundings, contributing to safer driving.
* **Efficient Monitoring**: Real-time metrics and dynamic information displays allow for better monitoring and quick adjustments, aiding in smoother and more responsive driving.
* **Personal Touch**: The ability to personalize the driving UI with themes, sounds, and interactive elements adds a unique and engaging aspect to the openpilot experience. (FP, SP)

These features ensure a more personalized, informative, and enjoyable driving experience by allowing extensive customization of the driving UI.

</details>

<details>

<summary>Developer UI</summary>

**Overview**

The Developer UI in openpilot provides real-time metrics and detailed insights into the vehicle’s autonomous driving system. It is designed to assist developers in monitoring, debugging, and enhancing the performance of the openpilot software.

**Key Features**

1. **Real-time Metrics Display**:
   * **Vehicle State**: Shows current speed, steering angle, throttle position, and brake status.
   * **System Performance**: Provides data on CPU usage, memory consumption, and system temperature, ensuring that developers can monitor the health and performance of the device running openpilot.
2. **Driving Model Metrics**:
   * **Lane Detection**: Visualizes the lane lines detected by the system, including confidence levels and lane curvature.
   * **Path Planning**: Displays the planned path for the vehicle, helping developers understand how the driving model is making decisions.
3. **Sensor Data Visualization**:
   * **Camera Feeds**: Live video feed from the vehicle’s cameras, showing what the vehicle "sees" in real-time.
   * **Sensor Readings**: Data from other sensors, such as radar and ultrasonic sensors, providing a comprehensive view of the vehicle’s environment.
4. **Event Logging and Alerts**:
   * **Event Markers**: Marks significant events such as lane changes, obstacle detection, and speed adjustments, allowing developers to review and analyze these occurrences.
   * **Error Notifications**: Alerts developers to any errors or anomalies detected by the system, facilitating quick identification and troubleshooting of issues.
5. **Customizable UI Elements**:
   * **User Preferences**: Developers can customize the UI to display specific metrics and data points that are most relevant to their work.
   * **Debugging Tools**: Offers tools for in-depth analysis and debugging, such as log file access and system diagnostics.

**Benefits**

* **Enhanced Monitoring**: Provides detailed, real-time insights into the autonomous driving system, enabling developers to monitor and optimize performance effectively.
* **Improved Debugging**: Facilitates the identification and resolution of issues, ensuring that the system operates smoothly and reliably.
* **Comprehensive Data Access**: Offers a holistic view of the vehicle’s state and environment, aiding in the development and refinement of driving models and algorithms.
* **Customization**: Allows developers to tailor the UI to their specific needs, improving workflow efficiency and effectiveness.

These features make the Developer UI an essential tool for developers working on openpilot, providing the necessary insights and tools to enhance the performance and reliability of the autonomous driving system.

</details>

<details>

<summary>Device Management</summary>

**Overview**

Both FrogPilot and SunnyPilot forks of openpilot provide comprehensive device management features, allowing users to maintain, customize, and optimize the performance of their openpilot hardware. These features enhance the usability and reliability of the device, ensuring it operates efficiently under various conditions.

**Key Features**

1. **Screen and Display Management**:
   * **Adjustable Screen Brightness**: Users can manually set screen brightness levels for both onroad and offroad states to improve visibility and reduce glare. (FP, SP)
   * **Screen Timeout**: Configurable screen timeout settings to automatically dim or turn off the display after a specified period of inactivity, preserving screen life and reducing power consumption. (FP, SP)
2. **Power Management**:
   * **Battery Level Thresholds**: Set thresholds for the car battery’s voltage to automatically shut down the device if the battery falls below a certain level, preventing battery drain. (FP, SP)
   * **Automatic Shutdown Timer**: Device can be set to shut down automatically after a specified duration when the car is turned off, ensuring the device does not remain on unnecessarily. (FP, SP)
3. **Data Management**:
   * **Data Logging and Upload Control**: Options to disable logging and uploading of data when onroad, helping to manage data usage and protect privacy.
   * **Backup and Restore**: Backup and restore device settings, configurations, and previous versions of the software, ensuring that users can quickly recover from any issues or revert to preferred settings.&#x20;
4. **Firmware and Software Updates**:
   * **Panda Firmware Updates**: Users can flash the Panda firmware directly from the device management menu, keeping the hardware up to date with the latest improvements and fixes.
   * **Software Maintenance**: Manage software updates, including automatic updates and the ability to download and install specific versions as needed.
5. **Operational Modes**:
   * **Offline Mode**: Enables the device to operate offline indefinitely, ensuring functionality even without an active internet connection.
   * **Standby Mode**: Configurable standby mode that wakes the screen or activates certain functions between engagement states or when important alerts are triggered.
6. **Customization and Advanced Settings**:
   * **Custom Toggles**: Advanced settings and toggles for fine-tuning various aspects of the device’s operation, such as enabling experimental features or adjusting performance parameters.
   * **Theming and Personalization**: Options to customize the device’s interface with themes and personalized settings to enhance the user experience. (FP)

**Benefits**

* **Enhanced Usability**: Provides users with extensive control over their device’s operation, allowing for a more tailored and user-friendly experience.
* **Improved Power Efficiency**: Power management features ensure that the device does not drain the car battery, preserving battery life and preventing potential issues.
* **Data Control and Privacy**: Allows users to manage data logging and uploads, protecting their privacy and managing data usage effectively.
* **Reliable Performance**: Regular updates and backup features ensure that the device remains up-to-date and can recover quickly from any issues.

These features ensure that users can maintain their openpilot device effectively, providing a reliable, customizable, and user-friendly experience.

</details>

<details>

<summary>Fleet Manager</summary>

**Overview**

The Fleet Manager feature is designed to provide comprehensive management tools for monitoring and maintaining multiple vehicles equipped with openpilot systems. This feature is especially useful for fleet operators and developers who need to oversee and optimize the performance of several vehicles.

**Key Features**

1. **Dashcam Footage and Screen Recordings**:
   * **Real-time and Archived Access**: View and download dashcam footage and screen recordings from each vehicle. This is useful for reviewing incidents, training purposes, and ensuring compliance with driving policies.
2. **Error Logs and Diagnostics**:
   * **Detailed Logs**: Access and review error logs from each vehicle to identify and troubleshoot issues quickly. This helps maintain the fleet’s reliability and performance.
   * **System Health Monitoring**: Continuous monitoring of system health metrics like CPU usage, memory consumption, and sensor status to preemptively address potential issues.
3. **Location Tracking and Telemetry**:
   * **GPS Tracking**: Real-time tracking of each vehicle’s location, speed, and route history. This is crucial for logistics, route optimization, and ensuring that vehicles are being used efficiently.
   * **Telemetry Data**: Comprehensive telemetry data including acceleration, braking, and steering inputs to analyze driving behavior and vehicle performance.
4. **Remote Configuration and Updates**:
   * **Software Updates**: Push software updates and configurations to multiple vehicles simultaneously, ensuring that all systems are up-to-date with the latest features and security patches.
   * **Remote Settings Adjustments**: Adjust settings and configurations remotely to optimize performance or comply with regulatory changes without needing to access each vehicle physically.
5. **Fleet Analytics and Reporting**:
   * **Performance Reports**: Generate detailed reports on vehicle performance, usage patterns, and maintenance needs. These reports help in making informed decisions about fleet management and optimization.
   * **Driver Behavior Analysis**: Analyze driver behavior using data on speed, acceleration, and braking to provide feedback and improve driving safety and efficiency.

**Benefits**

* **Enhanced Monitoring**: Provides real-time visibility into the status and performance of each vehicle in the fleet, allowing for proactive maintenance and issue resolution.
* **Improved Efficiency**: Enables remote updates and configuration changes, reducing the downtime and logistical challenges associated with managing a large fleet.
* **Increased Safety**: Continuous monitoring and detailed analytics help identify risky driving behaviors and vehicle issues, improving overall fleet safety.
* **Cost Savings**: By optimizing routes, maintenance schedules, and driving behavior, fleet managers can reduce operational costs and extend the lifespan of their vehicles.

These features ensure that fleet operators can manage their vehicles effectively, providing enhanced safety, efficiency, and performance across the entire fleet.

</details>
