> 学习过程记录

# 1. 资源

主站：[动手学深度学习](http://zh.d2l.ai)

视频：[B站](https://space.bilibili.com/209599371/channel/detail?cid=23541)

测试环境：

# 2. 预备知识

## 2.1 环境搭建

##### 第一步 下载[Miniconda](https://docs.conda.io/en/latest/miniconda.html)

```
~ sh Miniconda3-latest-Linux-x86_64.sh
~ source ~/.bashrc
```

附：

> The following packages are included in this distribution that relate to cryptogr
> aphy:
>
> openssl
>     The OpenSSL Project is a collaborative effort to develop a robust, commercia
> l-grade, full-featured, and Open Source toolkit implementing the Transport Layer
>  Security (TLS) and Secure Sockets Layer (SSL) protocols as well as a full-stren
> gth general purpose cryptography library.
>
> pycrypto
>     A collection of both secure hash functions (such as SHA256 and RIPEMD160), a
> nd various encryption algorithms (AES, DES, RSA, ElGamal, etc.).
>
> pyopenssl
>     A thin Python wrapper around (a subset of) the OpenSSL library.
>
> kerberos (krb5, non-Windows platforms)
>     A network authentication protocol designed to provide strong authentication 
> for client/server applications by using secret-key cryptography.
>
> cryptography
>     A Python library which exposes cryptographic recipes and primitives.
>    
> Miniconda3 will now be installed into this location:
> /home/renz/miniconda3
>
> \# To activate this environment, use
> \#
> \#     $ conda activate gluon
> \#
> \# To deactivate an active environment, use
> \#
>
> \#     $ conda deactivate

##### 第二步 下载实验代码：

```
~ mkdir d2l-zh && cd d2l-zh
~ curl https://zh.d2l.ai/d2l-zh-1.0.zip -o d2l-zh.zip
~ unzip d2l-zh.zip && rm d2l-zh.zip
```

##### 第三步 使用conda创建虚拟环境

配置清华PyPI镜像：

```
~ pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
```

```
~ conda env create -f environment.yml
```

##### 第四步 激活虚拟环境

```
~ conda activate gluon
```

##### 第五步 打开Jupyter记事本

```
~ jupyter notebook
```

## 2.2 数据操作

### 2.2.1 NDArray

> 导入ndarray模块、创建NDArray实例、reshape、运算（+、-、*、/、exp、矩阵乘法）、连结

### 2.2.2 广播（broadcasting）

### 2.2.3 索引（index）

### 2.2.3 运算的内存开销

## 2.3 自动求梯度

# 3. 深度学习基础

## 3.1 线性回归

## 3.2 线性回归从零开始实现

## 3.3 线性回归的简洁实现

## 3.4 softmax回归

