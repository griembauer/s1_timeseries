# s1_timeseries
A tool to create a GRASS GIS SpaceTimeRasterDataset of Sentinel-1 backscatter data for a given region and time of interest

## TODO:
- make s1_grd OS and t.sentinel.s1_import and install it in Dockerfile
- create new addon t.sentinel.s1_import in mundialis repo that runs download, importing, STRDS creation/registration and output
- create an interface shellscript that takes arguments and launches the docker container
