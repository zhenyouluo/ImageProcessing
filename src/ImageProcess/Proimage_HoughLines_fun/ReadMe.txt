========================================================================
    CONSOLE APPLICATION : Proimage_HoughLines_fun Project Overview
========================================================================

AppWizard has created this Proimage_HoughLines_fun application for you.

This file contains a summary of what you will find in each of the files that
make up your Proimage_HoughLines_fun application.


Proimage_HoughLines_fun.vcxproj
    This is the main project file for VC++ projects generated using an Application Wizard.
    It contains information about the version of Visual C++ that generated the file, and
    information about the platforms, configurations, and project features selected with the
    Application Wizard.

Proimage_HoughLines_fun.vcxproj.filters
    This is the filters file for VC++ projects generated using an Application Wizard. 
    It contains information about the association between the files in your project 
    and the filters. This association is used in the IDE to show grouping of files with
    similar extensions under a specific node (for e.g. ".cpp" files are associated with the
    "Source Files" filter).

Proimage_HoughLines_fun.cpp
    This is the main application source file.

/////////////////////////////////////////////////////////////////////////////
Other standard files:

StdAfx.h, StdAfx.cpp
    These files are used to build a precompiled header (PCH) file
    named Proimage_HoughLines_fun.pch and a precompiled types file named StdAfx.obj.

/////////////////////////////////////////////////////////////////////////////
Other notes:

AppWizard uses "TODO:" comments to indicate parts of the source code you
should add to or customize.

/////////////////////////////////////////////////////////////////////////////
图像处理之霍夫变换（直线检测算法）

霍夫变换是图像变换中的经典手段之一，主要用来从图像中分离出具有某种相同特征的几何

形状（如，直线，圆等）。霍夫变换寻找直线与圆的方法相比与其它方法可以更好的减少噪

声干扰。经典的霍夫变换常用来检测直线，圆，椭圆等。