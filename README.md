<div align="center">

  <h1>맘편해 MOMFY</h1>
  <p>영유아를 위한 비접촉 자동 체온 측정과 AI 발열 리포트 생성 서비스</p>
</div>

<br/>

<div align="center">
  <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2036daea-0ef3-485a-9ac7-1297d2bf2a4b" />
</div>

<br/>

---
## 💡 1. 프로젝트 개요

**1-1. 프로젝트 소개**

- 프로젝트 명: **맘편해**
- 프로젝트 정의: IoT 센서 측정과 AI 분석을 기반으로 리포트를 제공하는 영유아 스마트 헬스케어 서비스
<br><br>


**1-2. 개발 배경 및 필요성**

기존 접촉식 체온계는 수면 방해와 반복 측정의 불편함이 있고, 웨어러블 기기는 접촉에 의한 피부 자극과 발열로 인한 착용 부담이 발생합니다. 또한 부모가 진료 시 상황을 정확히 기록·전달하지 못해 의사 진단이 제한되는 문제도 존재합니다. 이러한 한계를 해결하기 위해 **비접촉 IoT 센서와 AI 분석 기술을 기반으로 한 영유아 발열 관리 서비스**가 필요합니다.
<br><br>

**1-3. 프로젝트 특장점**

맘편해는 영유아의 체온과 환경을 비접촉 방식으로 측정해 아기 피부에 부담 없이 데이터를 확보합니다. 순간 수치에 그치지 않고 체온과 환경 변화를 지속적으로 기록하고 분석하여 신뢰성을 높이고, 이를 기반으로 AI 발열 리포트를 생성해 부모가 의사에게 진료를 받을 때 객관적인 정보를 제공할 수 있도록 돕습니다. 더불어 체온·환경 모니터링과 홈캠 영상을 하나의 앱에서 한 번에 확인하고 관리할 수 있어 편리성이 높으며, 고열이나 환경 이상 발생 시 즉각적인 알림과 의료 정보 제공을 통해 부모가 빠르고 적절하게 대응할 수 있도록 지원합니다.
<br><br>

**1-4. 주요 기능**

- **실시간 체온 측정**: 적외선 센서를 활용한 자동 체온 기록
- **환경 모니터링**: 온습도 센서를 통한 실시간 환경 관리 및 홈캠을 통한 실시간 영상 확인
- **AI 발열 리포트**: 체온, 증상, 외출 기록, 해열제 복용 여부 등 발열 데이터와 환경 정보를 종합해 AI 리포트 자동 생성
- **헬스케어 알림**: 발열 징후 또는 환경 이상 감지 시 즉각 알림 전송을 통한 부모의 신속 대응 지원
- **의료 정보 제공**: 주변 병원 및 응급실 정보 제공으로 긴급 상황 시 빠른 대응 가능
<br><br>

**1-5. 기대 효과 및 활용 분야**

영유아는 미세한 체온 변화나 고열을 몸짓과 행동으로 표현하지만, 초보 부모는 이를 즉시 알아차리지 못하는 경우가 종종 있습니다. 본 서비스는 이러한 변화를 빠르게 감지하여 부모의 부담을 줄이고, 보다 안심할 수 있는 양육 환경을 제공합니다. 또한 부모는 영유아가 열이 날 때 부정확한 기억에 의존해 의사에게 설명하는 경우가 많아 의사는 제한된 정보만으로 진단해야 하는 어려움이 있습니다. 이에 따라 오진이나 진료 지연이 발생할 수 있는데, 본 서비스가 제공하는 발열 리포트는 정확하고 체계적인 데이터를 전달하여 불필요한 검사나 치료를 줄이고, 더욱 빠르고 정확한 진단을 가능하게 합니다.
<br><br>

**1-6. 기술 스택**

- **프론트엔드**: Flutter
- **백엔드**: Java 21, Spring Boot, Spring Security
- **IoT/임베디드**: ESP32, MLX90640(비접촉 체온), DHT11(온습도), OV2640(카메라)
- **데이터베이스**: MySQL, Redis
- **클라우드**: AWS EC2, S3, RDS
- **배포 및 관리**: Docker, GitHub Actions
<br><br>
---

