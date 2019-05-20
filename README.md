# VEINS urban simulator configuration

[Install SUMO](http://sumo.sourceforge.net/) and make sure to add SUMO to your path (required for certain scripts):

**IMPORTANTL** VEINS requires SUMO 0.32 (not the current version!)

```
export SUMO_HOME="/usr/local/opt/sumo/share/sumo" # Dependant on install location
```

[Install OMNET++ and VEINS](https://veins.car2x.org/)yy

## Download this project

Change directories to your veins install location

`cd /your/path/to/veins/. . ./examples`

```
git clone https://github.com/StevenMHernandez/VEINS-Simulation.git
```

## Running the project

In OMNET++ IDE, you should now see this project. Following the VEINS tutorial actions, simply right-click the `omnetpp.ini` file from this repo and click `Run as OMNeT++ Simulation`.
Do make sure that `../sumo-launchd.py -vv -c /opt/local/bin/sumo` is running as explained in the VEINS tutorial.

