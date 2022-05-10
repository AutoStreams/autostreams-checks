# About this project
This repository contains the checkstyle file used during the development of all other [AutoStreams](https://github.com/AutoStreams) repositories.

The checkstyle is based on the [Google checkstylestyle](https://checkstyle.sourceforge.io/google_style.html), but with indentation changed from 2 spaces to 4 spaces. 

# Getting started
First acquire this project by cloning the repository. Cloning this repository can be done by downloading [Git](https://git-scm.com/) then executing the command:
```
git clone https://github.com/AutoStreams/prototype-pulsar.git
```
**Prerequisites**
* Downlaod and install [IntelliJ Idea](https://www.jetbrains.com/idea/). Community edition is sufficient
* Downlaod and install the [Checkstyle plugin](https://plugins.jetbrains.com/plugin/1065-checkstyle-idea). Version 10 or above is recommended due to compatability issues

After installing Checkstyle on your IntelliJ IDEA, Open the project where you want to use the AutoStreams Checkstyle rules.

Open the settings menu by going to File -> Settings in the upper left menu or by inputing Ctrl+Alt+S
![image](https://user-images.githubusercontent.com/42466095/167728428-636a77a1-3071-4877-82c8-6373f36bf5eb.png)

In the search bar, type "Checkstyle" to find the settings for the Checkstyle plugin. Select Checkstyle under Tools -> Checkstyle![Captura de pantalla_2022-05-11_00-03-37](https://user-images.githubusercontent.com/42466095/167729654-c21efb88-e8bc-4dfe-83ea-884115429543.png)

Click the + sign under the "Configuration File" header. A window will open. Add a descriptive name under "Description".  Make sure the radio button for "Use local Checkstyle file" is toggled and find the downloaded streams_checks.xml file.
![image](https://user-images.githubusercontent.com/42466095/167730685-57a50ef3-7428-4667-b6db-439d87f805ec.png)

Click  "Next" to verify the settings for the Checkstyle ruleset. You will likely encounter warnings after clicking "Next". Ignore these errors and click "Next" again.

![image](https://user-images.githubusercontent.com/42466095/167731310-283c2ef3-1e96-41f7-803d-b780bd9e0c31.png)

The stylerules are now ready for use!
