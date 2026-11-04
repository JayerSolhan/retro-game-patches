# BIOHAZARD ZERO modern_control v1.0

지원: Nintendo GameCube 일본판 GBZJ08 Rev0 (Disc 1·2 인식)

## 구성
- Dolphin GameINI: 게임 속성 > 패치에서 `modern_control` 활성화. 원본 이미지 그대로 사용.
- Windows 영구 패처: 원본 ISO/GCM/RVZ를 `Apply_modern_control.bat`에 끌어다 놓으면 `_modern_control` 이름으로 별도 이미지 생성.
- 사용자 매뉴얼: UTF-8 BOM / CRLF **TXT** 파일 3개. 기존 사용자 설정을 백업한 후 적용.

**두 방식을 동시에 사용하지 마세요.** 기존 Gecko/AR 모던 컨트롤 코드도 함께 켜지 마세요. 게임 이미지·원본 DOL·에뮬레이터 미포함.

## 검증
- Disc 1: Dolphin INI 및 Windows 영구 패처 사용자 실게임 PASS.
- Disc 2: 실행 코드·후크 정적 검증 PASS, 실제 게임 및 디스크 교체 미검증.
- 패치 코드 불변(표시 이름·출력 이름만 조정), 오프라인 회귀검사 126/126 PASS.
- 새 Windows BAT의 실제 Windows 실행 및 실제 RVZ 변환은 별도 미검증.

SHA-256 (`BIOHAZARD_ZERO_modern_control_GBZJ08.zip`): `9c5da31c0264ff7cc1098813b3a6a9a661b11d7cd1f07b7f07b12cfd09faea02`
