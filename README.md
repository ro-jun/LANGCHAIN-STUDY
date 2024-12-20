# LangChain_Study

LangChain 및 관련 기술(LangSmith, LangGraph)을 학습하기 위한 프로젝트입니다.

---

## 프로젝트 구조
```bash
LANGCHAIN-STUDY/
├── Langsmith/
│   ├── files/
│   │   ├── polly_facts.txt        : Polly와 관련된 정보를 담은 텍스트 파일
│   │   ├── polly_langchain.ipynb  : LangChain 관련 구현과 분석을 포함한 Jupyter Notebook
│   │   ├── polly_traceable.ipynb  : LangSmith 및 데이터 추적을 다루는 Jupyter Notebook
│   │   ├── polly_prompt_hub.ipynb : Prompt 관리를 다루는 Jupyter Notebook
│   │   └── polly_experiment.ipynb : Polly와 관련된 실험 내용을 담은 Jupyter Notebook
│   ├── .env                      : 환경 변수 파일
│   └── README.md                 : 프로젝트 설명 문서
└── requirements.txt              : Python 의존성 패키지 목록
```
---

## 주요 파일 설명

- **`polly_facts.txt`**  
  Polly와 관련된 기본적인 정보를 기록한 텍스트 파일:

- **`polly_langchain.ipynb`**  
  LangChain의 주요 기능과 활용 사례를 담은 Jupyter Notebook 파일입니다.

- **`polly_traceable.ipynb`**  
  LangSmith와 LangGraph를 활용하여 데이터 추적 및 분석을 다루는 Jupyter Notebook 파일입니다.

- **`polly_prompt_hub.ipynb`**  
  다양한 Prompt 관리를 위한 Jupyter Notebook 파일입니다.

- **`requirements.txt`**  
  프로젝트 실행에 필요한 Python 라이브러리 목록:
  - 주요 라이브러리: `langchain`, `langsmith`, `numpy`, `openai` 등.

---

## 설치 및 실행 방법

### 1. Python 의존성 설치
```bash
pip install -r requirements.txt
```
---

## 학습 목표

1. **LangChain의 주요 기능 학습**  
   LangChain을 사용하여 데이터 처리 및 워크플로 관리 방법을 익힙니다.

2. **LangSmith 및 LangGraph 활용**  
   데이터 추적, 시각화, 분석 방법을 실습합니다.

3. **Polly 데이터를 사용한 통합 실습**  
   Polly 데이터를 활용하여 LangChain 및 Python의 통합적 활용을 학습합니다.

---

## 사용 기술 스택

- **언어 및 환경**: Python 3.11.9
- **주요 라이브러리**: LangChain, LangSmith, LangGraph, OpenAI, Jupyter Notebook