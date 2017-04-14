# Getting started

This explains the easiest way to build your own GIS program based on DotSpatial.

1. Create a Windows Forms project.
2. Rename Form1 to MainForm.
3. Download the [DotSpatial dlls](https://ci.appveyor.com/api/projects/mogikanin/dotspatial/artifacts/Source/bin/Release.zip?branch=master).
4. Unzip the file.
5. Add the following dlls to your projects references.
   * System.ComponentModel.Composition
   * DotSpatial.Controls
   * DotSpatial.Data
   * DotSpatial.Symbology
6. Create a new Toolbox tab.
   * Right-click on a toolbox.
   * Select "Add Tab"
   * Enter DsControls as name
7. Add the DotSpatial Controls into the Visual Studio Toolbox.
   * Right-click on the DsControls toolbox
   * Select "Choose Items"
   * Browse to the unzipped DotSpatial.Controls.dll
   * Add it
8. Select the AppManager and add it to your form.
9. Rename the added appManager1 to appManager.
10. Add the following code to your MainForm.cs
11. [import, lang:"csharp"](../Source/DemoMap/MainForm.cs)
12. Compile.
13. Add the plugins folder to the folder your program was compiled to.




