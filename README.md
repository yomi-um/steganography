# Steganograpy
## Računalniška Večpredstavnost 3. Vaja

### How to build
- Using docker:
  1. Different commands for docker are [here](docker.sh)
  2. Build an image using Dockerfile
  3. Run this image, use volume to see the results of program execution
  4. Exec in docker container to work inside of it

- Locally:
  1. I am using CLion with MinGW compiler on Windows, so if you use Visual Studio or Linux process will be a little bit different
  2. I used [this repo](https://github.com/huihut/OpenCV-MinGW-Build) to download build
  3. Extract it somewhere (e.g. C:\opencv_mingw\)
  4. Then add ...\x64\mingw\bin and ...\x64\mingw\lib to Path (absolute path e.g. C:\opencv_mingw\x64\mingw\bin and C:\opencv_mingw\x64\mingw\bin)