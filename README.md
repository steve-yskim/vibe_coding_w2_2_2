# vibe_coding_w2-1

## 프로젝트 개요
- 온라인 쇼핑 최저가 검색 챗봇 Agent
- 사용자가 상품명을 입력하면 여러 쇼핑몰의 가격을 비교하여 최적의 구매 선택을 도와주는 AI 챗봇

## 주요 기능
- 상품명 입력 시 실시간 가격 비교
- 여러 쇼핑몰 정보 통합 제공
- FastAPI 백엔드 + Streamlit 프론트엔드
- LangGraph 기반 React Agent, Gemini LLM, DuckDuckGo Tool 연동

## 폴더 구조
```
backend/   # FastAPI 백엔드
frontend/  # Streamlit 프론트엔드
docs/      # 문서 및 와이어프레임
```

## 실행 방법

### 1. 백엔드 실행
```bash
cd backend
pip install -r requirements.txt
python run.py
```

### 2. 프론트엔드 실행
```bash
cd frontend
pip install -r requirements.txt
streamlit run app.py
```

## 환경 변수 설정
- backend/env.example 참고

## 테스트
```bash
cd backend
python -m pytest tests/
```

## 기술 스택
- Python 3.11, FastAPI, Streamlit, LangGraph, Gemini LLM, DuckDuckGo, Pytest

테스트용 PR 생성 작업입니다. 

테스트용 PR을 위한 임시 수정입니다. 