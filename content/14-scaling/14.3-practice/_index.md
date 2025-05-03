---
title : "Practice"

weight : 3
chapter : false
pre : " <b> 14.3 </b> "
---

{{% notice info %}}

After watching **Plan**, the player prepares for **Practice**

{{% /notice %}}

1. In the **Practice** interface

- Read step 1 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select **START LAB**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/1-practice.png)

2. In the **Practice** interface

- Read step 2 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select **Open AWS Console**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/2-practice.png)

3. In the **AWS Console** interface

- Find **EC2**
- Select **EC2**

![Practice](/images/14-scaling/14.3-practice/3-practice.png)

4. In the **Practice** interface

- Read step 3 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/4-practice.png)

5. In the **EC2** interface

- Select **Instances**

![Practice](/images/14-scaling/14.3-practice/5-practice.png)

6. In the **Practice** interface

- Read step 4 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/6-practice.png)

7. In the **Instances** interface

- View details of **Game Server**
- Copy **Public IPv4 address**

![Practice](/images/14-scaling/14.3-practice/7-practice.png)

8. In the **Practice** interface

- Read step 5 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/8-practice.png)

9. Open browser

- Paste **Public IPv4 address**
- Select **Enter**
- View results

![Practice](/images/14-scaling/14.3-practice/9-practice.png)

10. In the **Practice** interface

- Read step 6 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/10-practice.png)

11. In the **Instance** interface

- Select **Game Server**
- Select **Actions**
- Select **Image and templates**
- Select **Create image**

![Practice](/images/14-scaling/14.3-practice/11-practice.png)

12. In the **Practice** interface

- Read step 7 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/12-practice.png)

13. In the **Create image** interface

- **Image name**, enter ```Game Server```
- **Image description**, enter ```Regular customer game server```
![Practice](/images/14-scaling/14.3-practice/13-practice.png)

14. In the **Practice** interface

- Read step 8 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/14-practice.png)

15. In the **Create image** interface

- Click **Create image**

![Practice](/images/14-scaling/14.3-practice/15-practice.png)

16. In the **Practice** interface

- Read step 9 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/16-practice.png)

17. In the **Practice** interface

- Select **AMIs**
- Select **Game Server**
- Select **refresh**
- View **Status**
- Select **Launch Templates**

![Practice](/images/14-scaling/14.3-practice/17-practice.png)

18. In the **Practice** interface

- Read step 10 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/18-practice.png)

19. In the **Launch Templates** interface

- Select **Create launch template**

![Practice](/images/14-scaling/14.3-practice/19-practice.png)

20. In the **Practice** interface

- Read step 11 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/20-practice.png)

21. In the **Practice** interface

- **Launch template name**, enter ```GameServerTemplate```
- **Template version description**, enter ```Regular customer game server templagte```
- Uncheck **Provide guidance to help me set up a template tht I can use with EC2 Auto Scaling**

![Practice](/images/14-scaling/14.3-practice/21-practice.png)

22. In the **Practice** interface

- Read step 12 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/22-practice.png)

23. In the **Create launch template** interface

- Select **My AMIs**
- Select **Owned by me**
- In **Amazon Machine Image (AMI)**, select **GameServer**

![Practice](/images/14-scaling/14.3-practice/23-practice.png)

24. In the **Practice** interface

- Read step 13 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/24-practice.png)

25. In the **Create launch template** interface

- In **Instance type**, select **t2.nano**
- Select **Create new key pair**

![Practice](/images/14-scaling/14.3-practice/25-practice.png)

26. In the **Practice** interface

- Read step 14 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/26-practice.png)

27. In the **Create key pair** interface

- **Key pair name**, enter ```GameServerKeyPair```
- **Key pair type**, select **RSA**
- **Private key file format**, select **.pem**
- Select **Create key pair**

![Practice](/images/14-scaling/14.3-practice/27-practice.png)

28. In the **Practice** interface

- Read step 15 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/28-practice.png)

29. In the **Create launch template** interface

- In **Network settings**, select **Select existing security group**
- Select **WebServerSecurityGroup**

![Practice](/images/14-scaling/14.3-practice/29-practice.png)

30. In the **Practice** interface

- Read step 16 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/30-practice.png)

- In the **personal** interface
- Select **Create launch template**

![Practice](/images/14-scaling/14.3-practice/30.1-practice.png)

31. In the **Practice** interface

- Read step 17 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/31.1-practice.png)

- Select **View launch template**

![Practice](/images/14-scaling/14.3-practice/31-practice.png)

32. In the **Practice** interface

- Read step 18 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/32-practice.png)

33. In the **Auto Scaling Groups** interface

- Select **Create Auto Scaling Groups**

![Practice](/images/14-scaling/14.3-practice/33-practice.png)

34. In the **Practice** interface

- Read step 19 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/34-practice.png)

35. In the **Pracitce** interface

