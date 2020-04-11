# EasyConnect-for-ZJU-on-Arch
Enjoy RVPN on Arch Linux! 

A version **NOT** specifically for ZJU can be downloaded from [EasyConnect-767](https://github.com/alk3p/EasyConnect-767).

# Usage

```shell
git clone https://gitee.com/ilovedorothy/EasyConnect-for-ZJU-on-Arch
cd EasyConnect-for-ZJU-on-Arch
sudo pacman -U easyconnect-7.6.3.0.86415-1-x86_64.pkg.tar.xz
sudo cp -r lib /usr/share/sangfor/easyconnect/
```

To make it fast for China users, I push the repo to the Gitee and all the codes above will enable you to download the file from Gitee. It’s a release package so it’s relatively big, around 40M. 

# Build it yourself (not recommended)

If you want to build it yourself, you can check the acknowledgement. It’s a bit complicated so it’s not recommended. 

1. You have to download the original `EasyConnect` package for Ubuntu from [rvpn.zju.edu.cn](rvpn.zju.edu.cn). 
2. Then you can extract the package by `debtap`.
3. Extract the `tar.xz` file. 
4. Errors in `.INSTALL` should be fixed. You may refer it to [EasyConnect-767](https://github.com/alk3p/EasyConnect-767). 
5. After that, the `easyconnect` can be installed via `pacman`. 
6. Later, an old `Harfbuzz` version should be copied to the `EasyConnect` file directory. 
7. Finally the `EasyConnect` should be able to work.

# Acknowledgement

Thanks to [alk3p](https://github.com/alk3p), who did the most work for making EasyConnect compatible on Arch. Thanks for his every reply for my questions. The original package is [EasyConnect-767](https://github.com/alk3p/EasyConnect-767).

Also Thanks to this [link](https://zzzmh.cn/single?id=93), which helps me fix the `Harfbuzz` problem. 

