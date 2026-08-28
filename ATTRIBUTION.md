# 저작권·라이선스 고지 (Attribution)

이 킷의 스킬(`gonggam-design`, `gonggam-design-deck`, `korean-writing`)은 아래 세 공개 저작물을 결합·개작한 **파생 저작물**입니다. 원저작자의 라이선스 조건에 따라 고지를 유지합니다.

> 이 킷은 공감에듀테크 내부 디자인 스킬 계열(코어 + 매체 4종)에서 **발표 슬라이드 부분만 추린 배포판**입니다. 앱 화면·랜딩·인쇄물용 스킬과 학원 업무 관련 참조는 포함하지 않았습니다.

## 1. frontend-design — 미감·방향 축
- 출처: Anthropic, `anthropics/skills` 리포지토리의 `skills/frontend-design`
- 라이선스: **Apache License 2.0**
- 사용 범위: `references/design-direction.md`는 원 SKILL.md의 디자인 철학·원칙·프로세스를 한국어/공감에듀테크 맥락으로 재정리한 것.
- 전문: https://www.apache.org/licenses/LICENSE-2.0

## 2. ui-ux-pro-max — 사용성·규칙 축
- 출처: Next Level Builder, `nextlevelbuilder/ui-ux-pro-max-skill`
- 라이선스: **MIT License** (Copyright (c) 2024 Next Level Builder)
- 사용 범위: 원 스킬의 사용성 규칙(접근성·터치·성능·레이아웃·폼·내비게이션)은 공감에듀테크 내부 디자인 계열이 보존하고 있습니다. **이 슬라이드 배포판에는 포함하지 않았습니다** — 화면 UI 전용이라 발표 자료에 해당하지 않습니다. 이 킷에 남은 것은 대비·간격·타이포 등 매체 무관 항목뿐이며 `references/craft-floor.md` 에 재작성되어 있습니다. 원 스킬의 Python 검색 도구·CSV 데이터베이스·폰트 자산은 포함하지 않았습니다.

## 3. taste-skill — 안티슬롭·리디자인 축 (v2.0에서 추가)
- 출처: Leonxlnx, `Leonxlnx/taste-skill`
- 라이선스: **MIT License** (Copyright (c) 2026 Leonxlnx)
- 사용 범위:
  - `SKILL.md`의 **Design Read 선언**과 **3다이얼**(VARIANCE / MOTION / DENSITY) 개념은 원 스킬 §0·§1의 구조를 참고했습니다. 다이얼 수치는 공감에듀테크 학원 산출물 기준으로 **새로 산정**했습니다(원본 기본값 8/6/4 → 학원 4/2/4).
  - `references/craft-floor.md`의 **거부 목록**(미감 기본값 4종·색·타이포·구조·히어로·「홍길동 효과」·모션·줄표)은 원 스킬 §9(AI Tells)의 항목 구성을 참고해 한국어·학원·인쇄 맥락으로 재작성했습니다. 아이콘 CDN 규칙은 저희 환경(CSP·인쇄)에 맞춰 **반대로 바꿨고**, em-dash 전면 금지 규칙은 한국어 관례에 맞춰 **조건부로 완화**했습니다.
    > 이 파일은 impeccable(4번)과 **한 파일로 합쳐져** 있습니다. 두 원본이 같은 항목을 다르게 규정한 곳(아이브로우)은 더 엄격한 impeccable 쪽으로 통일했습니다.
  - `references/redesign-protocol.md`는 원 스킬 §11(Redesign Protocol)과 `redesign-skill`의 감사 구조를 참고해 재작성했습니다.
  - 원 스킬의 모션 스켈레톤(sticky-stack, horizontal-pan), 블록 라이브러리, 이미지 생성 스킬군은 **가져오지 않았습니다.** 학원 산출물의 MOTION 상한(2)과 맞지 않습니다.

### MIT 라이선스 고지 (원문 유지)
```
MIT License

Copyright (c) 2024 Next Level Builder
Copyright (c) 2026 Leonxlnx

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALING IN THE
SOFTWARE.
```

## 4. impeccable — 품질 바닥선·검사 축 (v2.1 에서 추가)
- 출처: Paul Bakaus, `pbakaus/impeccable` (v4.1.2)
- 라이선스: **Apache License 2.0**
- 사용 범위:
  - `references/craft-floor.md` 의 **§1 검증**(대비·깊이·간격·타이포·모션·상태·안 그린 표면)과 거부 목록 일부는 원 스킬 `reference/craft-floor.md` 의 구성을 참고해 한국어·학원·인쇄/슬라이드 맥락으로 재작성했습니다. 웹 전용 항목(브라우저 표면·CSS 값)은 뜻을 살려 옮기고, 슬라이드·인쇄에 없는 항목은 뺐습니다.
  - **실눈 검사(squint test)** 는 원 스킬 `reference/layout.md` 의 진단법입니다.
  - **만들기 전에 선언한다**(역할·대비·밀도·측정을 먼저 명시) 는 `reference/typeset.md`·`layout.md` 의 "Set the system / Set the spatial thesis" 를 슬라이드용으로 옮긴 것입니다.
  - **모드**(청중의 성공으로 규칙을 가르는 축)는 원 스킬의 Persuade / Operate / Read / Experience 를 참고해, 슬라이드용 **설득 / 강의 / 보고** 셋으로 새로 정의했습니다.
  - 어두운 배경에서 **줄간·자간·굵기 세 축을 함께 보정**하는 규칙은 `reference/typeset.md` 에서 왔습니다.
  - 원 스킬의 실행 도구(detect.mjs·라이브 브라우저 반복·네이티브 iOS/Android 지침·훅)는 **가져오지 않았습니다.**
- Apache-2.0 전문: https://www.apache.org/licenses/LICENSE-2.0

## 공감에듀테크 신규 저작

원본 넷에 없는 부분입니다.

- **슬라이드**(`gonggam-design-deck`) 전체 — 모드 3종(설득·강의·보고), 크기 하한 18pt, 투사 환경과 어두운 배경 3축 보정, 한 장의 구성, 슬라이드 거부 목록, 대면 설명회 실무
- **한글 글쓰기**(`korean-writing`) 전체 — 번역투 대조표, 속 빈 형용사 치환, 독자별 문체 분리, 불안 자극 화법 차단
- 슬라이드용 다이얼 프리셋
- 발행 전 검수(과장·후기·숫자·개인정보)

## 라이선스

- 원본 부분: Apache-2.0 및 MIT (위 고지 유지)
- 공감에듀테크 추가분: MIT

**재배포할 때 이 파일을 함께 둡니다.**
