# TestVector

При попытки скомпилировать в консоли 'g++ main.cpp -o MAIN'
вылезает ошибка
'''
Undefined symbols for architecture x86_64:
  "Vector4d::Vector4d(double, double, double, double)", referenced from:
      _main in main2-bb1f3a.o
  "Vector4d::~Vector4d()", referenced from:
      _main in main2-bb1f3a.o
ld: symbol(s) not found for architecture x86_64
clang: error: linker command failed with exit code 1 (use -v to see invocation)
'''
