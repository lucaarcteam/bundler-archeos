

# list sources files
FILE(GLOB LIBRARY_FILES_C "./*.c")
FILE(GLOB LIBRARY_FILES_H "./*.h")

ADD_LIBRARY(getopt
${LIBRARY_FILES_C}
${LIBRARY_FILES_H}
)