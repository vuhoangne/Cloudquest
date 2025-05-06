---
title : "Practice"

weight : 3
chapter : false
pre : " <b> 15.3 </b> "
---

{{% notice info %}}

After watching **Plan**, the player prepares for **Practice**

{{% /notice %}}

1. In the **Practice** interface
- Read step 1 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select **START LAB**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/1-practice.png?width=90pc)

2. In the **Practice** interface
- Read step 2 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select **Open AWS Console**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/2-practice.png?width=90pc)

3. In the **AWS Console** interface
- Find **EC2**
- Select **EC2**
![Practice](/images/15-highlyavailable/15.3-practice/3-practice.png?width=90pc)

4. In the **Practice** interface
- Read step 3 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/4-practice.png?width=90pc)

5. In the **EC2** interface
- Select **Auto Scaling Groups**
- Select **TravelAgencyWebServers**
- View details of **Desired capacity**, **Minimum capacity**, **Maximum capacity**
![Practice](/images/15-highlyavailable/15.3-practice/5-practice.png?width=90pc)

6. In the **Practice** interface
- Read step 4 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/6-practice.png?width=90pc)

7. In the **Auto Scaling groups** interface
- Select **Instance management**
- View instances
![Practice](/images/15-highlyavailable/15.3-practice/7-practice.png?width=90pc)

8. In the **Practice** interface
- Read step 5 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/8-practice.png?width=90pc)

9. In the **Auto Scaling groups** interface
- Select **Details**
![Practice](/images/15-highlyavailable/15.3-practice/9-practice.png?width=90pc)

10. In the **Practice** interface
- Read step 6 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/10-practice.png?width=90pc)

11. In the **Practice** interface
- Read step 7 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/11-practice.png?width=90pc)

12. In the **Auto Scaling groups** interface
- Under **Integrations-new**
- In **Load balancing**, select **Edit**
![Practice](/images/15-highlyavailable/15.3-practice/12-practice.png?width=90pc)

13. In the **Practice** interface
- Read step 8 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/13-practice.png?width=90pc)

14. In the **Edit TravelAgencyWebServers** interface
- Click **Add a new load balancer**
![Practice](/images/15-highlyavailable/15.3-practice/14-practice.png?width=90pc)

15. In the **Practice** interface
- Read step 9 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/15-practice.png?width=90pc)

16. In the **Edit TravelAgencyWebServers** interface
- Select **Application Load Balancer**
- Select **internet-facing**
![Practice](/images/15-highlyavailable/15.3-practice/16-practice.png?width=90pc)

17. In the **Practice** interface
- Read step 10 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/17-practice.png?width=90pc)

18. In the **Edit TravelAgencyWebServers** interface
- Select all 3 availability zones
- Select **Public subnet**
- In **Default routing (forward to)**, select **Create a target group**
- Select **Update**
![Practice](/images/15-highlyavailable/15.3-practice/18-practice.png?width=90pc)

19. In the **Practice** interface
- Read step 11 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/19-practice.png?width=90pc)

20. In the **Security Groups** interface
- Select **Create security group**
![Practice](/images/15-highlyavailable/15.3-practice/20-practice.png?width=90pc)

21. In the **Practice** interface
- Read step 12 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/21-practice.png?width=90pc)

22. In the **Create security group** interface
- **Security group name**: Enter ```TravelAgencyLoadBalancer```
- **Description**: Enter ```Allow access to the Travel Agency Balancer from the Internet```
- Select **VPC**
- In **Inbound rules**, select **Add rule**
![Practice](/images/15-highlyavailable/15.3-practice/22-practice.png?width=90pc)

23. In the **Practice** interface
- Read step 13 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/23-practice.png?width=90pc)

24. In the **Create security group** interface
- In **Inbound rules**, select **HTTP**, select **Source** as **Custom**, enter ```0.0.0.0/0```
![Practice](/images/15-highlyavailable/15.3-practice/24-practice.png?width=90pc)

25. In the **Practice** interface
- Read step 14 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/25-practice.png?width=90pc)

26. In the **Create security group** interface
- In **Outbound rules**, select **HTTP**, select **Destination** as **Custom**, select **Security group**
![Practice](/images/15-highlyavailable/15.3-practice/26-practice.png?width=90pc)

27. In the **Practice** interface
- Read step 15 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/27-practice.png?width=90pc)

28. In the **Security Groups** interface
- Select **Create security group**
![Practice](/images/15-highlyavailable/15.3-practice/28-practice.png?width=90pc)

29. In the **Practice** interface
- Read step 16 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/29-practice.png?width=90pc)

