

# Eclipse Project settings #
  * Open the project Properties dialog
  * Navigate to "Java Compiler/Annotation Processing"
  * Check the "Enable Project specific settings" checkbox

> ![Eclipse Project Setting](https://raw.githubusercontent.com/niko-rodrigue/spi/master/eclipse-project-settings1.png)

> _Screenshot of the Properties window after enabling annotation processing for this project_

  * Navigate to "Java Compiler/Annotation Processing/Factory Path"
  * Check the "Enable Project specific settings" checkbox
  * Press "Add Jar..." or "Add External Jar..." to choose the jar file.
    * The jar file to use can be found in the jsbml source tree at trunk/core/lib/spi-full-0.2.4.jar.
  * After this, the Properties window should look like this:

> ![Eclipse Project Setting2](https://raw.githubusercontent.com/niko-rodrigue/spi/master/eclipse-project-settings2.png)

> _Screenshot of the Properties window after registering the jar file as an annotation processor_

  * Press OK to confirm
  * Eclipse will ask if it should rebuild the project. You probably want to.
