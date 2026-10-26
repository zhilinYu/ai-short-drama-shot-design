# AI短剧镜头语言与情绪编码 Skill (AI Short Drama Shot Design)

🎬 **专为 AI 短剧、漫剧、叙事短视频打造的分镜设计与镜头情绪编码技能库。**

基于「焦距与视角类镜头」和「机位与角度类镜头」的双维情绪编码矩阵，将剧本冲突与角色心理精准转化为导演级镜头语言与 AI 生图 / 生视频提示词（Midjourney, Kling, Seedance, Runway, Sora, Veo 等）。

---

## 📖 核心知识矩阵

### 1. 第一类：焦距与视角类镜头 (Lens & Perspective)

| 镜头名 | AI 提示词常用词 | 情绪编码 | 典型应用场景 |
| :--- | :--- | :--- | :--- |
| **广角镜头** | `wide-angle lens`, `16mm/24mm lens` | **压迫、卷入、临场、宏大、不安** | 狭窄走廊推进、近身打斗、史诗大场面、第一人称追逐、恐怖片密闭空间 |
| **标准镜头** | `standard lens`, `35mm/50mm lens` | **真实、克制、平视、信任、日常** | 双人对话、生活流叙事、纪录片、家庭剧、文艺片日常戏 |
| **中长焦人像镜头** | `medium telephoto lens`, `85mm portrait lens` | **凝视、亲密、暧昧、精致、被审视** | 人物特写、情感独白、暗恋戏、肖像广告、时尚MV |
| **长焦/超长焦镜头** | `telephoto lens`, `135mm/200mm lens` | **宿命、孤立、窥视、史诗、不可抗拒** | 雪原孤行、狙击视角、追逐戏远观、史诗结尾、命运感场面 |
| **鱼眼镜头** | `fisheye lens`, `extreme barrel distortion` | **迷幻、超现实、混乱、青春、极限** | 滑板/冲浪极限运动、迷幻药物体验、梦境、嘻哈MV、儿童视角 |
| **微距镜头** | `macro lens`, `extreme close-up (ECU)` | **精致、私密、被忽视的世界、超细节、感官放大** | 化妆品广告、美食广告、自然纪录片、情绪空镜、产品特写 |
| **移轴镜头** | `tilt-shift lens`, `miniature effect` | **玩具感、上帝视角、抽离、童趣、模型化现实** | 城市俯瞰、节日活动、品牌广告创意片头、节奏明快的MV |

### 2. 第二类：机位与角度类镜头 (Camera Angle & Rigging)

| 镜头名 | AI 提示词常用词 | 情绪编码 | 典型应用场景 |
| :--- | :--- | :--- | :--- |
| **俯拍镜头** | `high-angle shot`, `bird's-eye view` | **渺小、无助、被审视、上帝视角、宿命** | 人物在巨大空间里的孤独感、群体场面俯瞰、悬疑片受害者视角、品牌片宏观叙事 |
| **仰拍镜头** | `low-angle shot`, `worm's-eye view` | **威严、强大、英雄感、压迫、敬畏** | 英雄登场、反派威慑、建筑宏伟感、运动员胜利时刻、领导力品牌片 |
| **荷兰角（倾斜）** | `Dutch angle`, `tilted frame` | **失衡、混乱、精神错乱、危险临近、不安** | 恐怖片心理崩溃、动作片打斗中的眩晕、悬疑片真相揭露、反派出场 |
| **平视镜头** | `eye-level shot`, `neutral angle` | **平等、对话、客观、共情、真实** | 访谈、对话戏、纪录片、人物介绍、真诚向品牌片 |
| **过肩镜头 (OTS)** | `over-the-shoulder shot (OTS)` | **对峙、对话、视角代入、关系张力** | 双人对话戏、谈判戏、对峙戏、采访、约会场景 |
| **主观镜头 (POV)** | `point-of-view shot (POV)` | **代入、临场、紧迫、私密、第一人称体验** | 恐怖片追逐、第一人称游戏化叙事、Vlog、品牌沉浸式体验片 |

---

## 🎯 焦距 × 机位 黄金组合公式

1. **极致压迫 / 霸总反派登场**：`广角镜头 (Wide) + 仰拍镜头 (Low-angle)`
2. **绝境孤立 / 角色无助崩盘**：`长焦镜头 (Telephoto) 或 广角镜头 + 垂直俯拍 (High-angle)`
3. **真相暴击 / 心理崩溃失衡**：`广角或微距 + 荷兰角倾斜 (Dutch Angle)`
4. **博弈拉扯 / 对立谈判**：`中长焦 (85mm) + 过肩镜头 (OTS) 正反打`
5. **惊悚追逃 / 沉浸式开场钩子**：`广角镜头 + 主观视角 (POV)`

---

## 🚀 安装与使用

### 方式 1：用于 Antigravity / Ekko / Agent
将本仓库克隆至你的 Agent Skills 目录：
```bash
git clone git@github.com:zhilinYu/ai-short-drama-shot-design.git ~/.gemini/config/skills/ai-short-drama-shot-design
```

### 方式 2：用于 Claude Code / Cursor / Windsurf
直接将 `SKILL.md` 加入你的 `.cursorrules`、`CLAUDE.md` 或项目分镜提示词规则中。

---

## 📄 License
MIT License
