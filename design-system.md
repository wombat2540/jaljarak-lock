# 잘자락(Lock) — Design System

## 개요
- 서비스명: 잘자락(Lock)
- 무드: 다크톤, 암순응을 고려한 낮은 채도
- 컨셉: 밤에만 사용하는 서비스 특성에 맞게 눈의 자극을 최소화
- 아이덴티티: 라벤더 꽃 모티프를 서비스 전반에 활용
- 폰트: Pretendard (단일 폰트)

---

# FOUNDATION

## 1. Color

### Brand (라벤더 계열)
--color-brand-50: #F3EEFF
--color-brand-100: #E4D4FC
--color-brand-200: #D4B8F8
--color-brand-300: #C4A0F4
--color-brand-400: #B48EF0   ← 메인 라벤더 (Primary)
--color-brand-500: #9D72D8
--color-brand-600: #8A6BC4
--color-brand-700: #6B4FA0
--color-brand-800: #4D3478
--color-brand-900: #2E1E50

### Background
--color-bg-base: #08080F
--color-bg-primary: #0D0D14
--color-bg-secondary: #16161F
--color-bg-tertiary: #1E1E2E
--color-bg-elevated: #252535

### Text
--color-text-primary: #F0EAF8
--color-text-secondary: #C4B8D8
--color-text-tertiary: #8A7FA0
--color-text-disabled: #4A4460
--color-text-inverse: #0D0D14
--color-text-brand: #B48EF0

### Border
--color-border-default: #2A2A3E
--color-border-subtle: #1E1E2E
--color-border-strong: #3D3D5C
--color-border-brand: #B48EF0
--color-border-focus: #D4B8F8

### System
--color-success-default: #7EC8A4
--color-success-subtle: #1A3D2E
--color-warning-default: #F0C87A
--color-warning-subtle: #3D2E0A
--color-error-default: #E87A7A
--color-error-subtle: #3D1A1A
--color-info-default: #7AB8E8
--color-info-subtle: #1A2E3D

### Overlay
--color-overlay-dim: rgba(0, 0, 0, 0.6)
--color-overlay-heavy: rgba(0, 0, 0, 0.8)
--color-overlay-brand: rgba(180, 142, 240, 0.1)

### Interactive
/* Primary Button */
--color-interactive-primary-default: #B48EF0
--color-interactive-primary-hover: #C4A0F4
--color-interactive-primary-pressed: #9D72D8
--color-interactive-primary-disabled: #4A3D60

/* Secondary Button */
--color-interactive-secondary-default: #1E1E2E
--color-interactive-secondary-hover: #252535
--color-interactive-secondary-pressed: #16161F
--color-interactive-secondary-disabled: #111118

/* Ghost Button */
--color-interactive-ghost-default: transparent
--color-interactive-ghost-hover: rgba(180, 142, 240, 0.1)
--color-interactive-ghost-pressed: rgba(180, 142, 240, 0.2)
--color-interactive-ghost-disabled: transparent

---

## 2. Typography

### 폰트 패밀리
--font-family-base: 'Pretendard', sans-serif

### 폰트 사이즈
--font-size-12: 12px
--font-size-14: 14px
--font-size-16: 16px
--font-size-18: 18px
--font-size-20: 20px
--font-size-24: 24px
--font-size-28: 28px
--font-size-32: 32px
--font-size-40: 40px
--font-size-56: 56px

### 폰트 웨이트
--font-weight-regular: 400
--font-weight-medium: 500
--font-weight-semibold: 600
--font-weight-bold: 700

### 라인 헤이트
--line-height-tight: 1.2
--line-height-normal: 1.5
--line-height-loose: 1.8

### 레터 스페이싱 (-2% 기준)
--letter-spacing-12: -0.24px
--letter-spacing-14: -0.28px
--letter-spacing-16: -0.32px
--letter-spacing-18: -0.36px
--letter-spacing-20: -0.40px
--letter-spacing-24: -0.48px
--letter-spacing-28: -0.56px
--letter-spacing-32: -0.64px
--letter-spacing-40: -0.80px
--letter-spacing-56: -1.12px

