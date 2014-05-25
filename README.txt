# To compile this package with scram use
scram build -j8
cmsenv

# To compile a standalone executable use
clang++ `root-config --cflags --glibs` -std=c++11 -stdlib=libc++  src/lheReader.cpp -o test/lheReader 
