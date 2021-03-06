# CALCPONG
A custom version of pong for your TI-84 plus CE calculator.

The calculator on the left is controlled with the 2nd key and the alpha key, the calculator on the right is controlled with the up and down arrow keys.

You can download the newest release in the releases tab (on the right side of this github page).
To install the game on your calculator, you will need to have [TI connect CE](https://education.ti.com/en/products/computer-software/ti-connect-ce-sw) and you also need to install the [CE C 'Standard' Libraries](https://github.com/CE-Programming/libraries/releases/tag/v9.0).

This was my first project ever in c/c++ for the TI-84 plus CE calculator, so the code may not be the best, but i've tried my best to restructure the original source code and add comments so that the code makes more sense :)

You are always free to add new features.

# SCREENSHOTS
![image](https://user-images.githubusercontent.com/81973766/124315341-16320c00-db74-11eb-9321-205648276604.png)
![PongScored](https://user-images.githubusercontent.com/81973766/124316212-89884d80-db75-11eb-9fc8-8983b0e11ebb.png)

# BUILDING
If you would like to build CALCPONG yourself, be sure you have the latest LLVM [CE C Toolchain](https://github.com/CE-Programming/toolchain/releases/latest) installed.

Then simply clone or download the repository from above, and run the following commands:

    make gfx
    make

# INFO
if you want to know more about developing games for the TI-84 plus CE calculator, I highly recommend to take a look at the [CE C Toolchain](https://github.com/CE-Programming/toolchain) they also have a [documentation](https://ce-programming.github.io/toolchain/). You can also use the [CEmu emulator](https://github.com/CE-Programming/CEmu) to experiment on a virtual calculator, so that if you do something wrong, you won't crash your actual calculator.
