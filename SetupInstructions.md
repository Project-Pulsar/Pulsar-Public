# How to setup Pulsar on Minecraft Launcher
1. Open the Minecraft Launcher, go to Installation > New installation
![1](https://github.com/Project-Pulsar/Pulsar-Public/blob/main/Images/1.png)

2. Name the installation whatever you want, for this case i will name it Pulsar,
3. select "release Pulsar" in Version dropdown
4. Click "More Options".
5. Change "Java Executable" to a java version that is 17 or higher, in my case im using zulu17.
NOTE: /usr is a Linux directory, if you are not using linux, search up the location of your java installs.
6. In JVM Arguments, add the following argument:
'-Djava/library.path/path/to/.minecraft/versions/Pulsar/natives`
make sure it is properly separated from the other jvm arguments
Note: if you are using mac, make sure to surround the directory with quotes "" so it stays as a single argument

![2](https://github.com/Project-Pulsar/Pulsar-Public/blob/main/Images/2.png)

7. Click "Save", find the installation you just created and click "Play".
