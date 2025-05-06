---
title : "DIY"

weight : 4
chapter : false
pre : " <b>7.4 </b> "
---

{{% notice info %}}

After completing the lab, the player does **DIY**

{{% /notice %}}

1. Select **DIY**

![DIY](/images/7-vpc/7.4-diy/1-diy.png?width=90pc)

2. The **DIY** interface appears including:
- Lab Files
- DIY Activity
- Networking Concepts
- VALIDATION FORM
- Read **SOLUTION VALIDATION METHOD**

![DIY](/images/7-vpc/7.4-diy/2-diy.png?width=90pc)

3. In the **AWS Console**, search for and select **EC2**, click on **Instance**
- Select **DB Server**

![DIY](/images/7-vpc/7.4-diy/3-diy.png?width=90pc)

4. In **Instances**
- Select **DB Server**
- Select **Security**
- Click **Security groups**

![DIY](/images/7-vpc/7.4-diy/4-diy.png?width=90pc)

5. In the **Security Groups** interface
- Select **Edit inbound rules**

![DIY](/images/7-vpc/7.4-diy/5-diy.png?width=90pc)

6. In the **Edit inbound rules** interface
- Select **Add rule**
- **Type**: choose **MYSQL/Aurora**
- **Source**: choose **Custom**
- **DbServerSecurityGroup**
- Then click **Save rules**

![DIY](/images/7-vpc/7.4-diy/6-diy.png?width=90pc)

7. Interface after creating **DbServerSecurityGroup**
- Copy the name

![DIY](/images/7-vpc/7.4-diy/7-diy.png?width=90pc)

8. In the **DIY** interface
- Paste **Database security group name**
- Click **Validate**
- A green message **you did it!...** will appear, indicating completion

![DIY](/images/7-vpc/7.4-diy/8-diy.png?width=90pc)

9. In **Assignments**, select **Collect**

![DIY](/images/7-vpc/7.4-diy/9-diy.png?width=90pc)

10. Click **Collect**

![DIY](/images/7-vpc/7.4-diy/10-diy.png?width=90pc)

11. **CONGRATULATIONS**
- Congratulations, you have completed the **Networking Concepts** lab

![DIY](/images/7-vpc/7.4-diy/11-diy.png?width=90pc)