- In **Choose launch template or conriguration**
- **Auto Scaling group name**, enter **```RegularCustomerGameServer```**
- **Launch template**, enter ```GameServerTemplate```

![Practice](/images/14-scaling/14.3-practice/35-practice.png)

36. In the **Practice** interface

- Read step 20 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/36-practice.png)

37. In the **Create Auto Scaling Group** interface

- Scroll down and select **Next**

![Practice](/images/14-scaling/14.3-practice/37-practice.png)

38. In the **Practice** interface

- Read step 21 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/38-practice.png)

39. In the **Create Auto Scaling Group** interface

- Select **vpc (auto-healing-and-scaling/GameServerVPC)**
- In **Network**, Select **VPC**
- In **Availability Zones and subnet**, select **(auto-healing-and-scaling/GameServerVPC/game-server-netSubnet1)**, **(auto-healing-and-scaling/GameServerVPC/game-server-netSubnet2)**

![Practice](/images/14-scaling/14.3-practice/39-practice.png)

40. In the **Practice** interface

- Read step 22 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/40-practice.png)

41. In the **Create Auto Scaling Group** interface

- Select **Next**

![Practice](/images/14-scaling/14.3-practice/41-practice.png)

42. In the **Practice** interface

- Read step 23 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/42-practice.png)

43. In the **Configure advanced options - optional** interface

- Select **No load balancer**

![Practice](/images/14-scaling/14.3-practice/43-practice.png)

44. In the **Practice** interface

- Read step 24 of **Auto-healing and Scaling Applications**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/44-practice.png)

45. In the **Create Auto Scaling Group** interface

- **Health check grace period**: **240**
- Select **Next**

![Practice](/images/14-scaling/14.3-practice/45-practice.png)

46. In the **Practice** interface

- Read step 25 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/46-practice.png)

47. In the **Create Auto Scaling Group** interface

- **Minimum capacity**, enter 2
- **Maximum capacity**, enter 4
- In **Scaling policies**, select **target tracking scaling policy**

![Practice](/images/14-scaling/14.3-practice/47-practice.png)

48. In the **Practice** interface

- Read step 26 of **Auto-healing and Scaling Applications**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/48-practice.png)

49. In the **Create Auto Scaling Group** interface

- In **Scaling policy name**, enter ```CPU Utilization```
- **Metric type**, select **Aerage CPU utilization**
- **Target value**, enter ```70```
- Scroll down

![Practice](/images/14-scaling/14.3-practice/49-practice.png)

50. In the **Practice** interface

- Read step 27 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/50-practice.png)

51. In the **Create Auto Scaling Group** interface

- Select **Skip to review**

![Practice](/images/14-scaling/14.3-practice/51-practice.png)

52. In the **Practice** interface

- Read step 28 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/52-practice.png)

53. In the **Create Auto Scaling Group** interface

- Scroll down
- Select **Create Auto Scaling Group**

![Practice](/images/14-scaling/14.3-practice/53-practice.png)

54. In the **Practice** interface

- Read step 29 of **Auto-healing and Scaling Applications**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/54-practice.png)

55. In the **Auto Scaling group** interface

- Select **RegularCustomerGameServer**

![Practice](/images/14-scaling/14.3-practice/55-practice.png)

56. In the **Practice** interface

- Read step 30 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/56-practice.png)

57. In the **Auto Scaling group** interface

- View initialization results of **RegularCustomerGameServer**

![Practice](/images/14-scaling/14.3-practice/57-practice.png)

58. In the **Practice** interface

- Read step 31 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/58-practice.png)

59. In the **Auto Scaling Group** interface

- Select **Automatic scaling**
- Scroll down

![Practice](/images/14-scaling/14.3-practice/59-practice.png)

60. In the **Practice** interface

- Read step 32 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/60-practice.png)

61. In the **Auto Scaling Group** interface

- Select **Create scheduled action**

![Practice](/images/14-scaling/14.3-practice/61-practice.png)

62. In the **Practice** interface

- Read step 33 of **Auto-healing and Scaling Applications**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/62-practice.png)

63. In the **Create scheduled action** interface

- **Name**, enter **```SecondWaveOfRegulars```**
- **Desired capacity**, enter ```3```
- **Min**, enter ```3```
- **Max**, enter ```4```
- **Recurrence**, select **Every week**
- **Specific start time**, select a future time
- Select **Create**

![Practice](/images/14-scaling/14.3-practice/63-practice.png)

64. In the **Practice** interface

- Read step 34 of **Auto-healing and Scaling Applications**
- Select right arrow to view next steps

![Practice](/images/14-scaling/14.3-practice/64-practice.png)

65. In the **Auto Scaling Group** interface

- Review

![Practice](/images/14-scaling/14.3-practice/65-practice.png)

66. Congratulations on completing the lab

![Practice](/images/14-scaling/14.3-practice/66-practice.png)