30. In the **Security Groups** interface
- Select **Security Groups**
- Select **TravelAgencyWebServer**
- Select **Actions**
- Select **Edit inbound rules**
![Practice](/images/15-highlyavailable/15.3-practice/30-practice.png?width=90pc)

31. In the **Practice** interface
- Read step 17 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/31-practice.png?width=90pc)

32. In the **Edit inbound rules** interface
- Select **Remove**
- Select **Add rule**
![Practice](/images/15-highlyavailable/15.3-practice/32-practice.png?width=90pc)

33. In the **Practice** interface
- Read step 18 of **Highly Available Web Applications**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/33-practice.png?width=90pc)

34. In the **Edit inbound rules** interface
- Select **HTTP**
- Select **TravelAgencyLoadBalancer** security group
![Practice](/images/15-highlyavailable/15.3-practice/34-practice.png?width=90pc)

35. In the **Practice** interface
- Read step 19 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/35-practice.png?width=90pc)

36. In the **Edit inbound rules** interface
- Select **Save rules**
![Practice](/images/15-highlyavailable/15.3-practice/36-practice.png?width=90pc)

37. In the **Practice** interface
- Read step 20 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/37-practice.png?width=90pc)

38. In the **Load Balancers** interface
- Select **Load Balancers**
- Select **TravelAgencyWebServer-1 ALB**
![Practice](/images/15-highlyavailable/15.3-practice/38-practice.png?width=90pc)

39. In the **Practice** interface
- Read step 21 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/39-practice.png?width=90pc)

40. In the **Load Balancers** interface
- Scroll down
![Practice](/images/15-highlyavailable/15.3-practice/40-practice.png?width=90pc)

41. In the **Practice** interface
- Read step 22 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/41-practice.png?width=90pc)

42. In the **Load Balancers** interface
- Click **Edit**
![Practice](/images/15-highlyavailable/15.3-practice/42-practice.png?width=90pc)

43. In the **Practice** interface
- Read step 23 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/43-practice.png?width=90pc)

44. In the **Edit Security groups** interface
- **Security groups**: Deselect **TravelAgencyWebServer**
![Practice](/images/15-highlyavailable/15.3-practice/44-practice.png?width=90pc)

45. In the **Practice** interface
- Read step 24 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/45-practice.png?width=90pc)

46. In the **Edit Security groups** interface
- **Security groups**: Select **TravelAgencyLoadBalancer**
![Practice](/images/15-highlyavailable/15.3-practice/46-practice.png?width=90pc)

47. In the **Practice** interface
- Read step 25 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/47-practice.png?width=90pc)

48. In the **TravelAgencyWebServer-1** interface
- Copy **DNS name**
![Practice](/images/15-highlyavailable/15.3-practice/48-practice.png?width=90pc)

49. In the **Practice** interface
- Read step 26 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/49-practice.png?width=90pc)

50. In the **browser** interface
- Paste **DNS name** in address bar and view results
![Practice](/images/15-highlyavailable/15.3-practice/50-practice.png?width=90pc)

51. In the **Practice** interface
- Read step 27 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/51-practice.png?width=90pc)

52. In the **browser** interface
- Append to end of **DNS name**: ```/health```
- View results
![Practice](/images/15-highlyavailable/15.3-practice/52-practice.png?width=90pc)

53. In the **Practice** interface
- Read step 28 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/53-practice.png?width=90pc)

54. In the **Target groups** interface
- Select **TravelAgencyWebServers-1**
- Select **Health checks**
- Select **Edit**
![Practice](/images/15-highlyavailable/15.3-practice/54-practice.png?width=90pc)

55. In the **Practice** interface
- Read step 29 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/55-practice.png?width=90pc)

56. In the **Edit health check settings** interface
- Enter ```/health```
- Select **Advanced health check settings**
![Practice](/images/15-highlyavailable/15.3-practice/56-practice.png?width=90pc)

57. In the **Practice** interface
- Read step 30 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/57-practice.png?width=90pc)

58. In the **Edit health check settings** interface
- **Healthy threshold**: 5
- **Unhealthy threshold**: 2
- **Timeout**: 2
- **Interval**: 5
- Select **Save changes**
![Practice](/images/15-highlyavailable/15.3-practice/58-practice.png?width=90pc)

59. In the **Practice** interface
- Read step 31 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/59-practice.png?width=90pc)

60. In the **Auto Scaling groups** interface
- Select **Auto Scaling Groups**
- Select **TravelAgencyWebServers**
- Scroll down and select **Edit**
![Practice](/images/15-highlyavailable/15.3-practice/60-practice.png?width=90pc)

