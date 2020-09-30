# Competitive Programming Buddy

CP Buddy is a Command Line Interface tool made using C++ to push reminders for the
upcoming competitions on various CP platforms, mainly CodeForces.

The project is in an infant stage and is expected to be developed within the
month of October 2020.

The setup and build is done using CMake.

### How to set up the project?

1. Go to a suitable directory you want this project to be cloned. Open up your terminal.

1. `git clone https://github.com/houseofgeeks/CP-Buddy.git --recursive`
 (Remember to add `--recursive` to the command.)

1. Open the CP-Buddy directory with VS Code.

1. Press `Ctrl + Shift + P` to issue a command. Look for `Cmake: Configure`.
(You might see your Intellisense picking the project up and making a build directory.
In such a case, skip this step)

1. Build the project by issuing a build command or look for the `build` option in the 
extension panel at the bottom.

1. Look for an executable named `CP-Buddy` and execute it in your bash.

OR

1. Follow the first 3 steps mentioned above.

1. Open up the terminal inside main directory of the repository.

1. Issue the command `cmake .`. This will create a `build` folder which will contain all
the binaries.

### Want to contribute?

Checkout the [Contributing Guidelines](.github/CONTRIBUTING.md) which you need to follow.

Also, go though the [Code of Conduct](.github/CODE_OF_CONDUCT.md) for this project.