# Personal Outfit Coach

一个用中文回答日常穿搭问题的 Codex Skill。它从场合、目标气质和现有衣橱出发，把搭配建议拆成可试穿的选择，并说明哪些条件会让首选和备选换位。

## 原创内容来源

这个 Skill 的穿搭判断框架蒸馏自 B 站 UP 主 **小徐先生的** 的公开视频。参考资料基于本地 ASR 转录，保留了用于说明判断、前提和反例的原文摘录。视频内容和原始观点归原作者，Skill 中对新搭配的应用属于整理者的归纳和推断。 [小徐先生的 B 站主页](https://space.bilibili.com/429829274)

## 使用

把本仓库目录放进 Codex 的 skills 目录，例如 `~/.codex/skills/personal-outfit-coach`。在 Codex 中调用 `$personal-outfit-coach`，发照片或用文字描述现有单品和场合。

- 这件深色印花大衣怎么搭？我想周末去看展穿。
- 我要去见客户，希望显得专业又好接近。这两套怎么选？
- 这条直筒裤搭德比鞋还是慢跑鞋？我可以补一张裤脚和鞋的同框照。
- 我脸偏长窄，怎么一起看刘海、镜框、领口和肩线？

## 文件

- [SKILL.md](SKILL.md) 定义调用场景、判断顺序和回答方式。
- [场合、单品和鞋](references/judgment.md) 说明风格主次和选鞋改判。
- [配色、廓形和材质](references/color-shape-material.md) 说明颜色面积、衣服松量和面料怎样互相影响。
- [脸型、发型与身材](references/face-hair-proportions.md) 说明如何把眉眼、发型、领口和全身比例放在一起判断。
