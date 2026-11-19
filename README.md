# core-econ-macro

配合 CORE Econ 宏观教材学习的中文 Agent Skill。可以输入一组数据，请助手检查统计口径、复算模型并解释假设，也可以按单元出题，作答后再批改。入口见 [SKILL.md](SKILL.md)。

## 安装到 Codex

在终端运行以下命令。需要 Git，技能本身只使用 Markdown。若目标目录已存在，请先检查现有版本。

```sh
mkdir -p "${CODEX_HOME:-$HOME/.codex}/skills"
git clone https://github.com/slevin17f/core-econ-macro.git "${CODEX_HOME:-$HOME/.codex}/skills/core-econ-macro"
```

在新会话中输入：

> $core-econ-macro 失业率下降，但就业人数持平。给我一组能解释这个现象的数据，让我先算就业率与劳动参与率，再批改我的推理。

## 教材与署名

学习参考为 The CORE Econ Team (2025), *The Economy 2.0: Macroeconomics*，出版方 CORE Economics Education。本项目独立编写中文操作说明与合成练习。原版的图表、互动练习及正文请在出版方网站阅读。[原书目录](https://books.core-econ.org/the-economy/macroeconomics/0-3-contents.html) · [引用格式](https://books.core-econ.org/the-economy/macroeconomics/0-5-note-to-instructors.html#how-to-cite-the-economy-20-macroeconomics)

教材版权及使用条件见 [出版方版权页](https://books.core-econ.org/the-economy/macroeconomics/0-2-copyright.html)与 [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)。
