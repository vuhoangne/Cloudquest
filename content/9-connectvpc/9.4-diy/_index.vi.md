---
title : "DIY"

weight : 4
chapter : false
pre : " <b> 9.4 </b> "
---

{{% notice info %}}

Sau khi hoàn thành bài lab, người chơi thực hiện **DIY**

{{% /notice %}}


1. Chọn **Open AWS Console**

![DIY](/images/9.-connectvpc/9.4-diy/1-diy.png?width=90pc)

2. Trong giao diện **AWS Console**

- Tìm **VPC**
- Chọn **VPC**

![DIY](/images/9.-connectvpc/9.4-diy/2-diy.png?width=90pc)

3. Trong giao diện **AWS Console**

- Chọn **Your VPCs**

![DIY](/images/9.-connectvpc/9.4-diy/3-diy.png?width=90pc)

4. Trong giao diện **EC2**

- Chọn **Instances**

![DIY](/images/9.-connectvpc/9.4-diy/4-diy.png?width=90pc)

5. Trong giao diện **Instances**

- Chọn **Developer Server**
- Chọn **Connect**

![DIY](/images/9.-connectvpc/9.4-diy/5-diy.png?width=90pc)

6. Trong giao diện **Connect to instance**

- Chọn **Session Manager**
- Chọn **Connect**

![DIY](/images/9.-connectvpc/9.4-diy/6-diy.png?width=90pc)

7. Trong giao diện **CLI**

- Gõ ```172.31.0.130```

![DIY](/images/9.-connectvpc/9.4-diy/7-diy.png?width=90pc)

8. Trong giao diện **Peering connections**

- Chọn **Create peering connection**

![DIY](/images/9.-connectvpc/9.4-diy/8-diy.png?width=90pc)

9. Trong giao diện **Create peering connection**

- Chọn **Developer VPC** review CIDR 192.168.0.0/20
- Chọn **Finance VPC** review CIDR 172.31.0.0/16

![DIY](/images/9.-connectvpc/9.4-diy/9-diy.png?width=90pc)

10. Trong giao diện **Create peering connection**

- Chọn **Create peering connection**

![DIY](/images/9.-connectvpc/9.4-diy/10-diy.png?width=90pc)

11. Trong giao diện **Peering connection settings**

- Click **Actions**
- Click **Accept request**

![DIY](/images/9.-connectvpc/9.4-diy/11-diy.png?width=90pc)

12. Trong giao diện **Peering connection settings**

- Chọn **Accept request**

![DIY](/images/9.-connectvpc/9.4-diy/12-diy.png?width=90pc)

13. Trong **Route tables**

- Chọn **FinancePublicSubnet1** và click **Edit routes**

![DIY](/images/9.-connectvpc/9.4-diy/13-diy.png?width=90pc)

14. Trong giao diện **Edit routes**

- Gõ ```192.168.0.0/20```
- Chọn **Peering Connections**
- Chọn **Developer <> Finance**
- Chọn **Save change**

![DIY](/images/9.-connectvpc/9.4-diy/14-diy.png?width=90pc)

15. Review

![DIY](/images/9.-connectvpc/9.4-diy/15-diy.png?width=90pc)

16. Chọn DeveloperPublicSubnet1 

- Chọn **Routes** 
- Chọn **Edit routes**

![DIY](/images/9.-connectvpc/9.4-diy/16-diy.png?width=90pc)

17. Trong giao diện **VPC**

- Gõ ```172.31.0.0/16```
- Chọn **Peering Connections**
- Chọn **Developer <> Finance**
- Chọn **Save change**

![DIY](/images/9.-connectvpc/9.4-diy/17-diy.png?width=90pc)

18. Review

![DIY](/images/9.-connectvpc/9.4-diy/18-diy.png?width=90pc)

19. Click vào **FinanceServerSecurityGroup**

- Click **Edit Inbound Rules**

![DIY](/images/9.-connectvpc/9.4-diy/19-diy.png?width=90pc)

20. Trong giao diện **Edit Inbound Rules**

- Chọn **Add rule**
- Chọn **All ICMP - IPv4**
- Gõ ```192.168.0.0/16```
- Chọn **Save rules**

![DIY](/images/9.-connectvpc/9.4-diy/20-diy.png?width=90pc)

21. Click vào **DeveloperServerSecurityGroup**

- Click **Edit Inbound Rules**

![DIY](/images/9.-connectvpc/9.4-diy/21-diy.png?width=90pc)

22. Trong giao diện **Edit Inbound Rules**

- Chọn **Add rule**
- Chọn **All ICMP - IPv4**
- Gõ ```172.31.0.0/16```
- Chọn **Save rules**

![DIY](/images/9.-connectvpc/9.4-diy/22-diy.png?width=90pc)

23. Trong giao diện **EC2**

- Chọn **Instances**
- Chọn **DeveloperServer**
- Chọn **Connect**

![DIY](/images/9.-connectvpc/9.4-diy/23-diy.png?width=90pc)

24. Trong giao diện **Connect to instance**

- Chọn **Session Manager**
- Chọn **Connect**

![DIY](/images/9.-connectvpc/9.4-diy/24-diy.png?width=90pc)

25. Trong giao diện **CLI**

- Nhập ```ping 172.31.0.130```
- Xem kết quả

![DIY](/images/9.-connectvpc/9.4-diy/25-diy.png?width=90pc)

26. Trong giao diện **EC2**

- Chọn **Instances**
- Chọn **DeveloperServer**
- Chọn copy **Instance ID**

![DIY](/images/9.-connectvpc/9.4-diy/26-diy.png?width=90pc)

27. Trong giao diện **DIY**

- Copy và dán Developer instance ID
- Copy và dán Finance instance ID
- Click **Validate**

![DIY](/images/9.-connectvpc/9.4-diy/27-diy.png?width=90pc)

28. Trong giao diện **DIY**

- Xuất hiện dòng chữ xanh lá cây : **you did it!...** là đã hoàn thành
- Click **Exit**

![DIY](/images/9.-connectvpc/9.4-diy/28-diy.png?width=90pc)

29. Chọn **Collect**

![DIY](/images/9.-connectvpc/9.4-diy/29-diy.png?width=90pc)

30. Chúc mừng người chơi hoàn thành bài lab **Connecting VPCs**

![DIY](/images/9.-connectvpc/9.4-diy/30-diy.png?width=90pc)
