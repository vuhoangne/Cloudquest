---
title : "DIY"

weight : 4
chapter : false
pre : " <b> 12.4 </b> "
---

{{% notice info %}}

Sau khi hoàn thành bài lab, người chơi thực hiện **DIY**

{{% /notice %}}

1. Trong giao diện **AWS Console**

- Tìm **EFS**
- Chọn **EFS**
- Chọn **PetModels-EFS-1**

![DIY](/images/12-filesystems/12.4-diy/1-diy.png?width=90pc)

2. Trong giao diện **EFS**

- Chọn **Network**
- Chọn **Manage**

![DIY](/images/12-filesystems/12.4-diy/2-diy.png?width=90pc)

3. Trong giao diện **Network**

- Chọn **Add mount target**

![DIY](/images/12-filesystems/12.4-diy/3-diy.png?width=90pc)

4. Trong giao diện **Create security group**

- Chọn **us-east-1c**
- Chọn **Security groups** : **PetModels-EFS-1-SG**

![DIY](/images/12-filesystems/12.4-diy/4-diy.png?width=90pc)

5. Review

![DIY](/images/12-filesystems/12.4-diy/5-diy.png?width=90pc)

6. Review các AZ **available**

![DIY](/images/12-filesystems/12.4-diy/6-diy.png?width=90pc)

7. Trong giao diện **EC2**

- Chọn **instances (running)**

![DIY](/images/12-filesystems/12.4-diy/7-diy.png?width=90pc)

8. Trong giao diện **instances**

- Chọn **Webserver3**
- Click **Connect**

![DIY](/images/12-filesystems/12.4-diy/8-diy.png?width=90pc)

9. Trong giao diện **Connect to instance**

- Chọn **Session Manager**
- Click **Connect**

![DIY](/images/12-filesystems/12.4-diy/9-diy.png?width=90pc)

10. Trong giao diện **CLI**

- Gõ ```sudo yum install -y amazon-efs-utils``` và Enter
- Review 

![DIY](/images/12-filesystems/12.4-diy/10-diy.png?width=90pc)

11. Trong **File System**

- Chọn **PetModels-EFS-1**
- Click **Attach**

![DIY](/images/12-filesystems/12.4-diy/11-diy.png?width=90pc)

12. Trong giao diện **Attach**

- Copy dòng lệnh đầu tiên

![DIY](/images/12-filesystems/12.4-diy/12-diy.png?width=90pc)

13. Trong giao diện **CLI**

- Nhập ```sudo -i```
- Nhập ```mkdir data```
- Nhập ```ls```
- Nhập dòng lệnh của **Using the EFS mount helper** đã sao chép trước đó, sau đó thay **efs** thành **data**
- Nhập ```cd data```
- Nhập ```cat efs-l-setup.log```
- Nhập ```sudo bash -c "cat >> efs-l-setup.log"```
- Review **efs-1-mounted in site C**

![DIY](/images/12-filesystems/12.4-diy/13-diy.png?width=90pc)

14. Trong giao diện **File System**

- Copy fs-xxxxxxxxxxxxxxx sau tên **PetModels-EFS-1**

![DIY](/images/12-filesystems/12.4-diy/14-diy.png?width=90pc)

15. Trong giao diện **DIY**

- Dán vào **Amazon EFS file system ID**
- Click **Validate**

![DIY](/images/12-filesystems/12.4-diy/15-diy.png?width=90pc)

16. Trong giao diện **DIY**

- Xuất hiện dòng chữ xanh lá cây : **you did it!..*** là đã hoàn thành

![DIY](/images/12-filesystems/12.4-diy/16-diy.png?width=90pc)

17. Trong giao diện **thành phố**

- Chọn **Collect**

![DIY](/images/12-filesystems/12.4-diy/17-diy.png?width=90pc)

18. Chọn **Collect**

![DIY](/images/12-filesystems/12.4-diy/18-diy.png?width=90pc)

19. **CONGRATULATIONS!**

- Chúc mừng người chơi đã hoàn thành bài lab **File Systems in the Cloud**

![DIY](/images/12-filesystems/12.4-diy/19-diy.png?width=90pc)
