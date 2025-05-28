# 🧐 Langchain 학습 노트 및 예제 코드 🚀

이 저장소는 **Langchain 프레임워크**의 핵심 기능과 사용법을 학습하고 실험하기 위한 **Jupyter Notebook 예제 모음**입니다.  
핵심 내용을 간결하게 정리하여, 이동 중에도 빠르게 학습할 수 있도록 구성했습니다.

그리고 **LLM 기반 신약약 논문/특허 검색 및 요약 도구**를 위한 프로젝트를 수행 (~ing)

---

## 📂 디렉터리 구성

모든 노트북은 `src/notebooks/` 디렉터리에 정렬되어 있으며, 각 파일은 다음과 같은 주제를 담당합니다:

| 파일명                                         | 주제 설명                                                      |
| ------------------------------------------- | ---------------------------------------------------------- |
| `01.Overall_Components.ipynb`               | LangChain의 한신 컨트리버트 개요 및 기본 사용법 소개 (LLM, Prompt, Chain 등). |
| `02.LCEL.ipynb`                             | LCEL (LangChain Expression Language)를 사용한 체인 구성 실습.        |
| `03.Processing_data_by_document_type.ipynb` | 다양한 문서 형식(PDF, TXT 등)의 데이터 로드하기 및 전처리 방법.                  |
| `04.Text_Segmentation.ipynb`                | 텍스트 분할 전략 및 LangChain 내 Splitter 사용법.                      |
| `05.embedding.ipynb`                        | 임베딩 모델을 이용한 텍스트 벡터화 및 활용 예시.                               |
| `06.Building_a_Multilingual_RAG.ipynb`      | 다국어 RAG(Retrieval-Augmented Generation) 시스템 구축 실습.         |
| `07.vector_store.ipynb`                     | Vector Store 구성 및 검색을 위한 벡터 삽입, 쿼리 실습.                    |
| `08.RAG_Retriever.ipynb`                    | RAG 구조에서 Retriever 구성 및 세부 튜닝.                             |
| `09.retriever_performance_eval.ipynb`       | Retriever의 검색 성능 평가 및 비교 실습.                               |
| `10.Advanced_Retrieval.ipynb`               | 고급 검색 전략(MMR, Hybrid Retrieval 등) 적용 및 배열.                 |

---

## 🧪 주요 학습 키워드

* LangChain Core: LLM, PromptTemplate, Chains
* LangChain Expression Language (LCEL)
* Document Loaders & Text Splitters
* Embedding & Vector Store
* Retrieval-Augmented Generation (RAG)
* 성능 평가 및 고급 검색 전략

---

## 📚 참고 리부

* [LangChain 공식 문서](https://docs.langchain.com/)
* [LangChain GitHub](https://github.com/langchain-ai/langchain)
* [OpenAI API](https://platform.openai.com/docs/)

---