# 芙莉莲 · 浮空魔导书桌宠

[English](README.en.md) | 简体中文

一个以芙莉莲为灵感、手持浮空魔导书的 Codex 桌宠。它采用 v2 精灵表格式，包含待机、移动、挥手、跳跃、等待、失败、阅读/工作和 16 向视线跟随动画。

> 这是非官方粉丝创作，与《葬送的芙莉莲》的作者、出版社、动画制作委员会及 OpenAI 均无隶属、赞助或背书关系。使用前请阅读 [素材与版权说明](ASSET_NOTICE.md)。

![全部动画状态](previews/all-states.gif)

## 特性

- 11 行 × 8 列、单格 192 × 208 px 的 RGBA PNG
- 共 73 个有效动画帧
- 9 类动画状态与 16 个视线方向
- 透明背景，无残留色键像素
- v2 精灵表尺寸为 1536 × 2288 px

## 安装

GitHub 会过滤 `codex://` 自定义协议，因此安装地址无法在 README 中直接点击。请复制下面的完整地址：

```text
codex://pets/install?name=Frieren&imageUrl=https%3A%2F%2Fraw.githubusercontent.com%2Fkinster-123%2FFrieren-Codex-pet%2Fmain%2Ffrieren-floating-book-spritesheet-v2.png&description=Frieren%20with%20a%20floating%20spellbook&spriteVersionNumber=2
```

然后使用下列任一方式打开：

- Windows：按 `Win + R`，粘贴地址并按回车；也可以在 PowerShell 中运行 `Start-Process '<复制的地址>'`。
- macOS：在终端中运行 `open '<复制的地址>'`。

Codex 将打开桌宠安装确认页。安装后前往 `Settings > Pets` 选择 `Frieren`，再输入 `/pet` 显示桌宠。如果系统没有响应，请先更新桌面应用并确认 Pets 功能已开放。

该地址使用公开的 GitHub Raw HTTPS 精灵图和 `spriteVersionNumber=2`。也可以[单独下载精灵图](https://raw.githubusercontent.com/kinster-123/Frieren-Codex-pet/main/frieren-floating-book-spritesheet-v2.png)。参数详情见 [OpenAI 官方深链接说明](https://learn.chatgpt.com/docs/reference/commands#pets)。

## 手动使用

兼容 Codex v2 精灵表的桌宠加载器可以直接使用 [`frieren-floating-book-spritesheet-v2.png`](frieren-floating-book-spritesheet-v2.png)，并将精灵版本设置为 `2`。

## 文件

```text
.
├── frieren-floating-book-spritesheet-v2.png  # 最终精灵表
├── previews/all-states.gif                    # 动画总览
├── README.md                                  # 中文说明
├── README.en.md                               # English documentation
└── ASSET_NOTICE.md                            # 素材与版权说明
```

## 版权

本仓库不附带可将角色形象用于商业用途的授权，也不以开源许可证重新许可第三方知识产权。详情见 [ASSET_NOTICE.md](ASSET_NOTICE.md)。
