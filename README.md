# README #

This repository contains a ugly hacked version of the ROVIO (Robust Visual Inertial Odometry) framework. Use the real one instead https://github.com/ethz-asl/rovio/wiki

### Hacks ###
The hacks in this version of rovio center around forcing the linear velocity estimates to 0 if the feature tracking fails. This stops rovio going to the moon, but introduces other serious issues.
