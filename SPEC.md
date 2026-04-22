# SPEC.md - 项目规格说明书

## 1. 项目概述

- **项目名称**: test-txt2mysql
- **项目类型**: other（数据处理项目）
- **项目描述**: Python 脚本读取 txt 数据文件并导入 MySQL 数据库。包含 USNewsDATA 和 qsDATA 两个数据目录。

## 2. 技术栈

- Python
- MySQL Connector

## 3. 项目结构

```
test-txt2mysql/
├── qsDATA/                 # qs 数据目录（183个txt文件）
├── USNewsDATA/             # USNews 数据目录（144个txt文件）
├── dataSample/              # 示例数据
│   ├── demo1USNews.py      # USNews 数据处理脚本
│   └── demo2qs.py          # qs 数据处理脚本
├── README.md               # 项目说明
├── LICENSE                 # 许可证
└── .gitignore              # Git 忽略配置
```

## 4. 核心功能

- 读取 txt 格式数据文件
- 数据解析和清洗
- 批量导入 MySQL 数据库

## 5. 验证运行

Python 脚本项目，直接运行 python 脚本即可。

## 6. Git 状态

- 仓库状态: clean
- 分支: main