# OpenGL template
Template for OpenGL C++17 apps that are developed in Visual Studio. Uses [any-project-setup](https://github.com/Matej-Chmel/any-project-setup) to download libraries GLEW, GLFW and GLM.

## Setup

1. Use this repo as a template.
2. Run [init.bat](init.bat) to download submodule and libraries.
3. Create Visual Studio solution in root directory with Empty C++ project.
4. Add [main.cpp](src/main.cpp) to the project.
5. Add [OpenGL.props](res/props/OpenGL.props) as property sheet for the project via Property Manager.
6. Set platform **x86** as active in Configuration Manager.
7. Run the project and check that a triangle is rendered with no errors.

## Libraries

After the libraries are downloaded, all unnecessary library files are deleted.
