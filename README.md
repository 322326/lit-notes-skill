# lit-notes

Zotero论文 → Obsidian结构化文献笔记，一键生成6文件笔记包。

## 产出结构

```
{论文标题}/
├── 01_总览.md              ← 导航枢纽，串联所有子笔记
├── 02_快速摘要.md          ← 300字极简概览
├── 03_精读笔记.md          ← 七段式深度精读
├── 04_分主题笔记/          ← 按论文主题拆分（2-5篇）
├── 05_论文复现.md          ← 仿真+实验可操作复现指南
└── 06_思维导图.md          ← Xmind可直接导入的Markdown大纲
```

## 安装

将此仓库克隆到 Cowork 的 skills 目录：

```bash
git clone https://github.com/{your-username}/lit-notes-skill.git
```

或直接将 `SKILL.md` 复制到 `{skills目录}/lit-notes/SKILL.md`。

## 使用

在 Cowork 中说：
- "精读这篇文献"
- "把zotero文件夹下的论文整理成笔记"
- "整理文献笔记到obsidian"

## 迭代

每次遇到新论文类型（综述/英文/特殊学科），更新 SKILL.md 后用 `overwrite: true` 保存即可，skill 会随使用越来越准。
