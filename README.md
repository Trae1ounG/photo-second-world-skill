<div align="center">

# 照片之下

### PHOTO SECOND WORLD

把真实照片打开，让同一个场景在另一种世界里继续生长。

**Trae1ounG made**

[English](README.en.md) · [作品示例](#作品示例) · [开始使用](#开始使用)

</div>

![照片之下：真实世界与纸上第二世界在同一条边界相遇](assets/showcase/armor-second-world.webp)

> 照片下面，还藏着另一个世界。

`photo-second-world` 是一个面向 Codex 的图像创作 Skill。它不为照片套统一滤镜，也不在完整原图上堆叠装饰。它先找到画面中不可替代的主体关系，再沿原有轮廓打开一个大面积区域，让同一场景在纸张、版画、压印、剪纸或其他手工材质中继续成立。

现实与想象共享同一套几何，但不再服从同一种视觉现实。

---

## 它如何创作

```text
读取照片 → 保留真实锚点 → 找到结构边界 → 打开第二世界 → 让两侧重新成为一张完整作品
```

- **真实锚点**：保留人物、动物、建筑、地貌或空间关系中最不可替代的部分。
- **结构裂口**：让边界沿水线、屋脊、身体、道路、山脊、阴影或透视自然发生。
- **第二世界**：只选择一种主要材料语言，重新组织裂口另一侧的时间、季节、尺度或质感。
- **连续几何**：主体轮廓和空间方向跨过边界继续，避免两张无关图片的生硬拼接。
- **一眼可见**：重构区域必须足够大，在信息流缩略图中也能直接读出结构变化。

## 作品示例

这些示例仅展示经授权发布的生成结果，不收录用户原始照片。

| 湖面之下 | 历史之中 |
| :---: | :---: |
| <img src="assets/showcase/lake-second-world.webp" alt="湖面下显露深色版画森林" width="440"> | <img src="assets/showcase/history-second-world.webp" alt="现实广场延展为历史版画游行" width="440"> |

| 彩色乐园 | 月夜寺院 |
| :---: | :---: |
| <img src="assets/showcase/theme-park-second-world.webp" alt="主题乐园延展为丝网印刷幻想城市" width="440"> | <img src="assets/showcase/temple-second-world.webp" alt="寺院沿屋脊进入月夜木版画" width="440"> |

| 铠甲山脊 | 狮身人面像 |
| :---: | :---: |
| <img src="assets/showcase/armor-second-world.webp" alt="铠甲沿金色脊柱延展为黑纸山脉" width="440"> | <img src="assets/showcase/sphinx-second-world.webp" alt="狮身人面像跨越现实与古埃及夜色版画" width="440"> |

同一个 Skill 会根据照片自身的结构与色彩选择第二世界，不要求所有作品使用相同画幅、裂口方向或靛蓝配色。

## 开始使用

### 安装

```bash
git clone https://github.com/Trae1ounG/photo-second-world-skill.git
mkdir -p ~/.codex/skills
cp -R photo-second-world-skill/skills/photo-second-world ~/.codex/skills/
```

如果 Skill 没有立即出现，请重启 Codex。

### 调用

上传一张照片，然后输入：

```text
用 $photo-second-world 创作这张照片。
```

也可以补充希望保留的主体或情绪方向，但不需要指定裂口位置、材料与构图；Skill 会从照片本身做出选择。

## 仓库结构

```text
photo-second-world-skill/
├── README.md
├── README.en.md
├── assets/
│   └── showcase/
└── skills/
    └── photo-second-world/
        ├── SKILL.md
        └── agents/
            └── openai.yaml
```

## 隐私与图片

Skill 只把用户提供的图片用于当前生成任务。除非用户明确授权，不应把原始图片保存到项目、上传到其他位置或公开展示。本仓库中的作品图均为用户明确要求发布的生成结果。

<div align="center">

**Trae1ounG made · 照片下面，还藏着另一个世界。**

</div>
