# Ailys Frontier Portfolio | 김진원 (KIM JIN WON)

**아일리스프런티어(주) (Ailys Frontier Corp.), 선행연구팀 매니저**
2021.03 ~ 2023.07 (2년 5개월)

금융·공공 분야 자연어처리 기업 아일리스프런티어의 선행연구팀에서 NLP 모델 개발, 정부과제 수행, AI 신사업 기획까지 AI 프로젝트 전 주기를 맡았습니다. KAIST 전산학부와의 공동연구에도 참여했습니다. 재직 중 성과를 프로젝트, 특허, 학술 논문, 공개 코드로 모아둔 저장소입니다. 이력서와 경력기술서에서 근거 자료로 참조하기 위해 만들었습니다.

> 회사 내부 문서와 고객사 데이터는 넣지 않았습니다. 여기 있는 자료는 학회와 특허청을 통해 이미 공개된 것입니다.

## At a Glance

| 구분 | 성과 |
|---|---|
| 특허 | 공동 발명 7건 (등록 3건, 공개 4건), 출원인 아일리스프런티어 |
| 학술 논문 | 공저 5편 (HCLT 2021·2022, KSC 2021, IEEE BigComp 2022 워크숍, KSII 2022 춘계) |
| 현장 적용 | 광주 119 긴급신고 접수 지원 실시간 텍스트 분석 |
| 모델 | 119 도메인 NER, 44개 감정 멀티라벨 감성분석, ELECTRA + CRF 개체명 인식, 금융 문장유사도(STS-B), TabNet·Prophet 현금흐름 예측 |
| 사업 | AI바우처 사업 수행 (사업계획서, 제3기관 인증 테스트, 최종 발표), AI 신사업 제안서 작성 |

## Projects

### 1. 동인 분석 기반 실시간 현금흐름 모니터링 AI 서비스 (2021.03 ~ 2021.08)

기업의 통장 적요와 카드 매출 같은 실제 거래 내역을 분류하고, 현금 흐름의 동인(Driver)을 분석해 기업별 보유 현금을 예측하는 서비스입니다.

- 시계열 성질의 테이블형 데이터 분류, TabNet·Prophet 기반 시계열 예측 모델링
- 통장 적요·카드 매출 분류 정확도 90% 이상, 기업별 보유 현금 예측 오류율 0.0865 (KSC 2021 논문 기준)
- 후속 연구로 거시경제지표와 재무제표를 결합한 중소기업 현금흐름 예측 모형을 KSII 2022 춘계학술발표대회에서 발표
- 관련 특허: 동인 분석 기반 실시간 현금흐름 예측 모니터링 서비스 시스템, 문자 인식 기반 통장 거래내역 분석 시스템

### 2. 119 긴급신고 접수 지원과 챗봇 NLU 엔진 (2021.09 ~ 2022.10)

119 종합상황실로 들어오는 신고 전화를 음성 인식 결과로 실시간 분석해, 신고 접수와 출동 지령서 작성을 돕는 시스템입니다.

- 119 도메인 맞춤형 개체명(NER) 태그 체계를 설계하고, 전사 데이터를 태깅해 학습셋 구축
- 개체명 인식 모델 개발·파인튜닝, 대화 상태 추적과 요약 기반 신고 접수 지원
- 광주 119 현장 신고 접수 업무에 적용, HCLT 2021 논문 발표
- 챗봇 NLU 엔진: 일반화된 개체명 사전 구축, 데이터 수집·태깅 툴 연계, ELECTRA + CRF 개체명 인식 모델 미세조정과 성능 비교

### 3. 심리상담 특화 감성분석 AI 챗봇, AI바우처 사업 (2022.01 ~ 2022.10)

심리상담 도메인에 특화한 언어모델로 대화 속 감정을 분석하는 챗봇 솔루션입니다. 정부 AI바우처 지원사업으로 수행했습니다.

- 사업계획서 작성, ML 모델링, 제3기관 인증 테스트, 최종 발표까지 전 과정 주도
- 44개 감정 멀티라벨(Multi-Label) 감성분석 모델 개발
- GCP TPU 기반 도메인 언어모델 추가 학습

