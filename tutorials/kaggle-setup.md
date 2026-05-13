# Kaggle 环境搭建

## 安装
```bash
pip install kaggle
kaggle competitions list  # 验证安装
```

## API 认证
1. Kaggle网站 → Account → Create API Token
2. 下载 kaggle.json 到 ~/.kaggle/
3. chmod 600 ~/.kaggle/kaggle.json

## 常用命令
```bash
kaggle competitions download <name>
kaggle kernels pull <author>/<notebook>
```

## 金融数据集推荐
| 比赛 | 类型 | 适合学习 |
|------|------|----------|
| Home Credit | 信贷违约 | LightGBM/XGBoost |
| Porto Seguro | 保险风险 | CatBoost |
| Jane Street | 量化交易 | 时序模型 |
