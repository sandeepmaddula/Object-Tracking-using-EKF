# Object-Tracking-using-EKF
C++, EKF
This code implements the extended Kalman filter in C++. We are providing simulated lidar and radar measurements detecting a bicycle that travels around your vehicle. You will use a Kalman filter, lidar measurements and radar measurements to track the bicycle's position and velocity.

Dependencies
cmake >= 3.5
All OSes: click here for installation instructions
make >= 4.1
Linux: make is installed by default on most Linux distros
Mac: install Xcode command line tools to get make
Windows: Click here for installation instructions
gcc/g++ >= 5.4
Linux: gcc / g++ is installed by default on most Linux distros
Mac: same deal as make - [install Xcode command line tools]((https://developer.apple.com/xcode/features/)
Windows: recommend using MinGW
Basic Build Instructions
Clone this repo.
Make a build directory: mkdir build && cd build
Compile: cmake .. && make
On windows, you may need to run: cmake .. -G "Unix Makefiles" && make
Run it: ./ExtendedKF path/to/input.txt path/to/output.txt. You can find some sample inputs in 'data/'.
eg. ./ExtendedKF ../data/sample-laser-radar-measurement-data-1.txt output.txt
Editor Settings
We've purposefully kept editor configuration files out of this repo in order to keep it as simple and environment agnostic as possible. However, we recommend using the following settings:

indent using spaces
set tab width to 2 spaces (keeps the matrices in source code aligned)
Code Style
Please (do your best to) stick to Google's C++ style guide.
