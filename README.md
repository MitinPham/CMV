# CMV
CNC
 - - - Welcome to NCViewer! - - -
A Powerful GCode Viewer for Desktop & Mobile.

A product from Toolpath.com

Features:
- Powerful browser based gcode editor
    Built on modern libraries for max performance
- Offline Mode
    No installation! NC Viewer is automatically 
    cached by your browser and will load offline! 
- Mobile Fully Supported
    Works on android, iOS, and tablets devices.
    Just "Add to Homescreen" to install.
- Multi Axis Support
    View, edit, and simulate 3 or 5 Axis files.
- 3D Mouse Compatible
    Supports all 3DCONNEXION input devices.
- Mill, Lathe, and 3D Printers Supported.
    More features are constantly being added.
- Modern, Easy to use interface.
- Highly Optimized
    Easily load and view multi million line files.
- Learn to write G Code
    Easily visualize line by line what your code is doing.
    Eliminates the guessing and helps teach basic gcode.
- Advanced Code and Syntax Highlighting
    Smart code highlighting allows easy identifaction.
- Customizable Editor
    Multiple themes available.
- Resizeable Editor
    Drag the edge of the panel to adjust.
- We respect your privacy
    Processed locally. File are never sent to our servers.
    Offline support is baked in for sensitve installations.
- No account required
- AD FREE: Never see an ad
    Nobody likes ads, so I won't bother you them.

- Keyboard Shortcuts
    Ctrl-F: Find
    Ctrl-H: Find & replace
    Ctrl-Enter: Plot current file
    ESC: Toggle Menu
    Spacebar: Play/Pause

Enjoy Guys!

- - - CHANGELOG - - -

v1.1.X Minor Patches:
Minor UI update. Enhanced mobile UI buttons. 

~~ RELEASE v1.1.0 ~~
Added option to disable 5 Axis codes
Enabled Right Click+Drag on ViewCube
Added Hotkeys
Added options for text editor
Improved caching behavior
Enabled automatic offline support
Improved 3D Mouse Detection
Enabled PWA behaviors
Added additional social links
Optimized site loading speed
Upgrade to HTTPS/2 and HSTS
Removed extra event listeners
Performance improvements
Accessability improvements
Updated UI framework
Updated Code Editor
Updated three.js to r94

// Detailed Changelog //
v1.0.43
Added Memory & CPU to performance graph.
Fixed bug with raycaster failing 
when a new file is opened.
General code optimizations.

v1.0.42
Improved ViewCube behavior and performance.
Right click + Drag to rotate ViewCube.
Optimized tool simulation display.

v1.0.41
Added Hotkeys!
 - Added 'ctrl-enter' hotkey to plot file.
 - Added 'escape' hotkey to toggle menu.
 - Added 'spaceboar' hotkey to play/pause simulation.
Fixed rare crash when changing lines in editor.
Improved comment detection.

v1.0.40
Fixed 3D Mouse not always being detected.
Minor optimization & code organization.

v1.0.36
Fixed user settings not persisting
after updating application.

v1.0.0 (2018.06.02)
Added support for resizing text editor.
Performance meter can now be repositioned.
Supports standard native file extensions.
Updated to three.js r93

/// CHANGELOG - V0.68 (2018.02.18) \\\
Added support for 3D Mice (3D Connexion)
Added UI Toolbar + Tooltips.
Increased size of editor.
Drag and Drop files anywhere on the page now.
Increased DRO accuracy to 4 decimals.
Added Undo / Redo Buttons.
Fixed Link to privacy policy.
General UI improvements.
Updated to three.js r90

/// CHANGELOG - V0.67 (2018.02.08) \\\
Fixed a few settings that weren't saving.
Added basic mouse button customization.
Improved camera snapping on top / bottom views.

/// CHANGELOG - V0.66 \\\
Rewrote entire site.
Added reverse play button.
Fast forward / rewind now change speed.
View cube is now clickable (hype!)
Improved auto scrolling during simulation.
Improved Raycasting performance.
Improved Raycasting accuracy when zoomed in.
Fixed bug with blank lines improperly simulated.
Fixed bug where last line would not be simulated.
Fixed incorrect Z position value in DRO.
Fixed inverted (negative) DRO Rotations.
Fixed G90 / G91 not being detected.
Fixed bug where the last movement was not plotted.
Fixed bug where first point was always X0 Y0 Z0.
Fixed bug where some 5 Axis movements were wrong.
Fixed styling bug in editor when CTRL-F'ing.
Updated to three.js r89

/// CHANGELOG - V0.65 \\\
Updated ViewCube to Rhombicuboctahedron
Menu Buttons are no longer blocked by invisible div
Updated to three.js r87

/// CHANGELOG - Beta V0.64 \\\
Added support for 360° arcs.
Changed view cube to a rhombicuboctahedron.
Added cookies for experimental options.
Improved arc linearization.
Added interaction support for view cube.
Increased size of view cube.

/// CHANGELOG - Beta V0.63 \\\
Improved Zoom - Now zooms to cursor position.
Fixed incorrect offset when using R or CR values.
Improved DRO - Decreased height, increased font size.
Updated to three.js r85

/// CHANGELOG - Beta V0.62 \\\
Added support for G2.4 / G3.4 3D Arcs.
(comments) are now properly filtered out.
Jump to a point by clicking on it.
Double click a point to as camera focus.
Toggle visiblity of toolpath after position.
Ability to view toolpath points.
Added simple viewcube.
New UI buttons and animations.
Added Tooltips.
Added A/B/C Rotation to DRO.
FPS graph can now be hidden.

/// CHANGELOG - Beta V0.60 \\\
Now automatically plots files.
Made grid partially transparent.
Added support for file saving.
Added filename display.
Added support for radius arcs. (ex: G2 X1 Y1 R1)
Automatically detect units from G20/G21.
Fixed G55 to G59 not being detected after G53.
Files are now case insensitive. (G01 == g01)
Minor UI fixes for mobile devices
Fixed DRO not showing current position.
Added Play/Pause/Stop functionality!
Fixed metric scale (was 1/100, now 1/10).
Fixed metric tool simulation.
Added Diameter mode for lathes.
Improved performance when loading large files.

::Known Bugs::
Tool may appear in wrong orientation for lathes.
G154 WCS not detected

::Coming Soon::
Bug reporter + Improved changelog.
