# decent-metric
Metric skin for Decent Espresso

Standing on the shoulders of giants: thanks to John (Insight), Damian (DSV), Sheldon (SWDark)

TODO
- Sleep button
- Test support for Bluetooth scale
- Test functionality of GHC somehow
- Test translations
- Test Fahrenheit temperatures
- bug: Head temperature reading in status bar reads 100+ when DE1 is starting

IDEAS
- Option to choose your grinder to set the range of values for grid size (and also save which grinder to the results file)
- Smart up/down arrows which change increment for larger numbers (eg yield delta is 1.0/0.1 when under <=20, 5.0/0.5 when 21..99, 10/1 for >=100)
- Add button to post-shot page to show chart full screen

Release notes

v2.0
 - Removed the main menu
 - Added a bar at the bottom for steam, water, flush and settings
 - Made the flush and steam buttons start immediately
 - Visual updates

v0.6
 - Implemented Pour Over button on Home menu
 - Added space for writing the bean details
 - Implemented changing a profile within skin
 - All Metric settings are now effective

v0.5
 - New espresso menu screen with parameters for dose, grind, temp, ratio and yield
 - Reduced status bar to only show in corners
 - Head temperature meter reads the correct temperature
 - Water empty warning displayed at slightly higher level (sometimes did not display yet DE1 refused to start due to low water)
 - Water and temperature meters now read zero when DE1 disconnected
 - Automatically jump back to previous menu after steam or flush functions
 - Added labels to action buttons

v0.4 
- Added a timer to the Espresso page
- Added post-shot page to show summary of shot, chart and buttons for steam and flush
- Swapped water and temp meters on status bar so that they are closer to corresponding meters in Espresso window
- When the water level runs out, it will stay on the most recent page
- Detects when DE1 is not connected, displays a warning message and disables the start buttons
- Removed the "menu" page

v0.3 15/01/2020
- Added message to status bar during heating
- Added message to status bar when tank is empty, and removed "tankempty" page so you can stay in the menus
- Disabled espresso, steam, water and flush buttons when machine status is not ready
- Gauges no longer show target if value is zero.
- Weight gauge now shows scale weight if a scale connected, or falls back to volume of water dispensed.

v0.2 10/01/2020
- Separated main menu buttons for easier targetting
- Increased size of action buttons and re-laid out settings menu
- Return to main menu when exiting sleep
- Display target Espresso temperature, pressure and flow using settings from DE1.
- Added simple smoothing algorithm to meters (average of 2 values)

v0.1 06/01/2020
- first Alpha released to Decent Diaspora
