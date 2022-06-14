# Step 4. Configure an S3 connector to the data source

데이터 원본은 인덱싱을 위해 문서를 저장하는 Amazon S3(Amazon Simple Storage Service) 버킷과 같은 위치입니다. 원본 리포지토리의 새 문서, 업데이트된 문서 또는 삭제된 문서가 검색에 포함되도록 데이터 소스를 Amazon Kendra 인덱스와 자동으로 동기화할 수 있습니다. 커넥터는 문서 액세스 권한을 유지하며 색인을 데이터 원본과 자동으로 동기화하도록 예약할 수 있으므로 항상 최신 콘텐츠를 안전하게 검색할 수 있습니다.

Amazon.com 도움말 문서 샘플을 데이터 소스로 포함하는 Amazon S3 버킷에 커넥터를 추가합니다.

참고: 자세한 내용은 Amazon Kendra 설명서의 데이터 소스를 참조하십시오.

a. **Indexes** 리스트에서, **hands-on-tutorial 를 선택**.

![](<.gitbook/assets/image (20).png>)

b. 왼쪽 탐색 창의 데이터 관리에서 데이터 소스를 선택합니다. 커넥터 유형의 Amazon S3 상자에서 커넥터 추가를 선택합니다.

![](<.gitbook/assets/image (19).png>)

c. 특성 정의 페이지에서 데이터 소스 이름에 Amazon-com-help-pages를 입력하고 Next를 선택합니다.

![](<.gitbook/assets/image (29).png>)

d. 설정 구성 페이지의 데이터 원본 위치에 s3://serverless-analytics를 입력합니다. IAM 역할의 경우 앞에서 만든 AmazonKendra-us-east-1-hands-on-tutorial 역할을 선택합니다. 그런 다음 추가 구성을 확장하십시오.

![](<.gitbook/assets/image (3).png>)

e. 추가 구성 섹션에서 패턴 포함에 amazon-help/documents/를 입력하고 Add를 선택합니다.

![](<.gitbook/assets/image (15).png>)

f. 동기화 실행 일정 설정 섹션의 Frequency(빈도)에 대해 Run on demand(요청 시 실행)을 선택한 후 Next(다음)을 선택합니다.

![](<.gitbook/assets/image (21).png>)

g. 구성 세부 정보를 검토한 다음 **Create**(생성)을 선택합니다.

![](<.gitbook/assets/image (27).png>)

h. **Data source details(데이터 원본 세부 정보)** 페이지에서 **Sync now(지금 동기화)**를 선택합니다. S3 커넥터는 할당된 IAM 역할을 통해 액세스할 수 있는 권한이 있는 콘텐츠를 크롤링하고 색인화하기 시작합니다.

![](<.gitbook/assets/image (31).png>)

동기화가 완료되면 데이터 원본의 마지막 동기화 상태가 성공으로 변경됩니다. 왼쪽메뉴에서 Data Sources를 선택합니다.

![](<.gitbook/assets/image (5).png>)
