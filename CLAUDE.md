# today CLI

Shell 脚本 CLI 工具，管理 ~/daily/YYYY/MM/DD/ 每日工作目录。

## 构建与测试

```bash
bash today        # 直接运行
bash -n today     # 语法检查
```

## 关键约定

- 目录格式：~/daily/YYYY/MM/DD/
- Obsidian 默认不打开，-o 主动开启
- macOS date -v 偏移：正数需 +N，负数 -N，0 不传偏移参数
