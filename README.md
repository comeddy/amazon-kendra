---
description: 이 자습서에서는 Amazon Kendra를 사용하여 새 인덱스를 생성하고 결과에 대한 인덱스를 쿼리하는 방법을 배웁니다.
coverY: 0
---

# Create and query index with Amazon Kendra

Amazon Kendra는 기계 학습을 기반으로 하는 매우 정확하고 사용하기 쉬운 엔터프라이즈 검색 서비스입니다. Amazon Kendra는 웹 사이트와 애플리케이션에 강력한 검색 기능을 제공하므로 최종 사용자는 회사 전체에 퍼져 있는 방대한 콘텐츠 내에서 필요한 정보를 빠르게 찾을 수 있습니다.

Amazon Kendra를 사용하면 간단한 키워드 외에도 자연어 질문을 할 수 있으며 정확한 답변인지, FAQ 응답인지, 전체 문서인지 등 원하는 답변을 얻을 수 있습니다. 또한 Amazon Kendra를 사용하면 Amazon S3, Amazon RDS, Microsoft SharePoint Online, ServiceNow 및 Salesforce의 콘텐츠를 중앙 집중화된 위치에 쉽게 추가할 수 있습니다.

이 튜토리얼에서는 다음을 학습합니다:

1. Set up a new index in Amazon Kendra
2. Set up an Amazon S3 bucket as a data source and ingest data using an Amazon Kendra connector
3. Set up an FAQ data source
4. Query the index using the Console search

이 튜토리얼에서는 Amazon Kendra 데이터 원본 커넥터에 의해 검색된 HTML 형식의 Amazon.com 도움말 문서를 사용합니다.
