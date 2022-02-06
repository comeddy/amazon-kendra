# Step 5. Add an FAQ

이 단계에서는 자주 묻는 질문에 대한 Kendra의 직접적인 답변을 제공하는 FAQ를 업로드합니다. 아마존 켄드라가 검색 질의에 가장 근접한 질문을 찾아 해당 답변을 반환합니다.&#x20;

샘플 _Amazon-help-faq_를 사용하여 FAQ를 추가하려면 다음 단계를 완료하십시오.

**Note:** For more information, see [Amazon Kendra Features](https://aws.amazon.com/kendra/features/).



a. Amazon Kendra 콘솔의 왼쪽 탐색 창에서 FAQ를 선택한 다음 FAQ 추가를 선택합니다.

![](<.gitbook/assets/image (2).png>)

b. FAQ 추가 페이지에서 다음 필드를 채우고 Add(추가)를 선택합니다.

* **FAQ name:** amazon-help-faqs
* **S3:** s3://serverless-analytics/amazon-help/faqs/kendrapost.csv
* **IAM role:** AmazonKendra-us-east-1-hands-on-tutorial

![](<.gitbook/assets/image (14).png>)

새 FAQ와 _'Amazon-help-faqs'_라는 메시지가 표시됩니다.

![](<.gitbook/assets/image (4).png>)
