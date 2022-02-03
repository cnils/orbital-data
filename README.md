![](https://raw.githubusercontent.com/schevla/orbital-data/master/celestia_orbits.png)
# XYZV from TLE Orbital Data

Display orbital data forecasts in [Celestia](http://www.shatters.net/celestia/). The data is pulled from text files from the [Celestrack](http://www.celestrak.com/NORAD/elements/) website. [SGP4](https://github.com/brandon-rhodes/python-sgp4) Python implementation provided by Brandon Rhodes and is linked as a submodule in this repository.

## Code
Ensure all environmental variables are set correctly in `master.sh` before running.
```bash
# add crontab file contents to your system's crontab to pull data every hour
$ crontab master_crontab.sh
```
