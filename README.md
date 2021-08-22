# Dungeon Crawler Group 43

## Setup Process
1. Use Java 11.
2. Go to https://gluonhq.com/products/javafx/ to download JavaFX version 11.0.2.
3. In IntelliJ, go to File -> Project Structure -> Libraries
    1. Add a new Java library and add the `lib` folder of the JavaFX package
4. Go to Run -> Edit Configurations
    1. Add the following VM Options: `--module-path /path/to/javafx-sdk-11.0.2/lib --add-modules javafx.controls,javafx.fxml`
    2. Replace the `/path/to/javafx-sdk-11.0.2/lib` with the path to the `lib` folder
5. It should run successfully now!
