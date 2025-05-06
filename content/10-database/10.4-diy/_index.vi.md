---
title : "DIY"

weight : 4
chapter : false
pre : " <b> 10.4 </b> "
---

{{% notice info %}}

Sau khi hoàn thành bài lab, người chơi thực hiện **DIY**

{{% /notice %}}

1. Trong giao diện **DIY**

- Đọc **DIY ACTIVITIES**
- Đọc **SOLUTION VALIDATION METHOD**

![DIY](/images/10-database/10.4-diy/1-diy.png?width=90pc)

2. Trong giao diện **AWS Console**

- Tìm **RDS**
- Chọn **Database** , trong giao diện **Databases** , chọn **my_database**

![DIY](/images/10-database/10.4-diy/2-diy.png?width=90pc)

3. Trong giao diện **my_database**

- Chọn **Actions**
- Chọn **Create read replica**

![DIY](/images/10-database/10.4-diy/3-diy.png?width=90pc)

4. Trong giao diện **Create read replica DB instance**

- Chọn **my-database**
- Gõ ```my-database-read-replica```
- Chọn **db.t3.xlarge**

![DIY](/images/10-database/10.4-diy/4-diy.png?width=90pc)

5. Trong giao diện **Create read replica DB instance**

- Trong **Region : US.East ( N.Virginia )**
- Trong **allocated storage**, gõ **20**
- chọn **General Purpose SSD (gp3)**

![DIY](/images/10-database/10.4-diy/5-diy.png?width=90pc)

6. Trong giao diện **Create read replica DB instance**

- Chọn như trong ảnh

![DIY](/images/10-database/10.4-diy/6-diy.png?width=90pc)

7. Trong giao diện **Create read replica DB instance**

- Click vào **Tags**

![DIY](/images/10-database/10.4-diy/7-diy.png?width=90pc)

8. Trong giao diện **Create read replica DB instance**

- Click vào **Create a stanby...**

![DIY](/images/10-database/10.4-diy/8-diy.png?width=90pc)

9. Trong giao diện **Create read replica DB instance**

- Bỏ chọn **Enable Enhanced monitoring**

![DIY](/images/10-database/10.4-diy/9-diy.png?width=90pc)

10. Chọn **Create read replica**

![DIY](/images/10-database/10.4-diy/10-diy.png?width=90pc)

11. Trong giao diện **Databases**

- Copy ```my_database```
- Copy ```my-database-read-replica```

![DIY](/images/10-database/10.4-diy/11-diy.png?width=90pc)

12. Trong giao diện **DIY**

- Dán Amazon RDS DB 
- Dán read replica DB

![DIY](/images/10-database/10.4-diy/12-diy.png?width=90pc)

13. Trong giao diện **DIY**

- Sau khi chọn **VALIDATE**, giao diện **VALIDATION MESSAGE** xuất hiện **You did it!...**
- Hoàn thành bài **DIY**
- Chọn **EXIT** để thoát và quay về giao diện thành phố

![DIY](/images/10-database/10.4-diy/13-diy.png?width=90pc)

14. Chọn **COLLECT**

![DIY](/images/10-database/10.4-diy/14-diy.png?width=90pc)

15. Chúc mừng người chơi đã hoàn thành bài lab

![DIY](/images/10-database/10.4-diy/15-diy.png?width=90pc)