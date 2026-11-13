# 安装教程

## 安装前确认

本 Skill 的目录中应包含：

```text
mine-cross-border-private-projects/
├── SKILL.md
├── agents/
│   └── openai.yaml
├── assets/
│   └── icon.svg
└── references/
    └── methodology.md
```

不要只下载 `SKILL.md`，否则会缺少 TikTok 竞争评分方法和界面配置。

## 方法一：ChatGPT 上传 ZIP

1. 打开仓库右侧的 **Releases**。
2. 进入最新版本。
3. 下载名称类似 `mine-cross-border-private-projects-v1.0.0.zip` 的附件。
4. 在 ChatGPT 中打开 **Plugins → Skills**。
5. 选择 **Create → Upload from computer**。
6. 上传 ZIP。
7. 查看 Skill 名称、说明和文件列表，确认来源可信后安装。

安装完成后，在输入框输入 `@`，选择“跨境私域项目挖掘”。

如果当前账号或工作区没有上传入口，可能是产品权限或管理员设置限制；可以改用 Codex 安装。

## 方法二：让 Codex Skill Installer 安装

在 Codex 中输入：

```text
$skill-installer

请从下面的 GitHub 地址安装 Skill：
https://github.com/wukaikai586-bit/cross-border-private-project-miner/tree/main/skill/mine-cross-border-private-projects
```

安装后可显式调用：

```text
$mine-cross-border-private-projects
```

## 方法三：手动安装到 Codex

克隆仓库：

```bash
git clone https://github.com/wukaikai586-bit/cross-border-private-project-miner.git
```

将 Skill 文件夹复制到个人 Skill 目录：

```bash
mkdir -p "$HOME/.agents/skills"
cp -R cross-border-private-project-miner/skill/mine-cross-border-private-projects \
  "$HOME/.agents/skills/"
```

也可以放进某个项目的：

```text
项目根目录/.agents/skills/
```

这样它只对该项目生效。

## 更新

### ZIP 用户

下载新版本 ZIP，重新上传或替换旧版本。

### Git 用户

```bash
cd cross-border-private-project-miner
git pull
cp -R skill/mine-cross-border-private-projects "$HOME/.agents/skills/"
```

## 卸载

在 ChatGPT 的 Skills 页面卸载，或删除 Codex 中对应的：

```text
$HOME/.agents/skills/mine-cross-border-private-projects
```
