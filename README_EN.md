<div align="center">

# 🖼️ Image Inspirer.skill

<br>

> **668+ battle-tested GPT-Image2 image prompt case library, covering 13 major categories — your inspiration source and creative reference for AI image generation**

[![License: Apache-2.0](https://img.shields.io/badge/License-Apache--2.0-orange.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>

**Struggling with image prompts?** <br>
**Can't find reliable examples anywhere?** <br>
**All the inspiration you need is right here.**

<br>

More than just prompt templates — a **battle-tested creative methodology**. <br>
Every case comes with a finished image reference, so you can see it, learn it, and adapt it.

---

**Quick Navigation**

[Demos](#demos) | [Installation](#installation) | [Category Stats](#category-stats) | [Featured Cases](#featured-cases) | [Repository Structure](#repository-structure) | [Pitfall Guide](#pitfall-guide) | [About Me](#about-me)

<br>

**Languages**

[中文](README.md) · [日本語](README_JA.md) · [한국어](README_KO.md) · [Español](README_ES.md)

<br>

</div>

---

## Demos

### Scenario 1: Search & Reuse

Already know what you need? Search for case references directly:

```
User      ❯ Any examples of infographic visualization?

image-inspirer  ❯ Reading 图表与信息可视化/prompt.md, found 55 infographic cases

                  【Case 1】Urban Metabolism Atlas
                  Type: Infographic | Ratio: 9:16

                  城市生命系统图谱 / Urban Metabolism Atlas
                  Vertical 9:16 isometric cutaway infographic "城市生命系统图谱"。
                  Smart city from sky to bedrock: skyscrapers, streets, subway...
                  Style: engineering white paper + scientific atlas, 8K.

                  【Case 2】AI Neural Network Diagram
                  ...
```

### Scenario 2: Vague Needs, Guided Discovery

Not sure what you want? I'll help you figure it out:

```
User      ❯ Give me a nice image

image-inspirer  ❯ Launching inspiration framework, asking one by one:

                  Q1: What type do you want?
                  → Poster / Photography / Illustration / UI / Other

                  Q2: What's the use case?
                  → Social media / E-commerce / Personal collection / Business proposal

                  Q3: Style preference?
                  → Photorealistic / Cinematic / Minimalist / Illustration / Chinese aesthetic

                  Based on your answers, I'll provide 2-3 directions to explore.
```

### Scenario 3: Custom Creation, Template + Case

Clear requirements but need a custom prompt:

```
User      ❯ Design a brand poster for "AI之道" tech company

image-inspirer  ❯ Reading 海报与排版/prompt.md for brand poster cases
                  ↓ Custom creation

                  Generate a premium AI tech company brand poster, vertical 9:16.
                  Logo: Bagua-Taiji fused with neural network, pure black lines + cyan glow
                  Title: "AI之道" (Song typeface, ultra-light weight)
                  Subtitle: "Dao of Artificial Intelligence"
                  Colors: Pure white background + pure black + cyan accent
                  Style: Minimalist, generous negative space, premium feel
                  Constraint: Text must be clearly readable, no neon effects
```

### Scenario 4: Sports Brand Poster

```
User      ❯ Generate a sports brand commercial poster with a sense of power

image-inspirer  ❯ Reading 海报与排版/prompt.md for sports poster cases

                  Design a sports brand commercial Campaign poster.
                  Subject: Athlete/muscular male, power pose.
                  Key prop: Dumbbell/boxing gloves, exaggerated proportions as visual anchor.
                  Headline: "BREAK THE LIMIT"
                  Visual style: Premium sports brand ad, dramatic lighting, reflective floor.
                  Constraints: Subject sharp, text readable, unified tone.
                  Output: 4:5, sports commercial visual optimized for social media.
```

---

## Installation

### Method 1: CLI (for developers)

Install directly with npx:

```bash
npx skills add wukongnotnull/image-inspirer
```

After installation, tell your Agent:

```markdown
> Find infographic visualization examples
> Generate a Chinese-style poster prompt
> Give me a nice image
```

### Method 2: Conversational (for non-developers)

Copy this to your Agent:

```bash
Install this skill: https://github.com/wukongnotnull/image-inspirer
```

---

## Category Stats

| Category | Count | Description |
|----------|:-----:|-------------|
| UI & Interface | 122 | App UI, web pages, livestream screenshots, components |
| Posters & Layout | 91 | Commercial posters, movie posters, event posters, covers |
| Other Applications | 82 | Creative composites, fun scenarios, crossover mashups |
| Illustration & Art | 78 | Anime, Chinese ink, watercolor, doodle, sci-fi |
| Infographics & Data Viz | 76 | Infographics, flowcharts, exploded diagrams, data visualization |
| Photography & Realism | 55 | Portraits, product photography, fashion editorials |
| E-commerce & Products | 54 | Product hero images, detail pages, product ads |
| Characters & Roles | 36 | Character design, cards, action breakdowns |
| Branding & Logos | 21 | Logo design, brand visuals, icon fonts |
| Architecture & Space | 17 | Interior design, architectural renders, city scenes |
| Scenes & Narrative | 14 | Cinematic scenes, story frames, storyboards |
| Historical & Ancient Styles | 13 | Dynastic styles, historical figures, Chinese chic |
| Documents & Publications | 9 | Magazine layouts, menus, newspapers, textbooks, notes |

**Total: 668 battle-tested cases, each with a finished image reference**

---

## Featured Cases

### 🖥️ UI & Interface

| Case | Description | Highlight |
|------|-------------|-----------|
| App Screenshots | iOS/Android app UI design | Clear platform + ratio + layout |
| Social Media Screenshots | Social posts, profile page design | Realistic UI simulation |
| Landing Pages | Product landing page design | Clear information hierarchy |

### 📊 Infographics & Data Viz

| Case | Description | Highlight |
|------|-------------|-----------|
| Urban Metabolism Atlas | Isometric cutaway infographic | Engineering white paper style |
| Flowcharts & Comparisons | Data comparison visualization | Clean logic, color-coded |
| AI Neural Network Diagram | Technical concept visualization | Complex ideas made intuitive |

### 🎨 Posters & Layout

| Case | Description | Highlight |
|------|-------------|-----------|
| Commercial Campaign | Brand marketing visuals | Sharp subject, readable text |
| Movie Posters | Film promotional visuals | Strong atmosphere, refined composition |
| Chinese Chic Posters | Chinese-style commercial visuals | Traditional elements modernized |

### 📸 Photography & Realism

| Case | Description | Highlight |
|------|-------------|-----------|
| Portrait Photography | Character portrait shots | Realistic skin texture |
| Product Photography | Commercial product shots | Refined lighting, accurate materials |
| Scene Photography | Atmospheric space photography | Cinematic lighting |

### 🎭 Illustration & Art

| Case | Description | Highlight |
|------|-------------|-----------|
| Japanese-style Illustration | Anime-style characters | Locked-in brush style, avoids plastic look |
| Chinese-style Illustration | Traditional Chinese aesthetics | Ink/gongbi/rich color |
| Flat Illustration | Modern minimalist style | Clean color blocks, clear layers |

---

## Repository Structure

```
image-inspirer/
├── README.md                    # Docs + pitfall guide
├── SKILL.md                     # Skill definition
├── db/
│   ├── UI与界面/                # prompt.md + images/
│   ├── 图表与信息可视化/         # prompt.md + images/
│   ├── 海报与排版/              # prompt.md + images/
│   ├── 商品与电商/              # prompt.md + images/
│   ├── 品牌与标志/              # prompt.md + images/
│   ├── 建筑与空间/              # prompt.md + images/
│   ├── 摄影与写实/              # prompt.md + images/
│   ├── 插画与艺术/              # prompt.md + images/
│   ├── 人物与角色/              # prompt.md + images/
│   ├── 场景与叙事/              # prompt.md + images/
│   ├── 历史与古风题材/           # prompt.md + images/
│   ├── 文档与出版物/             # prompt.md + images/
│   └── 其他应用场景/             # prompt.md + images/
└── LICENSE
```

13 category directories, each containing `prompt.md` (prompt collection) and `images/` (finished images).

---

## Pitfall Guide

### General Principles

| Principle | Description |
|-----------|-------------|
| Clear Type | Clearly define: poster / UI / photography, etc. |
| Specific Subject | Describe the specific person/object/scene, avoid vagueness |
| Locked-in Style | Explicitly specify: illustration / photographic / cinematic |
| Complete Parameters | Include ratio, resolution, composition and other key parameters |
| Readable Text | If text is needed, explicitly require it to be clearly readable |

### Key Points by Type

| Type | Focus | Common Pitfalls |
|------|-------|-----------------|
| UI | Clear platform + ratio + layout | Vague instructions cause layout chaos |
| Poster | Specific hero visual, lock in title/subtitle | Blurry text, layout errors |
| Photography | Add skin texture, film grain | AI plastic look, overly smooth |
| Illustration | Lock in brush style | Default plastic look, style drift |
| E-commerce | Product prominence + realistic lighting | Product distortion, inconsistent lighting |
| Logo | Recognizability + scalability | Overly complex, not scalable |

---

## About Me

**悟空非空也 (wukongnotnull)** — Founder of AI之道 (Way to AI), indie developer, content creator.

| Platform | Link |
|----------|------|
| 🌐 Website | [waytoai.cn](https://waytoai.cn) |
| 𝕏 Twitter | [@wukongnotnull](https://x.com/wukongnotnull) |
| 📺 Bilibili | [悟空非空也](https://space.bilibili.com/456634391) |
| ▶️ YouTube | [悟空非空也](https://www.youtube.com/@wukongnotnull) |
| 📕 Xiaohongshu | [悟空非空也](https://www.xiaohongshu.com/user/profile/5ca89c2f000000001100952b) |
| 💬 WeChat | Search "悟空非空也" |

---

## Acknowledgements

Materials partially sourced from:

- [YouMind](https://youmind.com/)
- [OpenNana](https://opennana.com/)
- [awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2)

---

<div align="center">

Apache-2.0 license © [悟空非空也](https://github.com/wukongnotnull)

</div>
