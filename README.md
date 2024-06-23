# prusa-slicer-config

The default Prusa MK3 G-code sets the temperature to the first layer temperature and then does the calibration in 9 different spots, which can leave filament all over the heating bed. This instead increases the temperature to 160, performs the calibration, then increases the temperature to the first layer temperature and does the intro line, which dumps the excess filament into the intro line.

This can be set by switching to Expert Mode in Prusa Slicer and Custom G-code -> Start G-code.