### 타이포그래피 스타일
/* Display */
font-size: 32px
font-weight: 700
line-height: 1.2
letter-spacing: -0.64px

/* H1 */
font-size: 24px
font-weight: 700
line-height: 1.2
letter-spacing: -0.48px

/* H2 */
font-size: 20px
font-weight: 600
line-height: 1.2
letter-spacing: -0.40px

/* H3 */
font-size: 18px
font-weight: 600
line-height: 1.5
letter-spacing: -0.36px

/* Body 1 */
font-size: 16px
font-weight: 400
line-height: 1.5
letter-spacing: -0.32px

/* Body 2 */
font-size: 14px
font-weight: 400
line-height: 1.5
letter-spacing: -0.28px

/* Caption */
font-size: 12px
font-weight: 400
line-height: 1.8
letter-spacing: -0.24px

/* Label */
font-size: 14px
font-weight: 600
line-height: 1.5
letter-spacing: -0.28px

/* Time Display (취침 모드 전용) */
font-size: 56px
font-weight: 700
line-height: 1.2
letter-spacing: -1.12px

/* Time Sub (취침 시간 UI) */
font-size: 40px
font-weight: 700
line-height: 1.2
letter-spacing: -0.80px

---

## 3. Spacing

### 기본 스페이싱 스케일
--spacing-2: 2px
--spacing-4: 4px
--spacing-8: 8px
--spacing-12: 12px
--spacing-16: 16px
--spacing-20: 20px
--spacing-24: 24px
--spacing-32: 32px
--spacing-40: 40px
--spacing-48: 48px
--spacing-56: 56px
--spacing-64: 64px

### 레이아웃 스페이싱
--layout-padding-horizontal: 20px
--layout-padding-vertical: 24px
--layout-gap-sm: 8px
--layout-gap-md: 16px
--layout-gap-lg: 24px

### 컴포넌트별 스페이싱
/* Button */
--button-padding-vertical-sm: 12px
--button-padding-horizontal-sm: 16px
--button-padding-vertical-md: 12px
--button-padding-horizontal-md: 24px
--button-padding-vertical-lg: 16px
--button-padding-horizontal-lg: 32px

/* Input Field */
--input-padding-vertical: 14px
--input-padding-horizontal: 16px

/* Card */
--card-padding: 20px

/* Bottom Sheet */
--bottom-sheet-padding-top: 24px
--bottom-sheet-padding-horizontal: 20px
--bottom-sheet-padding-bottom: 40px

/* Navigation Bar */
--navbar-height: 56px
--navbar-padding-bottom: 16px

---

## 4. Border Radius

### 기본 레디우스 스케일
--radius-2: 2px
--radius-4: 4px
--radius-8: 8px
--radius-12: 12px
--radius-16: 16px
--radius-20: 20px
--radius-24: 24px
--radius-32: 32px
--radius-full: 9999px

### 컴포넌트별 레디우스
/* Button */
--button-radius-sm: 12px
--button-radius-md: 12px
--button-radius-lg: 16px
--button-radius-full: 9999px

/* Input Field */
--input-radius: 12px

/* Card */
--card-radius: 16px

/* Badge */
--badge-radius: 9999px

/* Bottom Sheet */
--bottom-sheet-radius: 24px

/* Toggle */
--toggle-radius: 9999px

/* Progress Bar */
--progress-radius: 9999px

/* Navigation Bar */
--navbar-radius: 0px

---

## 5. Shadow

### 기본 그림자 (Elevation)
--shadow-sm: 0px 1px 4px rgba(0, 0, 0, 0.3)
--shadow-md: 0px 4px 12px rgba(0, 0, 0, 0.4)
--shadow-lg: 0px 8px 24px rgba(0, 0, 0, 0.5)
--shadow-xl: 0px 16px 40px rgba(0, 0, 0, 0.6)

### 브랜드 글로우 (라벤더)
--shadow-glow-sm: 0px 0px 8px rgba(180, 142, 240, 0.3)
--shadow-glow-md: 0px 0px 16px rgba(180, 142, 240, 0.4)
--shadow-glow-lg: 0px 0px 32px rgba(180, 142, 240, 0.5)
--shadow-glow-xl: 0px 0px 56px rgba(180, 142, 240, 0.6)

