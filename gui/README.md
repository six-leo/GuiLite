## How to build gui libary for Windows?
depdency: Windows 10, visul stdio 2015/2017
- Open "gui.sln" by Visual studio 2017
- Click `build` 

## How to build gui libary for Linux（x64 & arm）?
- `cmake .`
- `make`

## How to build gui libary for Android?
- `sudo apt-get install gcc-arm-linux-androideabi`
- `cmake cmake -D CMAKE_C_COMPILER="/usr/bin/arm-linux-androideabi-gcc" -D CMAKE_CXX_COMPILER="/usr/bin/arm-linux-androideabi-g++" .`
- `make`
