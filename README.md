# HDR Images

#### Authors: Gabriela Zorzo and Morgana Weber
##### About the project
This repository was created to develop a university work on Low-Level Programming. 
The main idea of this project is read a image (.hdf) and convert it for a HDR image. 
The process order is: 

- read and decodify the image
- apply the exposure factor
- apply the tone mapping 
- convert the result to 24 bits
- create the histogram 
- adjust the black and white tones 

##### Requirements 
- [Mingw-w64] https://www.mingw-w64.org/downloads/ to run the output of GCC on Windows 

##### Running the project
If you are using a Linux System, you need to run: 
`sudo apt-get install freeglut3-dev`

After, if you are on a Windows System, run:
`mingw32-make -f Makefile.mk`

Or if you are using a Linux or macOS, just run `make`

When the project is running, you will have the following options: 
- arrows rigth and left to reduce or increase the exposure factor
- A or S to reduce or increas black 
- K or L to reduce or increas white 
- H to show or hide the histogram 

