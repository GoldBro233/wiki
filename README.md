## 关于如何进行本地部署

首先，从 Github 上克隆整个仓库到本地目录

```
git clone https://github.com/GoldBro233/wiki.git
```

确保自己已经正确安装了 python，要求 python 版本>=3.10

```
python -v
```

之后安装 pip 依赖项

```
pip install -r requirements.txt
```

最后使用 mkdocs 预览网页效果

```
mkdocs serve
```

## 关于如何部署到 Git 仓库

首先使用对应命令由 `pip` 生成对应的 `requirements.txt`

```
pip freeze > requirements.txt
```

之后由对应的 Git 提交流程推送至对应的 Git 仓库