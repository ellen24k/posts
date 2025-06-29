---
title: AIPoemGallery 2024
post_status: publish
featured_image: /_images/AIPoemGallery/aipoem.png
post_date: 2024-02-24T12:00:00+09:00
taxonomy:
  category:
    - Projects
  post_tag:
    - Python
    - Streamlit
    - PostgreSQL
    - PLpgSQL
    - Langchain
    - Oracle Cloud
    - Jenkins
    - CI/CD
    - Minio
    - APScheduler
    - AI 프로젝트
    - 삼행시 생성기
    - 음성 합성
    - 이미지 생성
    - ChatGPT
    - DALL·E
    - TTS
---

![AIPOEM](https://raw.githubusercontent.com/ellen24k/AIPoemGallery/master/resources/aipoem.png)

# AI 삼행시 갤러리 v2.0 2025
### 프로젝트 소개

> _**AI 삼행시 갤러리**_ 는 사용자가 제시한 단어를 기반으로 삼행시와 삼행시에 기반한 이미지, 시 낭송 음성을 생성합니다.

(v1.0) Azure Speech(TTS), Dall-e3, Chat-GPT4
with GitHub, Streamlit, Supabase(Storage, PostgreSQL, Edge Function), Azure AI Studio and GitHub Action Deploy, SQL & PLpgSQL routines(stored procedure) with pg_net extension, Trigger, TypeScript, Python, Docker, Langchain, pyshorteners, npm, pip, requests, dot-env, thread, async.. 등등 다양한 api를 활용해 개발했습니다.

(v2.0) Streamlit 사이트에서 작동하던 앱을 Oracle Cloud로 이전하였습니다. Supabase의 Storage, PostgreSQL, Edge Fucntion를 Minio Object Storage, Python Apscheduler로 변경하였습니다. 또한 Jenkins를 적용하여 이미지를 자동빌드 및 배포하게 CI/CD를 변경하였습니다.
### AI 삼행시 갤러리 v1.0~v2.0

AI를 활용한 삼행시 생성 및 삼행시 기반 이미지 생성기
> v1.0 프로젝트 기간: `2024.11~2024.12`
> \
> v2.0 프로젝트 기간: `2025.1~2025.2`
> \
> [DEMO PAGE V2.0](https://gallery.ellen24k.kro.kr)

### 주요 기능

- 삼행시 생성
    - 사용자가 세 글자 단어를 입력하면 해당 글자를 이용해 삼행시와, 삼행시에 어울리는 그림을 생성할 수 있다.
- 갤러리
    - 지금까지 생성한 삼행시, 음성 파일 및 그림을 확인할 수 있다.
- 갤러리 관리
    - 관리자는 생성된 삼행시 자료들을 삭제할 수 있다.

### 데모 동영상 (V1.0)
![AIPoemGallery](https://raw.githubusercontent.com/ellen24k/AIPoemGallery/master/resources/chatbot_mobile_gallery.gif)

### 데모 동영상 다운로드 (V1.0) (시낭송 음성을 듣기 위해 동영상으로 감상하세요)
[데모 영상 다운로드](https://github.com/ellen24k/AIPoemGallery/raw/master/resources/chatbot_mobile_gallery.webm)

### Deployment Diagram - v1.0
![Diagram (v1.0)](https://raw.githubusercontent.com/ellen24k/AIPoemGallery/master/resources/diagram_deployment-1-.png)

### Deployment Diagram - v2.0
![Diagram (v2.0)](https://raw.githubusercontent.com/ellen24k/AIPoemGallery/master/resources/diagram_deployment_new.png)


### Tech Stacks v2.0
- - -
###### - _Languages & Frameworks_
<div style="display: flex; gap: 10px">
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Badge"> 
    <img src="https://img.shields.io/badge/PL%2FpgSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PL/pgSQL Badge">
    <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit Badge">
    <img src="https://img.shields.io/badge/Langchain-46d3e6?style=for-the-badge&logo=Langchain&logoColor=white" alt="Langchain Badge">
</div>

###### - _Database_
<div style="display: flex; gap: 10px;">
    <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL Badge">
</div>

###### - _Tools & Libraries_
<div style="display: flex; gap: 10px;">
    <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker Compose Badge">
    <img src="https://img.shields.io/badge/APScheduler-004080?style=for-the-badge&logo=APScheduler&logoColor=white" alt="APScheduler Badge">
    <img src="https://img.shields.io/badge/MINIO-FF2C00?style=for-the-badge&logo=minio&logoColor=white" alt="MINIO Badge">
</div>

###### - _Cloud Service Provider_
<div style="display: flex; gap: 10px;">
    <img src="https://img.shields.io/badge/Oracle_Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white" alt="Oracle Badge">
</div>

##### - _CI/CD_
<div style="display: flex; gap: 10px;">
    <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" alt="Jenkins Badge">
    <img src="https://img.shields.io/badge/GitHub%20Webhook-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Webhook Badge">
</div>


