# Hermes Agent 配置指南

## 基本配置
```bash
hermes config set --global model "deepseek-v4-flash"
hermes config set --global provider "deepseek"
```

## 技能管理
```bash
hermes skills list          # 查看已有技能
hermes skills create name   # 创建新技能
```

## GitHub 配置
```bash
git config --global user.name "buzhidaoa8848-hash"
git config --global credential.helper store
```

## 常用快捷键
| 快捷键 | 功能 |
|--------|------|
| /new    | 新会话 |
| /stop   | 中断 |
| Ctrl+C  | 中断操作 |
