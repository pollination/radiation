# Radiation Express

Radiation Express recipe for Pollination

This recipe calculates average irradiance (W/m2) or cumulative radiation (kWh/m2)
over the time period of a specified Wea.

## Limitations

This recipe uses the ladybug-radiance
[RadiationStudy](https://github.com/ladybug-tools/ladybug-radiance/blob/master/ladybug_radiance/study/radiation.py).

```console
Such studies of incident radiation can be used to approximate the energy that can
be collected from photovoltaic or solar thermal systems. They are also useful
for evaluating the impact of a building's orientation on both energy use and the
size/cost of cooling systems. For studies of photovoltaic potential or building
energy use impact, a sky matrix from EPW radiation should be used. For studies
of cooling system size/cost, a sky matrix derived from the STAT file's clear sky
radiation should be used.

Note that no reflections of solar energy are included in the analysis performed by
this class. Ground reflected irradiance is crudely accounted for by means of an
emissive "ground hemisphere," which is like the sky dome hemisphere and is derived
from the ground reflectance that is associated with the connected sky_matrix. This
means that including geometry that represents the ground surface will effectively
block such crude ground reflection.
```
