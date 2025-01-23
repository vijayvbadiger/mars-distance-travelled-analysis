Project Documentation: Mars Surface Observation Analysis

Objective

To analyze the visibility of specific surface features on Mars, such as Olympus Mons, when observed from Earth over a specified time range using NASA's WebGeoCalc tool and SPICE kernels.

Overview

This project leverages the Sub-Observer Point Finder tool in WebGeoCalc to calculate the observable surface points on Mars from Earth. By using SPICE kernels and accurate ephemeris data, the project identifies the latitudes and longitudes of the visible Martian surface features during a specified observation period.

Inputs Used

1. Kernels Selected

Ground Stations Kernels

Solar System Kernels

ExoMars 2016 TGO Kernel Set

Mars 2020 Kernel Set

Mars Reconnaissance Orbiter Kernel Set

SPICE Class - ExoMars 2016 Geometric Event Finding Lesson Kernels

2. Target and Observer

Target: Mars

Observer: Earth

3. Reference Frame

Reference Frame: IAU_MARS (Mars body-fixed reference frame)

4. Aberration Correction

None: No light-time corrections were applied.

5. Time Range

Start Time: 2023-01-21 00:00:00 UTC

Stop Time: 2023-01-22 00:00:00 UTC

Step Size: 1 hour

6. Sub-Point Type

Intercept: Calculated where the observer’s line of sight intersects Mars’s surface.

Results,

<img width="1437" alt="Screenshot 2025-01-23 at 4 25 31 PM" src="https://github.com/user-attachments/assets/45cdbc8f-ebcf-4198-bb1c-112b03eabf4b" />


