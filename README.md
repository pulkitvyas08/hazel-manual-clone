# hazel-manual-clone

A Hand-Copied Clone of Hazel Engine Developed by TheCherno


## Solutions to problems I faced (not covered in the series):
- While writing source code for shaders, after the #version... line, in some openGL versions you might get an error like location requires "something". Just add that something after the version line. In my case it would be [commit 29] where I had to add the line: "#extension GL_ARB_separate_shader_objects: enable". More about this can be found [here][1] and [here][2]


[commit 29]: ae79cf4a6e8cc1cbdc6540d1546f5b890966aeee
[1]: https://community.khronos.org/t/problem-with-layout-syntax/69034
[2]: https://community.khronos.org/t/unable-to-create-core-profile/73364