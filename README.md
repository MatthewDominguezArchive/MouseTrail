# MouseTrail
Really dumb but satisfying animation following your mouse.
![image](https://github.com/user-attachments/assets/72085e94-76c7-4ed8-ab09-369f6856c41e)


### How To Install
x64 Release

```MouseTrail Project Properties (Change From Debug To Release):
 |
 |--- General
 |    |--- C++ Language Standard: ISO C++20 Standard (/std:c++20)
 |
 |--- C/C++
 |    |--- General
 |         |--- Additional Include Directories:
 |              |--- C:\Program Files (x86)\Microsoft DirectX SDK (June 2010)\Include      <- For this go to [here](https://download.microsoft.com/download/A/E/7/AE743F1F-632B-4809-87A9-AA1BB3458E31/DXSDK_Jun10.exe)
 |              |--- C:\Users\username\Desktop\CD\MouseTrail\Resources\GLFW\include
 |              |--- C:\Users\username\Desktop\CD\MouseTrail\Resources
 |--- Linker
      |--- General
           |--- Additional Library Directories
           |    |--- C:\Users\username\Desktop\CD\MouseTrail\Resources\GLFW\lib
           |--- Input
                |--- glfw3.lib
                |--- d3d11.lib```
