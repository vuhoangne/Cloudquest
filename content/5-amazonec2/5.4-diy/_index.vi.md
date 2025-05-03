---
title : "DIY"

weight : 4
chapter : false
pre : " <b> 5.4 </b> "
---

{{% notice info %}}

Sau khi hoàn thành bài lab, người chơi thực hiện **DIY**

{{% /notice %}}

1. Chọn **DIY** để thực hiện 

![DIY](/images/5-amazonec2/5.4-diy/1-diy.png)

2. Trong giao diện **DIY**

- Đọc **DIY ACTIVITIES**
- Đọc **SOLUTION VALIDATION METHOD**
- Chọn **Open AWS Console**

![DIY](/images/5-amazonec2/5.4-diy/2-diy.png)

3. Trong **EC2** , chọn **launch instance**

- Gõ ```webserver02```
- Chọn Amazon Linux 2023 AMI 
- Gõ ```Enable```
- Gõ ```LabHN```
- Gõ ```HTTP Security```
- Type : HTTP , Source type : Anywhere
![DIY](/images/5-amazonec2/5.4-diy/3-diy.png)

4. Trong giao diện **Launch an instance**

- Chọn vpc (cloud-first-steps/LabVpc)
- Chọn subnet có AZ : us-east-1b

![DIY](/images/5-amazonec2/5.4-diy/4-diy.png)

5. Trong giao diện **Launch an instance**

-  Review user-data.txt 
-  Chọn **Launch instance**

![DIY](/images/5-amazonec2/5.4-diy/5-diy.png)

6. Review

![DIY](/images/5-amazonec2/5.4-diy/6-diy.png)

7. Chọn **View all instances**

![DIY](/images/5-amazonec2/5.4-diy/7-diy.png)

8. Trong **Advanced Details**

- Chọn **Webserver02**
- Copy Instance ID 

![DIY](/images/5-amazonec2/5.4-diy/8-diy.png)


9. Trong giao diện **DIY**

- Gõ instance ID 1
- Gõ instance ID 2
- Chọn **Validate**

![DIY](/images/5-amazonec2/5.4-diy/9-diy.png)

10. Trong giao diện **DIY**

- Xuất hiện dòng chữ màu xanh lá:"you did it..." là đã hoàn thành


![DIY](/images/5-amazonec2/5.4-diy/10-diy.png)

11.  Trong giao diện thành phố 

- Chúc mừng bạn đã hoàn thành **Cloud First Steps**

![DIY](/images/5-amazonec2/5.4-diy/12-diy.png)

