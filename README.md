# CleanVid 다운로드

**현재 버전: v0.9.172** (게시: 2026-09-18 10:18 KST) ·
[전체 릴리스 목록](https://github.com/cineraria01/cleanvid_app/releases)

## 바로 받기 — 항상 최신 버전으로 연결됩니다

| 플랫폼 | 다운로드 |
|---|---|
| **macOS** (Apple Silicon, macOS 14 이상) | [⬇ cleanvid-darwin-arm64.app.zip](https://github.com/cineraria01/cleanvid_app/releases/latest/download/cleanvid-darwin-arm64.app.zip) |
| **Windows** (x64) | [⬇ cleanvid-windows-amd64.zip](https://github.com/cineraria01/cleanvid_app/releases/latest/download/cleanvid-windows-amd64.zip) |

위 두 링크는 버전 번호가 들어 있지 않은 고정 주소라, 새 버전이 나오면 자동으로
새 파일을 내려받습니다. 이 페이지의 버전 표기는 릴리스가 게시될 때 자동으로 바뀝니다.

## 설치

- **Windows**: zip을 풀고 `cleanvid.exe`를 실행합니다. "Windows의 PC 보호" 창이 뜨면
  **추가 정보 → 실행**을 누르세요(아직 코드 서명이 없어 나오는 표준 안내입니다).
- **macOS**: zip을 풀고 `cleanvid.app`을 응용 프로그램 폴더로 옮긴 뒤 **우클릭 → 열기**로
  처음 한 번 실행합니다.

## 자동 업데이트

앱은 실행될 때 이 저장소의 최신 릴리스를 확인하고, 새 버전이 있으면 백그라운드로
내려받아 교체합니다. **앱을 다시 실행하면 새 버전이 적용됩니다.** 그러니 한 번 설치하면
이 페이지에 다시 올 필요가 없습니다.

릴리스는 코드 저장소의 main 브랜치에 머지될 때마다 GitHub Actions가 자동으로
빌드·서명·업로드합니다 (patch 버전 자동 증가). 소스 코드는 별도의 비공개 저장소에서
관리됩니다.

> 참고: 여기 올라오는 zip은 실행 파일만 포함합니다. ML 모델 등 대용량 구성 요소(~2GB)는
> 앱이 첫 실행 시 자동으로 설치하며, 업데이트 시에는 다시 받지 않습니다.
