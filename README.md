Read me file for ENSF380 project

This file explains how to make use of the WeatherRevised.jar file for the program to function as intended

The Weather.java file is used to create this JAR file

1. In Eclipse IDE we begin by ensuring that our Weather.java file runs as intended
2. We then go to the "Package Explorer" on the left and find the Weather.java file under the WeatherFiles project
3. Right-click the file and select "Export..."
4. Under "Java" select "JAR file"
5. Ensure the "WeatherFiles" project is selected
6. Click on the "Export generated class files and resourses" and the "Export Java source files and resources" to check them off
7. Turn off "Export all output folders for checked projects" and "Export refactorings for checked projects"
8. Select the desired destination
9. Enable "Compress the contents of the JAR file"
10. Click "Finish"
11. Now right-click the Ads project and hover over "Build path" and click "Configure Build Path"
12. On the left "Java build path" should be selected, and on the top row, select "Libraries"
13. Left-click "Class path"
14. Then press "Add external JARs" on the right
15. Click the "WeatherRevised.jar" file
16. Click "Apply and close" at the bottom of the screen

The JAR file should now allow the Ads class to run as intended!
