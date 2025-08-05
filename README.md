### init:

```bash
$ pnpm i hexo -g
$ hexo init <folder>
$ cd <folder>
$ pnpm i
```

### 开发服务器:

```bash
# 普通启动
$ hexo server

# 下载热加载依赖
$ pnpm add hexo-browsersync

# 带热加载启动 (推荐)
$ hexo server --watch
```

初始化结构:

```
├── _config.yml
├── package.json
├── scaffolds
├── source
|   ├── _drafts
|   └── _posts
└── themes
```