### 이너 글로우
--shadow-inner: inset 0px 1px 4px rgba(0, 0, 0, 0.4)
--shadow-inner-brand: inset 0px 0px 8px rgba(180, 142, 240, 0.2)

### 컴포넌트별 Shadow
/* Button Primary */
--button-shadow-default: 0px 0px 8px rgba(180, 142, 240, 0.3)
--button-shadow-pressed: none

/* Card */
--card-shadow: 0px 1px 4px rgba(0, 0, 0, 0.3)

/* Bottom Sheet */
--bottom-sheet-shadow: 0px 8px 24px rgba(0, 0, 0, 0.5)

/* Navigation Bar */
--navbar-shadow: 0px -1px 0px rgba(255, 255, 255, 0.05)

/* 취침 모드 라벤더 모티프 */
--motif-shadow: 0px 0px 56px rgba(180, 142, 240, 0.6)

---

## 6. Icon

### 아이콘 사이즈
--icon-size-16: 16px
--icon-size-20: 20px
--icon-size-24: 24px
--icon-size-32: 32px
--icon-size-40: 40px
--icon-size-48: 48px
--icon-size-56: 56px
--icon-size-80: 80px
--icon-size-120: 120px

### 아이콘 컬러
--icon-color-default: #A89BBF
--icon-color-active: #B48EF0
--icon-color-disabled: #4A4460
--icon-color-inverse: #0D0D14
--icon-color-brand: #B48EF0

### 아이콘 라이브러리
Phosphor Icons 사용
- 무료 오픈소스
- 다양한 웨이트 지원 (Thin, Light, Regular, Bold, Fill)
- 설치: npm install @phosphor-icons/react

### 라벤더 모티프 SVG
/* 사용 위치별 사이즈 */
--motif-splash: 120px
--motif-onboarding: 80px
--motif-lock: 80px
--motif-reward: 24px
--motif-logo: 32px

/* 모티프 컬러 */
--motif-color-primary: #B48EF0
--motif-color-light: #D4B8F8
--motif-color-dark: #8A6BC4
--motif-color-stem: #7EC8A4
--motif-color-glow: rgba(180, 142, 240, 0.3)

### 앱 내 주요 아이콘 목록
/* 네비게이션 */
- 홈: house
- 리포트: chart-bar
- 리워드: gift
- 설정: gear

/* 기능 */
- 취침 알람: moon
- 앱 차단: lock
- 미션: puzzle-piece
- 해제: lock-open
- 포인트: star
- 쿠폰: ticket

/* 시스템 */
- 성공: check-circle
- 에러: x-circle
- 경고: warning
- 정보: info
- 뒤로가기: arrow-left
- 닫기: x

---

# COMPONENTS

## 1. Button

### Variant
- Primary    ← 메인 액션
- Secondary  ← 서브 액션
- Ghost      ← 텍스트 버튼
- Danger     ← 위험 액션

### Size
- SM: height 44px / font-size 14px / padding 12px 16px
- MD: height 48px / font-size 16px / padding 12px 24px
- LG: height 56px / font-size 16px / padding 16px 32px

### State
- Default / Hover / Pressed / Disabled / Loading

### Style
/* Primary */
background: #B48EF0
color: #0D0D14
border: none
border-radius: 12px
box-shadow: 0px 0px 8px rgba(180, 142, 240, 0.3)
min-height: 44px

/* Primary Hover */
background: #C4A0F4
box-shadow: 0px 0px 16px rgba(180, 142, 240, 0.4)

/* Primary Pressed */
background: #9D72D8
box-shadow: none

/* Primary Disabled */
background: #4A3D60
color: #4A4460
box-shadow: none

/* Secondary */
background: #1E1E2E
color: #F0EAF8
border: 1px solid #2A2A3E
border-radius: 12px
min-height: 44px

/* Secondary Hover */
background: #252535
border: 1px solid #3D3D5C

/* Ghost */
background: transparent
color: #B48EF0
border: none
min-height: 44px
padding: 12px 16px

/* Ghost Hover */
background: rgba(180, 142, 240, 0.1)

