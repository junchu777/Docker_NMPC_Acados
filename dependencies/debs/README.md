# Local Debian Packages

This directory contains prebuilt `.deb` packages for external dependencies used by this project.

These packages are included in the repository because they are not available through the standard Ubuntu/ROS APT repositories and do not provide a conventional installation mechanism (e.g. `make install` or official binary releases).

The packages are installed directly during the Docker image build process and should be treated as third-party dependencies.

## List of Packages
 - `rviz_2d_plot_plugin`: A plugin for RViz that provides online 2D plotting capabilities. This package is used to visualize data in a 2D plot format within the RViz environment. Original source: https://github.com/amgaber95/rviz_2d_plot_plugin