# lrose-blaze

<img align="left" width="175" height="175" src="./docs/images/LROSE_logo_small.png">
<img align="right" width="175" height="175" src="./docs/images/Rosa_Blaze_Superior.jpg">

## **LROSE Blaze** - The Lidar Radar Open Software Environment "Blaze" Release

The first LROSE release is called **"Blaze"** (a climbing rose) and encompasses four key tools that define a core lidar/radar workflow: RadxPrint, RadxConvert, HawkEye, and Radx2Grid. 

Blaze can be used from a 'Virtual Toolbox' using Docker and a wrapper script, or compiled in C++ for native apps on Linux or Mac. More tools will continue to be added to Blaze in 2018 to build more complex workflows.

Full documentation for Blaze is available on the [LROSE website](https://nsf-lrose.github.io)

We encourage users to [register](https://nsf-lrose.github.io/software.html) in order to receive critical software updates, and sign up for the mailing list to help build the LROSE community.

[Help](https://nsf-lrose.github.io/software.html) can be obtained by posting issues directly to the lrose-blaze Github repository, via our help mailing list, or Gitter user forum.

LROSE is a co-operative project between:

  * [Dept. of Atmospheric Science at Colorado State University (CSU)](http://www.atmos.colostate.edu/) and the
  * [The Earth Observing Lab at the National Center for Atmospheric Research (NCAR)](https://www.eol.ucar.edu/content/lidar-radar-open-software-environment).

LROSE is funded by the [National Science Foundation](https://www.nsf.gov).

**Blaze** focuses on high-quality, well-tested, well-maintained and well-documented key applications as ‘building blocks’, allowing users to assemble trusted, reproducible workflows to accomplish more complex scientific tasks.

Six key workflows were identified through community input for initial LROSE development: *Convert, Display, QC, Grid, Echo, and Winds*

In the current release, the following tools are available:

## Convert
  * **RadxPrint** - Query files to determine properties and support by the Radx engine
  * **RadxConvert** - Convert 24 different lidar and radar formats to CfRadial NetCDF format

## Display
  * **HawkEye** - Real-time and archive display suitable for both scanning and vertically pointing radars. New research capabilities and new editing features will continue to be added in 2018

## Grid
  * **Radx2Grid** - Recent development has streamlined options in parameter file for typical use cases, but with extensive flexibility for power users
    * 3-D Cartesian gridding (x, y, z)
    * Cartesian PPIs (x, y, elevation)
    * Regular polar grid (range, azimuth, elevation)

### Future Release Plans

QC, Echo, and Wind tools will be released in the Fall and Winter.
