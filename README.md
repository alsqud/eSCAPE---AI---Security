# 🛡️ eSCAPE: AI-Powered Anti-Scam Platform
   > 시민 참여형 데이터와 LLM 기반 전술 프로파일링을 활용한 지능형 피싱 예방 솔루션입니다.

# 📋 프로젝트 개요
   > 시민들의 자발적 제보 데이터를 실시간으로 학습하고, KAIST 9단계 전술 매트릭스에 기반하여
     피싱 위협을 정밀 진단하는 보안 플랫폼 eSCAPE의 핵심 로직입니다.

 ## 🚀 핵심 알고리즘 (Key Algorithms)
   - Self-Learning RAG : ChromaDB를 활용해 신종 수법을 실시간 자가 학습합니다.
   - Privacy Protection : 정규표현식 기반 마스킹으로 제보 데이터 내 개인정보를 비식별화합니다.
   - Dual Guardrails : 안전한 모의체험을 위해 입출력 가드레일을 적용했습니다.

## 🛠️ 기술 스택 (Tech Stack)
   - AI Model : Google Gemini (gemma-3-27b-it)
   - Backend : FastAPI, Uvicorn
   - Database : ChromaDB (Vector Store)
   - Security : Regex-based Masking, Safety Guardrails
