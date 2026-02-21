# 냥냥 다이스! - 랭킹, 업적 시스템 구현 / 플랫폼 연동 / 신규 빌드 배포

**🔹 진행 기간 :** **2025.12.23 ~ 2026.01.08**

## 🔷 사용 기술 스택

| 분류 | 내용 |
|------|------|
| **Engine** | Unity 6 |
| **Version Control** | SVN |
| **Build Target** | Android, iOS |

## 🔷 업무 내용

**🔹 랭킹 시스템 구현 및 플랫폼 연동**

<img src="https://github.com/user-attachments/assets/00bd643f-9ec1-4b61-a1c5-81807f1db994" width="20%">
<img src="https://github.com/user-attachments/assets/a5e94101-82f1-498f-a287-2e9178982698" width="20%">

⬆ 계정 생성 및 랭킹 조회/등록 기능 구현 :

사내 자체 랭킹 서버 API 및 .NET HttpClient를 이용하여 비동기 네트워킹 처리

Play Games Service 및 Game Center와 연동하여, 각 플랫폼의 계정 정보를 이용하여 계정 자동 생성

게임오버시 서버에 등록된 랭킹을 조회하고, 최종 점수에 따라 랭킹 등록

게임 삭제 후 재설치시, 기존 계정 정보 및 점수 복원



**🔹 업적 시스템 구현**

<img src="https://github.com/user-attachments/assets/5e1e8e3b-2c5f-4bc1-b56e-bf4f67571969" width="20%">

<img src="https://github.com/user-attachments/assets/7447a56d-c323-4517-be48-206a8216d9b1" width="20%">


⬆ 업적 달성 및 조회 기능 구현 :

플랫폼별 업적 기능을 이용하여 구현

플랫폼별 콘솔에 신규 업적 등록 및 게시



**🔹 신규 빌드 배포**

<img src="https://github.com/user-attachments/assets/120303f7-182f-4ac7-8f87-217818db3415" width="20%">

<img src="https://github.com/user-attachments/assets/b948c25e-4077-4f87-aad9-520e3ecda185" width="20%">


⬆ Android/iOS 크로스 플랫폼 빌드 진행 및 스토어 업로드 :

플랫폼별 빌드 세팅/빌드 (Android : 키스토어, iOS : XCode, 프로비저닝 등)

신규 빌드 배포를 위해 PM 및 서비스운영팀과 협업 수행
