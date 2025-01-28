# 🚗 AutoHive

- **프로젝트명**: AutoHive - 차량 성능 및 안전성 제공 서비스
- **사용 대상**:
    - 차량 성능과 안전성 정보를 신속히 확인하고 싶은 일반 사용자
    - 차량 구매 시 성능과 안전을 중요하게 생각하는 잠재 고객
- **문제 의식**:
    - 차량에 대한 성능과 안전성 정보는 복잡한 데이터와 자료를 통해야만 접근할 수 있어 비전문가에게 어려움.
    - 신뢰할 수 있는 데이터를 기반으로 차량 정보를 제공하는 간소화된 접근법 필요.
- **제공 서비스**:
    - **자동차 성능 및 안전성 정보 제공**: 사용자가 입력한 차량 모델명을 바탕으로 성능과 안전 정보를 요약하여 제공.
    - **RAG 기반 검색 및 응답 생성**: 최신 데이터를 기반으로 차량 정보를 정확하게 제공.
    - **사용자 맞춤형 정보 제공**: 차량 성능 및 안전성을 바탕으로 한 의사결정 지원.

## 👀 프로젝트 주요 화면

- **자동차 리스트 화면**
    - **자동차 이미지, 모델명, 연식, 평점**을 보여주는 리스트
  
![image](https://github.com/user-attachments/assets/22b5b1f4-0feb-40da-98b9-28c296f33dc4) ![image](https://github.com/user-attachments/assets/03e06600-9fc4-4012-bbad-2987da8d3f4c)

- **자동차 상세 정보 화면**
    - **직선 주행 성능, 곡선 주행 성능, 안전 장비, 편의 장치** 등 상세 정보 제공

![image](https://github.com/user-attachments/assets/3a830ff6-aadf-4781-befa-ce5184702865) ![image](https://github.com/user-attachments/assets/40f67d22-5481-4e68-8c4f-f3bfdd46a691)

- **AI 챗봇 채팅 화면**
    - RAG 기반 채팅 화면

<div style="display: flex; gap: 10px; justify-content: center;">
    <img src="https://github.com/user-attachments/assets/1921a48a-8b3f-4dcc-aaa2-ed35c21173ea" alt="Chatbot Screen 1" style="width: 30%; aspect-ratio: 16/9; object-fit: cover;">
    <img src="https://github.com/user-attachments/assets/daf06d74-0326-4c5e-abb3-f97670c01e08" alt="Chatbot Screen 2" style="width: 30%; aspect-ratio: 16/9; object-fit: cover;">
    <img src="https://github.com/user-attachments/assets/4c11a692-44c0-43ab-8bf3-8af4479ef7fe" alt="Chatbot Screen 3" style="width: 30%; aspect-ratio: 16/9; object-fit: cover;">

</div>


## 🛠 사용 기술 및 라이브러리
- **AI**: RAG (Retrieval-Augmented Generation), Gemini LLM
- **벡터스토어**: FAISS
- **임베딩 모델**: Upstage 임베딩 모델 (한국어 특화)
- **BE**: Flask, Spring Boot
- **DB**: MySQL
- **프론트엔드**: Android (Kotlin, Jetpack Compose)
- **API 문서화**: Swagger
- **배포 및 운영**: Docker, AWS EC2, ECR, S3, RDS

## ⚙️ Architecture
![image](https://github.com/user-attachments/assets/819f6f87-6b4f-41a8-86ec-17932408ac71)
