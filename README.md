# Street Lab Poster

一个用于生成高动势都市商业海报的 Codex Skill。它把超低机位鱼眼透视、3D 潮玩或产品主视觉、双色品牌系统、街头笔刷和编辑式信息排版整理成可复用的方法，而不是复制某张参考图的商标与文案。

## 适用场景

- 从参考海报提取可复用的色彩、构图、镜头和排版语言
- 为角色、潮玩、服饰、产品或活动编译图像生成提示词
- 生成 3:4 竖版品牌主视觉及后期排版计划
- 在保持风格骨架的同时替换主题、品牌色、文案和画幅

## 安装

将仓库克隆到 Codex skills 目录：

```bash
git clone https://github.com/wuchangcheng0829-max/poster-skill.git ~/.codex/skills/street-lab-poster
```

## 使用

```text
用 $street-lab-poster 为我的潮流运动鞋做一张蓝橙配色的 3:4 都市广告海报，标题是“向前一步”。
```

```text
用 $street-lab-poster 分析这张参考图，只提取镜头、色彩、构图和排版系统，不复制其中的商标与角色。
```

技能默认先整理视觉方向和最终英文提示词；用户要求生成图片时，再调用宿主环境提供的图像生成能力。

## 文件结构

```text
SKILL.md                         技能入口、工作流和约束
agents/openai.yaml              Codex 界面信息
references/style-system.md      风格系统与构图规则
references/prompt-recipes.md    提示词模板、负面词与排版计划
```
