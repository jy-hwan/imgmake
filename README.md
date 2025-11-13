# 🎨 Stable Diffusion 이미지 생성 프로젝트 (Google Colab)

이 프로젝트는 Google Colab 환경에서 **Stable Diffusion 모델을 이용한 이미지 생성 AI**를 구현한 예제입니다.  
프롬프트(텍스트 설명)에 따라 이미지를 자동으로 생성하며,  
FastAPI와 ngrok을 연동해 **외부 Flask 서버에서도 호출 가능한 이미지 생성 API** 형태로 구성했습니다.

---

## 🚀 주요 기능
- 🧠 Stable Diffusion 기반 텍스트-투-이미지 생성
- ⚡ Google Colab + GPU 환경 최적화
- 🌐 FastAPI + ngrok을 이용한 외부 접근 가능한 API 서버
- 💾 생성된 이미지 자동 저장 및 미리보기 제공

---

## ⚙️ 사용 기술
| 구분 | 기술 |
|------|------|
| Language | Python 3.10 |
| Environment | Google Colab |
| Framework | FastAPI |
| AI Model | Stable Diffusion (diffusers 라이브러리) |
| Tools | ngrok, torch, transformers, accelerate |

---

## 🧩 파일 구성

---

## 🪄 실행 방법
1. Google Colab에서 `imgmake.ipynb` 파일 열기
2. 런타임 유형을 GPU로 설정
3. 셀을 순서대로 실행
4. 마지막 셀에서 ngrok URL 확인 후 접속
5. 프롬프트 입력 시 해당 설명에 맞는 이미지 자동 생성

---

## 🙋‍♀️ 담당 역할
- Stable Diffusion 모델 설정 및 프롬프트 기반 이미지 생성 로직 구현  
- FastAPI + ngrok 연동으로 외부 Flask 서버와 연결 구조 구성  
- Colab 환경에서 이미지 생성 API 완성 및 테스트 수행  

---