## 💡 2. 팀원 소개
| <img width="150" height="150" alt="image" src="https://github.com/user-attachments/assets/49efe4b5-f2be-4e9a-8a59-1d4657af8818" /> | <img width="150" height="150" alt="image" src="https://github.com/user-attachments/assets/2c18ee4b-8f42-4a0c-ac8c-7d8608f387bb" /> | <img width="150" height="150" alt="image" src="https://github.com/user-attachments/assets/39743666-c770-4d26-8c3d-26bdb0af2ff9" /> | <img width="150" height="150" alt="image" src="https://github.com/user-attachments/assets/474c0ba4-52bf-475b-87f8-b21844dd38c4" /> | <img width="150" height="150" alt="5" src="https://github.com/user-attachments/assets/998329f0-cc22-4773-9d8d-4b74e335b966" /> | <img width="150" height="150" alt="3" src="https://github.com/user-attachments/assets/4e4420f6-9c57-48a1-9276-ac54a7a14093" /> | 
|:---:|:---:|:---:|:---:|:---:|:---:|
| **임준서** | **김준형** | **박현빈** | **신정현** | **박지환** | **최강민** |
| 팀장(PM) | 백엔드 <br> 임베디드 | 백엔드 <br> DB 관리 <br> 인프라 설계 | 백엔드 | 프론트엔드 <br> 형상 관리 | 프론트엔드 |



---

## 💡 3. 시스템 구성도

### **S/W 구성도**
<img width="70%" alt="image" src="https://github.com/user-attachments/assets/095b62d5-e18b-43cb-aff7-708ccee677d0" />
<br/><br/>

### **H/W 구성도**
<img width="555" height="432" alt="image" src="https://github.com/user-attachments/assets/6cc5e3f5-6dc4-406c-9e9f-ba5b52fd89f6" />

<br/><br/>

### **엔티티 관계**
<img width="3380" height="1312" alt="image" src="https://github.com/user-attachments/assets/065e120d-150a-4974-b200-5a9721e058b3" />
<br/><br/>

### **백엔드 아키텍처**
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d628c43e-4944-40c4-8010-4a5b280c2b9c" />
<br/><br/>

<br/>

---
## 💡 4. 기능 예시 화면
| <img width="161" height="308" alt="image" src="https://github.com/user-attachments/assets/66c399b7-523a-4f28-92c4-7b465fc20f07" /> | <img width="160" height="309" alt="image" src="https://github.com/user-attachments/assets/6879a3ee-6850-4cf5-89a5-b75d5af3db0d" /> | <img width="161" height="305" alt="image" src="https://github.com/user-attachments/assets/3f1c9c71-7d58-4bff-a9c0-5fbc68151de4" /> | <img width="160" height="303" alt="image" src="https://github.com/user-attachments/assets/4c15746c-d3e3-493f-87cb-cba4ffbfe1b3" /> | <img width="158" height="304" alt="image" src="https://github.com/user-attachments/assets/a239a025-e9b0-4add-87e5-232396d5e331" /> | 
|:---:|:---:|:---:|:---:|:---:|
| 시작 화면 | 로그인 화면 | 메인 화면 | 체온 그래프 | 케어 알림 |

| <img width="164" height="312" alt="image" src="https://github.com/user-attachments/assets/102de42d-3b36-42e4-ad50-1d20e2dbc809" /> | <img width="158" height="302" alt="image" src="https://github.com/user-attachments/assets/701dc948-ea32-4d5a-82ea-bab667d2e367" /> | <img width="156" height="305" alt="image" src="https://github.com/user-attachments/assets/ff7ee766-9c14-4015-8b28-ad5e56d55605" /> | <img width="158" height="304" alt="image" src="https://github.com/user-attachments/assets/6eb157ad-0193-451b-a6b1-7435c7b1f864" /> | <img width="157" height="304" alt="image" src="https://github.com/user-attachments/assets/d923d2ad-aabc-4fb7-b904-a5b95b9806ed" /> |
|:---:|:---:|:---:|:---:|:---:|
| 홈캠 화면 | 리포트 생성 | 리포트 결과 | 내 위치 주변 병원 | 캘린더 |

---
## 💡 5. 시연 영상
> 아래 이미지를 클릭하시면 시연 영상을 확인하실 수 있습니다.

[![시연 영상 바로가기](https://github.com/user-attachments/assets/d427c18c-c69c-49b4-b5b6-57b79818202e)](https://youtu.be/RlyZUbuNoy4)

<br/><br/>
