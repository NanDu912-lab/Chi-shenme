# 吃什么 - 今晚吃什么？问问就知道了

一个帮你快速决定吃什么的聊天助手。

## 功能特点

- **智能推荐**：基于对话了解你的需求，推荐 2-3 个方案
- **快速筛选**：预算、人数、方式（自己做/出去吃）一键筛选
- **口味记忆**：记住你的口味偏好，推荐更懂你
- **换一批**：不满意可以重新推荐
- **踩雷反馈**：不想吃的告诉它，后续不再推荐

## 使用方式

### 本地使用
直接双击打开 `index.html` 文件即可使用，无需安装任何依赖。

### 在线访问
- GitHub: https://github.com/NanDu912-lab/Chi-shenme
- GitHub Pages: https://nandu912-lab.github.io/Chi-shenme/

## 技术栈

- 纯 HTML/CSS/JavaScript，无框架依赖
- 通义千问 API（qwen-plus）
- localStorage 本地存储用户偏好

## 项目结构

```
chi-shenme/
├── index.html          # 主应用文件
├── README.md           # 项目说明
├── worker/             # Cloudflare Worker 代码（已弃用）
└── fc-api/             # 阿里云 FC 代码（已弃用）
```

## 开发说明

API Key 已内置在 `index.html` 中，仅用于课程演示。生产环境应通过后端代理调用 API。

## License

MIT
