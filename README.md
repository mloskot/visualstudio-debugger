Visualizers for Microsoft Visual Studio 11
==========================================

This is collection of visualizers for Microsoft Visual Studio debugger.
Most of the visualizers are developed for Visual Studio 2012+ which uses new style XML-based visualizers.

Download
--------

Git repository: https://github.com/mloskot/visualstudio-debugger

Usage
-----

Copy all or selected .natvis and .natfilter files to your profile folder

	%USERPROFILE%\My Documents\Visual Studio Dev11\Visualizers\

Documentation
-------------

There are only two sources of documentation I have found:

1. Comments in defaultvis.natvis provide a good overview of the format

		%VSINSTALLDIR%\Common7\Packages\Debugger\Visualizers\defaultvis.natvis

2. The debugger visualizers XML Schema is installed in

		%VSINSTALLDIR%\Xml\Schemas\natvis.xsd

References
----------

* [Using Visual Studio 2013 to write maintainable native visualizations](http://blogs.msdn.com/b/vcblog/archive/2013/06/28/using-visual-studio-2013-to-write-maintainable-native-visualizations-natvis.aspx)
* [C++ Debugger Visualizers for VS2012](http://visualstudiogallery.msdn.microsoft.com/c7e02633-86d9-4262-b745-6cc647afb3a8) by Arkadiy Shapkin
* [Debugger visualizers in Visual Sudio 11 Developer Preview](http://mateusz.loskot.net/posts/2011/11/19/debugger-visualizers-in-visual-sudio-11-developer-preview/)
* [Setting EnableNatvisDiagnostics in Visual Studio 11](http://mateusz.loskot.net/posts/2011/11/20/setting-enablenatvisdiagnostics-in-visual-studio-11/)
* [Modular visualizers in Visual Studio 11](http://mateusz.loskot.net/posts/2011/11/22/modular-visualizers-in-visual-studio-11/)
	
License
-------

Copyright (c) 2011-2013 Mateusz Loskot <mateusz@loskot.net>

Use, modification and distribution is subject to the Boost Software License,
Version 1.0. (See accompanying file LICENSE_1_0.txt or copy at
http://www.boost.org/LICENSE_1_0.txt)

See also important notes about exclusions in individual files.
