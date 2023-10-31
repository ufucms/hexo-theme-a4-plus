# hexo-theme-a4-plus

<div align="center">
    模仿A4纸张的一个hexo极简主题。主打一个简洁，体积小，配置少。
</div>

## 👋 如何使用

- 确认已通过命令`hexo init`创建好了文件夹,这里举例你的文件夹名为`website`
- `命令行`进入到`website`文件夹路径下
- **确保 hexo 版本为 v6.3.0 版本**，如果不是请执行命令`npm install hexo@6.3.0`
- 将`website`文件夹下的`_config.yml`文件中将主题设置为 `a4-plus`
- 接下来正式安装`a4-plus`主题

### Git 安装

- 执行命令：`git clone https://github.com/ufucms/hexo-theme-a4-plus.git themes/a4-plus`
- 将`themes/a4-plus/_config.yml.example` 文件复制到`website`文件夹路径下并重命名为`_config.a4-plus.yml`。
- 对主题的所有个性化配置都将在`_config.a4-plus.yml`文件中进行，可按照文件中的注释自行配置修改
- 执行命令：`hexo s` 运行项目查看效果

## ⚠️ 必读配置

首页和文章列表页需要手动生成，执行以下命令即可：

```shell
hexo new page index
hexo new page list
```

## 感谢

本主题是在[hexo-theme-a4](https://github.com/HiNinoJay/hexo-theme-A4)的基础上做了优化和升级，在此也向`hexo-theme-a4`的作者[HiNinoJay](https://github.com/HiNinoJay)表示感谢。
