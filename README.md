# flutter

```bash
# Ignore untracked content of flutter
git config -f .gitmodules submodule.sdk.ignore untracked

# Update flutter
cd /opt/flutter/sdk
git checkout master
git pull origin master
git branch -D stable   # 删除老的stable分支
flutter channel stable # 自动创建stable分支
flutter channel        # 查看是否切换到stable分支
```

