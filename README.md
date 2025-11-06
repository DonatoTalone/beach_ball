# beach_ball - a Qgis plugin for focal mechanisms visualization

**PLEASE NOTE THAT THIS IS A FORK FOR EXERIMENTAL FEATURES.**
**THE MAIN OFFICIAL RELEASE OF THE PLUGIN IS:**

**[GeoSeisUtilities - FromEarthToEarth Laboratory / beach_ball · GitLab](https://gitlab.com/GeoSeisUtilities/beach_ball)**

**beach_ball** is a Qgis plugin written in Python for representing focal mechanisms in map as beachballs.

![327](./screenshot/FM_in_map.png "beach_ball GUI")

Starting from the strike, dip, and rake values, it produces an SVG icon using the [Obspy](https://docs.obspy.org/) module and links it to the features in your layer using the ID. **beach_ball** also calculates the kinematics according to the [Zobac (1992)](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/92JB00132) classification and displays the focal mechanism with different customizable colours.
The plugin adds the attitudes of the P-T-B axes in the attribute table. It calculates the P-T projection on the horizontal plane and assumes the greatest of the two as SHmax, whose azimuth is also reported in the attribute table.

The users can simply install the *beach_ball.zip* from the "manage and install plugins" in Qgis. This is the compressed version of the *beach_ball* folder.

The *example* folder contains a small dataset of focal mechanisms from [Time Domain Moment Tensor (Scognamiglio et al., 2006)](https://terremoti.ingv.it/tdmt) for performing a test of the plugin. The *screenshot* folder displays how the plugin appears when it is in use.

**beach_ball** is released under [MIT licence](LICENSE).
