# Project Context

본 프로젝트는 400~500명 규모 기업을 가정한 사내 규정집 구축 프로젝트이다.

생성된 문서는 향후 RAG(Retrieval-Augmented Generation) 시스템의 지식 베이스로 사용될 예정이다.

문서는 사람이 읽기 위한 규정집인 동시에 LLM 검색 데이터셋 역할을 수행한다.

# Primary Goal

* 규정집 작성
* RAG 검색 정확도 향상
* 조(Article) 단위 청킹
* 문체 및 용어 통일

# Important Rules

* 모든 조항은 독립적으로 이해 가능해야 한다.
* 다른 조항을 참조하더라도 조항명을 함께 기재한다.
* 모호한 표현을 사용하지 않는다.
* 규정 문체를 사용한다.
* 모든 조항은 최소 500자 이상 작성한다.

# Output Format

문서는 Markdown 형식으로 작성한다.

JSON은 생성하지 않는다.

JSON 변환은 후처리 단계에서 수행한다.
