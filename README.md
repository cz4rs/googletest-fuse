# googletest-fuse
Fuse Google Test and Google Mock source code.

This repository contains `fuse_gtest_files.py` and `fuse_gmock_files.py` scripts that were removed from [GoogleTest](https://github.com/google/googletest) (see [47f819c3](https://github.com/google/googletest/commit/47f819c3) and [6202251f](https://github.com/google/googletest/commit/6202251f)). All the credit goes to original authors.

## Usage
Fuse Google Test source code into a .h file and a .cc file:
```
./fuse_gtest_files.py path/to/unpacked/gtest fused_gtest
```

Fuse Google Mock and Google Test source code into two .h files and a .cc file:
```
 ./fuse_gmock_files.py path/to/unpacked/gmock fused_gmock
```

## Deprecation warning
Before removal, in the original repo, the scripts we accompanied by a following warning:
> Please Note:
>
> Files in this directory are no longer supported by the maintainers. They
> represent mostly historical artifacts and supported by the community only. There
> is no guarantee whatsoever that these scripts still work.
