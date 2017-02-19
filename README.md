# molvis-tools

This repository contains code necessary to run JSMol and JSME web apps. The intended use is to clone it into your workspace and quickly visualize molecular structures, such as those described in MOL files and in GAMESS output.

## Getting started 

Clone in the usual way: 

```bash
    git clone https://github.com/garcias/molvis-tools.github
```

To test that the installation works, find `jsmol.html` in the repository. Serve the file and load in a browser. You should see a model of caffeine in the canvas.

## Using

It's easiest to leave `jsmol.html` in the repository and have it served. To load different structures, there are three approaches:

1. Change the `molFile` variable in the script so it contains the (relative) path to the file you want to view. 
2. Start up the Java console from within the app (available from the contextual menu of the canvas) and use the Jmol `Load` command to get the desired file.
3. Have `molFile` point to a specific file, e.g., "current.mol", and overwrite this file everytime you have a new structure to view.

