add_entrypoint_object(
  fopen
  SRCS
    fopen.cpp
  HDRS
    fopen.h
  DEPENDS
    libc.include.stdio
    libc.src.__support.File.file
    libc.src.__support.File.platform_file
)

add_entrypoint_object(
  fclose
  SRCS
    fclose.cpp
  HDRS
    fclose.h
  DEPENDS
    libc.include.stdio
    libc.src.__support.File.file
    libc.src.__support.File.platform_file
)

add_entrypoint_object(
  fread
  SRCS
    fread.cpp
  HDRS
    fread.h
  DEPENDS
    libc.include.stdio
    libc.src.__support.File.file
    libc.src.__support.File.platform_file
)

add_entrypoint_object(
  fwrite
  SRCS
    fwrite.cpp
  HDRS
    fwrite.h
  DEPENDS
    libc.include.stdio
    libc.src.__support.File.file
    libc.src.__support.File.platform_file
)

add_entrypoint_object(
  fseek
  SRCS
    fseek.cpp
  HDRS
    fseek.h
  DEPENDS
    libc.include.stdio
    libc.src.__support.File.file
    libc.src.__support.File.platform_file
)
