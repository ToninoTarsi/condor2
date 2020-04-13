# Condor 2 Tools
Tools for building landscapes for the Condor 2 flight simulator


## Condor .obj files
condor_obj_file_tool.py converts Condor's .obj files, which contains the coordinates, dimension and orientation of objects in the landscape. It can also help translate objects from one landscape's coordinate system to an other's. While Condor's .obj files contain relatives coordnates, the tool writes absolute coordinates to the JSON file.

Typical workflow

`condor_obj_file_tool.py --decompile --name <landscapefrom> --json objects.json`

`condor_obj_file_tool.py --compile --name <landscapeto> --json objects.json`
 
