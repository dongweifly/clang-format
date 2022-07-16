# clang-format
Clang format file


## Install clang-format

* Mac 
  
  ``` brew install clang-format ```
  
* Centos 7 
  
 ```
 yum install centos-release-scl-rh
 yum install llvm-toolset-7-git-clang-format  (deps toolsset-7, install file is big)
 
 ## find your clang-format bin path, create an link or add to path env. This is my config
 
 ln -s /opt/rh/llvm-toolset-7/root/usr/bin/clang-format /usr/local/bin
 
 ```
 
 ## UseAge
 
 copy clang-format to .clang-format  your project root dir
 
 * reference
  https://leimao.github.io/blog/Clang-Format-Quick-Tutorial/
