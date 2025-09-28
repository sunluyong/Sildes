## Python 官方安装包
Python 官方网站：[https://www.python.org/](https://www.python.org/)

![](https://cdn.nlark.com/yuque/0/2025/png/87727/1758462108467-91ea2421-5885-4c64-a1eb-7914dcf35ca8.png)

![](https://cdn.nlark.com/yuque/0/2025/png/87727/1758462429652-da0c148c-d7ec-477b-88d2-0974ad5b756f.png)

| **组件名称** | **功能描述** |
| --- | --- |
| Python 解释器 | 这是运行所有 Python 代码的基础。它负责读取、理解并执行 .py 文件中的指令，是将代码变为实际动作的核心。 |
| Python 标准库 | Python 自带的一系列强大模块，无需额外安装即可使用。例如：<br/>+ math：用于数学计算（如平方根、三角函数）。<br/>+ datetime：用于处理日期和时间。<br/>+ csv：用于读写 csv 格式文件。<br/>+ tkinter：用于创建简单的图形用户界面 (GUI)。 |
| pip 工具 | Python 的官方包管理器。可以使用 pip 命令从互联网上的 [PyPI](https://pypi.org/project/pip/) (Python Package Index) 软件仓库中，轻松下载、安装成千上万的第三方库。 |
| IDLE | Python 官方自带的一个轻量级开发工具。它提供了一个代码编辑器和一个交互式窗口，可以方便地编写、运行和测试代码，但不够强大。 |


## 实际写代码还需要安装更多
| **软件** | **作用** | **常见工具** |
| --- | --- | --- |
| IDE | 集成开发环境，编写、调试和运行代码 | PyCharm、VSCode |
| 包管理 | + 虚拟环境管理<br/>+ 安装、更新和卸载项目所需的第三方库 | Anaconda、Poetry、uv |
| Jupyter Notebook | 文档和代码在一起组织的交互式 Python 编程环境 | Jupyter Notebook、JupyterLab |


配置非常复杂

## PyCharm 一次性搞定
PyCharm 官方地址：[https://www.jetbrains.com/pycharm/](https://www.jetbrains.com/pycharm/)

对于新手来说，使用 PyCharm 学习 Python 的核心好处是**一站式的高效学习环境，让你专注于代码本身，而不是工具配置。**

### <font style="color:rgb(27, 28, 29);">1. 语法提示 & 调试功能强大</font>
<font style="color:rgb(27, 28, 29);">这是 PyCharm 作为顶级 IDE 的核心优势，也是对新手最友好的地方。</font>

+ **<font style="color:rgb(27, 28, 29);">语法提示</font>**<font style="color:rgb(27, 28, 29);">：</font>
    - <font style="color:rgb(27, 28, 29);">不需要死记硬背所有函数和方法名，PyCharm 会根据上下文，智能地预测开发者想写什么，并提供精准的补全列表。这能极大减少拼写错误，并帮助开发者快速发现和学习新的函数。</font>
    - <font style="color:rgb(27, 28, 29);">代码还没运行，PyCharm 就会用波浪线标出潜在的语法错误和不规范的写法（比如变量名不符合 PEP 8 规范）。将鼠标悬停在上面，它会给出详细的解释和修改建议。这就像有一个经验丰富的程序员在实时帮你 Code Review，能帮助开发者从一开始就养成专业、规范的编码习惯。</font>

![](https://cdn.nlark.com/yuque/0/2025/png/87727/1758545365079-5ddbb933-a700-4ecd-abcc-ef9d20e77c85.png)

+ **<font style="color:rgb(27, 28, 29);">调试功能</font>**<font style="color:rgb(27, 28, 29);">：</font>
    - <font style="color:rgb(27, 28, 29);">新手最怕程序出错却不知道错在哪，PyCharm 的可视化调试器允许开发者在任意代码行设置“断点”，程序运行到此会自动暂停。程序暂停时，可以清晰地看到每个变量当前的值。</font>
    - <font style="color:rgb(27, 28, 29);">可以控制程序“单步”运行，观察每一步执行后，变量是如何变化的。这对于理解循环、函数调用和复杂的数据处理逻辑，比用 </font>`<font style="color:rgb(87, 91, 95);">print()</font>`<font style="color:rgb(27, 28, 29);"> 语句要直观一万倍。</font>

![](https://cdn.nlark.com/yuque/0/2025/png/87727/1758545958836-d3e63778-1e3a-4121-acda-150ebe3ffac2.png)

### <font style="color:rgb(27, 28, 29);">2. 自带 Python 和包管理工具集成</font>
<font style="color:rgb(27, 28, 29);">PyCharm 解决了新手最头疼的环境配置问题，提供了一站式的解决方案。</font>

+ **<font style="color:rgb(27, 28, 29);">解释器与虚拟环境管理</font>**<font style="color:rgb(27, 28, 29);">：创建新项目时，PyCharm 会引导开发者自动创建一个隔离的“虚拟环境”（venv）。这意味着每个项目都有自己独立的 Python 环境和库，互不干扰，这是专业开发的标准实践。可以在 PyCharm 内部轻松切换不同的 Python 解释器（比如系统安装的 Python、Conda 环境等），管理非常清晰。</font>

![](https://cdn.nlark.com/yuque/0/2025/png/87727/1758545692609-3726b0c8-2363-4f74-a8ac-7ec3f9851835.png)

![](https://cdn.nlark.com/yuque/0/2025/png/87727/1758545771756-ac667530-d668-4b69-a9ea-072fa4fe0605.png)

+ **<font style="color:rgb(27, 28, 29);">图形化的包管理器</font>**<font style="color:rgb(27, 28, 29);">：PyCharm 提供了一个可视化的包管理界面，只需在这个界面里搜索需要的库（如 </font>`<font style="color:rgb(87, 91, 95);">pandas</font>`<font style="color:rgb(27, 28, 29);">, </font>`<font style="color:rgb(87, 91, 95);">requests</font>`<font style="color:rgb(27, 28, 29);">），点击“安装”即可。升级和卸载也同样简单直观，让开发者可以更专注于代码逻辑本身。</font>

![](https://cdn.nlark.com/yuque/0/2025/png/87727/1758545854286-36862d13-9d1d-48f7-9b58-265386ae4bcb.png)

![](https://cdn.nlark.com/yuque/0/2025/png/87727/1758546214827-a06ee60c-956a-4934-b465-86b57eee5470.png)

### <font style="color:rgb(27, 28, 29);">3. 自带 Jupyter Notebook</font>
Jupyter Notebook 有多实用相信不用多说，PyCharm 直接内置而且比网页版的好用非常多

+ **<font style="color:rgb(27, 28, 29);">IDE 内的无缝体验</font>**<font style="color:rgb(27, 28, 29);">：开发者可以在 PyCharm 强大的编辑器中直接创建和编辑 Jupyter Notebook (</font>`<font style="color:rgb(87, 91, 95);">.ipynb</font>`<font style="color:rgb(27, 28, 29);"> 文件)，而无需在浏览器和编辑器之间来回切换。</font>
+ **<font style="color:rgb(27, 28, 29);">享受 IDE 的全部优势</font>**<font style="color:rgb(27, 28, 29);">：在 Notebook 的代码单元格里，开发者依然可以享受 PyCharm 顶级的代码补全、语法检查和代码导航功能。</font>
+ **<font style="color:rgb(27, 28, 29);">可视化调试 Notebook</font>**<font style="color:rgb(27, 28, 29);">：这是最强大的功能！开发者可以像调试普通 Python 脚本一样，在 Notebook 单元格里设置断点进行调试，这是浏览器版 Jupyter 难以做到的。</font>
+ **<font style="color:rgb(27, 28, 29);">便捷的变量查看器</font>**<font style="color:rgb(27, 28, 29);">：可以方便地查看 Notebook 中生成的数据框（DataFrame）和其他变量，体验远超原生 Jupyter。</font>

[此处为语雀卡片，点击链接查看](https://www.yuque.com/sunluyong/okofr7/lw85saqobi29gtpc#uTZfj)

### <font style="color:rgb(27, 28, 29);">4. 自带 Git 版本管理工具</font>
<font style="color:rgb(27, 28, 29);">版本控制是现代软件开发的基石，PyCharm 让新手也能轻松上手。</font>

+ **<font style="color:rgb(27, 28, 29);">开箱即用的版本控制</font>**<font style="color:rgb(27, 28, 29);">：PyCharm 内置了对 Git 的完美支持。开发者无需记忆复杂的 Git 命令，就可以通过点击图形界面中的按钮来完成绝大多数操作。</font>
+ **<font style="color:rgb(27, 28, 29);">直观的差异对比</font>**<font style="color:rgb(27, 28, 29);">：PyCharm 提供了非常强大的“Diff Viewer”，可以清晰地以并排视图显示当前修改了哪些代码，一目了然，这对于检查自己的改动和理解团队成员的代码非常有帮助。</font>

![](https://cdn.nlark.com/yuque/0/2025/png/87727/1758547493035-ae74fcbc-dfd0-4ac1-a11f-d3d14bff7755.png)

### <font style="color:rgb(27, 28, 29);">总结</font>
一句话总结：PyCharm 就像一个为 Python 初学者量身打造的“超级驾驶舱”，它把所有必需的工具都整合在了一起，并用智能化的方式辅助你，让你能更平稳、更快速地从新手成长为熟练的开发者。

## 社区版和 Pro 版区别
之前 PyCharm 提供了免费的社区版和付费的 Pro 版，在 PyCharm 最新版本中（从 **2025.1** 开始），官方做了一些更新，称为 **统一版本（Unified PyCharm）**。

1. 安装 PyCharm 后，新用户会有一个 **30 天免费 Pro 功能试用期**
2. 试用期过后，如果不付费，依然可以免费使用**核心功能**，这些功能大致等同于以前的 Community Edition。
3. 若想继续使用 Pro 的高级功能（Web 框架支持、数据库工具、远程 / 部署 /容器支持等），就需要购买 Pro 订阅。

:::info
学生可以免费使用 Pro 版：

[https://www.jetbrains.com/zh-cn/pycharm/buy/?section=students&billing=yearly](https://www.jetbrains.com/zh-cn/pycharm/buy/?section=students&billing=yearly)

:::

简单来说，免费版本对于 Python 学习而言绰绰有余

| 功能 / 特性 | Community / “核心免费功能” | Professional / Pro（高级功能） |
| --- | --- | --- |
| Python 基本功能（编辑、语法提示、重构、调试、本地运行） |  ✅ | 有✅ |
| 虚拟环境 / 依赖包管理 | 核心功能里包含基础支持 ✅ | 完整支持 ✅ |
| Jupyter Notebook 支持 | 从最近的版本开始被纳入核心免费功能。 | 完整支持 ✅ |
| Web 框架支持 | 不支持 / 支持很有限（社区版不含这类框架的专门模版与集成工具）  | 支持这些 Web 框架，提供模板、调试、部署、网页前端 + 后端整合等功能 ✅ |
| 数据库 / SQL 支持 | 社区版有限支持（SQLite、本地轻量 DB） | 专业版支持多种数据库连接、数据库工具窗口、SQL编辑/调试等 ✅  |
| 前端 / HTML / JavaScript / CSS / Web 技术 | 支持基础文件编辑（HTML, XML, JSON, YAML 等），但集成程度、前端工具支持弱；调试、自动刷新、前端框架等功能欠缺。 | 专业版集成这些功能，在做全栈／Web 项目时更加方便。 ✅  |
| 远程开发 / Docker / SSH /部署 /容器支持 | 基础支持少或没有。 | 专业版提供与服务器、Docker 容器、SSH 部署等高级功能。 ✅  |
| 版本控制系统（VCS）支持 | Git / GitHub 等基本支持 ✅ | 更丰富的 VCS 集成（更多系统 / 更多高级工具） ✅ |


## 为什么初学者不需要 Anaconda
1. **安装包体积较大**：由于包含了大量的库，Anaconda 的安装文件通常有几百 MB 甚至更大，安装后会占用数 GB 的硬盘空间。
2. **主要面向数据科学**：Anaconda 预装的库主要集中在数据科学领域。Python 初学者主要来做一些简单的脚本、网页后端开发或自动化任务，Anaconda 预装的大量科学计算库是多余的。
