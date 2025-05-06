---
title : "DIY"

weight : 4
chapter : false
pre : " <b> 7.4 </b> "
---

{{% notice info %}}

Sau khi hoàn thành bài lab, người chơi thực hiện **DIY**

{{% /notice %}}

1. Chọn **DIY**

![DIY](/images/7-vpc/7.4-diy/1-diy.png?width=90pc)

2. Giao diện **DIY** xuất hiện gồm:
- Lab Files
- DIY Activity
- Networking Concepts
- VALIDATION FORM
- Đọc **SOLUTION VALIDATION METHOD**

![DIY](/images/7-vpc/7.4-diy/2-diy.png?width=90pc)

3. Trong trang **AWS Console**, tìm và chọn **EC2** , click vào **Instance**
- Chọn **DB Server**

![DIY](/images/7-vpc/7.4-diy/3-diy.png?width=90pc)

4. Trong **Instances**

- Chọn **DB Server**
- Chọn **Security**
- Click **Security groups**

![DIY](/images/7-vpc/7.4-diy/4-diy.png?width=90pc)

5. Trong giao diện **Security Groups**

- Chọn **Edit inbound rules**

![DIY](/images/7-vpc/7.4-diy/5-diy.png?width=90pc)

6. Trong giao diện **Edit inbound rules**

- Chọn **Add rule**
- **Type**: chọn **MYSQL/Aurora**
- **Source**: chọn **Custom**
- **DbServerSecurityGroup**
- Sau đó chọn **Save rules**

![DIY](/images/7-vpc/7.4-diy/6-diy.png?width=90pc)

7. Giao diện sau khi tạo **DbServerSecurityGroup**

- Copy name 

![DIY](/images/7-vpc/7.4-diy/7-diy.png?width=90pc)

8. Trong giao diện **DIY**

- Dán **Database security group name**
- chọn **Validate**
- Xuất hiện dòng chữ màu xanh lá **you did it!...** là hoàn thành

![DIY](/images/7-vpc/7.4-diy/8-diy.png?width=90pc)

9. Trong **Assignments** , chọn **Collect**

![DIY](/images/7-vpc/7.4-diy/9-diy.png?width=90pc)

10. Chọn **Collect** 

![DIY](/images/7-vpc/7.4-diy/10-diy.png?width=90pc)

11. CONGRATULATIONS 

- Chúc mừng người chơi đã hoàn thành lab **Networking Concepts**

![DIY](/images/7-vpc/7.4-diy/11-diy.png?width=90pc)


