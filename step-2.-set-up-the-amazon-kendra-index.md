---
description: >-
  다음 단계를 완료하여 Amazon Kendra 색인을 설정합니다. 인덱스에는 데이터 원본에서 인덱싱된 문서, 인덱스에 직접 추가되는 문서 및
  FAQ가 포함될 수 있습니다. 색인이 활성화되면 작업을 사용하거나 지원되는 데이터 원본 중 하나를 사용하여 문서를 색인화할 수 있습니다.
---

# Step 2. Set up the Amazon Kendra index

참고: 자세한 내용은 Amazon Kendra 문서에서 [색인 만들기(Creating an index)](https://docs.aws.amazon.com/kendra/latest/dg/create-index.html)를 참조하십시오.



a. Amazon Kendra 콘솔에 로그인하고 오른쪽 상단 모서리에서 AWS 영역이 N. Virginia로 설정되었는지 확인합니다. 그런 다음 색인 만들기를 선택합니다.

![](<.gitbook/assets/image (12).png>)

b. 인덱스 세부 정보(Index details) 페이지에서 다음 필드를 채우고 다음(Next)을 선택합니다.

* **Index name:** hands-on-tutorial
* **Description:** Amazon Kendra tutorial.
* **IAM role:** Create a new role
* **Role name:** AmazonKendra-us-east-1-hands-on-tutorial

![](<.gitbook/assets/image (32).png>)

c. Provisioning editions 페이지에서 Developer edition을 선택한 다음 Create를 선택합니다.

![](<.gitbook/assets/image (25).png>)

인덱스 생성 프로세스는 평균 15분이 걸리지만 최대 30분이 소요될 수 있습니다.
