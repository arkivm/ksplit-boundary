
# Build

* Tested only on Clang 12. Other higher versions might require changes. There
  is no C++ API stability for LLVM.

* Install clang-12

* Make
```
make
```

## Run
* To run, you need the list of kernel and driver bc files. It can be extracted
  from a built kernel source using the [extract_bc.sh
  script](https://github.com/ksplit/lvd-linux/blob/99d395214bf48f706cae7739c2a090969ec8312f/extract-bc.sh)

```
./parse <driver_bc.list> <kernel_bc.list> <liblcd_funcs> <dest>
```
