---
title : "DIY"

weight : 4
chapter : false
pre : " <b> 8.4 </b> "
---

{{% notice info %}}

Sau khi hoàn thành bài lab, người chơi thực hiện **DIY**

{{% /notice %}}

1. Trong giao diện **DIY**
- Đọc **DIY ACTIVITIES**
- Đọc **SOLUTION VALIDATION METHOD**

![DIY](/images/8-awspricingcalculator/8.4-diy/0-diy.png?width=90pc)

2. Truy cập vào trang [AWS Pricing Calculator](https://calculator.aws/#/)

- Chọn **Create estimate**
  
![DIY](/images/8-awspricingcalculator/8.4-diy/1-diy.png?width=90pc)

3. Trong **My Estimate**

- Chọn **Create group**
  
![DIY](/images/8-awspricingcalculator/8.4-diy/2-diy.png?width=90pc)

4. Trong **Add group**
- **Group name**, nhập ```Web Servers```
- Chọn **Create group**

![DIY](/images/8-awspricingcalculator/8.4-diy/3-diy.png?width=90pc)

5. Trong giao diện **Web Servers**
- Chọn **Add service**
  
![DIY](/images/8-awspricingcalculator/8.4-diy/4-diy.png?width=90pc)

6. Trong **Add service**

- Tìm kiếm **EC2**
- Chọn **Configure**

![DIY](/images/8-awspricingcalculator/8.4-diy/5-diy.png?width=90pc)

7. Trong **Configure Amazon EC2**
- **Description**, nhập ```Web Server Estimate```
- **Region**, chọn **US East (N. Virginia)**
- Trong **EC2 instance specifications**, chọn **Linux**

![DIY](/images/8-awspricingcalculator/8.4-diy/6-diy.png?width=90pc)

8. Trong giao diện **Workload**
- Chọn **Daily spike traffic**
- **Daily spike pattern**, phần **Workload days**, chọn các ngày trong tuần
- **Baseline**, nhập ```2```
- **Peak**, nhập ```4```
- **Duration of peak**, nhập ```8``` và ```0```

![DIY](/images/8-awspricingcalculator/8.4-diy/7-diy.png?width=90pc)
![DIY](/images/8-awspricingcalculator/8.4-diy/8-diy.png?width=90pc)

9. Trong **EC2 Instances**
- Chọn **t2.micro**

![DIY](/images/8-awspricingcalculator/8.4-diy/9-diy.png?width=90pc)

10. Trong **Pricing strategy**

- **Pricing model**, chọn **On-demand**
- Chọn **Show calculations**
- Chọn **estimate workload hours**

![DIY](/images/8-awspricingcalculator/8.4-diy/10-diy.png?width=90pc)
![DIY](/images/8-awspricingcalculator/8.4-diy/11-diy.png?width=90pc)

11. Trong **Amazon Elastic Block Storage (EBS)**

- **Storage for each EC2 instance**, chọn **General Purpose SSD (gp2)**
- **Storage amount**, nhập ```30```
- **Snapshot Frequency**, nhập ```Weekly```
- **Amount changed per snapshot**, nhập ```1```

![DIY](/images/8-awspricingcalculator/8.4-diy/12-diy.png?width=90pc)

12. Xem kết quả **Estimated workload hours**

![DIY](/images/8-awspricingcalculator/8.4-diy/13-diy.png?width=90pc)

13. Trong **Amazon Elastic Block Storage (EBS)**
    
- **Inbound Data Transfer**, chọn **Internet (free)**
- Chọn 1
- Chọn **TB per month**
- **Outbound Data Transfer**, chọn **Internet (0.05 USD - 0.09 USD per GB)**
- Chọn 100
- Chọn **TB per month**
  
![DIY](/images/8-awspricingcalculator/8.4-diy/14-diy.png?width=90pc)

14. Chọn **Show calculations**

- Xem và chọn **Save and add service**

![DIY](/images/8-awspricingcalculator/8.4-diy/15-diy.png?width=90pc)

15. Trong giao diện **Web Servers**

- Chọn **Share**

![DIY](/images/8-awspricingcalculator/8.4-diy/16-diy.png?width=90pc)

16. Trong giao diện **Save estimate**

- Chọn **Copy public link**

![DIY](/images/8-awspricingcalculator/8.4-diy/17-diy.png?width=90pc)

17. Sau khi **Copy public link**
- Vào giao diện **DIY**
- Dán vào **VALIDATION FORM**
- Chọn **VALIDATE**
- Trên **VALIDATION MESSAGE**, xuất hiện **you did it!...** là hoàn thành **DIY**
- Sau đó chọn **EXIT** để thoát

![DIY](/images/8-awspricingcalculator/8.4-diy/18-diy.png?width=90pc)

18. Sau khi ra giao diện thành phố 

- Vào **ASSIGNMENT**, chọn **COLLECT**

![DIY](/images/8-awspricingcalculator/8.4-diy/19-diy.png?width=90pc)

19. Chọn **NEXT**

![DIY](/images/8-awspricingcalculator/8.4-diy/20-diy.png?width=90pc)

20. Chọn **COLLECT**

![DIY](/images/8-awspricingcalculator/8.4-diy/21-diy.png?width=90pc)

21. Chúc mừng người chơi nhận thưởng

![DIY](/images/8-awspricingcalculator/8.4-diy/22-diy.png?width=90pc)
