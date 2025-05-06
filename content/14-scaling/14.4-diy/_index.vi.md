---
title : "DIY"

weight : 4
chapter : false
pre : " <b> 14.4 </b> "
---

{{% notice info %}}

Sau khi hoàn thành bài lab, người chơi thực hiện **DIY**

{{% /notice %}}

1. Trong giao diện **DIY**

- Đọc **DIY ACTIVITIES**
- Đọc **SOLUTION VALIDATION METHOD**
- Chọn **Open AWS Console**

![DIY](/images/14-scaling/14.4-diy/1-diy.png?width=90pc)

2. Trong giao diện **AWS Console**

- Tìm **EC2**
- Chọn **EC2**

![DIY](/images/14-scaling/14.4-diy/2-diy.png?width=90pc)

3. Trong giao diện **EC2**

- Chọn **Instances**

![DIY](/images/14-scaling/14.4-diy/3-diy.png?width=90pc)

4. Trong giao diện **EC2**

- Chọn **Game Server**
- Chọn **Actions**
- Chọn **Image and templates**
- Chọn **Create image**


![DIY](/images/14-scaling/14.4-diy/4-diy.png?width=90pc)

5. Trong giao diện **Create image**

- **Image name**, nhập ```GameServer```
- **Image description**, nhập ```Regular customer game server```

![DIY](/images/14-scaling/14.4-diy/5-diy.png?width=90pc)

6. Trong giao diện **EC2**

- **Tags**, chọn **tag image and snapshots together**
- Chọn **Create image**

![DIY](/images/14-scaling/14.4-diy/6-diy.png?width=90pc)

7. Trong giao diện **EC2**

- Chọn **RegularCustomerGameServer**

![DIY](/images/14-scaling/14.4-diy/7-diy.png?width=90pc)

8. Trong giao diện **RegularCustomerGameServer**

- Chọn **Automatic scailing**

![DIY](/images/14-scaling/14.4-diy/8-diy.png?width=90pc)

9. Trong giao diện **RegularCustomerGameServer**

- Chọn **SecondWaveOfRegulars**
- Click vào **Actions** và chọn **Edit**


![DIY](/images/14-scaling/14.4-diy/9-diy.png?width=90pc)

10. Trong giao diện **Edit scheduled action**

- **Desired capacity**, nhập ```0```
- **Min**, nhập ```0```
- **Max**, nhập ```0```
- **Recurrence**, chọn **Every day**
- **Specific start time**, chọn 1 thời gian trong tương lai
- Chọn **01:00**
- Chọn **Save changes**


![DIY](/images/14-scaling/14.4-diy/10-diy.png?width=90pc)

11. Trong giao diện **RegularCustomerGameServer**

- Review

![DIY](/images/14-scaling/14.4-diy/11-diy.png?width=90pc)

12. Trong giao diện **DIY**

- Your Auto Scaling group name : ```RegularCustomerGameServer```
- Scheduled-action-name : ```SecondWaveOfRegulars```
- Chọn **Validate**

![DIY](/images/14-scaling/14.4-diy/12-diy.png?width=90pc)

13. Trong giao diện **DIY**

- Xuất hiện dòng chữ xanh lá cây : **you did it!..** là đã hoàn thành*

![DIY](/images/14-scaling/14.4-diy/13-diy.png?width=90pc)

14. Trong giao diện **thành phố**

- Chọn **Collect**

![DIY](/images/14-scaling/14.4-diy/14-diy.png?width=90pc)

15. Chọn **Collect**

![DIY](/images/14-scaling/14.4-diy/15-diy.png?width=90pc)

16. **CONGRATULATIONS!**

- Chúc mừng người chơi đã hoàn thành bài lab **Auto-Healing and Scaling Applications**

![DIY](/images/14-scaling/14.4-diy/16-diy.png?width=90pc)

