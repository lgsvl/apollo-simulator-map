# Apollo HD-map data for LG Automotive Simulator

This repository contains Apollo specific HD map information generated for the San Francisco map in the [LGSVL automotive simulator](https://github.com/lgsvl/simulator).

The HD-map data is in the `base_map.txt` file. Apollo generates topological maps and sim maps from `base_map.txt` which are needed for autounmous navigation. These maps are included in this repository, but will need to be regenerated if `base_map.txt` is modified. To generate these maps from `base_map.txt`, use the `generate_map.sh` script in the apollo repository (located in `apollo/scripts/`).


## Copyright and License

Copyright (c) 2018 LG Electronics, Inc.

This software contains code licensed as described in LICENSE.