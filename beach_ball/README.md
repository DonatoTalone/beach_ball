# beach_ball - a Qgis plugin for focal mechanisms visualization

**beach_ball** is a Qgis plugin written in Python for representing focal mechanisms in map as beachballs.

Starting from the strike, dip, and rake values, it produces an SVG icon using the [Obspy](https://docs.obspy.org/) module and links it to the features in your layer using the ID. **beach_ball** also calculates the kinematics according to the [Zobac (1992)](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/92JB00132) classification and displays the focal mechanism with different customizable colours.
The plugin adds the attitudes of the P-T-B axes in the attribute table. It calculates the P-T projection on the horizontal plane and assumes the greatest of the two as SHmax, whose azimuth is also reported in the attribute table.

**beach_ball** is released under [MIT licence](LICENSE).
