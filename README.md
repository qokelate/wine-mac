
# wine for macos

## 安装

### 1. 克隆仓库`git clone https://github.com/qokelate/wine-mac.git`
### 2. 创建链接`ln -sf $PWD/wine-mac/bin/wine-loader /usr/local/bin/` 

## 用法

###  1. `wine-loader <exe文件路径> [exe参数,可选]`

## 示例

```
# 运行win系统命令(注册表)
wine-loader regedit.exe

运行mac电脑里的exe
wine-loader ~/xxx/abc.exe

运行mac电脑里的exe,带参数xyz
wine-loader ~/xxx/abc.exe xyz
```


