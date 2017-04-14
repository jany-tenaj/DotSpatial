# Getting started

This explains the easiest way to build your own GIS program based on DotSpatial.

1. Create a Windows Forms project.
2. Rename Form1 to MainForm.
2. Download the [DotSpatial dlls](https://ci.appveyor.com/api/projects/mogikanin/dotspatial/artifacts/Source/bin/Release.zip?branch=master).
3. Unzip the file.
4. Add the following dlls to your projects references.
   * System.ComponentModel.Composition
   * DotSpatial.Controls
   * DotSpatial.Data
   * DotSpatial.Symbology
5. Create a new Toolbox tab.
   * Right-click on a toolbox.
   * Select "Add Tab"
   * Enter DsControls as name
6. Add the DotSpatial Controls into the Visual Studio Toolbox.
   * Right-click on the DsControls toolbox
   * Select "Choose Items"
   * Browse to the unzipped DotSpatial.Controls.dll
   * Add it
7. Select the AppManager and add it to your form.
8. Rename the added appManager1 to appManager.
9. Add the following code to your MainForm.cs
[import, template:"acefull", title:"example of code"](../Source/DemoMap/MainForm.cs)
10. Compile.
11. Add the plugins folder to the folder your program was compiled to.




