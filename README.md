# lrose-blaze

<img align="left" width="175" height="175" src="./docs/images/LROSE_logo_small.png">
<img align="right" width="175" height="175" src="./docs/images/Rosa_Blaze_Superior.jpg">

## **LROSE Blaze** - The Lidar Radar Open Software Environment "Blaze" Release

[![DOI](https://zenodo.org/badge/139178089.svg)](https://zenodo.org/badge/latestdoi/139178089)

The first LROSE release is called **"Blaze"** (a climbing rose) and encompasses six key toolsets that define a core lidar/radar workflow: *Convert, Display, QC, Grid, Echo, and Winds*

Blaze can be used from a 'Virtual Toolbox' using Docker and a wrapper script, or compiled in C++ for native apps on Linux or Mac. Preliminary support is available for some tools on Windows.

Full documentation for Blaze is available on the [LROSE website](https://nsf-lrose.github.io)

We encourage users to [register](https://nsf-lrose.github.io/software.html) in order to receive critical software updates, and sign up for the mailing list to help build the LROSE community.

[Help](https://nsf-lrose.github.io/software.html) can be obtained by posting issues directly to the lrose-blaze Github repository, via our help mailing list, or Gitter user forum.

LROSE is a co-operative project between:

  * [Dept. of Atmospheric Science at Colorado State University (CSU)](http://www.atmos.colostate.edu/) and the
  * [The Earth Observing Lab at the National Center for Atmospheric Research (NCAR)](https://www.eol.ucar.edu/content/lidar-radar-open-software-environment).

LROSE is funded by the [National Science Foundation](https://www.nsf.gov).

**Blaze** focuses on high-quality, well-tested, well-maintained and well-documented key applications as ‘building blocks’, allowing users to assemble trusted, reproducible workflows to accomplish more complex scientific tasks.

In the current release, the following tools are available:

## Convert
  * **RadxPrint** - Query files to determine properties and support by the Radx engine
  * **RadxConvert** - Convert 24 different lidar and radar formats to CfRadial NetCDF format
  * **RadxBufr** - Convert Bufr format to CfRadial NetCDF format

## Display
  * **HawkEye** - Real-time and archive display suitable for both scanning and vertically pointing radars. New research capabilities and new editing features will continue to be added in 2018

## Grid
  * **Radx2Grid** - Gridding and interpolation of ground-based radar data
    * 3-D Cartesian gridding (x, y, z)
    * Cartesian PPIs (x, y, elevation)
    * Regular polar grid (range, azimuth, elevation)

## Echo
  * **RadxKdp** - KDP and Attenuation calculations
  * **RadxPid** - KDP, Attenuation, and Particle Identification
  * **RadxRate** - KDP, Attenuation, PID, and Rain Rate
  * **RadxQpe** - Accumulated Quantitative Precipitation Estimation

## Wind
  * **RadxEvad** - Extended Velocity Azimuth Display single-Doppler retrieval
  * **FRACTL** - Fast Reorder and CEDRIC Technique in LROSE multi-Doppler retrieval
  * **SAMURAI** - Variational multi-Doppler retrieval and analysis package

### Future Release Plans

Blaze is considered a 'stable' release, with ongoing bug fixes
and limited feature addition to ensure maximum reproducibility.
New development is occurring in the "Cyclone" release series.
