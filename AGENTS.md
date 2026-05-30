# AGENTS

## Push

`examples/default` 是子模块。每次提交涉及该目录时，需先后执行：

```bash
# 1. 在子模块内推送
git -C examples/default push
# 2. 在父仓库推送
git push
```

如果子模块无新提交，只推送父仓库即可。
