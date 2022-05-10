# About this project
This repository contains the checkstyle file used during the development of all other [AutoStreams](https://github.com/AutoStreams) repositories.

The checkstyle is based on the [Google Checkstyle rules](https://github.com/checkstyle/checkstyle/blob/master/src/main/resources/google_checks.xml), but with indentation changed from 2 spaces to 4 spaces. 

# Getting started
First acquire this project by cloning the repository. Cloning this repository can be done by downloading [Git](https://git-scm.com/) then executing the command:
```
git clone https://github.com/AutoStreams/autostreams-checks.git
```
## Using Checkstyle with IntelliJ
**Prerequisites**
* Downlaod and install [IntelliJ Idea](https://www.jetbrains.com/idea/). Community edition is sufficient
* Downlaod and install the [Checkstyle plugin](https://plugins.jetbrains.com/plugin/1065-checkstyle-idea). Version 10 or above is recommended due to compatability issues

After installing Checkstyle on your IntelliJ IDEA, Open the project where you want to use the AutoStreams Checkstyle rules.

Open the settings menu by going to File -> Settings in the upper left menu or by inputing Ctrl+Alt+S
![image](https://user-images.githubusercontent.com/42466095/167728428-636a77a1-3071-4877-82c8-6373f36bf5eb.png)

In the search bar, type "Checkstyle" to find the settings for the Checkstyle plugin. Select Checkstyle under Tools -> Checkstyle
![2022-05-11_00-51](https://user-images.githubusercontent.com/42466095/167737674-96e57c5f-c380-42b8-b816-37c4a9063548.png)


Click the + sign under the "Configuration File" header. A window will open. Add a descriptive name under "Description".  Make sure the radio button for "Use local Checkstyle file" is selected and find the downloaded streams_checks.xml file. Click  "Next" to verify the settings for the Checkstyle ruleset.
![2022-05-11_00-54](https://user-images.githubusercontent.com/42466095/167737907-56629d46-bdf7-429d-8e00-ec65b4d3d3fc.png)


You will likely encounter warnings after clicking "Next". Ignore these warnings and click "Next" again.

![2022-05-11_00-55](https://user-images.githubusercontent.com/42466095/167738063-3a71c683-6a9d-46d7-b4f0-8bf16a0a2143.png)

The stylerules are now ready for use!
