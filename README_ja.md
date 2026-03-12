<div align="center">

# Awesome Kling AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Stars](https://img.shields.io/github/stars/atlas-cloud/awesome-kling-ai?style=social)](https://github.com/atlas-cloud/awesome-kling-ai)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Last Commit](https://img.shields.io/github/last-commit/atlas-cloud/awesome-kling-ai)](https://github.com/atlas-cloud/awesome-kling-ai)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/atlas-cloud/awesome-kling-ai/pulls)

**🎬 Kling AI 動画生成の究極リソースハブ**

**Kling AI** に関する厳選されたリソース、ツール、プロンプト、チュートリアル、API リファレンスのコレクション — Kuaishou（快手）が開発した最先端のAI動画生成モデル。

[EN](./README.md) | [中文](./README_zh-CN.md) | [日本語](./README_ja.md) | [한국어](./README_ko.md)

---

**役に立ったら ⭐ スターをお願いします — 他の人にも見つけてもらえます！**

</div>

---

> 🚀 **[Atlas Cloud API](https://www.atlascloud.ai?ref=JPM683) で 20 以上の全 Kling モデルにアクセス** — 検閲なし、最安値（最大85%オフ）、最速推論。**初回チャージで25%ボーナス**（最大$100）。

> 🔒 **エンタープライズグレードのセキュリティ** — Atlas Cloud は **SOC I & II 認証取得** | **HIPAA 準拠** | 米国企業、99.9% 稼働率 SLA 保証。

> 🎨 **NSFW ホワイトリスト更新** — Seedance と Kling に加えて、**Vidu シリーズ**（Q3-Pro、Q3-Turbo）も Atlas Cloud の検閲なしコンテンツ生成ホワイトリストに追加されました。

---

## 目次

- [Kling AI とは？](#kling-ai-とは)
- [モデル進化タイムライン](#モデル進化タイムライン)
- [モデル比較表](#モデル比較表)
- [Kling vs 競合比較](#kling-vs-競合比較)
- [クイックスタート](#クイックスタート)
- [プロンプトガイド＆例](#プロンプトガイド例)
  - [シネマティックシーン](#-シネマティックシーン)
  - [キャラクターアニメーション](#-キャラクターアニメーション)
  - [特殊効果](#-特殊効果)
  - [コマーシャル＆マーケティング](#-コマーシャルマーケティング)
  - [自然＆風景](#-自然風景)
  - [抽象＆アート](#-抽象アート)
- [プロンプトエンジニアリングのコツ](#プロンプトエンジニアリングのコツ)
- [公式リソース](#公式リソース)
- [ツール＆統合](#ツール統合)
- [チュートリアル＆動画](#チュートリアル動画)
- [API 料金比較](#api-料金比較)
- [FAQ](#faq)
- [Kling AI で制作を始めよう](#-kling-ai-で制作を始めよう)
- [Star 履歴](#star-履歴)
- [貢献ガイド](#貢献ガイド)
- [ライセンス](#ライセンス)

---

## Kling AI とは？

**Kling AI** は、中国最大のショート動画プラットフォームの一つである**快手科技（Kuaishou Technology）** が開発した最先端のAI動画生成モデルです。2024年のリリース以来、Kling は世界で最も強力な動画生成システムの一つに急速に進化し、OpenAI の Sora や Google の Veo と肩を並べ、多くの面で凌駕しています。

### 主な特長

- 🎥 **ネイティブ4K解像度** — 業界初の4K動画生成、60FPS対応
- 🎬 **マルチショット生成** — 1つの15秒動画で最大6ショット、空間的連続性とキャラクターの一貫性を維持
- 🔊 **音声・映像同時生成** — 5言語のネイティブ音声対応（中国語、英語、日本語、韓国語、スペイン語）
- 🌐 **統合マルチモーダル制作** — テキスト、動画、画像、被写体入力を1つのモデルで（O1/O3）
- ✂️ **リファレンス動画生成** — 参考画像からの動画生成、既存動画の編集、サウンドコントロール（O3）

### コア機能

| 機能 | 説明 |
|:---|:---|
| **テキストから動画（T2V）** | テキスト説明から高品質な動画を生成 |
| **画像から動画（I2V）** | 静止画をダイナミックな動画に変換 |
| **リファレンス動画生成** | 参考画像を使用して動画生成のスタイルと内容をガイド |
| **動画編集** | AIでの既存動画の編集と修正 |
| **アバター生成** | リップシンク付きのトーキングヘッド動画を作成 |
| **モーション制御** | キャラクターとカメラの動きを精密に制御 |
| **サウンド制御** | 動画内の音声要素を生成・制御 |
| **エフェクト** | AI駆動の特殊効果を動画に適用 |
| **マルチショット** | シーンの連続性を持つマルチショットのナラティブを作成 |

---

## モデル進化タイムライン

Kling AI はリリース以来、急速な開発を遂げてきました：

```
                         Kling AI モデル進化
  ─────────────────────────────────────────────────────────────────

  2024 Q2   ██ Kling 1.0    — 初リリース、テキストから動画
            ██              — 720p、5秒クリップ

  2024 Q3   ████ Kling 1.5  — 品質と一貫性の向上
            ████            — より良いモーション理解

  2024 Q4   ██████ Kling 1.6 — 延長時間対応
            ██████           — 解像度強化

  2024 Q4   ████████ Kling 2.0 — メジャーアーキテクチャ更新
            ████████          — 1080p対応、品質大幅向上

  2025 Q1   ██████████ Kling 2.1 — 生成品質の洗練
            ██████████          — テキストレンダリング改善

  2025 Q2   ████████████ Kling 2.5 — Turboモード導入
            ████████████          — 高速生成

  2025 Q3   ██████████████ Kling 2.6 — 音声・映像同時生成
            ██████████████          — 初のネイティブ音声モデル

  2026 Q1   ████████████████ Kling 3.0 — ネイティブ4K @ 60FPS
            ████████████████          — 6マルチショット、15秒動画

  2026 Q1   ██████████████████ Kling O1 — 統合マルチモーダル
            ██████████████████          — テキスト+動画+画像入力

  2026 Q1   ████████████████████ Kling O3 — フルクリエイティブスイート
            ████████████████████          — リファレンス動画生成、編集、サウンド
```

---

## モデル比較表

<table>
<thead>
<tr>
<th>モデル</th>
<th>解像度</th>
<th>FPS</th>
<th>時間</th>
<th>音声</th>
<th>マルチショット</th>
<th>4K</th>
<th>主な特長</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Kling 3.0 Pro</strong></td>
<td>最大4K</td>
<td>60</td>
<td>5s / 10s / 15s</td>
<td>✅</td>
<td>✅ 最大6</td>
<td>✅</td>
<td>最高品質、最高解像度、マルチショットナラティブ</td>
</tr>
<tr>
<td><strong>Kling 3.0 Std</strong></td>
<td>最大4K</td>
<td>60</td>
<td>5s / 10s / 15s</td>
<td>✅</td>
<td>✅ 最大6</td>
<td>✅</td>
<td>品質と速度のバランス</td>
</tr>
<tr>
<td><strong>Kling O3 Pro</strong></td>
<td>1080p</td>
<td>30</td>
<td>5s / 10s</td>
<td>✅</td>
<td>✅</td>
<td>❌</td>
<td>リファレンス動画生成、動画編集、サウンド制御、エレメント参照</td>
</tr>
<tr>
<td><strong>Kling O3 Std</strong></td>
<td>1080p</td>
<td>30</td>
<td>5s / 10s</td>
<td>✅</td>
<td>✅</td>
<td>❌</td>
<td>コスパに優れた統合制作</td>
</tr>
<tr>
<td><strong>Kling O1</strong></td>
<td>1080p</td>
<td>30</td>
<td>5s / 10s</td>
<td>✅</td>
<td>❌</td>
<td>❌</td>
<td>統合マルチモーダル入力（テキスト、動画、画像、被写体）</td>
</tr>
<tr>
<td><strong>Kling 2.6 Pro</strong></td>
<td>1080p</td>
<td>30</td>
<td>5s / 10s</td>
<td>✅</td>
<td>❌</td>
<td>❌</td>
<td>初の音声・映像同時生成</td>
</tr>
<tr>
<td><strong>Kling 2.6 Std</strong></td>
<td>1080p</td>
<td>30</td>
<td>5s / 10s</td>
<td>✅</td>
<td>❌</td>
<td>❌</td>
<td>低価格で音声対応</td>
</tr>
<tr>
<td><strong>Kling 2.5 Turbo Pro</strong></td>
<td>1080p</td>
<td>30</td>
<td>5s / 10s</td>
<td>❌</td>
<td>❌</td>
<td>❌</td>
<td>高速生成、良好な品質</td>
</tr>
<tr>
<td><strong>Kling 2.1</strong></td>
<td>1080p</td>
<td>30</td>
<td>5s / 10s</td>
<td>❌</td>
<td>❌</td>
<td>❌</td>
<td>テキストレンダリング改善</td>
</tr>
<tr>
<td><strong>Kling 2.0</strong></td>
<td>1080p</td>
<td>30</td>
<td>5s</td>
<td>❌</td>
<td>❌</td>
<td>❌</td>
<td>アーキテクチャ更新</td>
</tr>
<tr>
<td><strong>Kling 1.6</strong></td>
<td>720p</td>
<td>30</td>
<td>5s</td>
<td>❌</td>
<td>❌</td>
<td>❌</td>
<td>延長時間対応</td>
</tr>
</tbody>
</table>

---

## Kling vs 競合比較

Kling AI は他の主要動画生成モデルとどう比較されるか？

| 特長 | Kling 3.0 | Seedance 1.0 | Sora | Veo 3 | Wan 2.1 |
|:---|:---:|:---:|:---:|:---:|:---:|
| **最大解像度** | **4K** | 1080p | 1080p | 4K | 1080p |
| **最大FPS** | **60** | 30 | 24 | 30 | 30 |
| **最大時間** | **15s** | 10s | 60s | 8s | 5s |
| **ネイティブ音声** | ✅ 5言語 | ✅ | ✅ | ✅ | ❌ |
| **マルチショット** | ✅ 6ショット | ❌ | ❌ | ❌ | ❌ |
| **画像から動画** | ✅ | ✅ | ✅ | ✅ | ✅ |
| **リファレンス動画** | ✅ (O3) | ❌ | ❌ | ❌ | ❌ |
| **動画編集** | ✅ (O3) | ❌ | ✅ | ❌ | ❌ |
| **アバター** | ✅ | ❌ | ❌ | ❌ | ❌ |
| **モーション制御** | ✅ | ❌ | ❌ | ❌ | ❌ |
| **APIアクセス** | ✅ | ✅ | ✅ | ✅ | ✅ |
| **検閲なしAPI** | ✅ [Atlas Cloud](https://www.atlascloud.ai?ref=JPM683) 経由 | 制限あり | 制限あり | 制限あり | 制限あり |

> 💡 **Kling 3.0 は、ネイティブ4K/60FPSとマルチショットナラティブをサポートする唯一のモデル**であり、2026年初頭時点で最も汎用性の高い動画生成モデルです。

---

## クイックスタート

### Atlas Cloud API の利用

[Atlas Cloud API](https://www.atlascloud.ai?ref=JPM683) は、全20以上のKlingモデルに業界最安値でアクセスでき、Kling AI動画生成を始める最速の方法です。

#### cURL

```bash
# Atlas Cloud API で Kling 3.0 動画を生成
curl -X POST "https://api.atlascloud.ai/api/v1/model/generateVideo" \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -d '{
    "model": "kling-v3-pro",
    "prompt": "A majestic eagle soaring through golden sunset clouds above snow-capped mountains, cinematic aerial shot, 4K, dramatic lighting",
    "duration": 10,
    "aspect_ratio": "16:9",
    "fps": 60
  }'
```

#### Python

```python
import requests
import time

# Atlas Cloud API 設定
API_KEY = "YOUR_API_KEY"
BASE_URL = "https://api.atlascloud.ai/api/v1/model"

def generate_video(prompt, model="kling-v3-pro", duration=10):
    """Kling AI で動画を生成"""
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
    """動画生成状態を確認"""
    response = requests.get(
        f"{BASE_URL}/status/{task_id}",
        headers={"Authorization": f"Bearer {API_KEY}"}
    )
    return response.json()

# 例：壮大な風景動画を生成
result = generate_video(
    prompt="Aerial drone shot sweeping over a pristine alpine lake at sunrise, "
           "mist rising from crystal clear water, snow-capped peaks reflected "
           "in the mirror-like surface, cinematic color grading, 4K ultra HD",
    model="kling-v3-pro",
    duration=10
)

print(f"タスク ID: {result['task_id']}")

# 生成状態のポーリング
while True:
    status = check_status(result['task_id'])
    if status['status'] == 'completed':
        print(f"動画 URL: {status['video_url']}")
        break
    elif status['status'] == 'failed':
        print(f"生成失敗: {status['error']}")
        break
    time.sleep(5)
```

#### JavaScript / Node.js

```javascript
// Atlas Cloud API - Kling 動画生成サンプル
const API_KEY = 'YOUR_API_KEY';
const BASE_URL = 'https://api.atlascloud.ai/api/v1/model';

// 動画を生成
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

// 生成状態を確認
async function checkStatus(taskId) {
  const response = await fetch(`${BASE_URL}/status/${taskId}`, {
    headers: { 'Authorization': `Bearer ${API_KEY}` }
  });
  return response.json();
}

// 使用例
(async () => {
  const result = await generateVideo(
    'A samurai standing on a cliff edge overlooking a vast valley, '
    + 'cherry blossoms falling in slow motion, wind flowing through robes, '
    + 'golden hour lighting, cinematic wide shot, 4K'
  );

  console.log(`タスク ID: ${result.task_id}`);

  // 動画生成完了を待機
  const poll = setInterval(async () => {
    const status = await checkStatus(result.task_id);
    if (status.status === 'completed') {
      console.log(`動画 URL: ${status.video_url}`);
      clearInterval(poll);
    } else if (status.status === 'failed') {
      console.log(`生成失敗: ${status.error}`);
      clearInterval(poll);
    }
  }, 5000);
})();
```

---

## プロンプトガイド＆例

> 📝 **注意：** これらのプロンプトは Kling 3.0 Pro 向けに最適化されています。他のモデルバージョンでは設定を適宜調整してください。

### 🎬 シネマティックシーン

<details>
<summary><strong>1. 壮大な山の日の出</strong> — ドローンスタイルの空撮</summary>

**プロンプト：**
> A breathtaking aerial drone shot ascending over misty mountain peaks at golden hour. The camera rises slowly to reveal an endless chain of snow-capped mountains stretching to the horizon. Volumetric fog fills the valleys below. Warm sunlight breaks through clouds, casting god rays across the landscape. Ultra cinematic, photorealistic, 4K.

**設定：**
| パラメータ | 値 |
|:---|:---|
| モデル | Kling 3.0 Pro |
| 時間 | 10s |
| アスペクト比 | 16:9 |
| FPS | 60 |

**難易度：** ⭐ 初級

**コツ：** Klingは風景ショットが得意です。"aerial drone shot"と"ascending"で滑らかな垂直カメラ移動が得られます。"volumetric fog"と"god rays"を追加すると大気感が劇的に向上します。

</details>

<details>
<summary><strong>2. フィルムノワール探偵シーン</strong> — キャラクター駆動のナラティブ</summary>

**プロンプト：**
> A detective in a long trench coat walks down a rain-soaked alley at night. Neon signs reflect off wet cobblestones in shades of red and blue. Steam rises from a manhole cover. The camera follows behind him in a slow tracking shot. Film noir style, moody lighting, high contrast, anamorphic lens flare.

**設定：**
| パラメータ | 値 |
|:---|:---|
| モデル | Kling 3.0 Pro |
| 時間 | 10s |
| アスペクト比 | 21:9 |
| FPS | 30 |

**難易度：** ⭐⭐ 中級

**コツ：** "tracking shot"で滑らかなフォローカメラが得られます。フィルムノワールスタイルのプロンプトはKlingで非常にうまく機能します。

</details>

<details>
<summary><strong>3. 水中王国</strong> — ファンタジーワールド</summary>

**プロンプト：**
> A magical underwater city with bioluminescent coral towers and crystal domes. Schools of exotic fish swim through archways of living coral. Shafts of sunlight penetrate from the surface above, creating dancing light patterns. A mermaid glides gracefully past ancient ruins. The camera slowly orbits the city revealing its grand scale. Fantasy, ethereal, dreamlike atmosphere.

**設定：**
| パラメータ | 値 |
|:---|:---|
| モデル | Kling 3.0 Pro |
| 時間 | 15s |
| アスペクト比 | 16:9 |
| FPS | 60 |

**難易度：** ⭐⭐⭐ 上級

**コツ：** Kling 3.0のマルチショットで15秒のナラティブを作成し、水中都市の異なる部分を展示できます。

</details>

<details>
<summary><strong>4. 東京カーチェイス</strong> — 高速アクション</summary>

**プロンプト：**
> A high-speed car chase through the neon-lit streets of Shibuya, Tokyo at night. A sleek sports car drifts around a corner, tires smoking, headlights cutting through the rain. The camera is mounted low, tracking alongside the car. Neon signs blur past in streaks of color. Cinematic, fast-paced, adrenaline-pumping, Michael Bay style.

**設定：**
| パラメータ | 値 |
|:---|:---|
| モデル | Kling 3.0 Pro |
| 時間 | 10s |
| アスペクト比 | 2.39:1 |
| FPS | 60 |

**難易度：** ⭐⭐⭐ 上級

**コツ：** 高速モーションシーンには60FPSが不可欠です。"tracking alongside"で被写体をセンターに維持します。

</details>

<details>
<summary><strong>5. 古代神殿の発見</strong> — インディ・ジョーンズ風</summary>

**プロンプト：**
> An explorer with a torch enters a vast ancient temple hidden deep in the jungle. The camera follows from behind as golden light reveals massive stone columns covered in intricate carvings. Dust particles float in the torchlight. The explorer looks up in awe as the camera tilts upward to reveal a colossal stone statue. Adventure film style, warm color grading.

**設定：**
| パラメータ | 値 |
|:---|:---|
| モデル | Kling 3.0 Pro |
| 時間 | 15s |
| アスペクト比 | 16:9 |
| FPS | 30 |

**難易度：** ⭐⭐ 中級

**コツ：** マルチショットが最適 — ショット1：神殿に入る、ショット2：柱を見せる、ショット3：像の登場。

</details>

### 🧑‍🎤 キャラクターアニメーション

<details>
<summary><strong>6. ニュースキャスター</strong> — リップシンクアバター</summary>

**プロンプト：**
> A professional female news anchor sitting at a modern news desk, delivering breaking news. She speaks clearly and confidently, making subtle hand gestures. Clean studio lighting, shallow depth of field on the background showing multiple monitors. Professional broadcast quality, 4K.

**設定：**
| パラメータ | 値 |
|:---|:---|
| モデル | Kling 2.6 Pro（アバター） |
| 時間 | 10s |
| アスペクト比 | 16:9 |
| 音声 | 有効（日本語） |

**難易度：** ⭐ 初級

**コツ：** アバター/トーキングヘッド動画には、Kling 2.6 Proのアバターモードが最高のリップシンクを実現します。

</details>

<details>
<summary><strong>7. ダンス振付</strong> — ダイナミックなフルボディモーション</summary>

**プロンプト：**
> A professional dancer performing a contemporary dance routine in an empty industrial warehouse. Dramatic side lighting creates bold shadows. The dancer executes fluid spins and leaps with perfect form. Slow motion on the most dramatic movements. Shot from multiple angles. Cinematic, artistic, powerful.

**設定：**
| パラメータ | 値 |
|:---|:---|
| モデル | Kling 3.0 Pro |
| 時間 | 15s |
| アスペクト比 | 9:16 |
| FPS | 60 |

**難易度：** ⭐⭐⭐ 上級

**コツ：** 60FPSでダンスの動きを美しくキャプチャできます。マルチショットで1つの動画内でアングルの切り替えが可能です。

</details>

<details>
<summary><strong>8. キャラクターウォークサイクル</strong> — アニメスタイル</summary>

**プロンプト：**
> A stylish anime character walking confidently down a cyberpunk city street. Side view tracking shot. The character has flowing silver hair and a glowing blue jacket. Neon reflections on the wet ground. Each step is deliberate and smooth. Anime style, Makoto Shinkai-inspired lighting.

**設定：**
| パラメータ | 値 |
|:---|:---|
| モデル | Kling 3.0 Pro |
| 時間 | 5s |
| アスペクト比 | 16:9 |
| FPS | 30 |

**難易度：** ⭐⭐ 中級

**コツ：** アニメスタイルはKlingとの相性が良いです。特定のアニメ監督を参照して一貫したスタイルを維持しましょう。

</details>

<details>
<summary><strong>9. 感情的な独白</strong> — クローズアップ演技</summary>

**プロンプト：**
> Extreme close-up of a middle-aged man's face as he delivers an emotional monologue. Tears well up in his eyes. Single source lighting from the left creates dramatic shadows across his weathered face. The camera slowly pushes in. Raw emotion, intimate, documentary style, shallow depth of field.

**設定：**
| パラメータ | 値 |
|:---|:---|
| モデル | Kling O3 Pro |
| 時間 | 10s |
| アスペクト比 | 16:9 |
| FPS | 30 |

**難易度：** ⭐⭐⭐ 上級

**コツ：** Kling O3は表情生成に優れています。"extreme close-up"と"slowly pushes in"で親密なキャラクターワークを実現します。

</details>

<details>
<summary><strong>10. 格闘アクション</strong> — 武術のアクション振付</summary>

**プロンプト：**
> Two martial artists engaged in an intense kung fu battle in a bamboo forest. One fighter executes a spinning kick while the other blocks and counters. Bamboo leaves scatter with each impact. Camera orbits around them in a dynamic 360-degree shot. Wire-fu style, Crouching Tiger Hidden Dragon aesthetic, slow motion at impact moments.

**設定：**
| パラメータ | 値 |
|:---|:---|
| モデル | Kling 3.0 Pro |
| 時間 | 10s |
| アスペクト比 | 2.39:1 |
| FPS | 60 |

**難易度：** ⭐⭐⭐ 上級

**コツ：** 武術シーケンスには60FPSが不可欠です。映画参照がスタイルの定義に役立ちます。

</details>

### ✨ 特殊効果

<details>
<summary><strong>11. バレットタイム</strong> — マトリックス風スローモーション</summary>

**プロンプト：**
> A woman in a black leather jacket dodges a punch in extreme slow motion. The camera orbits around her frozen in mid-dodge as water droplets and glass shards hang suspended in the air. Time gradually resumes as she completes the dodge. Matrix-style bullet time effect, dramatic lighting, dark background.

**設定：** モデル: Kling 3.0 Pro | 時間: 10s | アスペクト比: 16:9 | FPS: 60

**難易度：** ⭐⭐⭐ 上級

</details>

<details>
<summary><strong>12. シティタイムラプス</strong> — 昼から夜への変遷</summary>

**プロンプト：**
> Hyperlapse of a major city skyline transitioning from day to night. Clouds race across the sky as shadows sweep across skyscrapers. City lights gradually illuminate building by building. Traffic becomes rivers of red and white light trails. Stars emerge in the darkening sky. Smooth time-lapse, 4K, ultra sharp.

**設定：** モデル: Kling 3.0 Pro | 時間: 10s | アスペクト比: 16:9 | FPS: 30

**難易度：** ⭐⭐ 中級

</details>

<details>
<summary><strong>13. パーティクルストーム</strong> — 抽象VFX</summary>

**プロンプト：**
> Millions of golden particles swirling in a tornado formation against a dark void. The particles gradually form the shape of a phoenix, which then explodes outward in a brilliant burst of light. Embers and sparks cascade downward. Magical, mystical, particle simulation, volumetric lighting.

**設定：** モデル: Kling 3.0 Pro | 時間: 10s | アスペクト比: 16:9 | FPS: 60

**難易度：** ⭐⭐ 中級

</details>

<details>
<summary><strong>14. モーフィングオブジェクト</strong> — シームレスな変形</summary>

**プロンプト：**
> A red rose slowly morphs into a butterfly. Each petal unfurls and transforms into a delicate wing. The stem becomes the butterfly's body. The transformation is smooth and organic. The butterfly takes flight and dissolves into golden dust. White background, studio lighting, macro lens detail.

**設定：** モデル: Kling O3 Pro | 時間: 10s | アスペクト比: 1:1 | FPS: 30

**難易度：** ⭐⭐ 中級

</details>

<details>
<summary><strong>15. 雷嵐</strong> — 気象VFX</summary>

**プロンプト：**
> A massive supercell thunderstorm over flat prairie land at dusk. Multiple bolts of lightning strike simultaneously, illuminating the rotating wall cloud. Wind whips through tall grass in the foreground. The camera is low and steady, creating a dramatic perspective. Storm chaser footage style, raw, powerful, awe-inspiring.

**設定：** モデル: Kling 3.0 Pro | 時間: 10s | アスペクト比: 16:9 | FPS: 60

**難易度：** ⭐⭐ 中級

</details>

### 📦 コマーシャル＆マーケティング

<details>
<summary><strong>16. 商品紹介 - 香水</strong> — ラグジュアリー商品ショーケース</summary>

**プロンプト：**
> A luxury perfume bottle materializes from swirling golden mist on a marble surface. The camera slowly orbits the bottle as light refracts through the amber liquid. Rose petals and gold leaf particles float elegantly around the bottle. Premium commercial, luxury aesthetic, high-end fashion photography style.

**設定：** モデル: Kling 3.0 Pro | 時間: 10s | アスペクト比: 9:16 | FPS: 60

**難易度：** ⭐⭐ 中級

</details>

<details>
<summary><strong>17. フード CM</strong> — 食欲をそそるコンテンツ</summary>

**プロンプト：**
> A gourmet burger is assembled in dramatic slow motion. The bun drops first, followed by the lettuce, then a perfectly grilled patty with melting cheese oozing over the edges. Each ingredient is lit individually with a highlight. Fast food commercial style, mouth-watering, appetizing.

**設定：** モデル: Kling 3.0 Pro | 時間: 10s | アスペクト比: 1:1 | FPS: 60

**難易度：** ⭐⭐ 中級

</details>

<details>
<summary><strong>18. スニーカー発売</strong> — ダイナミックな商品プロモ</summary>

**プロンプト：**
> A futuristic sneaker floats and rotates in zero gravity against a black background. Energy waves pulse outward from the shoe. The camera performs a smooth 360-degree orbit. Holographic details on the shoe shimmer and shift color. Product launch trailer style, premium, futuristic.

**設定：** モデル: Kling 3.0 Pro | 時間: 10s | アスペクト比: 16:9 | FPS: 60

**難易度：** ⭐⭐ 中級

</details>

<details>
<summary><strong>19. 不動産ウォークスルー</strong> — 物件紹介</summary>

**プロンプト：**
> A smooth cinematic walkthrough of a modern luxury penthouse. The camera glides through the open-plan living room with floor-to-ceiling windows overlooking a city skyline at sunset. Warm interior lighting, designer furniture. The camera continues through to a balcony with an infinity pool. Architectural visualization, real estate commercial, steadicam shot.

**設定：** モデル: Kling 3.0 Pro | 時間: 15s | アスペクト比: 16:9 | FPS: 30

**難易度：** ⭐⭐⭐ 上級

</details>

<details>
<summary><strong>20. ファッションランウェイ</strong> — ファッション業界コンテンツ</summary>

**プロンプト：**
> A supermodel walks down a dimly lit fashion runway wearing an avant-garde haute couture gown. Dramatic backlighting creates a silhouette effect. Camera flashes pop from the audience on both sides. Fashion week, Vogue editorial, haute couture.

**設定：** モデル: Kling 3.0 Pro | 時間: 10s | アスペクト比: 9:16 | FPS: 30

**難易度：** ⭐⭐ 中級

</details>

### 🏞️ 自然＆風景

<details>
<summary><strong>21. オーロラ</strong> — 大気現象</summary>

**プロンプト：**
> The aurora borealis dances across the Arctic sky in shimmering curtains of green, purple, and pink. The lights are reflected in a perfectly still fjord below. Snow-covered mountains frame the scene. A lone cabin with a warm glowing window sits on the shore. Time-lapse speed, magical, serene, awe-inspiring.

**設定：** モデル: Kling 3.0 Pro | 時間: 10s | アスペクト比: 16:9 | FPS: 30

**難易度：** ⭐ 初級

</details>

<details>
<summary><strong>22-25. その他の自然＆風景プロンプト</strong></summary>

完全なプロンプトリストは [英語版 README](./README.md#-nature--landscape) をご参照ください。火山噴火、海の波のスローモーション、四季の変化、珊瑚礁の生態系など、詳細なプロンプトが含まれています。

</details>

### 🎨 抽象＆アート

<details>
<summary><strong>26-30. 抽象＆アートプロンプト</strong></summary>

完全なプロンプトリストは [英語版 README](./README.md#-abstract--artistic) をご参照ください。インク・イン・ウォーター、フラクタルズーム、リビングペインティング、幾何学変換、夢のシーケンスなどが含まれています。

</details>

---

## プロンプトエンジニアリングのコツ

### カメラ移動キーワード

| キーワード | 効果 | 最適な用途 |
|:---|:---|:---|
| `tracking shot` | カメラが被写体を追従 | キャラクターの歩行/走行 |
| `dolly zoom` | めまい/ズーム効果 | ドラマチックな演出 |
| `crane shot` | 垂直カメラ移動 | 俯瞰ショット |
| `steadicam` | 滑らかな手持ち感 | 室内ウォークスルー |
| `aerial drone shot` | 高角度空撮 | 風景 |
| `orbit shot` | カメラが被写体を周回 | 商品ショーケース |
| `push in` | カメラが被写体に接近 | 緊張感の演出 |
| `pull back / reveal` | カメラが離れる | 全体像の演出 |
| `whip pan` | 高速水平パン | トランジション |
| `Dutch angle` | 傾いたカメラ | 不安/緊張 |
| `rack focus` | 焦点の切り替え | 注意の誘導 |
| `slow motion` | 再生速度の低下 | アクション/ディテール |

### cfg_scale の最適化

| cfg_scale | 効果 | 使用ケース |
|:---|:---|:---|
| 3-5 | 創造的、自由な解釈 | 抽象アート、実験的 |
| 5-7 | **バランス（推奨）** | ほとんどのケース |
| 7-9 | プロンプトに忠実 | 技術的、特定シーン |
| 9-12 | 非常に忠実、品質低下の可能性 | 精度が重要な時 |

### 時間 vs 品質のトレードオフ

| 時間 | 品質への影響 | ベストプラクティス |
|:---|:---|:---|
| 5s | フレームごとの最高品質 | 短い商品ショット、ループ |
| 10s | 優れた品質 | ほとんどのケース |
| 15s | 良好な品質、マルチショット | ナラティブ、ウォークスルー |

> 💡 **プロのコツ：** 最高品質を得るには、5秒で生成して複数のクリップをつなぎ合わせましょう。手軽さを優先するなら、Kling 3.0の15秒マルチショットモードを使いましょう。

---

## 公式リソース

- 🌐 [Kling AI 公式サイト](https://klingai.com/) — Kling AI 公式プラットフォーム
- 🏢 [快手オープンプラットフォーム](https://open.kuaishou.com/) — 快手開発者プラットフォーム
- 📖 [Kling API ドキュメント](https://docs.qingque.cn/d/home/eZQBMqNQR3bLYU9FB0kFv-wQK) — 公式APIドキュメント
- 🎨 [Kling AI クリエイティブセンター](https://klingai.com/global/explore) — コミュニティ作品とインスピレーション
- 📱 [Kling AI アプリ](https://klingai.com/global/download) — Kling AI モバイルアプリ

---

## ツール＆統合

### ComfyUI ノード

- 🔧 [ComfyUI-KlingAI](https://github.com/KwaiVGI/ComfyUI-KlingAI) — 公式 ComfyUI ノード
- 🔧 [ComfyUI-Kling-API](https://github.com/yolain/ComfyUI-Kling-API) — コミュニティ ComfyUI 統合

### SDK ＆ ラッパー

- 🐍 [kling-python-sdk](https://github.com/KwaiVGI/kling-python-sdk) — 公式 Python SDK
- 📦 [kling-js](https://github.com/KwaiVGI/kling-js) — 公式 JavaScript/Node.js SDK

### サードパーティツール

- 🛠️ [Atlas Cloud API](https://www.atlascloud.ai?ref=JPM683) — 全Klingモデルへの統合API、最安値
- 🛠️ [Kling プロンプトジェネレーター](https://github.com/search?q=kling+prompt+generator) — AI駆動のプロンプト生成ツール
- 🖼️ [Kling バッチプロセッサー](https://github.com/search?q=kling+batch) — バッチ動画生成ツール

---

## チュートリアル＆動画

### 入門ガイド

- 📺 [Kling AI 初心者ガイド](https://www.youtube.com/results?search_query=kling+ai+tutorial+beginner) — YouTube 初心者チュートリアル
- 📺 [Kling 3.0 新機能ウォークスルー](https://www.youtube.com/results?search_query=kling+3.0+tutorial) — 最新バージョンチュートリアル
- 📝 [Kling API の使い方](https://www.atlascloud.ai?ref=JPM683) — ステップバイステップ API 統合ガイド

### 上級テクニック

- 📺 [Kling マルチショット映像制作](https://www.youtube.com/results?search_query=kling+multi+shot+video) — マルチショットでナラティブを作成
- 📺 [Kling vs Sora 比較](https://www.youtube.com/results?search_query=kling+vs+sora) — 品質の横並び比較
- 📺 [Kling 商業動画制作](https://www.youtube.com/results?search_query=kling+ai+commercial) — ビジネス活用

---

## API 料金比較

> 💰 2026年3月更新

| プロバイダー | Kling 3.0 Pro (T2V) | Kling 3.0 Std (T2V) | Kling O3 Pro | 全モデル | 備考 |
|:---|:---:|:---:|:---:|:---:|:---|
| **[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683)** | **$0.204** | **より低い** | **✅ 利用可能** | **✅ 20+モデル** | ✅ 検閲なし、最速、85%オフ、初回チャージ25%ボーナス |
| 公式 API | ~$0.30+ | ~$0.20+ | 制限あり | ~10モデル | 地域制限あり、検閲あり |
| プロバイダー B | $0.25-0.40 | 不定 | 制限あり | ~5モデル | モデル選択が限定的 |
| プロバイダー C | $0.30-0.45 | 不定 | ❌ | ~3モデル | モデルが少ない、推論が遅い |

> 💡 **[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683)** は業界最安値で最も包括的なKlingモデルカバレッジを提供しています。新規ユーザーは**初回チャージで25%ボーナス**（最大$100ボーナス）を獲得できます。

### Atlas Cloud vs fal.ai 料金比較

| モデル | fal.ai 価格 | Atlas Cloud 価格 | 節約額 |
|:------|:------------|:-----------------|:---------|
| **Kling** | $0.224/秒 (5秒 = $1.12) | $0.204/秒から | **82% 安い** |
| **Seedance** | ~$0.26/動画 | $0.222/秒から | **15% 安い** |
| **Wan 2.5** | $0.05/秒 (5秒 = $0.25) | $0.05/秒から | **80% 安い** |
| **Wan 2.6** | 類似価格 | $0.07/秒から | 競争力あり |
| **Veo 3** | $0.40/秒 (8秒 = $3.20) | 近日公開 | 準備中 |
| **Vidu Q3-Pro** | — | $0.06/秒から | Atlas 限定 |
| **Vidu Q3-Turbo** | — | $0.034/秒から | Atlas 限定 |

*表示価格は最低価格です。より高い解像度や長い動画は追加料金が発生する場合があります。*

> 💡 Atlas Cloud は全主要動画モデルで**最安値**を提供しています。fal.ai から乗り換えて、動画生成コストを最大 **82%** 節約しましょう。

---

## FAQ

<details>
<summary><strong>Kling AI とは何ですか？</strong></summary>

**Kling AI** は**快手科技（Kuaishou Technology）**が開発した先進的なAI動画生成モデルです。テキストプロンプトから高品質な動画を作成（テキストから動画）、静止画をアニメーション化（画像から動画）、動画編集タスクを実行できます。最新バージョン **Kling 3.0** は、ネイティブ4K解像度、60FPS、1つの15秒動画に最大6つのマルチショットシーケンスをサポートしており、利用可能な最も強力な動画生成モデルの一つです。

</details>

<details>
<summary><strong>Kling API はどうやって使いますか？</strong></summary>

全てのKlingモデルにアクセスする最も簡単な方法は [Atlas Cloud API](https://www.atlascloud.ai?ref=JPM683) です：

1. [Atlas Cloud](https://www.atlascloud.ai?ref=JPM683) で**アカウント登録**
2. ダッシュボードから **API キーを取得**
3. `https://api.atlascloud.ai/api/v1/model/generateVideo` に **API コールを実行**
4. Kling 3.0 ProからO3まで、全バージョンから**モデルを選択**

コード例は [クイックスタート](#クイックスタート) セクションをご覧ください。

</details>

<details>
<summary><strong>Kling vs Sora vs Seedance — どれが最良ですか？</strong></summary>

各モデルに強みがあります：

| 側面 | Kling 3.0 | Sora | Seedance |
|:---|:---|:---|:---|
| **解像度** | **4K**（最高） | 1080p | 1080p |
| **FPS** | **60**（最高） | 24 | 30 |
| **マルチショット** | **✅ 6ショット**（唯一） | ❌ | ❌ |
| **時間** | 15s | **60s**（最長） | 10s |
| **音声** | ✅ 5言語 | ✅ | ✅ |

**Kling 3.0** は高解像度・高FPSの商業コンテンツに最適。**Sora** は長尺ナラティブに優れています。最安値で全Klingモデルにアクセスするには [Atlas Cloud](https://www.atlascloud.ai?ref=JPM683) をご利用ください。

</details>

<details>
<summary><strong>Kling AI は無料ですか？</strong></summary>

Kling AI は公式プラットフォームで限定的な無料クレジットを提供しています。APIアクセスの料金はプロバイダーにより異なります：

- **[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683)：** Kling 3.0 Pro $0.204/秒から（85%オフ）、**初回チャージで25%ボーナス**（最大$100）
- **公式 API：** ~$0.30+/秒から、地域制限あり

</details>

<details>
<summary><strong>Kling はどの言語の音声をサポートしていますか？</strong></summary>

Kling AI は **5言語** のネイティブ音声生成をサポートしています：

1. 🇨🇳 中国語（普通話）
2. 🇺🇸 英語
3. 🇯🇵 日本語
4. 🇰🇷 韓国語
5. 🇪🇸 スペイン語

</details>

---

## 🎬 Kling AI で制作を始めよう

<div align="center">

**1つの統合APIで20以上のKlingモデルにアクセス。**

| メリット | 説明 |
|:---|:---|
| ✅ **検閲なしAI** | 完全な創作の自由 — コンテンツ制限なし |
| ✅ **最大85%オフ** | 業界最安のKling API料金 |
| ✅ **全モデル** | Kling 3.0からO3まで、全バージョン利用可能 |
| ✅ **25%ボーナス** | 初回チャージで最大$100ボーナス |
| ✅ **最速推論** | 最適化されたインフラストラクチャ |
| ✅ **20+モデル** | 最も包括的なKlingモデルカバレッジ |

<br/>

### 👉 [Atlas Cloud で Kling を試す](https://www.atlascloud.ai?ref=JPM683)

*新規ユーザーは初回チャージで25%ボーナス（最大$100）*

</div>

---

## Star 履歴

<div align="center">

[![Star History Chart](https://api.star-history.com/svg?repos=atlas-cloud/awesome-kling-ai&type=Date)](https://star-history.com/#atlas-cloud/awesome-kling-ai&Date)

</div>

---

## 貢献ガイド

貢献を歓迎します！以下のガイドラインをお読みください：

1. このリポジトリを **Fork**
2. 新しいブランチを **作成**（`git checkout -b feature/add-resource`）
3. 適切なセクションにリソースを **追加**
4. 変更を **コミット**（`git commit -m 'Add new resource'`）
5. ブランチに **プッシュ**（`git push origin feature/add-resource`）
6. **Pull Request** を作成

---

## ライセンス

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

このプロジェクトは MIT ライセンスの下でライセンスされています — 詳細は [LICENSE](LICENSE) ファイルをご覧ください。

---

<div align="center">

**Kling AI コミュニティが ❤️ をこめて制作**

[⬆ トップに戻る](#awesome-kling-ai-)

</div>
