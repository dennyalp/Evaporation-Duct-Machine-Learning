Evaporation Duct Height
================

**Table of Contents**

-   [Background](#background)
-   [Exploration](#exploration)


Background
-----

We're given a couple of weeks worth of environmental observations at various
locations off the coast of Duck, North Carolina. Observations are made hourly,
and consist of the following features.

| Column Label | Meaning |
|-----|-----|
|    yyyy | year|
|    mm | month|
|dd | date|
|    HH | Hour|
|    LON | Longitude|
|    LAT | Latitude|
|    Pres(hpa) | Atmsopehric pressure|
|    T(°C) | Temperature at 5 m|
|    SST(°C) | Sea surface temperature|
|    RH(%) | Relative humidity at 5 m|
|   u(m/s) | Zonal component of wind|
|    v(m/s) |  Meridional component of the wind|
|     WS(m/s) | wind speed (estimated from u and v)|
|    WD(°)  | Wind direction (North = 0°)|
|     q(g/kg) | specific humidity|
|     dq(g/kg) | specific humidty at surface minus specific humidty at 5 m|
|     ASTD(°C) | air temperature at 5 m minus sea surface temperature|
|    RiB | Richardson number|
|    EDH(m)  | Evaporation duct height |

In total, 6,120,516 observations were made.

The goal of this exploration, is to determine whether or not Evaporation Duct
Height (EDH) can reasonably be predicted based on the above-observed features.

Exploration
-----

Our exploration is done using IPython notebook. The markdown version of the
notebook can be viewed.

If you intend to actually run the notebook, it's best that you check out the
project repository. Data size is very large. I haven't uploaded it here.
Please contact me for data :-). Cheers!
