# noBreak Photo

가볍고 빠른 Windows 사진 뷰어 + 비파괴 편집기 — 제작·소유 **noBrake technology**

- **무료 소프트웨어** (개인·비상업용) — 설치할 때 [이용 약관](TERMS.md)에 동의해야 합니다.
- 이 저장소는 **배포 전용**입니다: 설치 파일과 AI 모델을 [Releases](https://github.com/taro6222/noBrake-photo-releases/releases)에서 받습니다. 앱 안의 새 버전 확인·AI 모델 받기도 여기서만 받습니다.
- 공식 배포처는 이 저장소뿐입니다. 다른 곳에서 받은 파일은 쓰지 마세요.

## 설치

1. [최신 릴리스](https://github.com/taro6222/noBrake-photo-releases/releases/latest)에서 `noBreakPhoto-Setup-<버전>.exe` 를 받아 실행합니다.
2. 약관 동의 → 설치 위치·선택 → 설치. 내 계정에만 설치되며 **관리자 권한이 필요 없습니다** (`%LOCALAPPDATA%\Programs\noBreak Photo`).
3. 설치 파일에 코드 서명이 아직 없어 Windows SmartScreen 경고가 나올 수 있습니다 — "추가 정보 → 실행". 받은 파일의 SHA-256 은 같은 릴리스의 `.sha256` 파일과 비교할 수 있습니다.

- 요구 사항: Windows 10 22H2 이상 / Windows 11, x64
- 업데이트: 앱의 설정 › 업데이트 › 지금 확인 → 받고 다시 시작 (설정·탭·썸네일은 그대로)
- 제거: Windows 설정 › 앱 › noBreak Photo. 설정·캐시(`%LOCALAPPDATA%\nobreakPhoto`)는 남습니다.

## AI 모델

AI 개선(2배 확대·노이즈 제거·얼굴 복원) 모델은 설치 파일에 들어 있고, 빼고 설치했으면 앱의 설정 › AI 개선 › AI 모델에서 받습니다([models-v1](https://github.com/taro6222/noBrake-photo-releases/releases/tag/models-v1)). 모델별 라이선스는 `MODEL-LICENSES.txt` 를 보세요 (Real-ESRGAN BSD-3, NAFNet MIT, YuNet MIT, RestoreFormer++ Apache-2.0).

---

**noBreak Photo** — fast, lightweight photo viewer with non-destructive editing for Windows, by **noBrake technology**. Free for personal, non-commercial use under the [Terms of Use](TERMS.md). Download the installer from [Releases](https://github.com/taro6222/noBrake-photo-releases/releases/latest); no administrator rights required.
