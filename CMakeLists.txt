cmake_minimum_required(VERSION 3.20)
project(MAPIStubLibrary)

set(LIBRARY_NAME    MAPIStub)

include_directories(./include)
add_library(
${LIBRARY_NAME}
SHARED
library/stubutils.cpp
library/mapiStubLibrary.cpp
)


