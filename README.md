#Morph-SDK

************************

This project provides a 3D virtual applications software development kit, which has a 3D interface editor which allows users to manage their 3D scene and create their 3D application, and a base framework that the editor relies on.

##System Features

- User friendly, you can create a whole interactive 3D scene.
- Loading Ogre scene (.scene) contents (including meshes, animations, textures, ...etc) within scene tree hierarchy names.
- Real-time scene preview, navigation and manipulation (deleting objects, moving, rotating, scaling). 
- Visual Editor with command patten, undo/redo support, unicode support, Qt based user interface, object hierarchy system, property system. 
- Provide API classes to develop event-driven finite-state machine to define behavior for scene objects.
- Provide graphical tools for behavioral/logic editing, ex. automatically generate code equivalent to what user express in graphical tools. 
- Give ability to extend with code.
- Provide predefined widgets (buttons, sliders, knobs) to utilize with 3D objects.
- Provide integration with input/output devices. Make it ready to use with framework.
- Provide simple UI to link input events to output callbacks.
- Generate stand-alone 3D/VR applications.

Building and Installation
-------------------------

The following instructions apply to building Morph editor from an official release.

If you use any POSIX platform or Windows or MacOSX you can build the project by
launching QtCreator first ensure your system has it installed and a C++ compiler
installed and linked to it. Then open Morph.pro file then make sure you installed libOgre-dev.
After that all the build proccess should go fine.

Refer to the `INSTALL` file included with the Morph editor source repo for more
detailed installation instructions.

Contributing to the Project
---------------------------

Before contributing to the project make sure you understand the legal
implications of doing so.  These are outlined on the Crossroads I/O website[2].

To submit your contribution, send it as a patch (using `git format-patch`, `diff`,
or similar) to the mailing list.  Make sure to use your real name, and prefix
the subject of your post with `[PATCH]`.

All contributions will be reviewed and, if they pass review, accepted.  If you have a patch
and want to contribute it, please send an email to wazery [at] ubuntu [dot] com. If you have
a feature request don't hestiate to file it in our issues tracker.
github.com/Zeology/Morph-SDK/issues.

Copying
-------

Free use of this software is granted under the terms of the GNU Lesser General
Public License (LGPL).  For details see the files `COPYING` and `COPYING.LESSER`
included with the libxs distribution.

As a special exception, the copyright holders of libxs grant you the right
to link the library statically with your software.  Refer to the end of
the `COPYING.LESSER` file included with the libxs distribution for details.

Footnotes
---------

[1]: Bug tracker: https://github.com/Zeology/Morph-SDK/issues

[2]: Source code: https://github.com/Zeology/Morph-SDK             

[3]: Project website: http://zeology.github.com/Morph-SDK/