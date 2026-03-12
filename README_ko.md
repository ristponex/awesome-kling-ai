<div align="center">

# Awesome Kling AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Stars](https://img.shields.io/github/stars/atlas-cloud/awesome-kling-ai?style=social)](https://github.com/atlas-cloud/awesome-kling-ai)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Last Commit](https://img.shields.io/github/last-commit/atlas-cloud/awesome-kling-ai)](https://github.com/atlas-cloud/awesome-kling-ai)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/atlas-cloud/awesome-kling-ai/pulls)

**🎬 Kling AI 영상 생성 궁극의 리소스 허브**

**Kling AI** 관련 엄선된 리소스, 도구, 프롬프트, 튜토리얼 및 API 레퍼런스 모음 — Kuaishou(快手)가 개발한 최첨단 AI 영상 생성 모델.

[EN](./README.md) | [中文](./README_zh-CN.md) | [日本語](./README_ja.md) | [한국어](./README_ko.md)

---

**유용하다면 ⭐ 스타를 눌러주세요 — 더 많은 사람들이 발견할 수 있습니다!**

</div>

---

> 🚀 **[Atlas Cloud API](https://www.atlascloud.ai?ref=JPM683)로 20개 이상의 모든 Kling 모델에 접근** — 검열 없음, 최저가(최대 85% 할인), 최고속 추론. **첫 충전 시 25% 보너스** (최대 $100).

> 🔒 **엔터프라이즈급 보안** — Atlas Cloud는 **SOC I & II 인증** | **HIPAA 준수** | 미국 기업, 99.9% 가동률 SLA 보장.

> 🎨 **NSFW 화이트리스트 업데이트** — Seedance와 Kling 외에도 **Vidu 시리즈** (Q3-Pro, Q3-Turbo)가 Atlas Cloud의 무검열 콘텐츠 생성 화이트리스트에 추가되었습니다.

---

## 목차

- [Kling AI란?](#kling-ai란)
- [모델 발전 타임라인](#모델-발전-타임라인)
- [모델 비교표](#모델-비교표)
- [Kling vs 경쟁사 비교](#kling-vs-경쟁사-비교)
- [빠른 시작](#빠른-시작)
- [프롬프트 가이드 및 예시](#프롬프트-가이드-및-예시)
  - [시네마틱 씬](#-시네마틱-씬)
  - [캐릭터 애니메이션](#-캐릭터-애니메이션)
  - [특수 효과](#-특수-효과)
  - [커머셜 & 마케팅](#-커머셜--마케팅)
  - [자연 & 풍경](#-자연--풍경)
  - [추상 & 아트](#-추상--아트)
- [프롬프트 엔지니어링 팁](#프롬프트-엔지니어링-팁)
- [공식 리소스](#공식-리소스)
- [도구 & 통합](#도구--통합)
- [튜토리얼 & 영상](#튜토리얼--영상)
- [API 가격 비교](#api-가격-비교)
- [FAQ](#faq)
- [Kling AI로 제작 시작하기](#-kling-ai로-제작-시작하기)
- [Star 히스토리](#star-히스토리)
- [기여 가이드](#기여-가이드)
- [라이선스](#라이선스)

---

## Kling AI란?

**Kling AI**는 중국 최대 숏 영상 플랫폼 중 하나인 **Kuaishou Technology(快手科技)**가 개발한 최첨단 AI 영상 생성 모델입니다. 2024년 출시 이후, Kling은 세계에서 가장 강력한 영상 생성 시스템 중 하나로 빠르게 발전하여, OpenAI의 Sora, Google의 Veo 등과 경쟁하며 여러 면에서 이를 능가하고 있습니다.

### 핵심 하이라이트

- 🎥 **네이티브 4K 해상도** — 업계 최초 4K 영상 생성, 60FPS
- 🎬 **멀티 샷 생성** — 하나의 15초 영상에서 최대 6개 샷, 공간 연속성과 캐릭터 일관성 유지
- 🔊 **오디오-비디오 동시 생성** — 5개 언어 네이티브 오디오 지원 (중국어, 영어, 일본어, 한국어, 스페인어)
- 🌐 **통합 멀티모달 제작** — 텍스트, 영상, 이미지, 주제 입력을 하나의 모델로 (O1/O3)
- ✂️ **레퍼런스-투-비디오** — 참조 이미지에서 영상 생성, 기존 영상 편집, 사운드 제어 (O3)

### 핵심 기능

| 기능 | 설명 |
|:---|:---|
| **텍스트-투-비디오 (T2V)** | 텍스트 설명에서 고품질 영상 생성 |
| **이미지-투-비디오 (I2V)** | 정적 이미지를 동적 영상으로 변환 |
| **레퍼런스-투-비디오** | 참조 이미지를 사용하여 영상 생성의 스타일과 콘텐츠 가이드 |
| **영상 편집** | AI로 기존 영상 편집 및 수정 |
| **아바타 생성** | 립싱크가 있는 토킹헤드 영상 제작 |
| **모션 제어** | 캐릭터와 카메라 동작을 정밀하게 제어 |
| **사운드 제어** | 영상 내 오디오 요소 생성 및 제어 |
| **이펙트** | AI 기반 특수 효과를 영상에 적용 |
| **멀티 샷** | 씬 연속성이 있는 멀티 샷 내러티브 제작 |

---

## 모델 발전 타임라인

Kling AI는 출시 이후 빠른 발전을 거듭해왔습니다:

```
                         Kling AI 모델 발전
  ─────────────────────────────────────────────────────────────────

  2024 Q2   ██ Kling 1.0    — 첫 출시, 텍스트-투-비디오
            ██              — 720p, 5초 클립

  2024 Q3   ████ Kling 1.5  — 품질과 일관성 향상
            ████            — 더 나은 모션 이해

  2024 Q4   ██████ Kling 1.6 — 확장된 시간 지원
            ██████           — 해상도 강화

  2024 Q4   ████████ Kling 2.0 — 주요 아키텍처 업그레이드
            ████████          — 1080p 지원, 품질 대폭 향상

  2025 Q1   ██████████ Kling 2.1 — 생성 품질 개선
            ██████████          — 텍스트 렌더링 개선

  2025 Q2   ████████████ Kling 2.5 — Turbo 모드 도입
            ████████████          — 빠른 생성 속도

  2025 Q3   ██████████████ Kling 2.6 — 오디오-비디오 동시 생성
            ██████████████          — 최초의 네이티브 오디오 모델

  2026 Q1   ████████████████ Kling 3.0 — 네이티브 4K @ 60FPS
            ████████████████          — 6 멀티 샷, 15초 영상

  2026 Q1   ██████████████████ Kling O1 — 통합 멀티모달
            ██████████████████          — 텍스트+영상+이미지 입력

  2026 Q1   ████████████████████ Kling O3 — 풀 크리에이티브 스위트
            ████████████████████          — 레퍼런스 영상, 편집, 사운드
```

---

## 모델 비교표

<table>
<thead>
<tr>
<th>모델</th>
<th>해상도</th>
<th>FPS</th>
<th>시간</th>
<th>오디오</th>
<th>멀티 샷</th>
<th>4K</th>
<th>주요 특징</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Kling 3.0 Pro</strong></td>
<td>최대 4K</td>
<td>60</td>
<td>5s / 10s / 15s</td>
<td>✅</td>
<td>✅ 최대 6</td>
<td>✅</td>
<td>최고 품질, 최고 해상도, 멀티 샷 내러티브</td>
</tr>
<tr>
<td><strong>Kling 3.0 Std</strong></td>
<td>최대 4K</td>
<td>60</td>
<td>5s / 10s / 15s</td>
<td>✅</td>
<td>✅ 최대 6</td>
<td>✅</td>
<td>품질과 속도의 균형</td>
</tr>
<tr>
<td><strong>Kling O3 Pro</strong></td>
<td>1080p</td>
<td>30</td>
<td>5s / 10s</td>
<td>✅</td>
<td>✅</td>
<td>❌</td>
<td>레퍼런스-투-비디오, 영상 편집, 사운드 제어, 요소 참조</td>
</tr>
<tr>
<td><strong>Kling O3 Std</strong></td>
<td>1080p</td>
<td>30</td>
<td>5s / 10s</td>
<td>✅</td>
<td>✅</td>
<td>❌</td>
<td>가성비 좋은 통합 제작</td>
</tr>
<tr>
<td><strong>Kling O1</strong></td>
<td>1080p</td>
<td>30</td>
<td>5s / 10s</td>
<td>✅</td>
<td>❌</td>
<td>❌</td>
<td>통합 멀티모달 입력 (텍스트, 영상, 이미지, 주제)</td>
</tr>
<tr>
<td><strong>Kling 2.6 Pro</strong></td>
<td>1080p</td>
<td>30</td>
<td>5s / 10s</td>
<td>✅</td>
<td>❌</td>
<td>❌</td>
<td>최초의 오디오-비디오 동시 생성</td>
</tr>
<tr>
<td><strong>Kling 2.6 Std</strong></td>
<td>1080p</td>
<td>30</td>
<td>5s / 10s</td>
<td>✅</td>
<td>❌</td>
<td>❌</td>
<td>합리적인 가격의 오디오 버전</td>
</tr>
<tr>
<td><strong>Kling 2.5 Turbo Pro</strong></td>
<td>1080p</td>
<td>30</td>
<td>5s / 10s</td>
<td>❌</td>
<td>❌</td>
<td>❌</td>
<td>빠른 생성, 좋은 품질</td>
</tr>
<tr>
<td><strong>Kling 2.1</strong></td>
<td>1080p</td>
<td>30</td>
<td>5s / 10s</td>
<td>❌</td>
<td>❌</td>
<td>❌</td>
<td>텍스트 렌더링 개선</td>
</tr>
<tr>
<td><strong>Kling 2.0</strong></td>
<td>1080p</td>
<td>30</td>
<td>5s</td>
<td>❌</td>
<td>❌</td>
<td>❌</td>
<td>아키텍처 업그레이드</td>
</tr>
<tr>
<td><strong>Kling 1.6</strong></td>
<td>720p</td>
<td>30</td>
<td>5s</td>
<td>❌</td>
<td>❌</td>
<td>❌</td>
<td>확장된 시간 지원</td>
</tr>
</tbody>
</table>

---

## Kling vs 경쟁사 비교

Kling AI는 다른 주요 영상 생성 모델과 어떻게 비교되는가?

| 특징 | Kling 3.0 | Seedance 1.0 | Sora | Veo 3 | Wan 2.1 |
|:---|:---:|:---:|:---:|:---:|:---:|
| **최대 해상도** | **4K** | 1080p | 1080p | 4K | 1080p |
| **최대 FPS** | **60** | 30 | 24 | 30 | 30 |
| **최대 시간** | **15s** | 10s | 60s | 8s | 5s |
| **네이티브 오디오** | ✅ 5개 언어 | ✅ | ✅ | ✅ | ❌ |
| **멀티 샷** | ✅ 6 샷 | ❌ | ❌ | ❌ | ❌ |
| **이미지-투-비디오** | ✅ | ✅ | ✅ | ✅ | ✅ |
| **레퍼런스 영상** | ✅ (O3) | ❌ | ❌ | ❌ | ❌ |
| **영상 편집** | ✅ (O3) | ❌ | ✅ | ❌ | ❌ |
| **아바타** | ✅ | ❌ | ❌ | ❌ | ❌ |
| **모션 제어** | ✅ | ❌ | ❌ | ❌ | ❌ |
| **API 접근** | ✅ | ✅ | ✅ | ✅ | ✅ |
| **검열 없는 API** | ✅ [Atlas Cloud](https://www.atlascloud.ai?ref=JPM683) 경유 | 제한적 | 제한적 | 제한적 | 제한적 |

> 💡 **Kling 3.0은 네이티브 4K/60FPS와 멀티 샷 내러티브를 지원하는 유일한 모델**로, 2026년 초 기준 가장 다재다능한 영상 생성 모델입니다.

---

## 빠른 시작

### Atlas Cloud API 사용

[Atlas Cloud API](https://www.atlascloud.ai?ref=JPM683)는 20개 이상의 모든 Kling 모델에 업계 최저가로 접근할 수 있어, Kling AI 영상 생성을 시작하는 가장 빠른 방법입니다.

#### cURL

```bash
# Atlas Cloud API로 Kling 3.0 영상 생성
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

# Atlas Cloud API 설정
API_KEY = "YOUR_API_KEY"
BASE_URL = "https://api.atlascloud.ai/api/v1/model"

def generate_video(prompt, model="kling-v3-pro", duration=10):
    """Kling AI로 영상 생성"""
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
    """영상 생성 상태 확인"""
    response = requests.get(
        f"{BASE_URL}/status/{task_id}",
        headers={"Authorization": f"Bearer {API_KEY}"}
    )
    return response.json()

# 예시: 장대한 풍경 영상 생성
result = generate_video(
    prompt="Aerial drone shot sweeping over a pristine alpine lake at sunrise, "
           "mist rising from crystal clear water, snow-capped peaks reflected "
           "in the mirror-like surface, cinematic color grading, 4K ultra HD",
    model="kling-v3-pro",
    duration=10
)

print(f"작업 ID: {result['task_id']}")

# 생성 상태 폴링
while True:
    status = check_status(result['task_id'])
    if status['status'] == 'completed':
        print(f"영상 URL: {status['video_url']}")
        break
    elif status['status'] == 'failed':
        print(f"생성 실패: {status['error']}")
        break
    time.sleep(5)
```

#### JavaScript / Node.js

```javascript
// Atlas Cloud API - Kling 영상 생성 예시
const API_KEY = 'YOUR_API_KEY';
const BASE_URL = 'https://api.atlascloud.ai/api/v1/model';

// 영상 생성
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

// 생성 상태 확인
async function checkStatus(taskId) {
  const response = await fetch(`${BASE_URL}/status/${taskId}`, {
    headers: { 'Authorization': `Bearer ${API_KEY}` }
  });
  return response.json();
}

// 사용 예시
(async () => {
  const result = await generateVideo(
    'A samurai standing on a cliff edge overlooking a vast valley, '
    + 'cherry blossoms falling in slow motion, wind flowing through robes, '
    + 'golden hour lighting, cinematic wide shot, 4K'
  );

  console.log(`작업 ID: ${result.task_id}`);

  // 영상 생성 완료 대기
  const poll = setInterval(async () => {
    const status = await checkStatus(result.task_id);
    if (status.status === 'completed') {
      console.log(`영상 URL: ${status.video_url}`);
      clearInterval(poll);
    } else if (status.status === 'failed') {
      console.log(`생성 실패: ${status.error}`);
      clearInterval(poll);
    }
  }, 5000);
})();
```

---

## 프롬프트 가이드 및 예시

> 📝 **참고:** 이 프롬프트들은 Kling 3.0 Pro에 최적화되어 있습니다. 다른 모델 버전에서는 설정을 적절히 조정하세요.

### 🎬 시네마틱 씬

<details>
<summary><strong>1. 장대한 산 일출</strong> — 드론 스타일 항공 촬영</summary>

**프롬프트:**
> A breathtaking aerial drone shot ascending over misty mountain peaks at golden hour. The camera rises slowly to reveal an endless chain of snow-capped mountains stretching to the horizon. Volumetric fog fills the valleys below. Warm sunlight breaks through clouds, casting god rays across the landscape. Ultra cinematic, photorealistic, 4K.

**설정:**
| 매개변수 | 값 |
|:---|:---|
| 모델 | Kling 3.0 Pro |
| 시간 | 10s |
| 종횡비 | 16:9 |
| FPS | 60 |

**난이도:** ⭐ 초급

**팁:** Kling은 풍경 샷을 매우 잘 처리합니다. "aerial drone shot"과 "ascending"으로 부드러운 수직 카메라 이동을 얻을 수 있습니다. "volumetric fog"과 "god rays"를 추가하면 대기감이 극적으로 향상됩니다.

</details>

<details>
<summary><strong>2. 필름 누아르 탐정 씬</strong> — 캐릭터 중심 내러티브</summary>

**프롬프트:**
> A detective in a long trench coat walks down a rain-soaked alley at night. Neon signs reflect off wet cobblestones in shades of red and blue. Steam rises from a manhole cover. The camera follows behind him in a slow tracking shot. Film noir style, moody lighting, high contrast, anamorphic lens flare.

**설정:**
| 매개변수 | 값 |
|:---|:---|
| 모델 | Kling 3.0 Pro |
| 시간 | 10s |
| 종횡비 | 21:9 |
| FPS | 30 |

**난이도:** ⭐⭐ 중급

**팁:** "tracking shot"으로 부드러운 팔로우 카메라를 얻을 수 있습니다. 필름 누아르 스타일 프롬프트는 Kling에서 매우 잘 작동합니다.

</details>

<details>
<summary><strong>3. 수중 왕국</strong> — 판타지 월드</summary>

**프롬프트:**
> A magical underwater city with bioluminescent coral towers and crystal domes. Schools of exotic fish swim through archways of living coral. Shafts of sunlight penetrate from the surface above, creating dancing light patterns. A mermaid glides gracefully past ancient ruins. The camera slowly orbits the city revealing its grand scale. Fantasy, ethereal, dreamlike atmosphere.

**설정:**
| 매개변수 | 값 |
|:---|:---|
| 모델 | Kling 3.0 Pro |
| 시간 | 15s |
| 종횡비 | 16:9 |
| FPS | 60 |

**난이도:** ⭐⭐⭐ 고급

**팁:** Kling 3.0의 멀티 샷으로 15초 내러티브를 만들어 수중 도시의 여러 부분을 보여줄 수 있습니다.

</details>

<details>
<summary><strong>4. 도쿄 카 체이스</strong> — 고속 액션</summary>

**프롬프트:**
> A high-speed car chase through the neon-lit streets of Shibuya, Tokyo at night. A sleek sports car drifts around a corner, tires smoking, headlights cutting through the rain. The camera is mounted low, tracking alongside the car. Neon signs blur past in streaks of color. Cinematic, fast-paced, adrenaline-pumping, Michael Bay style.

**설정:**
| 매개변수 | 값 |
|:---|:---|
| 모델 | Kling 3.0 Pro |
| 시간 | 10s |
| 종횡비 | 2.39:1 |
| FPS | 60 |

**난이도:** ⭐⭐⭐ 고급

**팁:** 빠른 모션 씬에는 60FPS가 필수적입니다. "tracking alongside"로 피사체를 중앙에 유지합니다.

</details>

<details>
<summary><strong>5. 고대 사원 발견</strong> — 인디아나 존스 스타일</summary>

**프롬프트:**
> An explorer with a torch enters a vast ancient temple hidden deep in the jungle. The camera follows from behind as golden light reveals massive stone columns covered in intricate carvings. Dust particles float in the torchlight. The explorer looks up in awe as the camera tilts upward to reveal a colossal stone statue. Adventure film style, warm color grading.

**설정:**
| 매개변수 | 값 |
|:---|:---|
| 모델 | Kling 3.0 Pro |
| 시간 | 15s |
| 종횡비 | 16:9 |
| FPS | 30 |

**난이도:** ⭐⭐ 중급

**팁:** 멀티 샷이 여기서 잘 맞습니다 — 샷 1: 사원 입장, 샷 2: 기둥 공개, 샷 3: 석상 등장.

</details>

### 🧑‍🎤 캐릭터 애니메이션

<details>
<summary><strong>6. 뉴스 앵커</strong> — 립싱크 아바타</summary>

**프롬프트:**
> A professional female news anchor sitting at a modern news desk, delivering breaking news. She speaks clearly and confidently, making subtle hand gestures. Clean studio lighting, shallow depth of field on the background showing multiple monitors. Professional broadcast quality, 4K.

**설정:**
| 매개변수 | 값 |
|:---|:---|
| 모델 | Kling 2.6 Pro (아바타) |
| 시간 | 10s |
| 종횡비 | 16:9 |
| 오디오 | 활성화 (한국어) |

**난이도:** ⭐ 초급

**팁:** 아바타/토킹헤드 영상은 Kling 2.6 Pro의 아바타 모드가 최고의 립싱크를 제공합니다.

</details>

<details>
<summary><strong>7. 댄스 안무</strong> — 다이나믹한 풀바디 모션</summary>

**프롬프트:**
> A professional dancer performing a contemporary dance routine in an empty industrial warehouse. Dramatic side lighting creates bold shadows. The dancer executes fluid spins and leaps with perfect form. Slow motion on the most dramatic movements. Shot from multiple angles. Cinematic, artistic, powerful.

**설정:**
| 매개변수 | 값 |
|:---|:---|
| 모델 | Kling 3.0 Pro |
| 시간 | 15s |
| 종횡비 | 9:16 |
| FPS | 60 |

**난이도:** ⭐⭐⭐ 고급

**팁:** 60FPS로 댄스 동작을 아름답게 캡처할 수 있습니다. 멀티 샷으로 단일 영상 내에서 앵글 전환이 가능합니다.

</details>

<details>
<summary><strong>8-10. 추가 캐릭터 프롬프트</strong></summary>

전체 프롬프트 리스트는 [영어 README](./README.md#-character-animation)를 참조하세요. 캐릭터 워크 사이클, 감정적 독백, 무술 액션 등 상세한 프롬프트가 포함되어 있습니다.

</details>

### ✨ 특수 효과

<details>
<summary><strong>11. 불렛 타임</strong> — 매트릭스 스타일 슬로우 모션</summary>

**프롬프트:**
> A woman in a black leather jacket dodges a punch in extreme slow motion. The camera orbits around her frozen in mid-dodge as water droplets and glass shards hang suspended in the air. Time gradually resumes as she completes the dodge. Matrix-style bullet time effect, dramatic lighting, dark background.

**설정:** 모델: Kling 3.0 Pro | 시간: 10s | 종횡비: 16:9 | FPS: 60

**난이도:** ⭐⭐⭐ 고급

</details>

<details>
<summary><strong>12-15. 추가 특수 효과 프롬프트</strong></summary>

전체 프롬프트 리스트는 [영어 README](./README.md#-special-effects)를 참조하세요. 시티 타임랩스, 파티클 스톰, 모핑 오브젝트, 라이트닝 스톰 등이 포함되어 있습니다.

</details>

### 📦 커머셜 & 마케팅

<details>
<summary><strong>16. 상품 공개 - 향수</strong> — 럭셔리 상품 쇼케이스</summary>

**프롬프트:**
> A luxury perfume bottle materializes from swirling golden mist on a marble surface. The camera slowly orbits the bottle as light refracts through the amber liquid. Rose petals and gold leaf particles float elegantly around the bottle. Premium commercial, luxury aesthetic, high-end fashion photography style.

**설정:** 모델: Kling 3.0 Pro | 시간: 10s | 종횡비: 9:16 | FPS: 60

**난이도:** ⭐⭐ 중급

</details>

<details>
<summary><strong>17-20. 추가 커머셜 프롬프트</strong></summary>

전체 프롬프트 리스트는 [영어 README](./README.md#-commercial--marketing)를 참조하세요. 음식 CM, 스니커즈 런칭, 부동산 워크스루, 패션 런웨이 등이 포함되어 있습니다.

</details>

### 🏞️ 자연 & 풍경

<details>
<summary><strong>21. 오로라</strong> — 대기 현상</summary>

**프롬프트:**
> The aurora borealis dances across the Arctic sky in shimmering curtains of green, purple, and pink. The lights are reflected in a perfectly still fjord below. Snow-covered mountains frame the scene. A lone cabin with a warm glowing window sits on the shore. Time-lapse speed, magical, serene, awe-inspiring.

**설정:** 모델: Kling 3.0 Pro | 시간: 10s | 종횡비: 16:9 | FPS: 30

**난이도:** ⭐ 초급

</details>

<details>
<summary><strong>22-25. 추가 자연 & 풍경 프롬프트</strong></summary>

전체 프롬프트 리스트는 [영어 README](./README.md#-nature--landscape)를 참조하세요.

</details>

### 🎨 추상 & 아트

<details>
<summary><strong>26-30. 추상 & 아트 프롬프트</strong></summary>

전체 프롬프트 리스트는 [영어 README](./README.md#-abstract--artistic)를 참조하세요. 잉크 인 워터, 프랙탈 줌, 리빙 페인팅, 기하학적 변환, 꿈의 시퀀스 등이 포함되어 있습니다.

</details>

---

## 프롬프트 엔지니어링 팁

### 카메라 이동 키워드

| 키워드 | 효과 | 최적 용도 |
|:---|:---|:---|
| `tracking shot` | 카메라가 피사체를 추적 | 캐릭터 걷기/달리기 |
| `dolly zoom` | 버티고/줌 효과 | 드라마틱한 연출 |
| `crane shot` | 수직 카메라 이동 | 설정 샷 |
| `steadicam` | 부드러운 핸드헬드 느낌 | 실내 워크스루 |
| `aerial drone shot` | 높은 각도 항공 촬영 | 풍경 |
| `orbit shot` | 카메라가 피사체를 공전 | 상품 쇼케이스 |
| `push in` | 카메라가 피사체에 접근 | 긴장감 조성 |
| `pull back / reveal` | 카메라가 멀어짐 | 전체 공개 |
| `whip pan` | 빠른 수평 패닝 | 전환 |
| `Dutch angle` | 기울어진 카메라 | 불안/긴장 |
| `rack focus` | 초점 전환 | 시선 유도 |
| `slow motion` | 재생 속도 감소 | 액션/디테일 |

### cfg_scale 최적화

| cfg_scale | 효과 | 사용 케이스 |
|:---|:---|:---|
| 3-5 | 창의적, 자유로운 해석 | 추상 아트, 실험적 |
| 5-7 | **균형 (권장)** | 대부분의 케이스 |
| 7-9 | 프롬프트에 충실 | 기술적, 특정 씬 |
| 9-12 | 매우 충실, 품질 저하 가능 | 정밀도가 중요할 때 |

### 시간 vs 품질 트레이드오프

| 시간 | 품질 영향 | 베스트 프랙티스 |
|:---|:---|:---|
| 5s | 프레임당 최고 품질 | 짧은 상품 샷, 루프 |
| 10s | 우수한 품질 | 대부분의 케이스 |
| 15s | 양호한 품질, 멀티 샷 | 내러티브, 워크스루 |

> 💡 **프로 팁:** 최고 품질을 위해 5초로 생성하고 여러 클립을 이어붙이세요. 편의성을 우선한다면 Kling 3.0의 15초 멀티 샷 모드를 사용하세요.

---

## 공식 리소스

- 🌐 [Kling AI 공식 사이트](https://klingai.com/) — Kling AI 공식 플랫폼
- 🏢 [Kuaishou 오픈 플랫폼](https://open.kuaishou.com/) — Kuaishou 개발자 플랫폼
- 📖 [Kling API 문서](https://docs.qingque.cn/d/home/eZQBMqNQR3bLYU9FB0kFv-wQK) — 공식 API 문서
- 🎨 [Kling AI 크리에이티브 센터](https://klingai.com/global/explore) — 커뮤니티 작품과 영감
- 📱 [Kling AI 앱](https://klingai.com/global/download) — Kling AI 모바일 앱

---

## 도구 & 통합

### ComfyUI 노드

- 🔧 [ComfyUI-KlingAI](https://github.com/KwaiVGI/ComfyUI-KlingAI) — 공식 ComfyUI 노드
- 🔧 [ComfyUI-Kling-API](https://github.com/yolain/ComfyUI-Kling-API) — 커뮤니티 ComfyUI 통합

### SDK & 래퍼

- 🐍 [kling-python-sdk](https://github.com/KwaiVGI/kling-python-sdk) — 공식 Python SDK
- 📦 [kling-js](https://github.com/KwaiVGI/kling-js) — 공식 JavaScript/Node.js SDK

### 서드파티 도구

- 🛠️ [Atlas Cloud API](https://www.atlascloud.ai?ref=JPM683) — 모든 Kling 모델 통합 API, 최저가
- 🛠️ [Kling 프롬프트 생성기](https://github.com/search?q=kling+prompt+generator) — AI 기반 프롬프트 생성 도구
- 🖼️ [Kling 배치 프로세서](https://github.com/search?q=kling+batch) — 배치 영상 생성 도구

---

## 튜토리얼 & 영상

### 시작 가이드

- 📺 [Kling AI 초보자 가이드](https://www.youtube.com/results?search_query=kling+ai+tutorial+beginner) — YouTube 초보자 튜토리얼
- 📺 [Kling 3.0 새 기능 워크스루](https://www.youtube.com/results?search_query=kling+3.0+tutorial) — 최신 버전 튜토리얼
- 📝 [Kling API 사용법](https://www.atlascloud.ai?ref=JPM683) — 단계별 API 통합 가이드

### 고급 기법

- 📺 [Kling 멀티 샷 영상 제작](https://www.youtube.com/results?search_query=kling+multi+shot+video) — 멀티 샷으로 내러티브 제작
- 📺 [Kling vs Sora 비교](https://www.youtube.com/results?search_query=kling+vs+sora) — 품질 병렬 비교
- 📺 [Kling 상업 영상 제작](https://www.youtube.com/results?search_query=kling+ai+commercial) — 비즈니스 활용

---

## API 가격 비교

> 💰 2026년 3월 기준

| 제공업체 | Kling 3.0 Pro (T2V) | Kling 3.0 Std (T2V) | Kling O3 Pro | 전체 모델 | 비고 |
|:---|:---:|:---:|:---:|:---:|:---|
| **[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683)** | **$0.204** | **더 저렴** | **✅ 사용 가능** | **✅ 20+ 모델** | ✅ 검열 없음, 최고속, 85% 할인, 첫 충전 25% 보너스 |
| 공식 API | ~$0.30+ | ~$0.20+ | 제한적 | ~10 모델 | 지역 제한, 검열 있음 |
| 제공업체 B | $0.25-0.40 | 다양 | 제한적 | ~5 모델 | 모델 선택이 제한적 |
| 제공업체 C | $0.30-0.45 | 다양 | ❌ | ~3 모델 | 모델이 적고 추론이 느림 |

> 💡 **[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683)**는 업계 최저가로 가장 포괄적인 Kling 모델 커버리지를 제공합니다. 신규 사용자는 **첫 충전 시 25% 보너스** (최대 $100 보너스)를 받을 수 있습니다.

### Atlas Cloud vs fal.ai 가격 비교

| 모델 | fal.ai 가격 | Atlas Cloud 가격 | 절약 |
|:------|:------------|:-----------------|:---------|
| **Kling** | $0.224/초 (5초 = $1.12) | $0.204/초부터 | **82% 저렴** |
| **Seedance** | ~$0.26/영상 | $0.222/초부터 | **15% 저렴** |
| **Wan 2.5** | $0.05/초 (5초 = $0.25) | $0.05/초부터 | **80% 저렴** |
| **Wan 2.6** | 유사 가격 | $0.07/초부터 | 경쟁력 있음 |
| **Veo 3** | $0.40/초 (8초 = $3.20) | 출시 예정 | 준비 중 |
| **Vidu Q3-Pro** | — | $0.06/초부터 | Atlas 독점 |
| **Vidu Q3-Turbo** | — | $0.034/초부터 | Atlas 독점 |

*표시된 가격은 시작 가격입니다. 더 높은 해상도나 긴 영상은 추가 비용이 발생할 수 있습니다.*

> 💡 Atlas Cloud는 모든 주요 영상 모델에서 **최저가**를 제공합니다. fal.ai에서 전환하면 영상 생성 비용을 최대 **82%** 절약할 수 있습니다.

---

## FAQ

<details>
<summary><strong>Kling AI란 무엇인가요?</strong></summary>

**Kling AI**는 **Kuaishou Technology(快手科技)**가 개발한 고급 AI 영상 생성 모델입니다. 텍스트 프롬프트에서 고품질 영상을 생성(텍스트-투-비디오)하고, 정적 이미지를 애니메이션화(이미지-투-비디오)하며, 영상 편집 작업을 수행할 수 있습니다. 최신 버전 **Kling 3.0**은 네이티브 4K 해상도, 60FPS, 하나의 15초 영상에 최대 6개의 멀티 샷 시퀀스를 지원하여, 현재 사용 가능한 가장 강력한 영상 생성 모델 중 하나입니다.

</details>

<details>
<summary><strong>Kling API는 어떻게 사용하나요?</strong></summary>

모든 Kling 모델에 접근하는 가장 쉬운 방법은 [Atlas Cloud API](https://www.atlascloud.ai?ref=JPM683)입니다:

1. [Atlas Cloud](https://www.atlascloud.ai?ref=JPM683)에서 **계정 가입**
2. 대시보드에서 **API 키 발급**
3. `https://api.atlascloud.ai/api/v1/model/generateVideo`로 **API 호출**
4. Kling 3.0 Pro부터 O3까지, 모든 버전에서 **모델 선택**

코드 예시는 [빠른 시작](#빠른-시작) 섹션을 참조하세요.

</details>

<details>
<summary><strong>Kling vs Sora vs Seedance — 어떤 것이 더 좋나요?</strong></summary>

각 모델마다 강점이 있습니다:

| 측면 | Kling 3.0 | Sora | Seedance |
|:---|:---|:---|:---|
| **해상도** | **4K** (최고) | 1080p | 1080p |
| **FPS** | **60** (최고) | 24 | 30 |
| **멀티 샷** | **✅ 6 샷** (유일) | ❌ | ❌ |
| **시간** | 15s | **60s** (최장) | 10s |
| **오디오** | ✅ 5개 언어 | ✅ | ✅ |

**Kling 3.0**은 고해상도, 고FPS 상업 콘텐츠에 최적입니다. **Sora**는 긴 내러티브에 강합니다. 최저가로 모든 Kling 모델에 접근하려면 [Atlas Cloud](https://www.atlascloud.ai?ref=JPM683)를 이용하세요.

</details>

<details>
<summary><strong>Kling AI는 무료인가요?</strong></summary>

Kling AI는 공식 플랫폼에서 제한적인 무료 크레딧을 제공합니다. API 접근 요금은 제공업체에 따라 다릅니다:

- **[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683):** Kling 3.0 Pro $0.204/초부터 (85% 할인), **첫 충전 시 25% 보너스** (최대 $100)
- **공식 API:** ~$0.30+/초부터, 지역 제한 있음

</details>

<details>
<summary><strong>Kling은 어떤 언어의 오디오를 지원하나요?</strong></summary>

Kling AI는 **5개 언어**의 네이티브 오디오 생성을 지원합니다:

1. 🇨🇳 중국어 (보통화)
2. 🇺🇸 영어
3. 🇯🇵 일본어
4. 🇰🇷 한국어
5. 🇪🇸 스페인어

</details>

<details>
<summary><strong>Kling으로 영상 생성은 얼마나 걸리나요?</strong></summary>

생성 시간은 모델과 설정에 따라 다릅니다:

| 모델 | 5s 영상 | 10s 영상 | 15s 영상 |
|:---|:---|:---|:---|
| Kling 3.0 Pro | ~60-120초 | ~120-240초 | ~180-360초 |
| Kling 3.0 Std | ~30-60초 | ~60-120초 | ~90-180초 |
| Kling O3 | ~45-90초 | ~90-180초 | — |
| Kling 2.5 Turbo | ~15-30초 | ~30-60초 | — |

시간은 추정치이며 서버 부하에 따라 달라질 수 있습니다. [Atlas Cloud](https://www.atlascloud.ai?ref=JPM683)는 보통 더 빠른 추론 속도를 제공합니다.

</details>

---

## 🎬 Kling AI로 제작 시작하기

<div align="center">

**하나의 통합 API로 20개 이상의 Kling 모델에 접근하세요.**

| 혜택 | 설명 |
|:---|:---|
| ✅ **검열 없는 AI** | 완전한 창작의 자유 — 콘텐츠 제한 없음 |
| ✅ **최대 85% 할인** | 업계 최저 Kling API 가격 |
| ✅ **전체 모델** | Kling 3.0부터 O3까지, 모든 버전 사용 가능 |
| ✅ **25% 보너스** | 첫 충전 시 최대 $100 보너스 |
| ✅ **최고속 추론** | 최적화된 인프라로 빠른 생성 |
| ✅ **20+ 모델** | 가장 포괄적인 Kling 모델 커버리지 |

<br/>

### 👉 [Atlas Cloud에서 Kling 체험하기](https://www.atlascloud.ai?ref=JPM683)

*신규 사용자 첫 충전 시 25% 보너스 (최대 $100)*

</div>

---

## Star 히스토리

<div align="center">

[![Star History Chart](https://api.star-history.com/svg?repos=atlas-cloud/awesome-kling-ai&type=Date)](https://star-history.com/#atlas-cloud/awesome-kling-ai&Date)

</div>

---

## 기여 가이드

기여를 환영합니다! 아래 가이드라인을 읽어주세요:

1. 이 저장소를 **Fork**
2. 새 브랜치 **생성** (`git checkout -b feature/add-resource`)
3. 적절한 섹션에 리소스 **추가**
4. 변경사항 **커밋** (`git commit -m 'Add new resource'`)
5. 브랜치에 **푸시** (`git push origin feature/add-resource`)
6. **Pull Request** 생성

---

## 라이선스

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

이 프로젝트는 MIT 라이선스 하에 배포됩니다 — 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요.

---

<div align="center">

**Kling AI 커뮤니티가 ❤️을 담아 제작**

[⬆ 맨 위로 돌아가기](#awesome-kling-ai-)

</div>
