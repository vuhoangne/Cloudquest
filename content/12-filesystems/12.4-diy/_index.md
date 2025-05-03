---
title : "DIY"

weight : 4
chapter : false
pre : " <b> 12.4 </b> "
---

{{% notice info %}}

After completing the lab, the player does **DIY**

{{% /notice %}}

1. In the **AWS Console** interface:

- Search for **EFS**
- Select **EFS**
- Choose **PetModels-EFS-1**

![DIY](/images/12-filesystems/12.4-diy/1-diy.png)

2. In the **EFS** interface:

- Select **Network**
- Click **Manage**

![DIY](/images/12-filesystems/12.4-diy/2-diy.png)

3. In the **Network** interface:

- Click **Add mount target**

![DIY](/images/12-filesystems/12.4-diy/3-diy.png)

4. In the **Create security group** interface:

- Select **us-east-1c**
- Choose **Security groups**: **PetModels-EFS-1-SG**

![DIY](/images/12-filesystems/12.4-diy/4-diy.png)

5. Review

![DIY](/images/12-filesystems/12.4-diy/5-diy.png)

6. Review the **available** AZs

![DIY](/images/12-filesystems/12.4-diy/6-diy.png)

7. In the **EC2** interface:

- Select **Instances (running)**

![DIY](/images/12-filesystems/12.4-diy/7-diy.png)

8. In the **Instances** interface:

- Choose **Webserver3**
- Click **Connect**

![DIY](/images/12-filesystems/12.4-diy/8-diy.png)

9. In the **Connect to instance** interface:

- Select **Session Manager**
- Click **Connect**

![DIY](/images/12-filesystems/12.4-diy/9-diy.png)

10. In the **CLI** interface:

- Type ```sudo yum install -y amazon-efs-utils``` and press Enter
- Review

![DIY](/images/12-filesystems/12.4-diy/10-diy.png)

11. In the **File System** interface:

- Select **PetModels-EFS-1**
- Click **Attach**

![DIY](/images/12-filesystems/12.4-diy/11-diy.png)

12. In the **Attach** interface:

- Copy the first command line

![DIY](/images/12-filesystems/12.4-diy/12-diy.png)

13. In the **CLI** interface:

- Enter ```sudo -i```
- Enter ```mkdir data```
- Enter ```ls```
- Paste the command line from **Using the EFS mount helper** that was copied earlier, then replace **efs** with **data**
- Enter ```cd data```
- Enter ```cat efs-l-setup.log```
- Enter ```sudo bash -c "cat >> efs-l-setup.log"```
- Review **efs-1-mounted in site C**

![DIY](/images/12-filesystems/12.4-diy/13-diy.png)

14. In the **File System** interface:

- Copy fs-xxxxxxxxxxxxxxx after the name **PetModels-EFS-1**

![DIY](/images/12-filesystems/12.4-diy/14-diy.png)

15. In the **DIY** interface:

- Paste it into the **Amazon EFS file system ID**
- Click **Validate**

![DIY](/images/12-filesystems/12.4-diy/15-diy.png)

16. In the **DIY** interface:

- A green message will appear: **you did it!..*** indicating completion

![DIY](/images/12-filesystems/12.4-diy/16-diy.png)

17. In the **City** interface:

- Click **Collect**

![DIY](/images/12-filesystems/12.4-diy/17-diy.png)

18. Click **Collect**

![DIY](/images/12-filesystems/12.4-diy/18-diy.png)

19. **CONGRATULATIONS!**

- Congratulations on completing the **File Systems in the Cloud** lab

![DIY](/images/12-filesystems/12.4-diy/19-diy.png)
