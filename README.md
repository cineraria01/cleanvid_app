# CleanVid 다운로드

CleanVid 실행 파일 배포 저장소입니다. 소스 코드는 별도의 비공개 저장소에서 관리됩니다.

## 다운로드

[Releases](https://github.com/cineraria01/cleanvid_app/releases/latest)에서 최신 버전을 받으세요.

| 파일 | 플랫폼 |
|---|---|
| `cleanvid-darwin-arm64.app.zip` | macOS (Apple Silicon) |
| `cleanvid-windows-amd64.zip` | Windows x64 |

## 자동 업데이트

앱은 실행될 때 이 저장소의 최신 릴리스를 확인하고, 새 버전이 있으면 백그라운드로
내려받아 교체합니다. **앱을 다시 실행하면 새 버전이 적용됩니다.**

릴리스는 코드 저장소의 main 브랜치에 머지될 때마다 GitHub Actions가 자동으로
빌드/업로드합니다 (patch 버전 자동 증가).

> 참고: 여기 올라오는 zip은 실행 파일만 포함합니다. ML 모델 등 대용량 구성 요소(~2GB)는
> 앱이 첫 실행 시 자동으로 설치하며, 업데이트 시에는 다시 받지 않습니다.
