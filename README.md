# LangChain学习项目

## 项目简介

这是一个用于学习和探索LangChain框架的个人项目。LangChain是一个强大的框架，用于开发由大型语言模型（LLM）驱动的应用程序，提供了连接各种工具和服务的能力。

## 安装指南

### 前提条件

- Python 3.8+
- uv (更快的Python包管理器)

### 安装步骤

1. 克隆此仓库:
```bash
git clone https://github.com/aimuch/Learning_LangChain
cd Learning_LangChain
```

2. 安装uv (如果尚未安装):
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

3. 创建并激活虚拟环境:
```bash
uv venv
source .venv/bin/activate  # 在Windows上使用: .venv\Scripts\activate
```

4. 安装依赖:
```bash
uv pip install -r requirements.txt
```

5. 设置环境变量:
```bash
cp .env.example .env
# 编辑.env文件，添加您的API密钥
```

## 使用方法

此项目包含多个演示LangChain不同功能的示例：

- 基本LLM调用
- 提示工程与模板
- 链（Chains）的创建和使用
- 向量存储与检索
- 代理（Agents）的使用

运行示例：
```bash
python examples/<示例文件名>.py
```

## 项目结构

```
.
├── examples/           # 示例代码
├── notebooks/          # Jupyter笔记本
├── src/                # 源代码
├── tests/              # 测试代码
├── .env.example        # 环境变量示例
├── .gitignore          # Git忽略文件
├── requirements.txt    # 项目依赖
└── README.md           # 本文件
```

## 学习资源

- [LangChain官方文档](https://docs.langchain.com/)
- [LangChain Python SDK](https://python.langchain.com/docs/get_started/introduction)
- [LangChain GitHub仓库](https://github.com/langchain-ai/langchain)

## 许可证

[MIT](LICENSE)
