# Inner Core headers for native mods
This headers will be helpful for native mod development, using Inner Core

### Usage
To add this to Inner Core toolchain as system headers, choose innercore version, you are developing to create directory `toolchain/stdincludes/ic_headers` and copy headers into it. In this case include them like this `#include <innercore/global_context.h>`.

**THIS HEADERS REQUIRE ADDING https://github.com/zheka2304/gnustl-shared-headers TO YOUR** `stdincludes`! (`<stl/string>` and `<stl/vector>` are reqired), see its `README.md` for installation instructions.

You can also add this headers anywhere in your project and include as common headers, it might be required in case you have libraries for different versions in your project.