/* Danger */
background: #E87A7A
color: #0D0D14
border: none
border-radius: 12px
min-height: 44px

### 터치 영역
min-height: 44px
min-width: 44px

### Full Width
width: 100%
주요 CTA에 사용 (온보딩 완료, 미션 완료 등)

---

## 2. Input Field

### Variant
- Default  / Password / Search / Number

### Size
- MD: height 48px / font-size 16px / padding 14px 16px
- LG: height 56px / font-size 16px / padding 16px 16px

### State
- Default / Focus / Filled / Error / Disabled / Read Only

### Style
/* Default */
background: #1E1E2E
color: #F0EAF8
border: 1px solid #2A2A3E
border-radius: 12px
font-size: 16px
letter-spacing: -0.32px

/* Placeholder */
color: #8A7FA0

/* Focus */
border: 1px solid #B48EF0
box-shadow: inset 0px 0px 8px rgba(180, 142, 240, 0.2)

/* Error */
border: 1px solid #E87A7A

/* Disabled */
background: #16161F
border: 1px solid #1E1E2E
color: #4A4460

### 부속 요소
/* Label */
font-size: 14px
font-weight: 600
color: #C4B8D8
margin-bottom: 8px

/* Helper Text */
font-size: 12px
color: #8A7FA0
margin-top: 4px

/* Error Message */
font-size: 12px
color: #E87A7A
margin-top: 4px

/* Right Icon */
size: 20px
min-width: 44px
min-height: 44px

---

## 3. Card

### Variant
- Default / Highlight / List / Stat / Reward

### Size
- Full Width / Half (2열 그리드)

### State
- Default / Pressed / Selected / Disabled

### Style
/* Default */
background: #16161F
border: 1px solid #1E1E2E
border-radius: 16px
padding: 20px
box-shadow: 0px 1px 4px rgba(0, 0, 0, 0.3)

/* Highlight */
background: #16161F
border: 1px solid #B48EF0
border-radius: 16px
padding: 20px
box-shadow: 0px 0px 16px rgba(180, 142, 240, 0.4)

/* List */
background: #16161F
border: 1px solid #1E1E2E
border-radius: 16px
padding: 16px 20px
min-height: 44px

/* Stat */
background: #16161F
border: 1px solid #1E1E2E
border-radius: 16px
padding: 16px

/* Reward */
background: #16161F
border: 1px solid #B48EF0
border-radius: 16px
padding: 20px
box-shadow: 0px 0px 8px rgba(180, 142, 240, 0.3)

/* Pressed */
background: #252535
opacity: 0.8

/* Selected */
border: 1px solid #B48EF0
box-shadow: 0px 0px 8px rgba(180, 142, 240, 0.3)

### 내부 구조
/* Header */
- 아이콘 (optional)
- 타이틀: H3 스타일
- 서브타이틀: Body2 / #C4B8D8

/* Body */
- 메인 콘텐츠

/* Footer */
- 액션 버튼 (optional)
- 메타 정보 (optional)

---

## 4. Toggle

### Variant
- Switch / Checkbox / Radio

### Size
/* Switch */
- MD: width 51px / height 31px / thumb 27px
- LG: width 60px / height 36px / thumb 32px

/* Checkbox */
- MD: 24px × 24px
- LG: 28px × 28px

/* Radio */
- MD: 24px × 24px
- LG: 28px × 28px

/* 모든 터치 영역 */
min-width: 44px
min-height: 44px

### State
- Off Default / Off Pressed / On Default / On Pressed / Disabled Off / Disabled On

### Style
/* Switch Off */
background: #1E1E2E
border: 1px solid #2A2A3E
border-radius: 9999px
thumb-color: #8A7FA0

/* Switch On */
background: #B48EF0
border: none
box-shadow: 0px 0px 8px rgba(180, 142, 240, 0.3)
thumb-color: #0D0D14

/* Switch Disabled Off */
background: #16161F
border: 1px solid #1E1E2E
thumb-color: #4A4460

/* Switch Disabled On */
background: #4A3D60
thumb-color: #4A4460

/* Checkbox Off */
background: #1E1E2E
border: 1px solid #2A2A3E
border-radius: 4px

