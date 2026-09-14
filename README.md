# git-unity

Unity 2022.3 渲染 / 技术美术学习项目。

## 项目说明

- 引擎版本：Unity 2022.3 LTS
- 渲染管线：Universal Render Pipeline（URP）
- 用途：练习 Unity 渲染、Shader、技术美术工作流与 Git 版本管理

## 开发环境

- Unity 2022.3.x（通过 Unity Hub 安装）
- Git（含 Git LFS）
- 图形客户端（可选）：SourceTree 或 GitHub Desktop

## 如何打开项目

1. 使用 Unity Hub 打开本仓库根目录（包含 `Assets`、`Packages`、`ProjectSettings` 的目录）
2. 等待 Unity 导入资源完成

## 版本管理配置

本项目已配置以下内容：

- `.gitignore`：忽略 `Library`、`Temp`、`Logs`、`UserSettings`、`*.csproj`、`*.sln` 等自动生成文件
- Git LFS：大文件（`png`、`fbx`、`obj`、`wav`、`mp4` 等）通过 LFS 存储
- Unity 编辑器设置：`Visible Meta Files` + `Force Text`

## 学习进度

- [x] 初始化 Unity 2022.3 URP 项目
- [x] 配置 Git、`.gitignore`、Git LFS
- [ ] 手写 Shader / Shader Graph 练习
- [ ] 二次元 / 卡通渲染角色 demo
- [ ] URP 自定义渲染功能（Render Feature）
- [ ] 移动端性能优化

## 作者

- GitHub：ttq0915
