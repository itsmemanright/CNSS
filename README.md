# CNSS

**Core Nursing Skills Simulator** · 핵심간호술기 연습 게임

학교 실습실에서 물품 준비, 대상자 확인, 술기 수행과 기록을 연습합니다.

## 다운로드

### [Windows와 Android 최신 버전 받기](https://github.com/itsmemanright/CNSS/releases/latest)

현재 배포: **Windows / Android 0.27 · 2026-10-24**

| 플랫폼 | 바로 다운로드 | 제공 범위 |
| --- | --- | --- |
| Windows 64비트 | [Windows ZIP](https://github.com/itsmemanright/CNSS/releases/latest/download/CNSS-Windows-latest.zip) | 구현된 핵심술기 15종 |
| Android ARM64 | [Android APK](https://github.com/itsmemanright/CNSS/releases/latest/download/CNSS-Android-latest.apk) | 활력징후·근육주사·경구투약 3종, 나머지는 개발 중 |

최신 다운로드 주소는 다음 버전에도 유지됩니다. [이전 버전](https://github.com/itsmemanright/CNSS/releases)도 보관합니다. 이 저장소는 실행 파일과 이용 안내를 배포하는 곳입니다.

## 설치와 실행

Windows ZIP을 **전체 압축 해제**하고 `CNSS.exe`를 실행하세요. Unity 설치는 필요 없습니다. 실행 파일 옆의 CNSS_Data·DLL 등 모든 파일을 함께 보관하세요.

Android APK는 Android 8.0 이상·ARM64 기기용입니다. 다운로드한 파일을 열고 필요한 경우 해당 앱에 ‘출처를 알 수 없는 앱 설치’를 허용하세요. 기존 GitHub CNSS와 같은 서명키를 사용하므로 앱을 지우지 않고 업데이트할 수 있습니다. Play Store 설치본은 서명이 다를 수 있습니다.

## 조작

| 행동 | Windows | Android |
| --- | --- | --- |
| 이동 | WASD | 왼쪽 이동 조이스틱 |
| 시점 | 마우스 이동 | 오른쪽 시선 조이스틱·화면 드래그 |
| 기본 행동 | 마우스 왼쪽 클릭 | 좌클릭 버튼 |
| 추가 행동 | 마우스 오른쪽 클릭 | 우클릭 버튼 |
| 메뉴 | Esc | 메뉴 |
| 프로토콜 확인 | T | 순서 |
| 동작 배속 | R | 배속 |

Android에서도 연결된 키보드·마우스를 사용할 수 있습니다. 컨트롤러는 지원하지 않습니다. 환경설정에서 그래픽·30/60FPS, 화면 비율, 감도와 버튼 배치를 조정할 수 있습니다. 위치에 끼이면 메뉴에서 스폰 위치로 돌아가기를 사용하세요.

맥박·호흡은 30초 계수 후 ×2한 분당 값을 기록합니다. 혈압 측정은 기본 행동으로 가압하고 추가 행동으로 감압을 시작합니다. 감압 중 기본 행동으로 속도를 높이고 추가 행동으로 낮춥니다.

## 변경 내용과 확인 범위

이번에는 활력징후·근육주사·경구투약 3종의 진행과 손·기구·시점·UI 화면을 PC/모바일 모드에서 검사했습니다. 환자 팔 지지, 손씻기, 근육주사 손·소독솜 표시, 경구투약 관찰 장면, 기록실 가구와 책·TV·수납장·유리문·학교 외관 수정 등을 포함합니다.

[0.27 변경 내용과 검증 범위](https://github.com/itsmemanright/CNSS/releases/tag/v0.27)를 확인하세요. 실제 Android 기기에서의 손가락 조작과 장시간 60FPS는 이번에 확인하지 않았습니다. 모든 술기·모든 기기의 완전한 검증을 의미하지 않습니다.

## 문의

[GitHub Issues](https://github.com/itsmemanright/CNSS/issues)에 플랫폼·버전·술기·단계와 재현 방법을 적어 주세요. 문의: sunminwoo0228@gmail.com

## 크레딧

개발: 선민우. Unity와 외부 제작 도구·에셋을 사용합니다. 상세 출처는 게임 크레딧과 Windows 폴더의 CREDITS.txt를 확인하세요. 실행 파일 다운로드가 포함된 모델·이미지·음원의 별도 재배포 권한을 뜻하지는 않습니다.
