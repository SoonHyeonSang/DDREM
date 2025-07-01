# DDREM
ChatGPT와 영상처리를 이용한 졸음 감지 시스템

![그림8](https://github.com/user-attachments/assets/ebd63c19-b28a-4a9c-a7a5-a65d3cb2b9a7)
### 📌 프로젝트 소개

졸음운전 방지를 위한 딥러닝 기반 시스템으로, 운전자의 얼굴을 실시간으로 인식하고 눈 깜빡임, 하품 등의 졸음 신호를 감지하여 TTS 음성 퀴즈로 경고를 주는 시스템입니다. Jetson Nano에서 작동하도록 최적화하였으며, STT를 통해 사용자의 음성 응답을 인식하여 상호작용합니다.

![그림3](https://github.com/user-attachments/assets/25bb44d4-a9c2-4eb9-bf7b-5395559fc57c)

시스템 흐름도

![그림5](https://github.com/user-attachments/assets/9c474ab3-ac05-4898-a2a8-d95da1005ffa)

데이터 학습을 통한 판별

![그림4](https://github.com/user-attachments/assets/94648ccd-16e3-43c8-9499-b40072549521)

눈의 종횡비를 구해 판별

![그림7](https://github.com/user-attachments/assets/8b9acb34-416c-43c2-b9fd-c9975064a638)

PERCLOS공식 및 판단 기준

### 🛠 주요 기능

- **영상 처리 기반 졸음 감지**: OpenCV + Dlib을 활용한 눈/입 영역 추적 및 EAR, MAR 계산
- **실시간 경고**: 졸음 상태일 경우 ChatGPT + TTS를 활용한 음성 퀴즈 경고 시스템
- **음성 인터랙션**: STT를 통해 사용자 응답 인식 → 졸음 해소 효과 유도
- **최적화**: Jetson Nano 환경에서 경량화된 코드 구현

---

### 👨‍💻 본인 역할

- 얼굴 인식 및 졸음 판단 알고리즘 구현 (Dlib, OpenCV 기반)
- pyttsx3와 STT 모듈 연동을 통한 TTS/음성 인식 로직 구현
- ChatGPT API 연동 및 시스템 시나리오 구성

- ![그림](https://github.com/user-attachments/assets/9627e701-6dd7-44bb-973e-457d6b20f7bc)

- ![그림9](https://github.com/user-attachments/assets/207adef0-d8ae-48bc-b4fe-c56ae35b2ecd)

- ![그림10](https://github.com/user-attachments/assets/4b5a6650-6ca2-42f9-8e63-e3c6c6f156c0)


