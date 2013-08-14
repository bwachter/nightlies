# the name of the target operating system
SET(CMAKE_SYSTEM_NAME Windows)

IF (NOT TOOLCHAIN)
    SET(TOOLCHAIN "i386-mingw32-")
ENDIF()

# which compilers to use for C and C++
SET(CMAKE_C_COMPILER ${TOOLCHAIN}gcc)
SET(CMAKE_CXX_COMPILER ${TOOLCHAIN}g++)

# here is the target environment located
SET(CMAKE_FIND_ROOT_PATH  /build/mingw32 /build/tmw-libs )

# adjust the default behaviour of the FIND_XXX() commands:
# search headers and libraries in the target environment, search 
# programs in the host environment
set(CMAKE_FIND_ROOT_PATH_MODE_PROGRAM NEVER)
set(CMAKE_FIND_ROOT_PATH_MODE_LIBRARY ONLY)
set(CMAKE_FIND_ROOT_PATH_MODE_INCLUDE ONLY)
