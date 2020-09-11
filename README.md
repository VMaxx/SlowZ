# SlowZ
Ruthlessly stole the code from z offset plugin from Aldo Hoeben/fieldOfView to make this plugin

This plugin adds a setting named "Z Percentage" to the speed settings in the Custom print setup of Cura. It will slow the printer speed as the layers increase.

The SlowZ setting can be found in the Custom print setup by using the Search field on top of the settings. If you want to make the setting permanently visible in the sidebar, right click and select "Keep this setting visible".

This plugin assumes M220 will work with your printer.

*WARNING*
This will override any manual speed adjustments you make, so if you decide during the print to adjust it.  The gcode is set for each layer to set the speed so it will go back to the percentage it calculates on the next layer.
