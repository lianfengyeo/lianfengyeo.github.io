# Linux envrionment


## Linux tutorial
**bolg**
- [Linux Cluster Blog](https://thelinuxcluster.com/) is a collection of how-to and tutorials for Linux Cluster and Enterprise Linux
- [Linux 命令收藏](https://openfoam.top/linuxLearning/)

**Video tutorial**
- [莫烦 linux 建议教学](https://mofanpy.com/tutorials/others/linux-basic/)
- [Learn CentOS "LearnLinuxTV"](https://www.youtube.com/watch?v=Mi6GUcSW5xs&list=PLT98CRl2KxKHjHLIHrmmi5FmBGIZ8cNJE)
- [计算机科学课堂中学不到的知识 The Missing Semester of Your CS Education(2020)](https://www.bilibili.com/video/BV1x7411H7wa)

**Ubuntu**
- [List of releases](https://wiki.ubuntu.com/Releases)  
- [releases downloads](https://releases.ubuntu.com/)  
- [Mirror Tsinghua](https://mirror.tuna.tsinghua.edu.cn/help/ubuntu/) 

**CentOS**
- [Mirror Tsinghua Centos6](https://mirror.tuna.tsinghua.edu.cn/help/centos-vault/)
- [Mirror Tsinghua Centos7 8](https://mirror.tuna.tsinghua.edu.cn/help/centos/)



<br><br><br>


## Fortran

### tutorial

- [fcode](http://v.fcode.cn/)
  [[bilibili]](https://www.bilibili.com/video/BV1tx411u7o4)

-[[Fortran Tuto 2] Basics about variables](https://www.youtube.com/watch?v=GSJL6E1A6gM&list=PLvkU6i2iQ2fprrVmmkNP_V36mh0BMnS5L&index=2)

- [Python入门](https://www.youtube.com/playlist?list=PLq9fAEr-k3NxkPezuPpB4LaX8lOqIed3N)

- [零基础Python教程](https://www.youtube.com/playlist?list=PLHtXVCtcbbo2D6Pd6VYlNJz2PPE1hmeCH)

**doc**
- [ustc doc](http://micro.ustc.edu.cn/Fortran/)
- [Mistakes in Fortran 90 Programs That Might Surprise You](http://www.cs.rpi.edu/~szymansk/OOF90/bugs.html)
- [Clion Fortran](https://www.jetbrains.com/help/clion/fortran-support.html)





<br><br><br>


## Python

### anaconda  
  install
```bash
  wget https://repo.anaconda.com/archive/Anaconda3-2020.11-Linux-x86_64.sh
  bash Anaconda3-2020.11-Linux-x86_64.sh
```

### tutorial

- MorvanZhou  
  https://github.com/MorvanZhou/tutorials  
- [Python Documentation contents](https://docs.python.org/3/contents.html)  
- https://www.runoob.com/python/python-tutorial.html  
- [Python 入門教學課程](https://www.youtube.com/watch?v=wqRlKVRUV_k&list=PL-g0fdC5RMboYEyt6QS2iLb_1m7QcgfHk)  
- [Python全套教程 2019最适合零基础 提供源码笔记](https://www.youtube.com/playlist?list=PLmOn9nNkQxJFGvtKd7PI7AhsYmY-6FrJs)  

### numpy

- [Python NumPy 入門教學課程](https://www.youtube.com/watch?v=nJUMpIo5rmg&list=PL-g0fdC5RMboq4yOQmvwYXamPDL4uZYEL)

**doc**
NumPy 官网 http://www.numpy.org/  
NumPy 源代码：https://github.com/numpy/numpy  
SciPy 官网：https://www.scipy.org/  
SciPy 源代码：https://github.com/scipy/scipy  
Matplotlib 官网：https://matplotlib.org/  
Matplotlib 源代码：https://github.com/matplotlib/matplotlib  

NumPy官方文档  
https://numpy.org/doc/stable/user/whatisnumpy.html

runoob  
https://www.runoob.com/numpy/numpy-tutorial.html

from-python-to-numpy  
https://www.labri.fr/perso/nrougier/from-python-to-numpy




<br><br><br>








## julia
https://docs.julialang.org/en/v1/

https://www.youtube.com/c/TheJuliaLanguage/videos

### install julia

1. download from https://julialang.org/downloads/
2. decompress
```bash
tar zxf julia-1.6.0-linux-x86_64.tar.gz 
cd julia-1.6.0
```

env
```bash
export PATH=~/julia-1.6.0/bin/:$PATH
```

test
```julia
#!/usr/bin/env julia
println("Greetings! 你好! こんにちわ! 안녕하세요?")
```

install packages
```bash
julia   # activate julia env

using Pkg
Pkg.add("Plots")
Pkg.add("PyPlot")

Pkg.update()
Pkg.update("Plots")
Pkg.rm("Plots")

```

**tutorial**
- Julia for Numerical Computation in MIT Courses  
  https://github.com/mitmath/julia-mit
- Introduction to Computational Thinking by Alan Edelman, David P. Sanders & Charles E. Leiserson  
  https://computationalthinking.mit.edu/Spring21/syllabus/
- 

<br><br><br>










## java
[Java SE Development Kit 15 Downloads](https://www.oracle.com/java/technologies/javase-jdk15-downloads.html)

<br><br><br>







## git 

- [git命令查询](https://www.bookstack.cn/read/git-tutorial/docs-basic.md)  
- [GitHub Documentation](https://docs.github.com/en) 

**tutorial**
- [Lecture 6 - Version Control (git) (2020)](https://www.bilibili.com/video/BV1x7411H7wa?p=6)
- [Git 版本管理 教学 tutorial "Morvan"](https://www.youtube.com/playlist?list=PLXO45tsB95cKysjmSNln65YoUt9lwEl7-)

<br><br><br>

## complier

### Intel oneAPI Base Toolkit 
Intel oneAPI is the new version for free and the old version is intel parallel studio.

**Document**
* [Intel homepage](https://www.intel.com/content/www/us/en/homepage.html)  

Download from
* [Free Intel® Software Development Tools](https://software.intel.com/content/www/us/en/develop/articles/qualify-for-free-software.html#educator)  
* [Get the Intel® oneAPI Base Toolkit](https://software.intel.com/content/www/us/en/develop/tools/oneapi/base-toolkit/download.html)  
* [Get the Intel® oneAPI HPC Toolkit](https://software.intel.com/content/www/us/en/develop/tools/oneapi/hpc-toolkit/download.html)  

Release Notes
- [Intel® oneAPI Base Toolkit Release Notes](https://software.intel.com/content/www/us/en/develop/articles/intel-oneapi-toolkit-release-notes.html)
- [Intel® oneAPI HPC Toolkit Release Notes](https://software.intel.com/content/www/us/en/develop/articles/intel-oneapi-hpc-toolkit-release-notes.html)  

* [Get Started with the Intel® oneAPI Base Toolkit for Linux*](https://software.intel.com/content/www/us/en/develop/documentation/get-started-with-intel-oneapi-base-linux/top.html)  
* [Get Started with the Intel® oneAPI Base Toolkit for Windows*](https://software.intel.com/content/www/us/en/develop/documentation/get-started-with-intel-oneapi-base-windows/top.html)  
* [Get Started with the Intel® oneAPI HPC Toolkit for Linux*](https://software.intel.com/content/www/us/en/develop/documentation/get-started-with-intel-oneapi-hpc-linux/top.html)  
* [Get Started with the Intel® oneAPI HPC Toolkit for Windows*](https://software.intel.com/content/www/us/en/develop/documentation/get-started-with-intel-oneapi-hpc-windows/top/before-you-begin.html)  
* [Intel® Performance Libraries for oneAPI](https://software.intel.com/content/www/us/en/develop/tools/performance-libraries.html)  
  1. Intel® oneAPI Math Kernel Library  
  2. Intel® Integrated Performance Primitives  
  3. Intel® oneAPI Threading Building Blocks  
  4. Intel® oneAPI Data Analytics Library  
  5. [Intel® MPI Library](https://software.intel.com/content/www/us/en/develop/tools/oneapi/components/mpi-library.html)

* [Intel® Parallel Studio XE and oneAPI Toolkits Supported and Unsupported Product Versions](https://software.intel.com/content/www/us/en/develop/articles/intel-parallel-studio-xe-supported-and-unsupported-product-versions.html) 


Installation
* [Intel® oneAPI Toolkits Installation Guide for Linux* OS](https://software.intel.com/content/www/us/en/develop/documentation/installation-guide-for-intel-oneapi-toolkits-linux/top.html)  
* [Installing Intel® oneAPI Toolkits via APT](https://software.intel.com/content/www/us/en/develop/articles/installing-intel-oneapi-toolkits-via-apt.html) 


Compiler
* [Intel® C++ and Fortran Compilers Redistributable Libraries by Version](https://software.intel.com/content/www/us/en/develop/articles/intel-compilers-redistributable-libraries-by-version.html)  
* [Intel® Fortran Compiler for oneAPI Release Notes](https://software.intel.com/content/www/us/en/develop/articles/intel-oneapi-fortran-compiler-release-notes.html#top)  

MPI Libarary
* [Intel® MPI Library Release Notes](https://software.intel.com/content/www/us/en/develop/articles/intel-mpi-library-release-notes.html)  

Others
* [oneAPI-samples for vscode](https://github.com/oneapi-src/oneAPI-samples)  
* [Intel® oneAPI Toolkit Forums](https://software.intel.com/content/www/us/en/develop/tools/oneapi/support.html)  


**pre-install**

- MacOS

  Install Xcode, then go to [developer.apple.com](developer.apple.com) and download Command Line Tools for your Xcode version.

- Windows

  Install latest Visual Studio Community edition  

**install**

```bash  
sudo sh ./<installer>.sh     #launch the GUI Installer as the root 
sh ./<installer>.sh          #launch the GUI Installer as the current user

#default location
/opt/intel/oneapi

C:\Program Files (x86)\Intel\oneAPI
```

1. install the oneAPI **Base** Toolkit with these options  
    threaded building blocks  
    C++ compiler  
    C++ Library  
    Math Kernal Library  
    (optional) GDB debugger  
2. Install the oneAPI **HPC** toolkit with these options  
    Intel MPI library  
    Intel C++ compiler  
    Intel Fortran compiler  

**env set**

For Intel oneAPI  
- linux  

永久生效：vi /etc/profile or vi ~/.bashrc
```bash
source ~/intel/oneapi/setvars.sh intel64
or
source /opt/intel/oneapi/setvars.sh
```

  临时使用 terminal：  
```bash
source /opt/intel/oneapi/setvars.sh
or
. /opt/intel/oneapi/setvars.sh
or
~/intel/oneapi/setvars.sh
```

- Windows  
  OneAPI command prompt is installed in Start menu. Or run setvars.bat

- MacOS  
```bash
. /opt/intel/oneapi/setvars.sh
```



For the intel parallel studio 2020
```bash
source /opt/intel/compilers_and_libraries_2020.4.304/linux/mpi/intel64/bin/mpivars.sh intel64

or bashrc:
export PATH=$PATH:/opt/intel/compilers_and_libraries_2020.4.304/linux/mpi/intel64/bin
export LD_LIBRARY_PATH=/opt/intel/compilers_and_libraries_2020.4.304/linux/mpi/intel64/lib
```
For the intel parallel studio 2018
```bash
export PATH=$PATH:/opt/intel/impi/2018.0.128/bin64
export LD_LIBRARY_PATH=/opt/intel/impi/2018.0.128/lib64
```

**test**
```bash
mpiicc -o test  test.c
mpirun -r ssh -f mpd.hosts -n <Number of processes>  ./test
```


{{< admonition type=warning title="error and solution" open=true >}}
**Errors like stdio.h isn't found**

be sure you've installed Xcode Command Line Tools.
{{< /admonition >}}

**reference**  
- https://zhuanlan.zhihu.com/p/347913888




### GCC 
* [GCC, the GNU Compiler Collection](https://gcc.gnu.org/)
  [[download]](http://ftp.gnu.org/gnu/gcc/)  
* gfortran supports 95 2003 2008 2018




## CMake
* [CMake Community Wiki](https://gitlab.kitware.com/cmake/community)
* [CMake Documentation](https://cmake.org/cmake/help/latest/index.html#)



## intel Intrinsics  
- [intel SSE，AVX，AVX2，AVX512 IntrinsicsGuide](https://software.intel.com/sites/landingpage/IntrinsicsGuide/#)  














