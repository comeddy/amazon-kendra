---
description: 이 단계에서는 이 랩에서 사용한 리소스를 종료합니다.
---

# Step 7. Clean up

중요: 적극적으로 사용되지 않는 리소스를 종료하는 것이 비용을 절감하는 가장 좋은 방법입니다. 리소스를 종료하지 않으면 계정에 요금이 부과됩니다.



**Delete the index:**

1. Open the [Amazon Kendra Console.](https://console.aws.amazon.com/kendra/)
2. In the left navigation pane, choose **Indexes**.
3. Choose the **hands-on-tutorial** index and then choose **Actions**, **Delete**.
4. Type **Delete** to confirm.

**Delete the IAM role and policy:**

1. Open the [IAM Console.](https://console.aws.amazon.com/iam)
2. In the left navigation pane, choose **Roles**.
3. In the search box, type _hands-on-tutorial._
4. Select the **AmazonKendra-us-east-1-hands-on-tutorial** role and then choose **Delete** **role**.
5. Choose **Yes, delete**
6. In the left navigation pane, choose **Policies**.
7. In the search box, type _hands-on-tutorial_.
8. Select the **AmazonKendra-us-east-1-hands-on-tutorial** policy and then choose **Policy actions**, **Delete**.
9. Choose **Delete**.

![](<.gitbook/assets/스크린샷 2022-02-07 오전 3.35.48.png>)
