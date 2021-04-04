# Explore Close Approaches of Near-Earth Objects

In this project, I have used python3 - to search for and explore close approaches of near-Earth objects (NEOs), using data from NASA/JPL's Center for Near Earth Object Studies.

The output of the project would look like this:

[gif in action]

## Overview


$ python3 main.py inspect --help
usage: main.py inspect [-h] [-v] (-p PDES | -n NAME)

Inspect an NEO by primary designation or by name.

optional arguments:
  -h, --help            show this help message and exit
  -v, --verbose         Additionally, print all known close approaches of this NEO.
  -p PDES, --pdes PDES  The primary designation of the NEO to inspect (e.g. '433').
  -n NAME, --name NAME  The IAU name of the NEO to inspect (e.g. 'Halley').
