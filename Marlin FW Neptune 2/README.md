# Marlin-FW-Neptune-2

Open Dir in VSCode with PlatformIO Extension,
Build 
rename Firmware to elegoo.bin under /.pio/build/mks_robin_nano_v1_3_f4/firmware.bin


-------
Bedlevel grid mesh options:
change #define GRID_MAX_POINTS_X (3 points)
change for speedup 
// X and Y axis travel speed (mm/min) between probes
#define XY_PROBE_FEEDRATE (6000)

// Feedrate (mm/min) for the first approach when double-probing (MULTIPLE_PROBING == 2)
#define Z_PROBE_FEEDRATE_FAST (2000)

// Feedrate (mm/min) for the "accurate" probe of each point
#define Z_PROBE_FEEDRATE_SLOW (Z_PROBE_FEEDRATE_FAST / 2)


ATTENTION:
The Printer Bed Level in the MEnu still uses 5x5 grid
G29 to use the new grid
M500 to store