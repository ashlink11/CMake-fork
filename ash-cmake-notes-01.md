2024 february 02

```bash
git clone https://github.com/ashlink11/CMake-fork.git

cd Help/guide/tutorial/

mkdir Step1_build // empty

cd Step1_build

cmake ../Step1
-- Configuring done
-- Generating done

cmake --build .
[ 50%] Building CXX object CMakeFiles/Tutorial.dir/tutorial.cxx.o
[100%] Linking CXX executable Tutorial
[100%] Built target Tutorial

./Tutorial 10
The square root of 10 is 3.16228
```

