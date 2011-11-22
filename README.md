Visualizers for Microsoft Visual Studio 11
==========================================

This is collection of visualizers for Microsoft Visual Studio 11 debugger.
Visual Studio 11 uses new style XML-based visualizers

Download
--------

Git repository: https://github.com/mloskot/visualstudio11

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

I have posted several short articles about the new style visualizers:

http://mateusz.loskot.net/2011/11/19/debugger-visualizers-in-visual-sudio-11-developer-preview/

http://mateusz.loskot.net/2011/11/20/setting-enablenatvisdiagnostics-in-visual-studio-11/

http://mateusz.loskot.net/2011/11/22/modular-visualizers-in-visual-studio-11/
	
License
-------

Copyright (c) 2011 Mateusz Loskot <mateusz@loskot.net>
Use, modification and distribution is subject to the Boost Software License,
Version 1.0. (See accompanying file LICENSE_1_0.txt or copy at
http://www.boost.org/LICENSE_1_0.txt)

See also important notes about exclusions in individual files.