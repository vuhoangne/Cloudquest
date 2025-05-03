---
title : "DIY"

weight : 4
chapter : false
pre : " <b> 10.4 </b> "
---

{{% notice info %}}

After completing the lab, the player does **DIY**

{{% /notice %}}

1. In the **DIY** interface

- Read **DIY ACTIVITIES**
- Read **SOLUTION VALIDATION METHOD**

![DIY](/images/10-database/10.4-diy/1-diy.png)

2. In the **AWS Console** interface

- Search for **RDS**
- Select **Database**, in the **Databases** interface, select **my_database**

![DIY](/images/10-database/10.4-diy/2-diy.png)

3. In the **my_database** interface

- Click **Actions**
- Select **Create read replica**

![DIY](/images/10-database/10.4-diy/3-diy.png)

4. In the **Create read replica DB instance** interface

- Choose **my-database**
- Enter ```my-database-read-replica```
- Select **db.t3.xlarge**

![DIY](/images/10-database/10.4-diy/4-diy.png)

5. In the **Create read replica DB instance** interface

- In **Region: US East (N. Virginia)**
- In **allocated storage**, enter **20**
- Select **General Purpose SSD (gp3)**

![DIY](/images/10-database/10.4-diy/5-diy.png)

6. In the **Create read replica DB instance** interface

- Select as shown in the image

![DIY](/images/10-database/10.4-diy/6-diy.png)

7. In the **Create read replica DB instance** interface

- Click **Tags**

![DIY](/images/10-database/10.4-diy/7-diy.png)

8. In the **Create read replica DB instance** interface

- Click **Create a standby...**

![DIY](/images/10-database/10.4-diy/8-diy.png)

9. In the **Create read replica DB instance** interface

- Uncheck **Enable Enhanced monitoring**

![DIY](/images/10-database/10.4-diy/9-diy.png)

10. Click **Create read replica**

![DIY](/images/10-database/10.4-diy/10-diy.png)

11. In the **Databases** interface

- Copy ```my_database```
- Copy ```my-database-read-replica```

![DIY](/images/10-database/10.4-diy/11-diy.png)

12. In the **DIY** interface

- Paste the Amazon RDS DB 
- Paste the read replica DB

![DIY](/images/10-database/10.4-diy/12-diy.png)

13. In the **DIY** interface

- After selecting **VALIDATE**, the **VALIDATION MESSAGE** interface appears with **You did it!...**
- Completed the **DIY** lab
- Click **EXIT** to leave and return to the city interface

![DIY](/images/10-database/10.4-diy/13-diy.png)

14. Click **COLLECT**

![DIY](/images/10-database/10.4-diy/14-diy.png)

15. Congratulations on completing the lab

![DIY](/images/10-database/10.4-diy/15-diy.png)
