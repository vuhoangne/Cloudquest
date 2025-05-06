---
title : "DIY"

weight : 4
chapter : false
pre : " <b> 5.4 </b> "
---

{{% notice info %}}

After completing the lab, the player does **DIY**

{{% /notice %}}

1. Select **DIY** to proceed

![DIY](/images/5-amazonec2/5.4-diy/1-diy.png?width=90pc)

2. In the **DIY** interface

- Read **DIY ACTIVITIES**
- Read **SOLUTION VALIDATION METHOD**
- Click **Open AWS Console**

![DIY](/images/5-amazonec2/5.4-diy/2-diy.png?width=90pc)

3. In **EC2**, select **Launch instance**

- Enter ```webserver02```
- Choose Amazon Linux 2023 AMI
- Enter ```Enable```
- Enter ```LabHN```
- Enter ```HTTP Security```
- Type: HTTP, Source type: Anywhere

![DIY](/images/5-amazonec2/5.4-diy/3-diy.png?width=90pc)

4. In the **Launch an instance** interface

- Select VPC (cloud-first-steps/LabVpc)
- Select subnet with AZ: us-east-1b

![DIY](/images/5-amazonec2/5.4-diy/4-diy.png?width=90pc)

5. In the **Launch an instance** interface

- Review user-data.txt
- Click **Launch instance**

![DIY](/images/5-amazonec2/5.4-diy/5-diy.png?width=90pc)

6. Review

![DIY](/images/5-amazonec2/5.4-diy/6-diy.png?width=90pc)

7. Click **View all instances**

![DIY](/images/5-amazonec2/5.4-diy/7-diy.png?width=90pc)

8. In **Advanced Details**

- Select **Webserver02**
- Copy the Instance ID

![DIY](/images/5-amazonec2/5.4-diy/8-diy.png?width=90pc)

9. In the **DIY** interface

- Enter instance ID 1
- Enter instance ID 2
- Click **Validate**

![DIY](/images/5-amazonec2/5.4-diy/9-diy.png?width=90pc)

10. In the **DIY** interface

- A green message appears: "you did it..." — this means the task is completed

![DIY](/images/5-amazonec2/5.4-diy/10-diy.png?width=90pc)

11. In the city interface

- Congratulations! You have completed **Cloud First Steps**

![DIY](/images/5-amazonec2/5.4-diy/12-diy.png?width=90pc)
