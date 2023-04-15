# **Windows**

## **1. 查看自己显卡信息**

<img src="./images/nvidia.png">

## **2. 查看最高可以选择的CUDA版本**

```
打开命令行终端, 输入nvidia-smi
下载的CUDA版本应该尽量小于等于12.1
```

<img src="./images/nvidia_smi.png">

#### **2.1 在命令行输入nvidia-smi终端提示如下**

```
'nvidia-smi' 不是内部或外部命令，也不是可运行的程序


# 解决方案
添加环境变量，C:\Program Files\NVIDIA Corporation\NVSMI
```

#### **2.2 NVIDIA Corporation文件夹下没有NVSMI这个文件夹**

```
# 解决方案
将help/resources/NVSMI.zip文件夹复制到NVIDIA Corporation文件夹下，并且解压
```