# 项目创建

本地使用最好创建新的环境：

```shell
conda env create -f etc/environment.yml
conda activate ai
```

本项目的创建过程：

1. 在 Windows10 下安装配置 `jupyter-book`，接着创建一本书 `docs`：

```shell
jupyter-book create docs
```

2. 修改书籍的配置文件 `docs/_config.yml`，并创建 Github Action。
3. 添加主题：

```shell
git clone https://github.com/xinetzone/xin-css.git docs/_static/xin-css
git clone https://github.com/xinetzone/w3css.git docs/_static/w3css
```
