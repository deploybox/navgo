# NavGo

> 收录与 Go 语言相关的项目、软件、工具、框架、插件、类库、教程

## 演示

- 演示网站   
  https://navgo.idev.top
- 本地演示   
  ```sh
  zola serve
  ```

## 使用教程

1. 安装主题

> 在项目根目录下运行：

```sh
# 首次使用（首次从 Git 拉取代码时）
git submodule update --init --recursive

# 拉取当前主题最新代码
git submodule update --remote themes/navhive

# 拉取所有最新主题代码
git submodule foreach git pull origin main
```

2. *图标保存位置（根据 `config.toml` 的 `logosPath` 参数）
```sh
mkdir -p static/assets/images/logos
```

> 可自行将网站的图标保存至此处。可参考 [`.deploy.sh`](.deploy.sh)，通过 API 方式获取图标。

3. 运行本地测试
```sh
zola serve
```

4. 构建项目
```sh
zola build
```

## 仓库镜像

- https://git.jetsung.com/deploybox/navgo
- https://framagit.org/deploybox/navgo
- https://gitcode.com/deploybox/navgo
- https://github.com/deploybox/navgo

## Author

[Jetsung Chan](https://i.jetsung.com)
