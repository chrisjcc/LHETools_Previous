# To compile this package with scram use
scram build -j8
cmsenv

# To compile a standalone executable use
g++ `root-config --cflags --glibs` src/lheReader.cpp -o test/lheReader
