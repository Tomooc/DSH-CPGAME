# DSH-CPGAME

工作区仓库，同时关联两个远程：

| 远程名 | 平台 | 地址 |
| --- | --- | --- |
| `origin` | Gitee（主推送） | https://gitee.com/Tomooc/dsh-cpgame.git |
| `github` | GitHub（镜像） | https://github.com/Tomooc/DSH-CPGAME.git |

## 常用命令

```bash
git push origin main      # 推 Gitee
git push github main      # 推 GitHub
git push both main        # 一次推两边（已配置别名）
git pull origin main
git remote -v
```

## 初始化记录

- `git init -b main`
- 远程 `origin` = Gitee，`github` = GitHub；两边初始均为空仓库，首个提交直接推送，无需合并。

## 说明

- 默认分支：`main`
- 提交身份：`Tomooc <weidu_andan@163.com>`（全局配置）
- 凭据由 Git Credential Manager 2.9.1 托管，HTTPS 推送首次会弹一次登录。
