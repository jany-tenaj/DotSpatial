# Getting started

This explains the easiest way to build your own GIS program based on DotSpatial.

* Create a Windows Forms project.
* Rename Form1 to MainForm.
* Download the [DotSpatial dlls](https://ci.appveyor.com/api/projects/mogikanin/dotspatial/artifacts/Source/bin/Release.zip?branch=master).
* Unzip the file.
* Add the following dlls to your projects references.
  * System.ComponentModel.Composition
  * DotSpatial.Controls
  * DotSpatial.Data
  * DotSpatial.Symbology
* Create a new Toolbox tab.
  * Right-click on a toolbox.
  * Select "Add Tab"
  * Enter DsControls as name
* Add the DotSpatial Controls into the Visual Studio Toolbox.
  * Right-click on the DsControls toolbox
  * Select "Choose Items"
  * Browse to the unzipped DotSpatial.Controls.dll
  * Add it
* Select the AppManager and add it to your form.
* Rename the added appManager1 to appManager.
* Add the following code to your MainForm.cs
  [import, lang:"csharp"](../Source/DemoMap/MainForm.cs)
* Compile.
* Add the following plugins to the plugins folder in the folder your program was compiled to.



