<!-- 프로필 사진 -->
![image](https://github.com/user-attachments/assets/1c580072-7caf-484f-a55c-da4899cc22c2)

<!-- 팀원 및 역할 -->
## 팀원 및 역할

<div align="center">

| <img src="https://github.com/user-attachments/assets/dc4eb80e-edf4-41a2-abda-b1175dcf6206" width="120"/> | <img src="image2.jpg" width="120"/> | <img src="image3.jpg"  width="120"/> | <img src="https://emojipedia-us.s3.amazonaws.com/source/skype/289/thumbs-up_1f44d.png" width="120"/> | <img src="https://emojipedia-us.s3.amazonaws.com/source/skype/289/laptop_1f4bb.png" width="120"/> | <img src="image6.jpg" width="120"/> |
|------------------------------------------------------|--------------------------------------------------|--------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------|
| [Roki.Kim(김경록)](https://github.com/KimGyeongLock)                                            | [Austin.Choi(최윤서)](https://github.com/Austin-Choi)                                           | [Cellina.Jeong(정은채)](https://github.com/Goldchae)                                           | [Jay.Hwang(황지원)](https://github.com/JiwonHwang84)                                                                                                                                               | [Sofia.Park(박수현)](https://github.com/suugit)                                                                                                                                               | [Jimmy.Kim(김승엽)](https://github.com/yeopyeop-82)                                           |
| Full-Stack                                              | Full-Stack                                       | AI                                       | AI                                                                                                                                           | Cloud                                                                                                                                              | Cloud                                       |
</div>

<!-- 목차 -->
## 목차
* [⚒️ 기술스택](#stack)
* [🤔 아이디어 소개](#idea)
* [📞 주요 기능](#function)
* [💸 아키텍처](#architecture)
* [🗂️ ERD](#erd)
* [🔎 기술 사용 근거](#detail)
* [📈 성능 개선 & 리팩토링](#improve)
* [🖥️ 테스트 & 모니터링](#test)
* [🍻 결과](#result)
* [📺 시연 영상](#video)


<!-- 기술 스택 -->
<a id="stack"></a>
## ⚒️ 기술스택
<details>
<summary> 본문 확인 (👈 Click) </summary>
<div markdown="1">

### 📞 텍스트 통화
<img src="https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=WebRTC&logoColor=white">
<img src="https://img.shields.io/badge/socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white">
<img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
<img src="https://img.shields.io/badge/react.js-61DAFB?style=for-the-badge&logo=react&logoColor=black">
<img src="https://img.shields.io/badge/express.js-000000?style=for-the-badge&logo=express&logoColor=white">

<br>

### 🎤 STT / TTS
<img src="https://img.shields.io/badge/Amazon Transcribe-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white">
<img src="https://img.shields.io/badge/Amazon Polly-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white">

<br>

### 🤖 AI
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white">
<img src="https://img.shields.io/badge/NVIDIA CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white">
<img src="https://img.shields.io/badge/LangChain-333333?style=for-the-badge&logo=langchain&logoColor=white">
<img src="https://img.shields.io/badge/Google Cloud Speech to Text-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white">
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white">

<br>

### 🔄 CI/CD
<img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white">
<img src="https://img.shields.io/badge/Argo CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white">

<br>

### 🔍 모니터링
<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white">
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white">

<br>

### ⚙️ 인프라
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white">
<img src="https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white">
<img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white">
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white">
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">

</div>
</details>

<!-- 아이디어 소개 -->
<a id="idea"></a>
## 🤔 아이디어 소개
<details>
<summary> 본문 확인 (👈 Click) </summary>
<div markdown="1">

'콜포비아'를 가진 사람이 전화 통화를 할 때, 상대방은 음성으로 계속 대화를 이어가고, '콜포비아'인 사람은 말을 하지 않고 문자로 편하게 답변을 입력합니다.<br>
그러면 그 문자가 AI에 의해 음성으로 변환되어 상대방에게 전달됩니다. 상대방은 일반적인 전화 통화를 하는 것처럼 느끼지만, '콜포비아'인 사람은 문자만으로 모든 대화를 처리합니다.<br>
이 과정에서 AI는 대화의 맥락을 실시간으로 파악하여 적절한 답변 예시를 제시해 주어, '콜포비아'인 사람이 당황하지 않고 더 편안하게 대화를 이어갈 수 있도록 돕는 서비스입니다.

</div>
</details>

<!-- 기능 소개 -->
<a id="function"></a>
## 📞 주요 기능
<details>
<summary> 본문 확인 (👈 Click) </summary>
<div markdown="1">

주요 기능 내용입니다.

</div>
</details>

<!-- 아키텍처 -->
<a id="architecture"></a>
## 💸 아키텍처
<details>
<summary> 본문 확인 (👈 Click) </summary>
<div markdown="1">

아키텍처 내용입니다.

</div>
</details>

<!-- ERD -->
<a id="erd"></a>
## 🗂️ ERD
<details>
<summary> 본문 확인 (👈 Click) </summary>
<div markdown="1">

ERD 내용입니다.

</div>
</details>

<!-- 기술 사용 근거 -->
<a id="detail"></a>
## 🔎 기술 사용 근거
<details>
<summary> 본문 확인 (👈 Click) </summary>
<div markdown="1">

기술 사용 근거 내용입니다.

</div>
</details>

<!-- 성능 개선 & 리팩토링 -->
<a id="improve"></a>
## 📈 성능 개선 & 리팩토링
<details>
<summary> 본문 확인 (👈 Click) </summary>
<div markdown="1">

성능 개선 & 리팩토링 내용입니다.

</div>
</details>

<!-- 테스트 & 모니터링 -->
<a id="test"></a>
## 🖥️ 테스트 & 모니터링
<details>
<summary> 본문 확인 (👈 Click) </summary>
<div markdown="1">

테스트 & 모니터링 내용입니다.

</div>
</details>

<!-- 결과 -->
<a id="result"></a>
## 🍻 결과
<details>
<summary> 본문 확인 (👈 Click) </summary>
<div markdown="1">

결과 내용입니다.

</div>
</details>

<!-- 시연 영상 -->
<a id="video"></a>
## 📺 시연 영상
<details>
<summary> 본문 확인 (👈 Click) </summary>
<div markdown="1">

시연 영상 내용입니다.

</div>
</details>
