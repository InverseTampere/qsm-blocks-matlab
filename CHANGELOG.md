# Changelog

## 2019-07-12 Version 1.0.0

- Initial release as a separate repository.
	- QSMB, QSMBCylindrical and CubeVoxelization classes used to be part of the QSM-FaNNI repository.
- QSMBCylindrical plot_model method has been re-written to use a single PATCH command.
	- Various customization options are available as Name-Value pairs.
- QSMBCylindrical export method has been extended.
	- Wavefront OBJ export rewritten.
	- PLY export added.
	- Initial version of a custom text format.
	- QSM-Blender-Addons compatible format.
- Triangulated stem support added to QSMBCylindrical.
	- Triangulated stems can be visualized and exported by using the *TriangleStem* optional argument.