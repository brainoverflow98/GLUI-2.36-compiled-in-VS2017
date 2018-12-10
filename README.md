# GLUI-2.36-compiled-in-VS2017

I had to recompile the GLUI source code in VS2017. I leave the link here to relieve some headache for you.
Both x64 and x86 libraries incldued in the link. 
1- Just include the "glui.h"
2- copy the library to your "lib" folder you are good to go ! 
3- You don't have to link it. 
(make sure "freeglut.h" is visible in your project with the form "#include <freeglut.h>" 
otherwise specify the path in "glui.h" header for freeglut for example "#include <GL/freeglut.h>" )
I have also included the Manuel PDF. Refer to https://github.com/libglui/glui and http://www.cs.unc.edu/~rademach/glui/ for more info.

I included the latest version of Glut(3.0.0) and Glew(2.1.0) that I used to compile my glui.lib to link.
