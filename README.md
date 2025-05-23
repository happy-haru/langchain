# Langchain 학습 노트 및 예제 코드 🚀

이 저장소는 **Langchain 프레임워크**의 핵심 기능과 사용법을 학습하고 실험하기 위한 **Jupyter Notebook 예제 모음**입니다.  
핵심 내용을 간결하게 정리하여, 이동 중에도 빠르게 학습할 수 있도록 구성했습니다.

---

## 📚 노트북 소개

- **`01.Overall_Components.ipynb`**  
  Langchain의 주요 구성 요소(LLM, Prompt, Parser 등)를 소개하고, 기본 사용법을 다룹니다.

- **`02.LCEL.ipynb`**  
  Langchain Expression Language (LCEL)를 활용한 파이프라인 구성 방법을 실습합니다.

- **`03.Processing_data_by_document_type.ipynb`**  
  PDF, TXT 등 다양한 문서 유형의 데이터를 로드하고 처리하는 방법을 학습합니다.

- **`04.Text_Segmentation.ipynb`**  
  효과적인 정보 검색을 위한 텍스트 분할 전략과 구현 예제를 포함합니다.

- **`05.embedding.ipynb`**  
  다양한 임베딩 방법을 통해 데이터를 벡터로 변환하는 예제를 포함합니다.
---

## 🛠️ 시작하기

### 설치 및 환경 준비

- Python 3.8 이상
- Jupyter Notebook 또는 JupyterLab
- 필수 라이브러리는 `requirements.txt` 파일 참고
- (필요 시) OpenAI API Key  
  `.env` 파일에 아래와 같이 저장:
  ```env
  OPENAI_API_KEY="YOUR_KEY"

✨ 학습 포인트
1. Langchain을 활용한 전체 파이프라인 구성 이해

2. LCEL (Langchain Expression Language) 실습

3. 다양한 문서 로더(Document Loaders) 활용

4. 텍스트 분할기(Text Splitters) 전략

5. 임베딩(Embedding) 처리 방식

6. 추후 추가 학습 자료 업데이트 예정