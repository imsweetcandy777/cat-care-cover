# 猫咪科普封面 · cat-care-cover

根据中文标题或主题生成 3:4 猫咪科普、护理与生活封面的图片生成 Skill。

默认直接添加中文标题，顶部只留约 5%–8% 白色空间，延续暖色圆润大字、写实可爱猫咪与简洁插画的系列风格。用户明确要求时可改用卡通线条插画或生成无字版。

![封面风格参考](assets/reference.png)

## 安装

下载仓库 ZIP，解压后将包含 `SKILL.md` 的整个文件夹放到个人技能目录，并命名为 `cat-care-cover`。默认目录为 `~/.codex/skills/cat-care-cover`；Windows 通常为 `%USERPROFILE%\.codex\skills\cat-care-cover`。若设置了 `CODEX_HOME`，使用该目录下的 `skills` 文件夹。

技能需要运行环境提供图片生成能力；本仓库不包含独立图片生成服务。

## 调用

```text
$cat-care-cover 猫咪牙结石与牙龈炎，专业科普与预防护理指南
```

```text
$cat-care-cover 猫咪疯狂掉毛不用慌｜内外养护安稳度过换毛季，主体使用英长银渐层小猫
```

```text
$cat-care-cover 换季掉毛护理指南，改成干净的卡通线条插画
```

可同时提供猫咪照片、指定副标题、毛色品种或无字版要求。默认交付一张封面图片，具体生成规范见 [SKILL.md](SKILL.md)。

## 文件结构

```text
cat-care-cover/
├── SKILL.md
├── agents/
│   └── openai.yaml
├── assets/
│   └── reference.png
└── README.md
```

参考图用于保持系列风格；新封面会依据新主题替换标题、道具和示意内容。