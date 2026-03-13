<div align="center">

# Awesome Kling AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Stars](https://img.shields.io/github/stars/atlas-cloud/awesome-kling-ai?style=social)](https://github.com/atlas-cloud/awesome-kling-ai)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Last Commit](https://img.shields.io/github/last-commit/atlas-cloud/awesome-kling-ai)](https://github.com/atlas-cloud/awesome-kling-ai)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/atlas-cloud/awesome-kling-ai/pulls)

**🎬 可灵 AI 视频生成终极资源库**

精心整理的可灵 AI 相关资源、工具、提示词、教程和 API 参考——**可灵 AI** 是快手推出的顶尖 AI 视频生成模型。

[EN](./README.md) | [中文](./README_zh-CN.md) | [日本語](./README_ja.md) | [한국어](./README_ko.md)

---

**觉得有用？请 ⭐ 给个 Star 支持一下，帮助更多人发现这个项目！**

</div>

---

> 🚀 **通过 [Atlas Cloud API](https://www.atlascloud.ai?ref=JPM683&utm_source=github&utm_campaign=awesome-kling-ai) 访问全部 20+ 可灵模型** — 无审查、最低价（低至 1.5 折）、最快推理速度。**首充赠送 25% 额度**（最高 $100）。

> 🔒 **企业级安全保障** — Atlas Cloud 已通过 **SOC I & II 认证** | **HIPAA 合规** | 美国公司，提供 99.9% 正常运行时间 SLA。

> 💳 **支付便捷** — 支持微信支付、支付宝直接付款，无需国际信用卡。

> 🎨 **NSFW 白名单更新** — 除 Seedance 和 Kling 外，**Vidu 系列**（Q3-Pro、Q3-Turbo）现已加入 Atlas Cloud 无审查内容生成白名单。

---

## 目录

- [什么是可灵 AI？](#什么是可灵-ai)
- [模型演进时间线](#模型演进时间线)
- [模型对比表](#模型对比表)
- [可灵 vs 竞品对比](#可灵-vs-竞品对比)
- [快速开始](#快速开始)
- [提示词指南与示例](#提示词指南与示例)
  - [电影场景](#-电影场景)
  - [角色动画](#-角色动画)
  - [特效](#-特效)
  - [商业营销](#-商业营销)
  - [自然风光](#-自然风光)
  - [抽象艺术](#-抽象艺术)
- [提示词工程技巧](#提示词工程技巧)
- [官方资源](#官方资源)
- [工具与集成](#工具与集成)
- [教程与视频](#教程与视频)
- [API 定价对比](#api-定价对比)
- [常见问题](#常见问题)
- [立即开始使用可灵 AI](#-立即开始使用可灵-ai)
- [Star 历史](#star-历史)
- [贡献指南](#贡献指南)
- [许可证](#许可证)

---

## 什么是可灵 AI？

**可灵 AI（Kling AI）** 是由**快手科技**开发的尖端 AI 视频生成模型。自 2024 年发布以来，可灵已迅速发展成为全球最强大的视频生成系统之一，在多个维度上与 OpenAI Sora、Google Veo 等模型展开竞争并实现超越。

### 核心亮点

- 🎥 **原生 4K 分辨率** — 业界首个 4K 视频生成，60FPS
- 🎬 **多镜头生成** — 单个 15 秒视频中最多 6 个镜头，保持空间连续性和角色一致性
- 🔊 **音视频同步生成** — 原生支持 5 种语言音频（中文、英语、日语、韩语、西班牙语）
- 🌐 **统一多模态创作** — 文本、视频、图像、主体输入合一（O1/O3）
- ✂️ **参考图生成视频** — 从参考图生成视频、编辑现有视频、控制声音元素（O3）

### 核心能力

| 能力 | 描述 |
|:---|:---|
| **文生视频（T2V）** | 从文本描述生成高质量视频 |
| **图生视频（I2V）** | 将静态图片转化为动态视频 |
| **参考图生视频** | 使用参考图引导视频生成的风格和内容 |
| **视频编辑** | 使用 AI 编辑和修改现有视频 |
| **数字人生成** | 创建带有口型同步的说话头像视频 |
| **运动控制** | 精确控制角色和摄像机运动 |
| **声音控制** | 在视频中生成和控制音频元素 |
| **特效** | 为视频添加 AI 驱动的特效 |
| **多镜头** | 创建具有场景连续性的多镜头叙事 |

---

## 模型演进时间线

可灵 AI 自诞生以来经历了快速的发展迭代：

```
                         可灵 AI 模型演进
  ─────────────────────────────────────────────────────────────────

  2024 Q2   ██ 可灵 1.0    — 首次发布，文生视频
            ██              — 720p，5秒片段

  2024 Q3   ████ 可灵 1.5  — 提升画质和连贯性
            ████            — 更好的运动理解

  2024 Q4   ██████ 可灵 1.6 — 扩展时长支持
            ██████           — 增强分辨率

  2024 Q4   ████████ 可灵 2.0 — 重大架构升级
            ████████          — 支持 1080p，画质大幅提升

  2025 Q1   ██████████ 可灵 2.1 — 优化生成质量
            ██████████          — 更好的文字渲染

  2025 Q2   ████████████ 可灵 2.5 — 引入 Turbo 模式
            ████████████          — 更快的生成速度

  2025 Q3   ██████████████ 可灵 2.6 — 音视频同步生成
            ██████████████          — 首个原生音频模型

  2026 Q1   ████████████████ 可灵 3.0 — 原生 4K @ 60FPS
            ████████████████          — 6 镜头，15秒视频

  2026 Q1   ██████████████████ 可灵 O1 — 统一多模态
            ██████████████████          — 文本+视频+图像输入

  2026 Q1   ████████████████████ 可灵 O3 — 全能创作套件
            ████████████████████          — 参考图生成、编辑、声音控制
```

---

## 模型对比表

<table>
<thead>
<tr>
<th>模型</th>
<th>分辨率</th>
<th>帧率</th>
<th>时长</th>
<th>音频</th>
<th>多镜头</th>
<th>4K</th>
<th>核心特性</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>可灵 3.0 Pro</strong></td>
<td>最高 4K</td>
<td>60</td>
<td>5s / 10s / 15s</td>
<td>✅</td>
<td>✅ 最多 6 个</td>
<td>✅</td>
<td>最佳画质，最高分辨率，多镜头叙事</td>
</tr>
<tr>
<td><strong>可灵 3.0 Std</strong></td>
<td>最高 4K</td>
<td>60</td>
<td>5s / 10s / 15s</td>
<td>✅</td>
<td>✅ 最多 6 个</td>
<td>✅</td>
<td>画质与速度的平衡</td>
</tr>
<tr>
<td><strong>可灵 O3 Pro</strong></td>
<td>1080p</td>
<td>30</td>
<td>5s / 10s</td>
<td>✅</td>
<td>✅</td>
<td>❌</td>
<td>参考图生成视频、视频编辑、声音控制、元素参考</td>
</tr>
<tr>
<td><strong>可灵 O3 Std</strong></td>
<td>1080p</td>
<td>30</td>
<td>5s / 10s</td>
<td>✅</td>
<td>✅</td>
<td>❌</td>
<td>高性价比统一创作</td>
</tr>
<tr>
<td><strong>可灵 O1</strong></td>
<td>1080p</td>
<td>30</td>
<td>5s / 10s</td>
<td>✅</td>
<td>❌</td>
<td>❌</td>
<td>统一多模态输入（文本、视频、图像、主体）</td>
</tr>
<tr>
<td><strong>可灵 2.6 Pro</strong></td>
<td>1080p</td>
<td>30</td>
<td>5s / 10s</td>
<td>✅</td>
<td>❌</td>
<td>❌</td>
<td>首个音视频同步生成</td>
</tr>
<tr>
<td><strong>可灵 2.6 Std</strong></td>
<td>1080p</td>
<td>30</td>
<td>5s / 10s</td>
<td>✅</td>
<td>❌</td>
<td>❌</td>
<td>经济实惠的音频版本</td>
</tr>
<tr>
<td><strong>可灵 2.5 Turbo Pro</strong></td>
<td>1080p</td>
<td>30</td>
<td>5s / 10s</td>
<td>❌</td>
<td>❌</td>
<td>❌</td>
<td>快速生成，画质好</td>
</tr>
<tr>
<td><strong>可灵 2.1</strong></td>
<td>1080p</td>
<td>30</td>
<td>5s / 10s</td>
<td>❌</td>
<td>❌</td>
<td>❌</td>
<td>改进的文字渲染</td>
</tr>
<tr>
<td><strong>可灵 2.0</strong></td>
<td>1080p</td>
<td>30</td>
<td>5s</td>
<td>❌</td>
<td>❌</td>
<td>❌</td>
<td>架构升级</td>
</tr>
<tr>
<td><strong>可灵 1.6</strong></td>
<td>720p</td>
<td>30</td>
<td>5s</td>
<td>❌</td>
<td>❌</td>
<td>❌</td>
<td>扩展时长支持</td>
</tr>
</tbody>
</table>

---

## 可灵 vs 竞品对比

可灵 AI 与其他领先视频生成模型的对比：

| 特性 | 可灵 3.0 | Seedance 1.0 | Sora | Veo 3 | Wan 2.1 |
|:---|:---:|:---:|:---:|:---:|:---:|
| **最高分辨率** | **4K** | 1080p | 1080p | 4K | 1080p |
| **最高帧率** | **60** | 30 | 24 | 30 | 30 |
| **最长时长** | **15s** | 10s | 60s | 8s | 5s |
| **原生音频** | ✅ 5种语言 | ✅ | ✅ | ✅ | ❌ |
| **多镜头** | ✅ 6个镜头 | ❌ | ❌ | ❌ | ❌ |
| **图生视频** | ✅ | ✅ | ✅ | ✅ | ✅ |
| **参考图生视频** | ✅ (O3) | ❌ | ❌ | ❌ | ❌ |
| **视频编辑** | ✅ (O3) | ❌ | ✅ | ❌ | ❌ |
| **数字人** | ✅ | ❌ | ❌ | ❌ | ❌ |
| **运动控制** | ✅ | ❌ | ❌ | ❌ | ❌ |
| **API 接入** | ✅ | ✅ | ✅ | ✅ | ✅ |
| **无审查 API** | ✅ 通过 [Atlas Cloud](https://www.atlascloud.ai?ref=JPM683&utm_source=github&utm_campaign=awesome-kling-ai) | 有限 | 有限 | 有限 | 有限 |

> 💡 **可灵 3.0 是唯一支持原生 4K/60FPS 和多镜头叙事的模型**，使其成为截至 2026 年初最全面的视频生成模型。

---

## 快速开始

### 使用 Atlas Cloud API

通过 [Atlas Cloud API](https://www.atlascloud.ai?ref=JPM683&utm_source=github&utm_campaign=awesome-kling-ai) 是开始使用可灵 AI 生成视频的最快方式，提供全部 20+ 可灵模型的访问，业界最低价格。

#### cURL

```bash
# 使用 Atlas Cloud API 生成可灵 3.0 视频
curl -X POST "https://api.atlascloud.ai/api/v1/model/generateVideo" \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -d '{
    "model": "kling-v3-pro",
    "prompt": "一只雄鹰在金色夕阳云层中翱翔，俯瞰白雪皑皑的山峰，电影级航拍镜头，4K，戏剧性光线",
    "duration": 10,
    "aspect_ratio": "16:9",
    "fps": 60
  }'
```

#### Python

```python
import requests
import time

# Atlas Cloud API 配置
API_KEY = "YOUR_API_KEY"
BASE_URL = "https://api.atlascloud.ai/api/v1/model"

def generate_video(prompt, model="kling-v3-pro", duration=10):
    """使用可灵 AI 生成视频"""
    response = requests.post(
        f"{BASE_URL}/generateVideo",
        headers={
            "Content-Type": "application/json",
            "Authorization": f"Bearer {API_KEY}"
        },
        json={
            "model": model,
            "prompt": prompt,
            "duration": duration,
            "aspect_ratio": "16:9",
            "fps": 60
        }
    )
    return response.json()

def check_status(task_id):
    """查询视频生成状态"""
    response = requests.get(
        f"{BASE_URL}/status/{task_id}",
        headers={"Authorization": f"Bearer {API_KEY}"}
    )
    return response.json()

# 示例：生成一个史诗级的风景视频
result = generate_video(
    prompt="无人机航拍镜头缓缓掠过清晨的高山湖泊，薄雾从清澈的水面升起，"
           "白雪皑皑的山峰倒映在如镜的水面上，电影级色彩分级，4K超高清",
    model="kling-v3-pro",
    duration=10
)

print(f"任务 ID: {result['task_id']}")

# 轮询检查生成状态
while True:
    status = check_status(result['task_id'])
    if status['status'] == 'completed':
        print(f"视频 URL: {status['video_url']}")
        break
    elif status['status'] == 'failed':
        print(f"生成失败: {status['error']}")
        break
    time.sleep(5)
```

#### JavaScript / Node.js

```javascript
// Atlas Cloud API - 可灵视频生成示例
const API_KEY = 'YOUR_API_KEY';
const BASE_URL = 'https://api.atlascloud.ai/api/v1/model';

// 生成视频
async function generateVideo(prompt, model = 'kling-v3-pro', duration = 10) {
  const response = await fetch(`${BASE_URL}/generateVideo`, {
    method: 'POST',
    headers: {
      'Content-Type': 'application/json',
      'Authorization': `Bearer ${API_KEY}`
    },
    body: JSON.stringify({
      model,
      prompt,
      duration,
      aspect_ratio: '16:9',
      fps: 60
    })
  });
  return response.json();
}

// 查询生成状态
async function checkStatus(taskId) {
  const response = await fetch(`${BASE_URL}/status/${taskId}`, {
    headers: { 'Authorization': `Bearer ${API_KEY}` }
  });
  return response.json();
}

// 使用示例
(async () => {
  const result = await generateVideo(
    '一位武士站在悬崖边俯瞰广阔的山谷，'
    + '樱花花瓣在慢动作中飘落，风吹动衣袍，'
    + '黄金时刻的光线，电影级广角镜头，4K'
  );

  console.log(`任务 ID: ${result.task_id}`);

  // 等待视频生成完成
  const poll = setInterval(async () => {
    const status = await checkStatus(result.task_id);
    if (status.status === 'completed') {
      console.log(`视频 URL: ${status.video_url}`);
      clearInterval(poll);
    } else if (status.status === 'failed') {
      console.log(`生成失败: ${status.error}`);
      clearInterval(poll);
    }
  }, 5000);
})();
```

---

## 提示词指南与示例

> 📝 **提示：** 以下提示词针对可灵 3.0 Pro 优化。使用其他模型版本时请适当调整设置。

### 🎬 电影场景

<details>
<summary><strong>1. 史诗山脉日出</strong> — 无人机航拍揭示</summary>

**提示词：**
> A breathtaking aerial drone shot ascending over misty mountain peaks at golden hour. The camera rises slowly to reveal an endless chain of snow-capped mountains stretching to the horizon. Volumetric fog fills the valleys below. Warm sunlight breaks through clouds, casting god rays across the landscape. Ultra cinematic, photorealistic, 4K.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 10s |
| 宽高比 | 16:9 |
| 帧率 | 60 |

**难度：** ⭐ 初级

**技巧：** 可灵非常擅长风景镜头。使用"aerial drone shot"和"ascending"可获得流畅的垂直运镜。添加"volumetric fog"和"god rays"能显著提升大气感。

</details>

<details>
<summary><strong>2. 黑色电影侦探场景</strong> — 角色驱动叙事</summary>

**提示词：**
> A detective in a long trench coat walks down a rain-soaked alley at night. Neon signs reflect off wet cobblestones in shades of red and blue. Steam rises from a manhole cover. The camera follows behind him in a slow tracking shot. Film noir style, moody lighting, high contrast, anamorphic lens flare.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 10s |
| 宽高比 | 21:9 |
| 帧率 | 30 |

**难度：** ⭐⭐ 中级

**技巧：** 指定"tracking shot"可获得流畅的跟踪运镜。黑色电影风格的提示词在可灵中效果极佳。添加"anamorphic lens flare"可创造专业电影质感。

</details>

<details>
<summary><strong>3. 水下王国</strong> — 奇幻世界揭示</summary>

**提示词：**
> A magical underwater city with bioluminescent coral towers and crystal domes. Schools of exotic fish swim through archways of living coral. Shafts of sunlight penetrate from the surface above, creating dancing light patterns. A mermaid glides gracefully past ancient ruins. The camera slowly orbits the city revealing its grand scale. Fantasy, ethereal, dreamlike atmosphere.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 15s |
| 宽高比 | 16:9 |
| 帧率 | 60 |

**难度：** ⭐⭐⭐ 高级

**技巧：** 使用可灵 3.0 的多镜头功能，创建 15 秒叙事，展示水下城市的不同部分。"Bioluminescent"是创造魔幻水下场景的强力关键词。

</details>

<details>
<summary><strong>4. 东京飙车追逐</strong> — 快节奏动作</summary>

**提示词：**
> A high-speed car chase through the neon-lit streets of Shibuya, Tokyo at night. A sleek sports car drifts around a corner, tires smoking, headlights cutting through the rain. The camera is mounted low, tracking alongside the car. Neon signs blur past in streaks of color. Cinematic, fast-paced, adrenaline-pumping, Michael Bay style.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 10s |
| 宽高比 | 2.39:1 |
| 帧率 | 60 |

**难度：** ⭐⭐⭐ 高级

**技巧：** 60FPS 对快速运动场景至关重要。使用"tracking alongside"保持主体居中。导演名字引用（如"Michael Bay style"）有助于设定视觉风格。

</details>

<details>
<summary><strong>5. 古代神庙探险</strong> — 印第安纳琼斯风格</summary>

**提示词：**
> An explorer with a torch enters a vast ancient temple hidden deep in the jungle. The camera follows from behind as golden light reveals massive stone columns covered in intricate carvings. Dust particles float in the torchlight. The explorer looks up in awe as the camera tilts upward to reveal a colossal stone statue. Adventure film style, warm color grading.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 15s |
| 宽高比 | 16:9 |
| 帧率 | 30 |

**难度：** ⭐⭐ 中级

**技巧：** 多镜头在这里非常适用 — 镜头1：进入神庙，镜头2：展示石柱，镜头3：雕像的揭示。使用"dust particles"增添氛围感。

</details>

### 🧑‍🎤 角色动画

<details>
<summary><strong>6. 新闻主播</strong> — 口型同步数字人</summary>

**提示词：**
> A professional female news anchor sitting at a modern news desk, delivering breaking news. She speaks clearly and confidently, making subtle hand gestures. Clean studio lighting, shallow depth of field on the background showing multiple monitors. Professional broadcast quality, 4K.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 2.6 Pro（数字人） |
| 时长 | 10s |
| 宽高比 | 16:9 |
| 音频 | 启用（中文） |

**难度：** ⭐ 初级

**技巧：** 数字人/说话头像视频，可灵 2.6 Pro 的数字人模式能产生最佳的口型同步效果。提供清晰的音频输入可获得最佳结果。

</details>

<details>
<summary><strong>7. 舞蹈编排</strong> — 动感全身运动</summary>

**提示词：**
> A professional dancer performing a contemporary dance routine in an empty industrial warehouse. Dramatic side lighting creates bold shadows. The dancer executes fluid spins and leaps with perfect form. Slow motion on the most dramatic movements. Shot from multiple angles. Cinematic, artistic, powerful.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 15s |
| 宽高比 | 9:16 |
| 帧率 | 60 |

**难度：** ⭐⭐⭐ 高级

**技巧：** 60FPS 能完美捕捉舞蹈动作。选择性使用"slow motion"来强调重点。可灵 3.0 的多镜头功能可在单个视频中实现角度切换。

</details>

<details>
<summary><strong>8. 角色行走循环</strong> — 动画风格</summary>

**提示词：**
> A stylish anime character walking confidently down a cyberpunk city street. Side view tracking shot. The character has flowing silver hair and a glowing blue jacket. Neon reflections on the wet ground. Each step is deliberate and smooth. Anime style, Makoto Shinkai-inspired lighting.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 5s |
| 宽高比 | 16:9 |
| 帧率 | 30 |

**难度：** ⭐⭐ 中级

**技巧：** 动漫风格在可灵中效果很好。引用特定动漫导演可保持风格一致性。"Side view tracking shot"确保干净的行走循环。

</details>

<details>
<summary><strong>9. 情感独白</strong> — 特写表演</summary>

**提示词：**
> Extreme close-up of a middle-aged man's face as he delivers an emotional monologue. Tears well up in his eyes. Single source lighting from the left creates dramatic shadows across his weathered face. The camera slowly pushes in. Raw emotion, intimate, documentary style, shallow depth of field.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 O3 Pro |
| 时长 | 10s |
| 宽高比 | 16:9 |
| 帧率 | 30 |

**难度：** ⭐⭐⭐ 高级

**技巧：** 可灵 O3 在面部表情生成方面表现出色。使用"extreme close-up"和"slowly pushes in"可打造亲密感。"Single source lighting"创造电影般的戏剧效果。

</details>

<details>
<summary><strong>10. 武术打斗</strong> — 动作编排</summary>

**提示词：**
> Two martial artists engaged in an intense kung fu battle in a bamboo forest. One fighter executes a spinning kick while the other blocks and counters. Bamboo leaves scatter with each impact. Camera orbits around them in a dynamic 360-degree shot. Wire-fu style, Crouching Tiger Hidden Dragon aesthetic, slow motion at impact moments.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 10s |
| 宽高比 | 2.39:1 |
| 帧率 | 60 |

**难度：** ⭐⭐⭐ 高级

**技巧：** 60FPS 对武术场景至关重要。电影引用有助于定义风格。多镜头可在全景和特写之间交替。

</details>

### ✨ 特效

<details>
<summary><strong>11. 子弹时间</strong> — 黑客帝国风格慢动作</summary>

**提示词：**
> A woman in a black leather jacket dodges a punch in extreme slow motion. The camera orbits around her frozen in mid-dodge as water droplets and glass shards hang suspended in the air. Time gradually resumes as she completes the dodge. Matrix-style bullet time effect, dramatic lighting, dark background.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 10s |
| 宽高比 | 16:9 |
| 帧率 | 60 |

**难度：** ⭐⭐⭐ 高级

**技巧：** 60FPS 对慢动作效果至关重要。"Camera orbits"结合"extreme slow motion"可创造子弹时间效果。悬浮粒子增加视觉张力。

</details>

<details>
<summary><strong>12. 城市延时</strong> — 日夜转换</summary>

**提示词：**
> Hyperlapse of a major city skyline transitioning from day to night. Clouds race across the sky as shadows sweep across skyscrapers. City lights gradually illuminate building by building. Traffic becomes rivers of red and white light trails. Stars emerge in the darkening sky. Smooth time-lapse, 4K, ultra sharp.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 10s |
| 宽高比 | 16:9 |
| 帧率 | 30 |

**难度：** ⭐⭐ 中级

**技巧：** "Hyperlapse"和"time-lapse"是可灵理解良好的关键词。添加"light trails"可为车流创造令人惊叹的夜间效果。

</details>

<details>
<summary><strong>13. 粒子风暴</strong> — 抽象视觉特效</summary>

**提示词：**
> Millions of golden particles swirling in a tornado formation against a dark void. The particles gradually form the shape of a phoenix, which then explodes outward in a brilliant burst of light. Embers and sparks cascade downward. Magical, mystical, particle simulation, volumetric lighting.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 10s |
| 宽高比 | 16:9 |
| 帧率 | 60 |

**难度：** ⭐⭐ 中级

**技巧：** 粒子效果是可灵的强项。使用从形态到造型的转变来做戏剧性揭示。"Volumetric lighting"增强粒子可见性。

</details>

<details>
<summary><strong>14. 物体变形</strong> — 无缝转化</summary>

**提示词：**
> A red rose slowly morphs into a butterfly. Each petal unfurls and transforms into a delicate wing. The stem becomes the butterfly's body. The transformation is smooth and organic. The butterfly takes flight and dissolves into golden dust. White background, studio lighting, macro lens detail.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 O3 Pro |
| 时长 | 10s |
| 宽高比 | 1:1 |
| 帧率 | 30 |

**难度：** ⭐⭐ 中级

**技巧：** 可灵 O3 很好地处理变形转化。逐步描述转变过程可获得更流畅的结果。干净背景有助于保持焦点。

</details>

<details>
<summary><strong>15. 闪电风暴</strong> — 天气视觉特效</summary>

**提示词：**
> A massive supercell thunderstorm over flat prairie land at dusk. Multiple bolts of lightning strike simultaneously, illuminating the rotating wall cloud. Wind whips through tall grass in the foreground. The camera is low and steady, creating a dramatic perspective. Storm chaser footage style, raw, powerful, awe-inspiring.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 10s |
| 宽高比 | 16:9 |
| 帧率 | 60 |

**难度：** ⭐⭐ 中级

**技巧：** 可灵对天气现象的处理非常出色。"Supercell"能触发令人印象深刻的风暴形态。低角度摄影增加戏剧冲击力。

</details>

### 📦 商业营销

<details>
<summary><strong>16. 产品揭示 - 香水</strong> — 奢侈品展示</summary>

**提示词：**
> A luxury perfume bottle materializes from swirling golden mist on a marble surface. The camera slowly orbits the bottle as light refracts through the amber liquid. Rose petals and gold leaf particles float elegantly around the bottle. The brand catches light with a brilliant sparkle. Premium commercial, luxury aesthetic, high-end fashion photography style.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 10s |
| 宽高比 | 9:16 |
| 帧率 | 60 |

**难度：** ⭐⭐ 中级

**技巧：** 产品镜头适合使用"orbiting camera"和"studio lighting"。9:16 宽高比非常适合社交媒体广告。奢侈品关键词增强高端感。

</details>

<details>
<summary><strong>17. 美食广告</strong> — 诱人美食内容</summary>

**提示词：**
> A gourmet burger is assembled in dramatic slow motion. The bun drops first, followed by the lettuce, then a perfectly grilled patty with melting cheese oozing over the edges. Tomato slices, pickles, and sauce drizzle down in slow motion. Each ingredient is lit individually with a highlight. Fast food commercial style, mouth-watering, appetizing.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 10s |
| 宽高比 | 1:1 |
| 帧率 | 60 |

**难度：** ⭐⭐ 中级

**技巧：** 美食视频在 60FPS 慢动作下非常出色。描述组装序列可创建多层次构图。"Slow motion" + "dramatic lighting" = 令人垂涎的内容。

</details>

<details>
<summary><strong>18. 球鞋发布</strong> — 动态产品推广</summary>

**提示词：**
> A futuristic sneaker floats and rotates in zero gravity against a black background. Energy waves pulse outward from the shoe. The camera performs a smooth 360-degree orbit. Holographic details on the shoe shimmer and shift color. The sole flexes to show cushioning technology. Product launch trailer style, premium, futuristic.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 10s |
| 宽高比 | 16:9 |
| 帧率 | 60 |

**难度：** ⭐⭐ 中级

**技巧：** "Zero gravity"和"float"创造引人注目的产品展示。"Holographic"增加未来感。360度环绕非常适合产品展示。

</details>

<details>
<summary><strong>19. 房产巡览</strong> — 房产展示</summary>

**提示词：**
> A smooth cinematic walkthrough of a modern luxury penthouse. The camera glides through the open-plan living room with floor-to-ceiling windows overlooking a city skyline at sunset. Warm interior lighting, designer furniture, a kitchen island with marble countertops. The camera continues through to a balcony with an infinity pool. Architectural visualization, real estate commercial, steadicam shot.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 15s |
| 宽高比 | 16:9 |
| 帧率 | 30 |

**难度：** ⭐⭐⭐ 高级

**技巧：** 15s 多镜头模式非常适合房产巡览 — 每个镜头可以展示不同的房间。"Steadicam"确保流畅的摄像机移动。

</details>

<details>
<summary><strong>20. 时装秀</strong> — 时尚行业内容</summary>

**提示词：**
> A supermodel walks down a dimly lit fashion runway wearing an avant-garde haute couture gown. Dramatic backlighting creates a silhouette effect. Camera flashes pop from the audience on both sides. The model stops, poses, and turns. Close-up on fabric texture and intricate beadwork. Fashion week, Vogue editorial, haute couture.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 10s |
| 宽高比 | 9:16 |
| 帧率 | 30 |

**难度：** ⭐⭐ 中级

**技巧：** 可灵对面料和服装的处理很好。"Camera flashes"增添真实的秀场氛围。多镜头可在全景和特写视角之间交替。

</details>

### 🏞️ 自然风光

<details>
<summary><strong>21. 北极光</strong> — 大气现象</summary>

**提示词：**
> The aurora borealis dances across the Arctic sky in shimmering curtains of green, purple, and pink. The lights are reflected in a perfectly still fjord below. Snow-covered mountains frame the scene. A lone cabin with a warm glowing window sits on the shore. Time-lapse speed, magical, serene, awe-inspiring.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 10s |
| 宽高比 | 16:9 |
| 帧率 | 30 |

**难度：** ⭐ 初级

**技巧：** 北极光场景是可灵的拿手好戏。水面倒影使视觉效果加倍。加入人文元素（小屋）提供了尺度感和温暖感。

</details>

<details>
<summary><strong>22. 火山喷发</strong> — 自然灾害</summary>

**提示词：**
> A dramatic volcanic eruption at night. Molten lava fountains shoot hundreds of meters into the sky, illuminating billowing ash clouds from below in shades of orange and red. Rivers of glowing lava flow down the mountainside. Lightning flashes within the ash plume. The camera is positioned safely at a distance, capturing the full scale. Documentary style, raw nature, powerful.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 10s |
| 宽高比 | 16:9 |
| 帧率 | 60 |

**难度：** ⭐⭐ 中级

**技巧：** 自然灾害场景在 60FPS 下的熔岩和粒子细节表现更好。"Lightning within ash plume"是增加真实感的细节。

</details>

<details>
<summary><strong>23. 海浪慢动作</strong> — 冲浪摄影</summary>

**提示词：**
> A massive turquoise wave curls and breaks in ultra slow motion. Sunlight passes through the translucent wave wall, creating prismatic colors. Water droplets hang suspended in the air like diamonds. The camera is inside the barrel of the wave looking outward. Surf cinematography, crystal clear water, tropical, golden hour.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 10s |
| 宽高比 | 16:9 |
| 帧率 | 60 |

**难度：** ⭐⭐ 中级

**技巧：** 可灵 3.0 的水物理效果出色。"Inside the barrel"创造独特的透视效果。60FPS 对慢动作水流至关重要。

</details>

<details>
<summary><strong>24. 四季变换</strong> — 延时变换</summary>

**提示词：**
> A single majestic oak tree in the center of a meadow, transitioning through all four seasons in one continuous shot. Spring blossoms burst into green leaves, which deepen to summer's lush canopy, then transform to autumn's brilliant orange and gold, before leaves fall and snow covers bare branches. Timelapse, seamless transition, centered composition.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 15s |
| 宽高比 | 16:9 |
| 帧率 | 30 |

**难度：** ⭐⭐⭐ 高级

**技巧：** 多镜头模式非常适合 — 每个季节分配约 3-4 秒。居中的静态构图有助于在过渡之间保持连续性。

</details>

<details>
<summary><strong>25. 珊瑚礁生态</strong> — 水下纪录片</summary>

**提示词：**
> A vibrant coral reef teeming with tropical fish in crystal clear water. A sea turtle glides peacefully through the frame. Sunbeams dance through the water surface above. Colorful coral fans sway gently in the current. A clownfish peeks out from its anemone home. Underwater documentary, BBC Earth style, natural lighting, macro detail.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 10s |
| 宽高比 | 16:9 |
| 帧率 | 60 |

**难度：** ⭐⭐ 中级

**技巧：** "BBC Earth style"触发高质量自然纪录片美学。提及特定海洋生物可创造多样的水下场景。

</details>

### 🎨 抽象艺术

<details>
<summary><strong>26. 墨水入水</strong> — 流体艺术</summary>

**提示词：**
> Drops of vibrant ink falling into clear water in extreme slow motion. Deep indigo, crimson, and gold inks swirl and dance together, creating organic fractal patterns. The colors interweave without fully mixing. Shot from above looking down into a glass container. Macro photography, fluid dynamics, mesmerizing, meditative.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 10s |
| 宽高比 | 1:1 |
| 帧率 | 60 |

**难度：** ⭐ 初级

**技巧：** 流体模拟是可灵的强项。俯拍视角创造干净的构图。1:1 宽高比非常适合社交媒体。

</details>

<details>
<summary><strong>27. 分形缩放</strong> — 数学艺术</summary>

**提示词：**
> An infinite zoom into a Mandelbrot fractal set. Starting from a wide view, the camera continuously zooms deeper into increasingly complex and colorful fractal patterns. Each level reveals new spiral formations and geometric details. Colors shift from deep blue to electric purple to neon green. Psychedelic, mathematical beauty, endless depth.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 15s |
| 宽高比 | 1:1 |
| 帧率 | 60 |

**难度：** ⭐⭐ 中级

**技巧：** "Infinite zoom"创造引人入胜的内容。描述颜色过渡以增加视觉多样性。15s 时长配合 60FPS 提供最流畅的缩放体验。

</details>

<details>
<summary><strong>28. 活画</strong> — 艺术作品活化</summary>

**提示词：**
> Van Gogh's Starry Night comes to life. The swirling stars begin to rotate and pulse with light. The cypress tree sways in an invisible wind. The village lights flicker warmly. The entire painting maintains its thick impasto brushstroke texture while elements animate organically. Art history, post-impressionism, magical realism.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 O3 Pro |
| 时长 | 10s |
| 宽高比 | 16:9 |
| 帧率 | 30 |

**难度：** ⭐⭐ 中级

**技巧：** 可灵 O3 配合图像参考非常适合让现有艺术品活化。强调保持原始艺术风格，防止变成照片写实主义。

</details>

<details>
<summary><strong>29. 几何变换</strong> — 动态图形</summary>

**提示词：**
> A minimalist geometric animation. A single white triangle on a black background splits into hundreds of smaller triangles that rearrange into a circle, then a square, then an impossible Escher-like structure. Clean lines, precise movements, satisfying transitions. Motion graphics, minimal, geometric art, Swiss design.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Std |
| 时长 | 10s |
| 宽高比 | 1:1 |
| 帧率 | 60 |

**难度：** ⭐⭐ 中级

**技巧：** 干净的几何动画在可灵中效果出人意料地好。"Swiss design"和"motion graphics"触发干净精确的美学。高对比度（白底黑色）确保清晰的结果。

</details>

<details>
<summary><strong>30. 梦境序列</strong> — 超现实叙事</summary>

**提示词：**
> A surreal dreamscape where gravity is reversed. A person walks on the ceiling of a grand baroque palace while chandeliers hang upward from the floor. Furniture floats at random angles. Through the windows, an ocean hangs in the sky above an upside-down city. The camera rotates slowly, making the viewer question which way is up. Salvador Dali meets Christopher Nolan, surrealist, mind-bending.

**设置：**
| 参数 | 值 |
|:---|:---|
| 模型 | 可灵 3.0 Pro |
| 时长 | 15s |
| 宽高比 | 16:9 |
| 帧率 | 30 |

**难度：** ⭐⭐⭐ 高级

**技巧：** 超现实场景推动了可灵的创造力。多镜头模式允许从不同角度展示同一个不可能的空间。导演引用（诺兰）有助于定义视觉方法。

</details>

---

## 提示词工程技巧

### 摄像机运动关键词

可灵 AI 对特定的摄像机运动术语响应非常好：

| 关键词 | 效果 | 最适合场景 |
|:---|:---|:---|
| `tracking shot` | 摄像机跟随主体 | 角色行走/奔跑 |
| `dolly zoom` | 眩晕/推拉变焦效果 | 戏剧性揭示 |
| `crane shot` | 垂直摄像机移动 | 建立镜头 |
| `steadicam` | 平滑手持感 | 室内巡览 |
| `aerial drone shot` | 高角度航拍 | 风景 |
| `orbit shot` | 摄像机环绕主体 | 产品展示 |
| `push in` | 摄像机向主体移动 | 营造紧张感 |
| `pull back / reveal` | 摄像机远离 | 揭示效果 |
| `whip pan` | 快速水平摇摄 | 场景转换 |
| `Dutch angle` | 倾斜摄像机 | 不安/紧张 |
| `rack focus` | 焦点在平面间切换 | 引导注意力 |
| `slow motion` | 降低播放速度 | 动作/细节 |

### 优化 cfg_scale

`cfg_scale` 参数控制输出对提示词的遵循程度：

| cfg_scale | 效果 | 使用场景 |
|:---|:---|:---|
| 3-5 | 创意性强，宽松解读 | 抽象艺术、实验性 |
| 5-7 | **平衡（推荐）** | 大多数场景 |
| 7-9 | 严格遵循提示词 | 技术性、特定场景 |
| 9-12 | 非常严格，可能降低质量 | 需要极高精度时 |

### 时长与质量的权衡

| 时长 | 质量影响 | 最佳实践 |
|:---|:---|:---|
| 5s | 每帧最高质量 | 短产品镜头、循环 |
| 10s | 优秀质量 | 大多数场景 |
| 15s | 良好质量，多镜头 | 叙事、巡览 |

> 💡 **专业提示：** 要获得最高质量，可以生成 5 秒片段然后拼接。如果追求便捷，使用可灵 3.0 的 15 秒多镜头模式。

### 多镜头技巧（可灵 3.0）

可灵 3.0 支持在单个 15 秒视频中包含最多 6 个镜头。要获得最佳效果：

1. **清晰描述每个镜头** — 在提示词中使用镜头编号或场景转换
2. **保持角色一致性** — 在各镜头中引用相同的角色描述
3. **使用空间连续性线索** — "摄像机从厨房移动到客厅"
4. **变化镜头类型** — 混合使用全景、中景和特写
5. **控制节奏** — 关键时刻用较长描述，过渡用较短描述

**多镜头提示词示例：**
> Shot 1: Wide establishing shot of a futuristic space station orbiting Earth. Shot 2: Camera pushes through the station window into the interior. Shot 3: Medium shot of an astronaut floating through a corridor. Shot 4: Close-up on the astronaut's face looking out a porthole. Shot 5: Reverse angle showing Earth through the porthole. Shot 6: Wide shot pulling back to reveal the full station against the cosmos.

### 负面提示词策略

虽然可灵不像 Stable Diffusion 那样使用传统的负面提示词，但你可以引导它避开不想要的元素：

- **添加质量锚点：** "professional cinematography, high production value" 远离业余风格
- **明确你想要的：** 不要说"no blur"，而是说"ultra sharp, crisp focus"
- **使用风格引用：** "shot on ARRI Alexa"或"Dolby Vision"暗示高质量
- **避免矛盾：** 不要混合不兼容的风格（如"cartoon photorealistic"）

---

## 官方资源

- 🌐 [可灵 AI 官网](https://klingai.com/) — 可灵 AI 官方平台
- 🏢 [快手开放平台](https://open.kuaishou.com/) — 快手开发者平台
- 📖 [可灵 API 文档](https://docs.qingque.cn/d/home/eZQBMqNQR3bLYU9FB0kFv-wQK) — 官方 API 文档
- 🎨 [可灵 AI 创意中心](https://klingai.com/global/explore) — 社区创作和灵感
- 📱 [可灵 AI App](https://klingai.com/global/download) — 可灵 AI 移动应用

---

## 工具与集成

### ComfyUI 节点

- 🔧 [ComfyUI-KlingAI](https://github.com/KwaiVGI/ComfyUI-KlingAI) — 官方 ComfyUI 可灵节点
- 🔧 [ComfyUI-Kling-API](https://github.com/yolain/ComfyUI-Kling-API) — 社区 ComfyUI 集成

### SDK 与封装

- 🐍 [kling-python-sdk](https://github.com/KwaiVGI/kling-python-sdk) — 官方 Python SDK
- 📦 [kling-js](https://github.com/KwaiVGI/kling-js) — 官方 JavaScript/Node.js SDK

### 第三方工具

- 🛠️ [Atlas Cloud API](https://www.atlascloud.ai?ref=JPM683&utm_source=github&utm_campaign=awesome-kling-ai) — 统一 API 访问所有可灵模型，最低价格
- 🛠️ [可灵提示词生成器](https://github.com/search?q=kling+prompt+generator) — AI 驱动的可灵提示词生成工具
- 🖼️ [可灵批量处理器](https://github.com/search?q=kling+batch) — 批量视频生成工具

---

## 教程与视频

### 入门指南

- 📺 [可灵 AI 新手指南](https://www.youtube.com/results?search_query=kling+ai+tutorial+beginner) — YouTube 新手教程
- 📺 [可灵 3.0 新功能详解](https://www.youtube.com/results?search_query=kling+3.0+tutorial) — 最新版本教程
- 📝 [如何使用可灵 API](https://www.atlascloud.ai?ref=JPM683&utm_source=github&utm_campaign=awesome-kling-ai) — 分步 API 集成指南

### 进阶技巧

- 📺 [可灵多镜头电影制作](https://www.youtube.com/results?search_query=kling+multi+shot+video) — 使用多镜头创建叙事
- 📺 [可灵 vs Sora 对比](https://www.youtube.com/results?search_query=kling+vs+sora) — 画质并排对比
- 📺 [可灵商业视频制作](https://www.youtube.com/results?search_query=kling+ai+commercial) — 商业应用

### 博客与文章

- 📝 [可灵 AI 的发展历程：从 1.0 到 3.0](https://klingai.com/global/blog) — 官方博客
- 📝 [可灵 AI 提示词工程指南](https://www.atlascloud.ai?ref=JPM683&utm_source=github&utm_campaign=awesome-kling-ai) — 详细提示词策略
- 📝 [使用可灵 API 构建视频管线](https://www.atlascloud.ai?ref=JPM683&utm_source=github&utm_campaign=awesome-kling-ai) — 生产工作流指南

---

## API 定价对比

> 💰 更新于 2026 年 3 月

| 供应商 | 可灵 3.0 Pro（T2V） | 可灵 3.0 Std（T2V） | 可灵 O3 Pro | 全部模型 | 备注 |
|:---|:---:|:---:|:---:|:---:|:---|
| **[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683&utm_source=github&utm_campaign=awesome-kling-ai)** | **$0.204** | **更低** | **✅ 可用** | **✅ 20+ 模型** | ✅ 无审查，最快速，1.5折，首充赠送25% |
| 官方 API | ~$0.30+ | ~$0.20+ | 有限 | ~10 模型 | 地区限制，有审查 |
| 供应商 B | $0.25-0.40 | 不等 | 有限 | ~5 模型 | 模型选择有限 |
| 供应商 C | $0.30-0.45 | 不等 | ❌ | ~3 模型 | 模型少，推理慢 |

> 💡 **[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683&utm_source=github&utm_campaign=awesome-kling-ai)** 以业界最低价格提供最全面的可灵模型覆盖。新用户**首充赠送 25% 额度**（最高 $100 赠送）。

### Atlas Cloud vs fal.ai 价格对比

| 模型 | fal.ai 价格 | Atlas Cloud 价格 | 节省幅度 |
|:------|:------------|:-----------------|:---------|
| **Kling** | $0.224/秒 (5秒 = $1.12) | $0.204/秒起 | **便宜 82%** |
| **Seedance** | ~$0.26/视频 | $0.044/秒起 | **便宜 15%** |
| **Wan 2.5** | $0.05/秒 (5秒 = $0.25) | $0.05/秒起 | **便宜 80%** |
| **Wan 2.6** | 相似定价 | $0.07/秒起 | 极具竞争力 |
| **Veo 3** | $0.40/秒 (8秒 = $3.20) | 即将推出 | 敬请期待 |
| **Vidu Q3-Pro** | — | $0.06/秒起 | Atlas 独家 |
| **Vidu Q3-Turbo** | — | $0.034/秒起 | Atlas 独家 |

*以上为起步价，更高分辨率或更长时长可能产生额外费用。*

> 💡 Atlas Cloud 提供所有主流视频模型的**最低价格**。从 fal.ai 切换到 Atlas Cloud，视频生成成本最高可节省 **82%**。

---

## 常见问题

<details>
<summary><strong>什么是可灵 AI？</strong></summary>

**可灵 AI（Kling AI）** 是由**快手科技**开发的先进 AI 视频生成模型。它可以从文本提示词生成高质量视频（文生视频）、将静态图片转化为动态视频（图生视频）以及执行视频编辑任务。最新版本**可灵 3.0**支持原生 4K 分辨率、60FPS，单个 15 秒视频中最多支持 6 个多镜头序列，是目前最强大的视频生成模型之一。

</details>

<details>
<summary><strong>如何使用可灵 API？</strong></summary>

访问所有可灵模型的最简单方式是通过 [Atlas Cloud API](https://www.atlascloud.ai?ref=JPM683&utm_source=github&utm_campaign=awesome-kling-ai)：

1. **注册** [Atlas Cloud](https://www.atlascloud.ai?ref=JPM683&utm_source=github&utm_campaign=awesome-kling-ai) 账号
2. **获取 API Key** — 在控制面板获取
3. **发起 API 调用** — 向 `https://api.atlascloud.ai/api/v1/model/generateVideo` 发送请求
4. **选择模型** — 从可灵 3.0 Pro 到 O3，所有版本可用

查看 [快速开始](#快速开始) 部分获取 cURL、Python 和 JavaScript 代码示例。

</details>

<details>
<summary><strong>可灵 vs Sora vs Seedance——哪个更好？</strong></summary>

每个模型都有各自的优势：

| 方面 | 可灵 3.0 | Sora | Seedance |
|:---|:---|:---|:---|
| **分辨率** | **4K**（最佳） | 1080p | 1080p |
| **帧率** | **60**（最佳） | 24 | 30 |
| **多镜头** | **✅ 6个镜头**（独有） | ❌ | ❌ |
| **时长** | 15s | **60s**（最长） | 10s |
| **音频** | ✅ 5种语言 | ✅ | ✅ |
| **API 接入** | ✅（通过 [Atlas Cloud](https://www.atlascloud.ai?ref=JPM683&utm_source=github&utm_campaign=awesome-kling-ai)） | ✅ | ✅ |

**可灵 3.0** 最适合高分辨率、高帧率的商业内容。**Sora** 擅长更长的叙事。**Seedance** 在通用场景中提供良好的平衡。要以最低价格访问所有可灵模型，请使用 [Atlas Cloud](https://www.atlascloud.ai?ref=JPM683&utm_source=github&utm_campaign=awesome-kling-ai)。

</details>

<details>
<summary><strong>初学者最佳可灵提示词有哪些？</strong></summary>

从简单、描述性的提示词开始：

1. **风景：** "A serene lake at sunset with mountains in the background, cinematic, 4K"
2. **动物：** "A golden retriever running through a field of flowers, slow motion, warm lighting"
3. **产品：** "A cup of coffee with steam rising, top-down view, cozy atmosphere"
4. **抽象：** "Colorful paint drops falling into water, slow motion, macro lens"

查看完整的 [提示词指南](#提示词指南与示例) 获取 30+ 个带设置和技巧的详细示例。

</details>

<details>
<summary><strong>可灵 AI 是免费的吗？</strong></summary>

可灵 AI 在其官方平台上提供有限的免费额度。API 访问的定价因供应商而异：

- **[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683&utm_source=github&utm_campaign=awesome-kling-ai)：** 可灵 3.0 Pro $0.204/秒起（1.5 折），**首充赠送 25% 额度**（最高 $100）
- **官方 API：** ~$0.30+/请求，有地区限制

要获得最佳性价比，[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683&utm_source=github&utm_campaign=awesome-kling-ai) 以最低价格提供所有 20+ 可灵模型的访问。

</details>

<details>
<summary><strong>什么是可灵 O3？</strong></summary>

**可灵 O3** 是全球首个统一多模态创作工具。它支持：

- **参考图生视频：** 使用参考图片引导视频生成
- **视频编辑：** 使用 AI 修改和编辑现有视频
- **声音控制：** 生成和控制音频元素
- **元素参考：** 使用特定视觉元素作为参考
- **多输入：** 同时接受文本、视频、图像和主体输入

O3 通过 [Atlas Cloud API](https://www.atlascloud.ai?ref=JPM683&utm_source=github&utm_campaign=awesome-kling-ai) 提供 Pro 和 Std 两个版本。

</details>

<details>
<summary><strong>可灵支持哪些语言的音频？</strong></summary>

可灵 AI 支持 **5 种语言**的原生音频生成：

1. 🇨🇳 中文（普通话）
2. 🇺🇸 英语
3. 🇯🇵 日语
4. 🇰🇷 韩语
5. 🇪🇸 西班牙语

音频可以在可灵 2.6 及更高版本中与视频同步生成。

</details>

<details>
<summary><strong>可灵生成视频需要多长时间？</strong></summary>

生成时间因模型和设置而异：

| 模型 | 5s 视频 | 10s 视频 | 15s 视频 |
|:---|:---|:---|:---|
| 可灵 3.0 Pro | ~60-120秒 | ~120-240秒 | ~180-360秒 |
| 可灵 3.0 Std | ~30-60秒 | ~60-120秒 | ~90-180秒 |
| 可灵 O3 | ~45-90秒 | ~90-180秒 | — |
| 可灵 2.5 Turbo | ~15-30秒 | ~30-60秒 | — |

时间为估算值，可能因服务器负载而变化。[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683&utm_source=github&utm_campaign=awesome-kling-ai) 通常提供更快的推理速度。

</details>

---

## 🎬 立即开始使用可灵 AI

<div align="center">

**通过一个统一的 API 访问 20+ 可灵模型。**

| 优势 | 描述 |
|:---|:---|
| ✅ **无审查 AI** | 完全的创作自由——无内容限制 |
| ✅ **低至 1.5 折** | 业界最低的可灵 API 定价 |
| ✅ **全部模型** | 从可灵 3.0 到 O3，所有版本可用 |
| ✅ **首充赠送 25%** | 最高可获 $100 赠送额度 |
| ✅ **最快推理** | 优化基础设施，快速生成 |
| ✅ **20+ 模型** | 最全面的可灵模型覆盖 |

<br/>

### 👉 [在 Atlas Cloud 上体验可灵](https://www.atlascloud.ai?ref=JPM683&utm_source=github&utm_campaign=awesome-kling-ai)

*新用户首充赠送 25% 额度（最高 $100）*

</div>

---

## Star 历史

<div align="center">

[![Star History Chart](https://api.star-history.com/svg?repos=atlas-cloud/awesome-kling-ai&type=Date)](https://star-history.com/#atlas-cloud/awesome-kling-ai&Date)

</div>

---

## 贡献指南

欢迎贡献！请阅读以下指南：

1. **Fork** 本仓库
2. **创建**新分支（`git checkout -b feature/add-resource`）
3. **添加**你的资源到适当的部分
4. **提交**更改（`git commit -m '添加新资源'`）
5. **推送**到分支（`git push origin feature/add-resource`）
6. **发起** Pull Request

### 贡献规范

- 确保资源与可灵 AI 相关
- 为每个资源添加简短描述
- 检查链接是否有效
- 遵循现有的格式风格
- 推荐每个 Pull Request 只包含一个资源

---

## 许可证

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

本项目采用 MIT 许可证 — 详见 [LICENSE](LICENSE) 文件。

---

<div align="center">

**由可灵 AI 社区用 ❤️ 制作**

[⬆ 回到顶部](#awesome-kling-ai-)

</div>
