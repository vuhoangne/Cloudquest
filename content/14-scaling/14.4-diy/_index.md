---
title : "DIY"

weight : 4
chapter : false
pre : " <b> 14.4 </b> "
---

{{% notice info %}}

After completing the lab, the player does **DIY**

{{% /notice %}}

1. In the **DIY** interface

- Read **DIY ACTIVITIES**
- Read **SOLUTION VALIDATION METHOD**
- Select **Open AWS Console**

![DIY](/images/14-scaling/14.4-diy/1-diy.png)

2. In the **AWS Console** interface

- Find **EC2**
- Select **EC2**

![DIY](/images/14-scaling/14.4-diy/2-diy.png)

3. In the **EC2** interface

- Select **Instances**

![DIY](/images/14-scaling/14.4-diy/3-diy.png)

4. In the **EC2** interface

- Select **Game Server**
- Select **Actions**
- Select **Image and templates**
- Select **Create image**

![DIY](/images/14-scaling/14.4-diy/4-diy.png)

5. In the **Create image** interface

- **Image name**, enter ```GameServer```
- **Image description**, enter ```Regular customer game server```

![DIY](/images/14-scaling/14.4-diy/5-diy.png)

6. In the **EC2** interface

- **Tags**, select **tag image and snapshots together**
- Select **Create image**

![DIY](/images/14-scaling/14.4-diy/6-diy.png)

7. In the **EC2** interface

- Select **RegularCustomerGameServer**

![DIY](/images/14-scaling/14.4-diy/7-diy.png)

8. In the **RegularCustomerGameServer** interface

- Select **Automatic scailing**

![DIY](/images/14-scaling/14.4-diy/8-diy.png)

9. In the **RegularCustomerGameServer** interface

- Select **SecondWaveOfRegulars**
- Click **Actions** and select **Edit**

![DIY](/images/14-scaling/14.4-diy/9-diy.png)

10. In the **Edit scheduled action** interface

- **Desired capacity**, enter ```0```
- **Min**, enter ```0```
- **Max**, enter ```0```
- **Recurrence**, select **Every day**
- **Specific start time**, select a future time
- Select **01:00**
- Select **Save changes**

![DIY](/images/14-scaling/14.4-diy/10-diy.png)

11. In the **RegularCustomerGameServer** interface

- Review

![DIY](/images/14-scaling/14.4-diy/11-diy.png)

12. In the **DIY** interface

- Your Auto Scaling group name : ```RegularCustomerGameServer```
- Scheduled-action-name : ```SecondWaveOfRegulars```
- Select **Validate**

![DIY](/images/14-scaling/14.4-diy/12-diy.png)

13. In the **DIY** interface

- A green message appears: **you did it!..** means completed*

![DIY](/images/14-scaling/14.4-diy/13-diy.png)

14. In the **city** interface

- Select **Collect**

![DIY](/images/14-scaling/14.4-diy/14-diy.png)

15. Select **Collect**

![DIY](/images/14-scaling/14.4-diy/15-diy.png)

16. **CONGRATULATIONS!**

- Congratulations on completing the **Auto-Healing and Scaling Applications** lab

![DIY](/images/14-scaling/14.4-diy/16-diy.png)