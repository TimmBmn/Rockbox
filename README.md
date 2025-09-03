# This is a clone of the [Rockbox](https://www.rockbox.org/) project.

# Why
I was annoyed by the fact that if two artists each wrote a song and then wrote one song together they would be displayed as three separate artists in the database.

# Solution
I fixed it so that Rockbox can support multiple artists in the database.

# How to install
Follow all the normal steps you would follow to build a Rockbox zip
```
./tools/rockboxdev.sh
./tools/configure
make -j
make zip
```
and put it in the root directory of your device.

# Possible Problems
- The program was only tested with the simulated Rockbox instance and an iPod Classic 7th. Gen. If it doesn't work for you then i am sorry :(
- This version could break other features of Rockbox. Because i am not an active maintainer of the project, i don't know each in and out of the source code. I've barely understood enough to make this modification. This could mean my modification could break other features (that i don't use and therefore am not aware that i have broken them).