/* Checkbox On */
background: #B48EF0
border: none
border-radius: 4px
box-shadow: 0px 0px 8px rgba(180, 142, 240, 0.3)
icon: check / color: #0D0D14

/* Radio Off */
background: #1E1E2E
border: 1px solid #2A2A3E
border-radius: 9999px

/* Radio On */
background: #0D0D14
border: 2px solid #B48EF0
border-radius: 9999px
inner-dot: #B48EF0
box-shadow: 0px 0px 8px rgba(180, 142, 240, 0.3)

### 사용 위치
- Switch    ← 취침 알람 활성/비활성
- Checkbox  ← 차단 앱 선택 목록
- Radio     ← 미션 난이도 선택

---

## 5. Progress Bar

### Variant
- Linear / Circular / Step

### Size
/* Linear */
- SM: height 4px
- MD: height 8px
- LG: height 12px

/* Circular */
- SM: 48px / stroke 4px
- MD: 80px / stroke 6px
- LG: 120px / stroke 8px

/* Step */
- dot-size: 8px
- active-dot-size: 10px
- line-height: 2px

### State
- Empty / Progress / Complete

### Style
/* Linear Track */
background: #1E1E2E
border-radius: 9999px

/* Linear Fill */
background: #B48EF0
border-radius: 9999px
box-shadow: 0px 0px 8px rgba(180, 142, 240, 0.3)

/* Linear Complete */
background: #7EC8A4
box-shadow: 0px 0px 8px rgba(126, 200, 164, 0.4)

/* Circular Track */
stroke: #1E1E2E

/* Circular Fill */
stroke: #B48EF0
box-shadow: 0px 0px 8px rgba(180, 142, 240, 0.3)
stroke-linecap: round

/* Circular Complete */
stroke: #7EC8A4

/* Step Inactive */
background: #1E1E2E
border: 1px solid #2A2A3E
border-radius: 9999px

/* Step Active */
background: #B48EF0
border-radius: 9999px
box-shadow: 0px 0px 8px rgba(180, 142, 240, 0.3)

/* Step Complete */
background: #8A6BC4
border-radius: 9999px

/* Step Line */
background: #2A2A3E

/* Step Line Complete */
background: #B48EF0

### 라벨
/* Linear 퍼센트 */
font-size: 12px
font-weight: 600
color: #B48EF0
margin-bottom: 4px

/* Circular 중앙 텍스트 */
font-size: 20px
font-weight: 700
color: #F0EAF8

### 사용 위치
- Linear    ← 리포트 취침 준수율
- Circular  ← 홈 주간 달성률, 리워드 포인트
- Step      ← 온보딩 진행 단계

---

## 6. Badge

### Variant
- Label / Count / Dot / Reward

### Size
/* Label */
- SM: height 20px / font-size 11px / padding 4px 8px
- MD: height 24px / font-size 12px / padding 4px 10px
- LG: height 28px / font-size 14px / padding 6px 12px

/* Count */
- SM: min-width 16px / height 16px / font-size 10px
- MD: min-width 20px / height 20px / font-size 11px
- LG: min-width 24px / height 24px / font-size 12px

/* Dot */
- SM: 6px × 6px
- MD: 8px × 8px
- LG: 10px × 10px

/* Reward */
- MD: height 28px / font-size 14px / padding 4px 12px

### Color
- Brand / Success / Warning / Error / Neutral

### Style
/* Brand */
background: rgba(180, 142, 240, 0.15)
color: #C4A0F4
border: 1px solid rgba(180, 142, 240, 0.3)
border-radius: 9999px

/* Success */
background: rgba(126, 200, 164, 0.15)
color: #7EC8A4
border: 1px solid rgba(126, 200, 164, 0.3)
border-radius: 9999px

/* Warning */
background: rgba(240, 200, 122, 0.15)
color: #F0C87A
border: 1px solid rgba(240, 200, 122, 0.3)
border-radius: 9999px

/* Error */
background: rgba(232, 122, 122, 0.15)
color: #E87A7A
border: 1px solid rgba(232, 122, 122, 0.3)
border-radius: 9999px

