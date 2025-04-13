# 📦 smpb

一个简单的 博客生成器，生成静态html文件

## ✨ 特性

- 🚀 简洁易用的命令行接口
- 📂 支持文件输入或标准输入
- ⚙️ 易于扩展和集成

## 📦 安装

使用 npm 或 yarn 安装：

```bash
npm install -g smpb
# 或
yarn global add smpb
```

或者使用 `npx` 运行（无需安装）：

```bash
npx smpb
```

## 🛠 使用方法
进入markdown文件所在目录，执行以下命令
```bash
smpb [选项]
```

### 示例

```bash
smpb build
```

### 可用选项

| 选项            | 描述           |
|-----------------|----------------|
| build  | 将命令执行目录下所有markdown文件编译为html文件   |
| publish | Todo: 将命令执行目录下所有html文件发布到服务器网站静态文件夹 |
| `-v, --version` | 显示版本信息   |
| `-h, --help`    | 显示帮助信息   |

## 📁 项目结构

```
.
├── cli/
│   └── index.js       # CLI 入口文件
├── package.json
└── README.md
```

## 🧑‍💻 开发

克隆仓库并安装依赖：

```bash
git clone https://github.com/doesntit/smpb.git
cd smpb
npm install
```

运行 CLI：

```bash
node cli/index.js [参数]
```

## 📄 许可证

MIT License © ALec Liu