### 4. 금융 AI: 질의 의도 분류, 문장 유사도, 공시 문서 검색

- 투자정보 서비스용 금융 텍스트 문장유사도(STS-B) 모델 학습과 군집화
- 금융 용어 언어모델과 외부 데이터베이스를 활용한 금융 질의 의도 분류·답변 검색 (특허 2건 등록)
- 기계독해 기술로 기업 공시 전자문서를 추출·변환하고 정보를 검색하는 방법 (특허 등록)

### 5. 통계 분류 자동화 공동연구 (KAIST·통계청)

산업 분류처럼 국가 통계와 기업 분석의 기반이 되는 분류 작업을 기계학습으로 자동화하는 연구에 참여했습니다.

- 한국표준산업분류(KSIC) 기반 산업군 앙상블 분류 모델 (HCLT 2022)
- 대화형 통계 분류 서비스를 위한 텍스트 분석 프레임워크 (IEEE BigComp 2022, IWDS 2022 워크숍)

### 6. LLM 선행 연구: ChatGPT, LangChain (2023.02 ~ 2023.05)

- ChatGPT 연구와 사내 세미나 (2023.02 ~ 2023.03): GPT-4·ChatGPT 분석과 트렌드 조사로 조직의 LLM 활용 역량을 넓힘
- ChatGPT + LangChain 활용 특허분석·데이터 관리 연구 (2023.04 ~ 2023.05): 특허 요약·청구항 요약 자동화, 핵심 기술 도출, 특허 데이터 관리 툴 가능성 검토
- 이 연구가 이후 포스코퓨처엠 IP전략센터에서 LLM·RAG·Agent 시스템을 단독 구축하게 된 계기가 되었습니다. ([posco-future-m-portfolio](https://github.com/jw0831/posco-future-m-portfolio))

### 7. AI 신사업 기획

- XAI(설명가능 AI) 기술 연구, 솔루션 제안서와 개념도 작성
- 보험설계사 영업 지원용 추천시스템 기반 하이브리드 세일즈 플랫폼 제안서와 개념도 작성

## Patents

출원인은 모두 아일리스프런티어 주식회사이고, 김진원은 공동 발명자로 참여했습니다.

| 상태 | 번호 | 발명의 명칭 | 출원일 |
|---|---|---|---|
| 등록 (2025.08.26) | [KR 10-2850753](https://patents.google.com/patent/KR102850753B1/ko) | 금융 용어 언어 모델에 기반하여 금융 도메인의 다양한 질의에 대한 의도를 분류하고 및 답변을 검색하는 방법 및 시스템 | 2022.02.17 |
| 등록 (2025.11.24) | [KR 10-2887573](https://patents.google.com/patent/KR102887573B1/ko) | 외부 데이터베이스를 활용하여 금융 도메인의 다양한 질의에 대한 의도를 분류하고 및 답변을 검색하는 방법 및 시스템 | 2022.02.17 |
| 등록 (2026.01.08) | [KR 10-2909241](https://patents.google.com/patent/KR102909241B1/ko) | 기계독해 기술을 활용한 기업 공시 전자문서 추출-변환 및 정보 검색 방법과 이를 구현하는 시스템 | 2022.11.23 |
| 공개 (2023.11.30) | [KR 10-2023-0163267](https://patents.google.com/patent/KR20230163267A/ko) | 문자 인식 기반 통장 거래내역 분석 시스템 및 분석 방법 | 2022.09.05 |
| 공개 (2023.11.30) | [KR 10-2023-0163268](https://patents.google.com/patent/KR20230163268A/ko) | 동인 분석 기반 실시간 현금흐름 예측 모니터링 서비스 시스템 및 모니터링 방법 | 2022.09.14 |
| 공개 (2024.05.07) | [KR 10-2024-0057666](https://patents.google.com/patent/KR20240057666A/ko) | 문서 내의 범주형 문장을 추출 및 요약하는 방법 및 시스템 | 2022.10.25 |
| 공개 (2024.06.14) | [KR 10-2024-0085111](https://patents.google.com/patent/KR20240085111A/ko) | 직업의 위험등급을 분류하는 방법 및 시스템 | 2023.03.21 |

괄호 안 날짜는 등록공고일 또는 공개일이며, 상태는 2026.10.31 Google Patents 기준입니다. 공식 법적 상태는 [KIPRIS](https://www.kipris.or.kr)에서 확인할 수 있습니다.

## Publications

| 연도 | 학회 | 제목 | 저자 | 자료 |
|---|---|---|---|---|
| 2022 | 제34회 한글 및 한국어 정보처리 학술대회 (HCLT 2022) | 기업 비지니스 분석을 위한 한국표준산업코드 앙상블 분류 | 오교중, 최호진, **김진원**, 차원석, 김일구 | [PDF](papers/HCLT2022_KSIC-Ensemble-Classification.pdf) · [KoreaScience](https://koreascience.kr/article/CFKO202226455347842.page) |
| 2022 | 2022년도 한국인터넷정보학회 춘계학술발표대회 (KSII, 논문집 제23권 1호) | 거시경제지표와 재무제표 데이터를 결합한 시계열 모형 기반 중소규모 기업 현금흐름 예측 | 오교중, **김진원**, 김일훈, 안형준, 김성환 | [발표자료 (PPTX)](presentations/KSII2022-Spring_Corporate-Cash-Flow-Forecasting.pptx) |
| 2022 | IEEE BigComp 2022, The 5th International Workshop on Dialog Systems (IWDS 2022) | The Text Analysis Framework for Interactive Statistical Classification Service (pp. 404-407) | Kyo-Joong Oh, Ho-Jin Choi, **Jinwon Kim**, Wonsoek Cha, Kyungmin Lim | [DOI](https://doi.org/10.1109/BigComp54360.2022.00092) |
| 2021 | 한국소프트웨어종합학술대회 (KSC 2021) | 산업 리포트 자동화를 위한 기업 분석 시스템 | 김일훈, 오교중, **김진원**, 김성환 | [DBpia](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE11035808) |
| 2021 | 제33회 한글 및 한국어 정보처리 학술대회 (HCLT 2021) | 긴급 신고 접수 지원을 위한 대화 상태 추적 및 요약 기반 실시간 텍스트 분석 | 오교중, **김진원**, 김일훈, 임채균, 최호진 | [PDF](papers/HCLT2021_Emergency-Call-Text-Analysis.pdf) · [KoreaScience](https://www.koreascience.kr/article/CFKO202130060858861.page) |

## Public Code (재직 기간)

| Repository | 내용 | 관련 프로젝트 |
|---|---|---|
| [NER](https://github.com/jw0831/NER) | 개체명 인식 개념, 일반화 개체명 사전, 테스트 정리 | 2. 119·챗봇 NLU |
| [KOTE_sentiment_multi_label](https://github.com/jw0831/KOTE_sentiment_multi_label) | KOTE 데이터셋 멀티라벨 감성분류 노트북 | 3. 감성분석 챗봇 |
| [web_scraping](https://github.com/jw0831/web_scraping) | 뉴스·커뮤니티 텍스트 수집 스니펫 | 데이터 수집 |
| [vanilla_chain_chatgpt](https://github.com/jw0831/vanilla_chain_chatgpt) | ChatGPT·LangChain 체인 실험 코드 | 6. LLM 선행 연구 |

## Related

- 현재 회사: [posco-future-m-portfolio](https://github.com/jw0831/posco-future-m-portfolio)
- 학부: [academic-portfolio](https://github.com/jw0831/academic-portfolio)
- 교육과정: [Multicampus](https://github.com/jw0831/Multicampus) (딥러닝 기반 AI 엔지니어링, 2020)

## Contact

- GitHub: [jw0831](https://github.com/jw0831)
- LinkedIn: [jinwon0831kim](https://www.linkedin.com/in/jinwon0831kim/)