/* Neutral */
background: #1E1E2E
color: #C4B8D8
border: 1px solid #2A2A3E
border-radius: 9999px

/* Reward */
background: rgba(180, 142, 240, 0.15)
color: #C4A0F4
border: 1px solid rgba(180, 142, 240, 0.3)
border-radius: 9999px
icon: 라벤더 모티프 아이콘 (24px)

### 사용 위치
- Label   ← 리포트 상태 표시
- Count   ← 리워드 알림 카운트
- Dot     ← 새로운 쿠폰 알림
- Reward  ← 홈 포인트 현황

---

## 7. Bottom Sheet

### Variant
- Default / Mission / Confirm / App Select

### Size
- Small:  30% 화면 높이 ← Confirm
- Medium: 50% 화면 높이 ← Default
- Large:  75% 화면 높이 ← Mission, App Select
- Full:   90% 화면 높이

### State
- Hidden / Appearing / Visible / Dismissing

### Style
/* Container */
background: #252535
border-radius: 24px 24px 0px 0px
box-shadow: 0px 8px 24px rgba(0, 0, 0, 0.5)
padding-top: 24px
padding-horizontal: 20px
padding-bottom: 40px

/* Handle Bar */
width: 36px
height: 4px
background: #3D3D5C
border-radius: 9999px
margin: 0 auto 24px

/* Overlay */
background: rgba(0, 0, 0, 0.8)

/* Mission Variant */
background: #252535
border-top: 1px solid #B48EF0
box-shadow: 0px 0px 32px rgba(180, 142, 240, 0.5)

/* Confirm Variant */
background: #252535
border-top: 1px solid #2A2A3E

### 내부 구조
/* Header */
- Handle Bar
- 타이틀: H2 스타일
- 서브타이틀: Body2 / #C4B8D8
- 닫기 버튼 (optional): 24px / min 44px 터치 영역

/* Body */
- 메인 콘텐츠 (스크롤 가능)

/* Footer */
- Primary Button (Full Width)
- Secondary 또는 Ghost Button (optional)
- 버튼 간격: 12px

### 애니메이션
- 등장: translateY(100%) → translateY(0) / 300ms / ease-out
- 사라짐: translateY(0) → translateY(100%) / 250ms / ease-in
- 오버레이: opacity 0 → 0.8 / 300ms

### 사용 위치
- Mission     ← 차단 앱 클릭 시 미션 등장
- Confirm     ← 취침 모드 해제 확인
- App Select  ← 차단 앱 선택 목록
- Default     ← 취침 시간 변경, 설정 변경

---

## 8. Navigation Bar

### 구조
- 하단 고정 (Fixed Bottom)
- 탭 4개: 홈 / 리포트 / 리워드 / 설정

### Size
height: 56px
padding-bottom: 16px
총 높이: 72px
min-touch-area: 44px (각 탭)

### State
- Default / Active / Pressed

### Style
/* Container */
background: #16161F
border-top: 1px solid #1E1E2E
box-shadow: 0px -1px 0px rgba(255, 255, 255, 0.05)

/* Tab Item Default */
icon-color: #A89BBF
label-color: #8A7FA0
font-size: 12px
font-weight: 400

/* Tab Item Active */
icon-color: #B48EF0
label-color: #B48EF0
font-size: 12px
font-weight: 600
icon-shadow: 0px 0px 8px rgba(180, 142, 240, 0.3)

/* Tab Item Pressed */
opacity: 0.7

/* Active Indicator */
width: 4px
height: 4px
background: #B48EF0
border-radius: 9999px
margin-top: 4px
box-shadow: 0px 0px 8px rgba(180, 142, 240, 0.3)

### 탭 구성
1. 홈: house 아이콘 / 라벨: 홈 / route: /home
2. 리포트: chart-bar 아이콘 / 라벨: 리포트 / route: /report
3. 리워드: gift 아이콘 / 라벨: 리워드 / route: /reward
4. 설정: gear 아이콘 / 라벨: 설정 / route: /settings

### 애니메이션
- 탭 전환: icon scale 1.0 → 1.1 → 1.0 / 150ms
- Active Indicator: opacity 0 → 1 / 150ms