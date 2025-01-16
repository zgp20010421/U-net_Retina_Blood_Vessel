# 构建U-net模型分割视网膜分析(添加SENet注意力机制 tensorflow) 
## 项目构建步骤
### 1.获取该项目
从Github的https://github.com/zgp20010421/U-net_Retina_Blood_Vessel.git
```bash
    git clone https://github.com/zgp20010421/U-net_Retina_Blood_Vessel.git
```

### 2.获取该项目的数据集
```bash
    通过网盘分享的文件：archive.zip
    链接: https://pan.baidu.com/s/1VRxX0d66fZysPNh-BNe-2g?pwd=ktcc 提取码: ktcc
```

### 3.创建虚拟环境
```bash
    # 采用python -m
    python -m venv Unet
```

### 4.激活虚拟环境
```bash
    source Unet/bin/activate # Linux
    .\Unet\Scripts\activate # Windows 
```

### 5.下载虚拟环境依赖包
```bash
    pip3 install -r requirement.txt -i https://pypi.tuna.tsinghua.edu.cn/simple #  Linux 
    pip install -r requirement.txt -i https://pypi.tuna.tsinghua.edu.cn/simple #  Windows
```

### 6.配置python kernel
```bash
    python -m pip install --upgrade pip
    python -m ipykernel install --user --name=Unet
```

### 7.通过jupyter notebook打开选择kernel为Unet
```bash
    jupyter notebook
```

