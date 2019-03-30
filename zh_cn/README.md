# 简体中文文档

## 字体依赖

简体中文版本的文档需要安装以下字体：

* [方正黑体简体](http://www.foundertype.com/index.php/FontInfo/index.html?id=131)
* [方正书宋简体](http://www.foundertype.com/index.php/FontInfo/index.html?id=151)
* [方正仿宋简体](http://www.foundertype.com/index.php/FontInfo/index.html?id=128)
* [方正楷体简体](http://www.foundertype.com/index.php/FontInfo/index.html?id=137)

这些字体可以免费商用。

## 编译

### 准备工作

建议使用 TeX Live 套件。本文档使用 xelatex 编译。首先需要安装需要的字体并运行 `fc-cache -fv` 命令刷新字体缓冲。如果在 Windows 系统上 latex 实在无法找到上面四款字体，你可做下面的尝试：

1. 找到你的 texive 安装路劲，这里我们以 `C:\texlive\2018\` 为例。
2. 打开文件夹 `C:\texlive\2018\texmf-dist\fonts\truetype\`，在此目录下新建一个文件夹 `fangzheng`（名字随意）。
3. 将上述四款字体文件复制到该文件夹中。
4. 运行 `fc-cache -fv`。

### 编译

如果你使用 TeX Live 默认的 TeXworks 编辑器，你需打开 `index.tex` 并选择 xelatex 编译它。如果 xelatex 是最常用的编译器，建议你将它设置为默认的编译器。

如果使用 VS Code 作为编辑器，推荐安装 LaTeX Workshop 插件。你需要设置该插件使用 xelatex 编译。在这个环境中，你可以打开任意一个 tex 文件，然后按 Ctrl + Alt + B 编译。

其他编辑器的使用方法请查阅相关资料。
