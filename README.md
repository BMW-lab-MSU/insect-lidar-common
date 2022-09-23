# insect-lidar-common
Common code for projects that process insect lidar data

Throughout our various projects that process data from our insect lidar instrument, there are common functions that rarely contain per-project changes. This repository hosts these functions, and is intended to be used as a submodule or subtree. The main ideas behind this are:
- less code duplication and copying.
- ability to fix bugs in one place, not every project repo.
