# AI Computing Systems
## Introduction
This repository is the experimental environment for the course `AI Computing Systems` of ShanghaiTech University, 2024 Fall.

This experimental environment  is developed based on the project `oscpu-framework` of [OSCPU](https://github.com/OSCPU).

## Get started
Since Fall 2024, the on-campus remote-desk server will be provided for this course, so no additional package installation is necessary. 

If you're interested in exploring the experimental environments from previous years, a Docker image is available. Please refer to the following instructions for more details.

[Course Docker Image](https://github.com/ColsonZhang/EE219-ICS/blob/2022/doc/tutorial/manual-2.md)

Before exploring the experimental environment, you may need to perform the following minor configurations.

[Instructions for Configuration](doc/manual_1.md)

If you want to learn about the compiling script, you can read the introduction.

[Introduction of the Compiling Script](doc/manual_2.md)

## Directory
```
|-- README.md             # Readme file
|-- build.sh              # Build script file
|-- myinfo.txt            # User information file
|-- demo                  # Folder of demo
|-- doc                   # Folder of documents
|-- projects              # Folder of main projects
```
1. `README.md` is the project's description document.
2. The `build.sh` is a verilator compilation script that greatly simplifies the compilation of verilator. At the same time, this script can record the user's compilation history to avoid faking. **Note: Modification of this script is forbidden!!!**
3. The `myinfo.txt` records the user's personal information, which should be updated in this file first after entering the environment for the first time. The compile script records this information when it records the user's compile history. If personal information is written, the compile script will not work.
4. The directory `demo`, holds demo file to validate the environment setup.
5. The directory `doc`,  holds the relevant documentation and some manuals about RISC-V.
6. The directory `projects`, holds the user's custom project code.
## Contributors
We would like to thank teaching assistants for their contributions to the course.
* [Shen Zhang](https://github.com/ColsonZhang) @ RICL of ShanghaiTech SIST
* [Qixing Zhang](https://github.com/qixingzhang) @ RICL of ShanghaiTech SIST
* [Hongqiao Zhang](https://github.com/zhanghq2) @ CAS4ET of ShanghaiTech SIST
* [Yutao Gong](https://github.com/gongyt1112) @ CAS4ET of ShanghaiTech SIST
* Heng Shi @ CAS4ET of ShanghaiTech SIST
* [Zhaojun Ni](https://github.com/RealJustinNi) @ CAS4ET of ShanghaiTech SIST
* [Zhengkun Yu](https://github.com/yuzhk42) @ CAS4ET of ShanghaiTech SIST
