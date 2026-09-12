# FATAL TWELVE 한국어 패치
<img width="1358" height="768" alt="image" src="https://github.com/user-attachments/assets/d295195f-4c8e-4865-9c35-b39e3ee8fe88" />

FATAL TWELVE의 일본어판을 기준으로 제작한 비공식 한국어 패치입니다.

- 최신 버전: `v1.0`
- 배포 형식: 자체 포함형 Windows BAT 설치 파일
- 다운로드: [v1.0 릴리스](https://github.com/jjpatch12/fatal-twelve-korean-patch/releases/tag/v1.0)

## 설치 방법

1. 릴리스에서 `FATAL_TWELVE_Korean_Patch_v1.0.zip`을 받습니다.
2. ZIP의 파일을 `fatal.exe`가 있는 게임 폴더에 풉니다.
3. `FATAL_TWELVE_한국어패치_설치.bat`을 실행합니다.
4. 설치 완료 후 게임을 완전히 종료했다가 다시 실행합니다.

설치 BAT 내부에 번역·폰트·한국어 로고가 포함되어 있습니다. 설치 후 실제 패치 데이터는 `game` 폴더에 숨김 속성의 단일 RPA 아카이브로 저장됩니다. 번역 원문인 `.rpy` 파일은 배포본에 포함하지 않았습니다.

## 패치 범위

자세한 적용 범위와 검증 결과는 [PATCH_SCOPE.md](PATCH_SCOPE.md)를 확인하세요.

## 제거 방법

명령 프롬프트에서 다음과 같이 실행합니다.

```bat
FATAL_TWELVE_한국어패치_설치.bat --uninstall
```

## 폰트

이 패치는 편진고딕(Pyeojin Gothic)을 사용합니다.

- Copyright © 2025 서지환(Suh Ji-hwan)
- SIL Open Font License 1.1
- <https://scripts.sil.org/OFL>

FATAL TWELVE 및 원본 게임 자산의 권리는 각 권리자에게 있습니다. 이 패치는 정품 게임 보유자를 대상으로 합니다.
