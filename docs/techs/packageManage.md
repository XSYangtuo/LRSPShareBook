# 包管理器（pip/npm）

## 是什么？
包管理器是用于管理软件包（库、框架、工具等）的工具，可以自动处理依赖关系、版本控制和安装过程。常见的包管理器包括Python的pip和JavaScript的npm。

## 有什么特点？
### pip（Python包管理器）：
1. **Python标准**：Python的官方包管理器，随Python一起安装
2. **PyPI集成**：从Python包索引（PyPI）下载和安装包
3. **依赖管理**：自动处理包的依赖关系
4. **虚拟环境支持**：与venv、virtualenv等虚拟环境工具配合使用
5. **版本控制**：支持安装特定版本的包

### npm（Node.js包管理器）：
1. **Node.js生态**：Node.js的默认包管理器，随Node.js一起安装
2. **npm注册表**：全球最大的软件注册表，包含数百万个包
3. **package.json**：使用package.json文件管理项目依赖和配置
4. **脚本功能**：可以定义和运行自定义脚本
5. **版本管理**：使用语义化版本控制（semver）

## 如何Getting Started？
### pip基本使用：
1. **检查安装**：
   ```bash
   pip --version
   ```

2. **安装包**：
   ```bash
   pip install package_name
   ```

3. **安装特定版本**：
   ```bash
   pip install package_name==1.0.0
   ```

4. **列出已安装包**：
   ```bash
   pip list
   ```

5. **卸载包**：
   ```bash
   pip uninstall package_name
   ```

### npm基本使用：
1. **检查安装**：
   ```bash
   npm --version
   ```

2. **初始化项目**：
   ```bash
   npm init
   ```

3. **安装包**：
   ```bash
   npm install package_name
   ```

4. **安装为开发依赖**：
   ```bash
   npm install package_name --save-dev
   ```

5. **运行脚本**：
   ```bash
   npm run script_name
   ```

## 最佳实践
1. **使用虚拟环境**（Python）：避免全局安装，使用venv创建隔离环境
2. **使用package-lock.json**（npm）：锁定依赖版本，确保一致性
3. **定期更新**：定期更新包以获得安全修复和新功能
4. **检查依赖**：使用`pip check`或`npm audit`检查依赖问题

## 学习资源
- pip官方文档：[https://pip.pypa.io/](https://pip.pypa.io/)
- npm官方文档：[https://docs.npmjs.com/](https://docs.npmjs.com/)
- PyPI：[https://pypi.org/](https://pypi.org/)
- npm注册表：[https://www.npmjs.com/](https://www.npmjs.com/)

*目前内容由ai生成*