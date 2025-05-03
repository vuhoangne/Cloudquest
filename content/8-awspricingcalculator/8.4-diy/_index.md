---
title : "DIY"

weight : 4
chapter : false
pre : " <b> 8.4 </b> "
---

{{% notice info %}}

After completing the lab, the player does **DIY**

{{% /notice %}}

1. In the **DIY** interface  
- Read **DIY ACTIVITIES**  
- Read **SOLUTION VALIDATION METHOD**

![DIY](/images/8-awspricingcalculator/8.4-diy/0-diy.png)

2. Go to [AWS Pricing Calculator](https://calculator.aws/#/)

- Click **Create estimate**

![DIY](/images/8-awspricingcalculator/8.4-diy/1-diy.png)

3. In **My Estimate**

- Click **Create group**

![DIY](/images/8-awspricingcalculator/8.4-diy/2-diy.png)

4. In **Add group**  
- In **Group name**, enter ```Web Servers```  
- Click **Create group**

![DIY](/images/8-awspricingcalculator/8.4-diy/3-diy.png)

5. In the **Web Servers** interface  
- Click **Add service**

![DIY](/images/8-awspricingcalculator/8.4-diy/4-diy.png)

6. In **Add service**  
- Search for **EC2**  
- Click **Configure**

![DIY](/images/8-awspricingcalculator/8.4-diy/5-diy.png)

7. In **Configure Amazon EC2**  
- In **Description**, enter ```Web Server Estimate```  
- For **Region**, select **US East (N. Virginia)**  
- In **EC2 instance specifications**, select **Linux**

![DIY](/images/8-awspricingcalculator/8.4-diy/6-diy.png)

8. In the **Workload** interface  
- Select **Daily spike traffic**  
- In **Daily spike pattern**, under **Workload days**, select the weekdays  
- **Baseline**: enter ```2```  
- **Peak**: enter ```4```  
- **Duration of peak**: enter ```8``` and ```0```

![DIY](/images/8-awspricingcalculator/8.4-diy/7-diy.png)  
![DIY](/images/8-awspricingcalculator/8.4-diy/8-diy.png)

9. In **EC2 Instances**  
- Select **t2.micro**

![DIY](/images/8-awspricingcalculator/8.4-diy/9-diy.png)

10. In **Pricing strategy**  
- For **Pricing model**, select **On-demand**  
- Click **Show calculations**  
- Click **estimate workload hours**

![DIY](/images/8-awspricingcalculator/8.4-diy/10-diy.png)  
![DIY](/images/8-awspricingcalculator/8.4-diy/11-diy.png)

11. In **Amazon Elastic Block Storage (EBS)**  
- For **Storage for each EC2 instance**, select **General Purpose SSD (gp2)**  
- **Storage amount**: enter ```30```  
- **Snapshot Frequency**: enter ```Weekly```  
- **Amount changed per snapshot**: enter ```1```

![DIY](/images/8-awspricingcalculator/8.4-diy/12-diy.png)

12. View the **Estimated workload hours**

![DIY](/images/8-awspricingcalculator/8.4-diy/13-diy.png)

13. In **Amazon Elastic Block Storage (EBS)**  
- **Inbound Data Transfer**: select **Internet (free)**  
- Enter 1  
- Select **TB per month**  
- **Outbound Data Transfer**: select **Internet (0.05 USD - 0.09 USD per GB)**  
- Enter 100  
- Select **TB per month**

![DIY](/images/8-awspricingcalculator/8.4-diy/14-diy.png)

14. Click **Show calculations**  
- Then click **Save and add service**

![DIY](/images/8-awspricingcalculator/8.4-diy/15-diy.png)

15. In the **Web Servers** interface  
- Click **Share**

![DIY](/images/8-awspricingcalculator/8.4-diy/16-diy.png)

16. In the **Save estimate** interface  
- Click **Copy public link**

![DIY](/images/8-awspricingcalculator/8.4-diy/17-diy.png)

17. After **Copy public link**  
- Go to the **DIY** interface  
- Paste it into **VALIDATION FORM**  
- Click **VALIDATE**  
- In **VALIDATION MESSAGE**, if it shows **you did it!...**, the **DIY** is completed  
- Then click **EXIT** to leave

![DIY](/images/8-awspricingcalculator/8.4-diy/18-diy.png)

18. Back at the city interface  
- Go to **ASSIGNMENT**, click **COLLECT**

![DIY](/images/8-awspricingcalculator/8.4-diy/19-diy.png)

19. Click **NEXT**

![DIY](/images/8-awspricingcalculator/8.4-diy/20-diy.png)

20. Click **COLLECT**

![DIY](/images/8-awspricingcalculator/8.4-diy/21-diy.png)

21. Congratulations! You’ve earned your reward!

![DIY](/images/8-awspricingcalculator/8.4-diy/22-diy.png)