61. In the **Practice** interface
- Read step 32 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/61-practice.png?width=90pc)

62. In the **Activity history** interface
- Deselect **PublicSubnet1**
- Select **PrivateSubnet1**
- Select **Update**
![Practice](/images/15-highlyavailable/15.3-practice/62-practice.png?width=90pc)

63. In the **Practice** interface
- Read step 33 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/63-practice.png?width=90pc)

64. In the **Instances** interface
- Select **TravelAgencyWebServers**
- Select **Networking**
- Review **Subnet ID**
- Select **Instance state**
- Select **Terminate**
![Practice](/images/15-highlyavailable/15.3-practice/64-practice.png?width=90pc)

65. In the **Practice** interface
- Read step 34 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/65-practice.png?width=90pc)

66. In the **Instances** interface
- After a few minutes, click **refresh icon**
- Select **TravelAgencyWebServers**
- Select **Networking**
- Review **Subnet ID**
- Confirm **TravelAgencyWebServers** is **Terminated**
![Practice](/images/15-highlyavailable/15.3-practice/66-practice.png?width=90pc)

67. In the **Practice** interface
- Read step 35 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/67-practice.png?width=90pc)

68. In the **Auto Scaling Groups** interface
- Select **TravelAgencyWebServers**
- Select **Activity**
- Scroll down
![Practice](/images/15-highlyavailable/15.3-practice/68-practice.png?width=90pc)

69. In the **Practice** interface
- Read step 36 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/69-practice.png?width=90pc)

70. In the **Auto Scaling Groups** interface
- Review
![Practice](/images/15-highlyavailable/15.3-practice/70-practice.png?width=90pc)

71. In the **Practice** interface
- Read step 37 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/71-practice.png?width=90pc)

72. In the **browser** interface
- Select **refresh icon**
![Practice](/images/15-highlyavailable/15.3-practice/72-practice.png?width=90pc)

73. In the **Practice** interface
- Read step 38 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/73-practice.png?width=90pc)

74. In the **Auto Scaling Groups** interface
- Select **Auto Scaling Groups**
- Select **TravelAgencyWebServers**
- Select **Edit**
![Practice](/images/15-highlyavailable/15.3-practice/74-practice.png?width=90pc)

75. In the **Practice** interface
- Read step 39 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/75-practice.png?width=90pc)

76. In the **EditTravelAgencyWebServers** interface
- Select **PrivateSubnet1** and **PrivateSubnet2**
- Select **Update**
![Practice](/images/15-highlyavailable/15.3-practice/76-practice.png?width=90pc)

77. In the **Practice** interface
- Read step 40 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/77-practice.png?width=90pc)

78. In the **Auto Scaling Groups** interface
- Select **Auto Scaling Groups**
- Select **TravelAgencyWebServers**
- Select **Edit**
![Practice](/images/15-highlyavailable/15.3-practice/78-practice.png?width=90pc)

79. In the **Practice** interface
- Read step 41 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/79-practice.png?width=90pc)

80. In the **pop-up** interface
- **Desired capacity**: 2
- **Max desired capacity**: 2
- Click **Update**
![Practice](/images/15-highlyavailable/15.3-practice/80-practice.png?width=90pc)

81. In the **Practice** interface
- Read step 42 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/81-practice.png?width=90pc)

82. In the **Auto Scaling Groups** interface
- Select **TravelAgencyWebServers**
- Select **Activity**
- Scroll down
![Practice](/images/15-highlyavailable/15.3-practice/82-practice.png?width=90pc)

83. In the **Practice** interface
- Read step 43 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/83-practice.png?width=90pc)

84. Review
![Practice](/images/15-highlyavailable/15.3-practice/84-practice.png?width=90pc)

85. In the **Practice** interface
- Read step 44 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/85-practice.png?width=90pc)

86. In the **Instances** interface
- Select **TravelAgencyWebServers**
- Select **Networking**
- Review **Subnet ID**
![Practice](/images/15-highlyavailable/15.3-practice/86-practice.png?width=90pc)

87. In the **Practice** interface
- Read step 45 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the right arrow to view next steps
![Practice](/images/15-highlyavailable/15.3-practice/87-practice.png?width=90pc)

88. In the **browser** interface
- Select **refresh**
- Review
![Practice](/images/15-highlyavailable/15.3-practice/88-practice.png?width=90pc)

89. Congratulations on completing the lab
![Practice](/images/15-highlyavailable/15.3-practice/89-practice.png?width=90pc)