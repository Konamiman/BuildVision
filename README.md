BuildVision [![Build status](https://ci.appveyor.com/api/projects/status/celssa4tvmu865qs?svg=true)](https://ci.appveyor.com/project/nagits/buildvision)
===========

_ **NOTE:** This is a fork created with the sole purpose of updating the extension to work with Visual Studio 2017. [Here is the unmaintained original](https://github.com/nagits/BuildVision), this one will not be maintained either. And [here is the original "getting started" link](http://visualstudiogallery.msdn.microsoft.com/23d3c821-ca2d-4e1a-a005-4f70f12f77ba)._

A Visual Studio extension to visualize the building process.
<br/>You can grab the extension from [the Visual Studio Gallery](https://visualstudiogallery.msdn.microsoft.com/23d3c821-ca2d-4e1a-a005-4f70f12f77ba "BuildVision on the Visual Studio Gallery") (latest release).
<br/>All releases and pre-releases are available in [Releases](../../releases "BuildVision Releases on GitHub").

Supports Visual Studio 2015 and 2017.

##### Installation and startup
1. Install the VSIX package and restart Visual Studio.
2. Open BuildVision tool window from Main Menu: "View → Other Windows → BuildVision".

##### Description
BuildVision activates when Visual Studio starts the process of building, rebuilding or cleaning projects (solution).

BuildVision tool window and Visual Studio Status Bar displays the current state of the process, for example: "Build solution 'MyApplication' started at 18:24:12 ..." or "Clean project 'MyProject' completed successfully at 18:25:20".

During the process, for each project the following columns are updated: State, Build Start Time, Build End Time, Elapsed Time, etc., as well as Errors, Warnings and Messages produced by MSBuild.

Indicators Panel, which is located above the table of projects, displays total number of errors, warnings and messages produced by MSBuild, the number of failed projects and successfully processed.

##### Screenshots
![Build completed on Light Theme](Screenshots/screenshot1.png)
![Build completed on Dark Theme](Screenshots/screenshot2.png)
![Rebuild started on Light Theme](Screenshots/screenshot3.png)
![Build failed on Light Theme](Screenshots/screenshot4.png)

##### Configuring
You can configure BuildVision via "Tools → Options... → BuildVision".
