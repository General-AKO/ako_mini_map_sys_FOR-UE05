# ako_mini_map_sys
🚗 Racing Minimap Plugin for Unreal Engine 5

A lightweight and performance-friendly racing minimap system for Unreal Engine, designed to display track layouts, player progress, and opponents in real time — without using Scene Capture or heavy rendering systems.

This plugin focuses on simplicity, performance, and flexibility, making it suitable for racing games and projects where performance is critical.

✨ Key Features:

***Zero Scene Capture Usage
-The system does not rely on Scene Capture 2D or camera-based solutions, avoiding unnecessary GPU and CPU overhead.

***Near-Zero Performance Cost
From practical testing, the plugin introduces almost no noticeable performance impact, even when updating elements in real time.

***Spline-Based Track Visualization
Uses a spline actor to define the racing track, allowing accurate and smooth path representation on the minimap.

***Real-Time Player Progress Tracking
Displays the player’s position along the track dynamically and updates smoothly during gameplay.

***Dynamic actor Display
Supports showing multiple actors (such as npc cars) on the minimap with real-time position updates.

***Flexible Rotation Modes  (Fixed player with rotating map ,Map rotates with the player, Fully static map)---Choose the style that fits your game design.

***Customizable Map Appearance

-- Adjustable zoom and center behavior
-- Optional map borders (simple or custom shapes)
-- Adjustable transparency
-- Optional shear/tilt effect for visual style
-- Path Styling Options ( Path color , Thickness , Smoothness and style controls)
--- Runtime Path Update Control Decide whether the path is: 
Updated every frame
Or 
drawn once at the start for maximum performance

--- Beginner-Friendly Setup
Designed to work with just a few clicks, no need to modify internal plugin files.

📦 Installation:

--- Download the plugin from this repository.
---Navigate to your Unreal Engine project folder.
---Create a folder named Plugins if it does not already exist.
---Extract the plugin files into the Plugins folder.
---Open your project.
---The plugin will appear in the Plugins window and is enabled by default.

⚙️ Requirements:

Unreal Engine 5.4 or higher
---Versions below 5.4 are not supported and will not run the plugin.

🧩 Basic Setup Overview:

--- Assign a Spline Actor that represents your racing track.
Assign the Player Actor.
---(Optional) Customize the player indicator shape.
---Add the minimap widget to the viewport 
---Add the required spline info component to the player actor.
---(Optional) Add opponent actors and customize their appearance on the map.
and much more........

🧪 Beta Status & Known Limitations

⚠️ This plugin is currently in Beta.

Known Limitations:

--- Tested mainly on Unreal Engine 5.4 --- Higher engine versions have not been fully tested yet
--- Some features may require further polishing
--- Edge cases may produce non-perfect visual results
--- Your feedback is essential to improve stability and feature completeness.

❌ What This Plugin Does NOT Do

Does not use Scene Capture or camera-based minimap rendering

Does not aim to be a fully realistic satellite-style minimap

Does not automatically generate tracks without a spline

🛠 Debug & Development Tools

The plugin includes optional debug settings to:

Visualize internal data

Understand actor positioning

Assist with troubleshooting during development

These tools are intended for developers and can be disabled for production.

💬 Feedback & Support

A dedicated Discord channel is available to:

Report bugs

Share suggestions

Receive update notifications

Your feedback directly influences future updates and improvements.

📌 Roadmap (Planned)

Expanded testing on newer Unreal Engine versions

Additional customization options

Stability improvements based on user feedback

Documentation and example content improvements

📄 License

This plugin is provided for free for testing and educational purposes.
Please review the license file in this repository for usage limitations.
