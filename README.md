# awesome-vscode
🎨 A curated list of delightful VS Code packages and resources.

#### 语法高亮支持
VS Code 支持多种语言的语法高亮和代码片段，安装对应扩展即可。以下是一些常见语言的扩展链接：
- **Arduino**：[点击安装](https://marketplace.visualstudio.com/items?itemName=vsciot-vscode.vscode-arduino)
- **CMake**：[点击安装](https://marketplace.visualstudio.com/items?itemName=twxs.cmake)
- **Dockerfile**：[点击安装](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
- **Python**：[点击安装](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- **JavaScript**：[点击安装](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- 更多语言支持，请查看 [VS Code 扩展商店](https://marketplace.visualstudio.com/vscode)。

---

#### 从其他编辑器迁移
VS Code 提供了快捷键映射，方便从其他编辑器切换过来：
- 从 **Vim** 迁移：[Vim 模式扩展](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)
- 从 **Atom** 迁移：[Atom 快捷键扩展](https://marketplace.visualstudio.com/items?itemName=ms-vscode.atom-keybindings)
- 从 **Sublime Text** 迁移：[Sublime 快捷键扩展](https://marketplace.visualstudio.com/items?itemName=ms-vscode.sublime-keybindings)

---

#### 与特定技术配合使用
微软提供了专门的教程合集，用于指导如何用 VS Code 配合特定技术开发，访问 [vscode-recipes](https://github.com/Microsoft/vscode-recipes) 获取更多内容。

---

#### 代码质量（Lint 和 IntelliSense）
VS Code 默认支持代码检查（Lint）和智能提示（IntelliSense），无需额外安装扩展。你可以查看官方文档的 [语言支持部分](https://code.visualstudio.com/Docs/languages/overview) 了解更多。

---

#### 语言扩展推荐

- **Bash**：[Bash IDE](https://marketplace.visualstudio.com/items?itemName=mads-hartmann.bash-ide-vscode)（支持代码补全、调试等功能）
- **C++**：[C/C++ 扩展](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)
- **Java**：[Java 支持扩展](https://marketplace.visualstudio.com/items?itemName=redhat.java)
- **Markdown**：[Markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)（支持 Markdown 格式检查）
- **PHP**：[PHP Tools](https://marketplace.visualstudio.com/items?itemName=DEVSENSE.phptools-vscode)（支持调试、自动补全等）

---

#### 示例：Markdown 支持
- **Markdown All in One**：[功能强大的 Markdown 插件](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
  ![功能示例](https://user-images.githubusercontent.com/10897048/47027336-d8a9ac80-d199-11e8-9836-b8dbc4a97d1a.gif)

以下是内容的简化版，更适合中国人快速理解：

---

### 智能提示 (IntelliSense)
这两个扩展功能略有不同：
- **[PHP Intelephense](https://marketplace.visualstudio.com/items?itemName=bmewburn.vscode-intelephense-client)**：更好的代码补全支持。
- **[PHP IntelliSense](https://marketplace.visualstudio.com/items?itemName=felixfbecker.php-intellisense)**：功能更加全面。

---

### Laravel
推荐扩展：
1. **[Laravel 5 Snippets](https://marketplace.visualstudio.com/items?itemName=onecentlin.laravel5-snippets)**：Laravel 5 快捷代码片段。
2. **[Laravel Blade Snippets](https://marketplace.visualstudio.com/items?itemName=onecentlin.laravel-blade)**：Blade模板代码提示与语法高亮。
3. **[Laravel Model Snippets](https://marketplace.visualstudio.com/items?itemName=ahinkle.laravel-model-snippets)**：快速生成模型代码片段。
4. **[Laravel Artisan](https://marketplace.visualstudio.com/items?itemName=ryannaddy.laravel-artisan)**：在编辑器中执行 Artisan 命令。
5. **[DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)**：支持`.env`文件语法高亮。

---

### Twig
**[Twig Language 2](https://marketplace.visualstudio.com/items?itemName=mblode.twig-language-2)**：支持 Twig 文件的代码高亮与 Emmet。

```json
{
  "emmet.includeLanguages": {
    "twig": "html"
  }
}
```

---

### Smarty
**[Smarty Template Support](https://marketplace.visualstudio.com/items?itemName=aswinkumar863.smarty-template-support)**：支持Smarty模板格式化、代码片段和语法高亮。

---

### 其他扩展
1. **[Format HTML in PHP](https://marketplace.visualstudio.com/items?itemName=rifi2k.format-html-in-php)**：格式化PHP文件中的HTML代码。
2. **[PHP Debug](https://marketplace.visualstudio.com/items?itemName=felixfbecker.php-debug)**：用于调试PHP代码。
3. **[php cs fixer](https://marketplace.visualstudio.com/items?itemName=junstyle.php-cs-fixer)**：PHP代码格式化工具。
4. **[phpcs](https://marketplace.visualstudio.com/items?itemName=ikappas.phpcs)**：PHP代码质量检测。

---

### GitHub 支持
1. **[GitHub](https://marketplace.visualstudio.com/items?itemName=KnisterPeter.vscode-github)**：支持查看项目、问题、文件和创建合并请求。
2. **[GitHub Pull Requests and Issues](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)**：管理 GitHub 的 PR 和问题。

---

### 生产力工具
1. **[Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)**：标记代码行并快速跳转。
2. **[Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)**：本地开发服务器，支持自动刷新。
3. **[REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)**：直接在编辑器内发送HTTP请求。

---

### 美化工具
1. **[Better Align](https://marketplace.visualstudio.com/items?itemName=wwm.better-align)**：对齐代码中的冒号、等号等符号。
2. **[Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.vscode-auto-rename-tag)**：自动重命名HTML/XML标签。

---

### 图标主题
1. **[VSCode Icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)**：丰富的文件图标主题。
2. **[Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)**：流行的 Material Design 图标主题。

