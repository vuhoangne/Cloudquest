---
title : "DIY"

weight : 4
chapter : false
pre : " <b> 9.4 </b> "
---

{{% notice info %}}

After completing the lab, the player does **DIY**

{{% /notice %}}

1. Select **Open AWS Console**

![DIY](/images/9.-connectvpc/9.4-diy/1-diy.png)

2. In the **AWS Console** interface:

- Search for **VPC**
- Select **VPC**

![DIY](/images/9.-connectvpc/9.4-diy/2-diy.png)

3. In the **AWS Console** interface:

- Select **Your VPCs**

![DIY](/images/9.-connectvpc/9.4-diy/3-diy.png)

4. In the **EC2** interface:

- Select **Instances**

![DIY](/images/9.-connectvpc/9.4-diy/4-diy.png)

5. In the **Instances** interface:

- Select **Developer Server**
- Select **Connect**

![DIY](/images/9.-connectvpc/9.4-diy/5-diy.png)

6. In the **Connect to instance** interface:

- Select **Session Manager**
- Select **Connect**

![DIY](/images/9.-connectvpc/9.4-diy/6-diy.png)

7. In the **CLI** interface:

- Type ```172.31.0.130```

![DIY](/images/9.-connectvpc/9.4-diy/7-diy.png)

8. In the **Peering connections** interface:

- Select **Create peering connection**

![DIY](/images/9.-connectvpc/9.4-diy/8-diy.png)

9. In the **Create peering connection** interface:

- Select **Developer VPC** and review CIDR 192.168.0.0/20
- Select **Finance VPC** and review CIDR 172.31.0.0/16

![DIY](/images/9.-connectvpc/9.4-diy/9-diy.png)

10. In the **Create peering connection** interface:

- Select **Create peering connection**

![DIY](/images/9.-connectvpc/9.4-diy/10-diy.png)

11. In the **Peering connection settings** interface:

- Click **Actions**
- Click **Accept request**

![DIY](/images/9.-connectvpc/9.4-diy/11-diy.png)

12. In the **Peering connection settings** interface:

- Select **Accept request**

![DIY](/images/9.-connectvpc/9.4-diy/12-diy.png)

13. In **Route tables**:

- Select **FinancePublicSubnet1** and click **Edit routes**

![DIY](/images/9.-connectvpc/9.4-diy/13-diy.png)

14. In the **Edit routes** interface:

- Type ```192.168.0.0/20```
- Select **Peering Connections**
- Select **Developer <> Finance**
- Select **Save change**

![DIY](/images/9.-connectvpc/9.4-diy/14-diy.png)

15. Review

![DIY](/images/9.-connectvpc/9.4-diy/15-diy.png)

16. Select **DeveloperPublicSubnet1**

- Select **Routes**
- Select **Edit routes**

![DIY](/images/9.-connectvpc/9.4-diy/16-diy.png)

17. In the **VPC** interface:

- Type ```172.31.0.0/16```
- Select **Peering Connections**
- Select **Developer <> Finance**
- Select **Save change**

![DIY](/images/9.-connectvpc/9.4-diy/17-diy.png)

18. Review

![DIY](/images/9.-connectvpc/9.4-diy/18-diy.png)

19. Click on **FinanceServerSecurityGroup**

- Click **Edit Inbound Rules**

![DIY](/images/9.-connectvpc/9.4-diy/19-diy.png)

20. In the **Edit Inbound Rules** interface:

- Select **Add rule**
- Select **All ICMP - IPv4**
- Type ```192.168.0.0/16```
- Select **Save rules**

![DIY](/images/9.-connectvpc/9.4-diy/20-diy.png)

21. Click on **DeveloperServerSecurityGroup**

- Click **Edit Inbound Rules**

![DIY](/images/9.-connectvpc/9.4-diy/21-diy.png)

22. In the **Edit Inbound Rules** interface:

- Select **Add rule**
- Select **All ICMP - IPv4**
- Type ```172.31.0.0/16```
- Select **Save rules**

![DIY](/images/9.-connectvpc/9.4-diy/22-diy.png)

23. In the **EC2** interface:

- Select **Instances**
- Select **DeveloperServer**
- Select **Connect**

![DIY](/images/9.-connectvpc/9.4-diy/23-diy.png)

24. In the **Connect to instance** interface:

- Select **Session Manager**
- Select **Connect**

![DIY](/images/9.-connectvpc/9.4-diy/24-diy.png)

25. In the **CLI** interface:

- Type ```ping 172.31.0.130```
- View the result

![DIY](/images/9.-connectvpc/9.4-diy/25-diy.png)

26. In the **EC2** interface:

- Select **Instances**
- Select **DeveloperServer**
- Copy the **Instance ID**

![DIY](/images/9.-connectvpc/9.4-diy/26-diy.png)

27. In the **DIY** interface:

- Copy and paste Developer instance ID
- Copy and paste Finance instance ID
- Click **Validate**

![DIY](/images/9.-connectvpc/9.4-diy/27-diy.png)

28. In the **DIY** interface:

- A green message appears: **you did it!...** indicating completion
- Click **Exit**

![DIY](/images/9.-connectvpc/9.4-diy/28-diy.png)

29. Select **Collect**

![DIY](/images/9.-connectvpc/9.4-diy/29-diy.png)

30. Congratulations! You have completed the **Connecting VPCs** lab.

![DIY](/images/9.-connectvpc/9.4-diy/30-diy.png)

