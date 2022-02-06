# Step 3. Update the IAM role

인덱스, 데이터 소스 또는 FAQ를 만들 때 Amazon Kendra는 Amazon Kendra 리소스를 만드는 데 필요한 AWS 리소스에 액세스해야 합니다. 인덱스를 만드는 동안 IAM 역할을 업데이트하여 Amazon S3에서 읽을 수 있도록 할 수 있습니다. 프로덕션 환경에서 이 단계는 특정 버킷이나 파일/객체만 읽을 수 있도록 액세스를 잠글 수 있는 단계입니다.

다음 단계를 완료하여 IAM 역할을 업데이트하여 Amazon S3 액세스를 허용합니다.

참고: 자세한 내용은 Amazon Kendra 설명서에서 [Amazon Kendra에 대한 IAM 액세스 역할](https://docs.aws.amazon.com/kendra/latest/dg/iam-roles.html)을 참조하십시오.

a. IAM 콘솔을 열고 왼쪽 탐색 창에서 Roles(역할)을 선택합니다. 검색 상자에 Hands-on-tutorial을 입력합니다. AmazonKendra-us-east-1-hands-on-tutorial 역할을 선택하고 선택합니다.

![](<.gitbook/assets/image (9).png>)

b. Summary(요약) 페이지에서 Attach policies(정책 첨부)를 선택합니다.

![](<.gitbook/assets/image (30).png>)

c. 사용 권한 연결(Attach permissions) 페이지의 검색 상자에 S3을 입력하고 AmazonS3ReadOnlyAccess 정책을 선택합니다. 정책 연결(Attach policy)을 선택합니다.

![](<.gitbook/assets/image (22).png>)

요약 페이지에는 IAM 역할에 첨부된 두 가지 정책이 표시됩니다.

![](<.gitbook/assets/image (26).png>)

d. Amazon Kendra 콘솔로 돌아가서 다음 단계를 계속하기 전에 2단계의 인덱스 상태가 생성에서 활성으로 변경될 때까지 기다립니다.

![](<.gitbook/assets/image (1).png>)
