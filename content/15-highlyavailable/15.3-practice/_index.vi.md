---
title : "Practice"

weight : 3
chapter : false
pre : " <b> 15.3 </b> "
---

{{% notice info %}}

Sau khi xem **Plan**, người chơi chuẩn bị cho **Practice**

{{% /notice %}}

1. Trong giao diện **Practice**

- Đọc bước 1 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn **START LAB**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/1-practice.png)

2. Trong giao diện **Practice**

- Đọc bước 2 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn **Open AWS Console**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/2-practice.png)

3. Trong giao diện **AWS Console**

- Tìm **EC2**
- Chọn **EC2**

![Practice](/images/15-highlyavailable/15.3-practice/3-practice.png)

4. Trong giao diện **Practice**

- Đọc bước 3 của **highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/4-practice.png)

5. Trong giao diện **EC2**

- Chọn **Auto Scaling Groups**
- Chọn **TravelAgencuWebServers**
- Xem chi tiết về **Desired capacity**, **Minimum capacity**, **Maximum capacity**

![Practice](/images/15-highlyavailable/15.3-practice/5-practice.png)

6. Trong giao diện **Pracitce**

- Đọc bước 4 của **highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/6-practice.png)

7. Trong giao diện **Auto Scaling groups**

- Chọn **Instance management**
- Xem instance

![Practice](/images/15-highlyavailable/15.3-practice/7-practice.png)

8. Trong giao diện **Practice**

- Đọc bước 5 của **highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/8-practice.png)

9. Trong giao diện **Auto Scaling groups**

- Chọn **Deatils**

![Practice](/images/15-highlyavailable/15.3-practice/9-practice.png)

10. Trong giao diện **Practice**

- Đọc bước 6 của **highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/10-practice.png)

11. Trong giao diện **Practice**

- Đọc bước 7 của **highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo


![Practice](/images/15-highlyavailable/15.3-practice/11-practice.png)

12. Trong giao diện **Auto Scaling groups**

- Trong **Integrations-new**
- Trong **Load balancing**, chọn **Edit**


![Practice](/images/15-highlyavailable/15.3-practice/12-practice.png)

13. Trong giao diện **Practice**

- Đọc bước 8 của **highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo


![Practice](/images/15-highlyavailable/15.3-practice/13-practice.png)

14. Trong giao diện **Edit TravelAgencyWebServers**

- Click **Add a new load balancer**

![Practice](/images/15-highlyavailable/15.3-practice/14-practice.png)

15. Trong giao diện **Practice**

- Đọc bước 9 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/15-practice.png)

16. Trong giao diện **Edit TravelAgencyWebServers**

- Chọn **Application Load Balancer**
- Chọn **internet-facing**

![Practice](/images/15-highlyavailable/15.3-practice/16-practice.png)

17. Trong giao diện **Practice**

- Đọc bước 10 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo


![Practice](/images/15-highlyavailable/15.3-practice/17-practice.png)

18. Trong giao diện **Edit TravelAgencyWebServers**

- Chọn tất cả 3 availability zone
- Chọn **Public subnet**
- Trong **Default routing (forward to)**, chọn **Create a target group**
- Chọn **Update**

![Practice](/images/15-highlyavailable/15.3-practice/18-practice.png)

19. Trong giao diện **Practice**

- Đọc bước 11 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/19-practice.png)

20. Trong giao diện **Security Groups**

- Chọn **Create security group**

![Practice](/images/15-highlyavailable/15.3-practice/20-practice.png)

21. Trong giao diện **Practice**

- Đọc bước 12 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo


![Practice](/images/15-highlyavailable/15.3-practice/21-practice.png)

22. Trong giao diện **Create security group**

- **Security group name**, nhập ```TravelAgencyLoadBalancer```
- **Description**, nhập ```Allow access to the Travel Agency Balancer from the Internet```
- Chọn **VPC**
- Trong **Inbound rules**, chọn **Add rule**

![Practice](/images/15-highlyavailable/15.3-practice/22-practice.png)

23. Trong giao diện **Practice**
    
- Đọc bước 13 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/23-practice.png)

24. Trong giao diện **Create security group**

- Trong **Inbound rules**, chọn **HTTP**, chọn **Source** là **Custom**, chọn ```0.0.0.0/0```

![Practice](/images/15-highlyavailable/15.3-practice/24-practice.png)

25.  Trong giao diện **Practice**


- Đọc bước 14 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/25-practice.png)

26. Trong giao diện **Create security group**

- Trong **Outbound rules**, chọn **HTTP**, chọn **Destination** là **Custom**, chọn **Security group**

![Practice](/images/15-highlyavailable/15.3-practice/26-practice.png)

27. Trong giao diện **Practice**

- Đọc bước 15 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/27-practice.png)

28. Trong giao diện **Security Groups**

- Chọn **Create security group**

![Practice](/images/15-highlyavailable/15.3-practice/28-practice.png)

29. Trong giao diện **Practice**

- Đọc bước 16 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/29-practice.png)

30. Trong giao diện **Security Groups**

- Chọn **Security Groups**
- Chọn **TravelAgencyWebServer**
- Chọn **Actions**
- Chọn **Edit inblound rules**

![Practice](/images/15-highlyavailable/15.3-practice/30-practice.png)

31. Trong giao diện **Practice**

- Đọc bước 17 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/31-practice.png)

32. Trong giao diện **Edit inbound rules**

- Chọn **Remove**
- Chọn **Add rule**

![Practice](/images/15-highlyavailable/15.3-practice/32-practice.png)

33. Trong giao diện **Practice**

- Đọc bước 17 của **Highly Available Web Applications**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/33-practice.png)

34. Trong giao diện **Edit inbound rules**

- Chọn **HTTP**
- Chọn **TravelAgencyLoadBalancer** security group

![Practice](/images/15-highlyavailable/15.3-practice/34-practice.png)

35. Trong giao diện **Practice**

- Đọc bước 19 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/35-practice.png)

36. Trong giao diện **Edit inbound rules**

- Chọn **Save rules**

![Practice](/images/15-highlyavailable/15.3-practice/36-practice.png)

37. Trong giao diện **Practice**

- Đọc bước 20 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/37-practice.png)

38. Trong giao diện **Load Balencers**

- Chọn **Load Balancers**
- Chọn **TravelAgencyWebServer-1 ALB**

![Practice](/images/15-highlyavailable/15.3-practice/38-practice.png)

39. Trong giao diện **Practice**

- Đọc bước 21 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/39-practice.png)

40. Trong giao diện **Load Balencers**

- Kéo xuống phía dưới

![Practice](/images/15-highlyavailable/15.3-practice/40-practice.png)

41. Trong giao diện **Practice**

- Đọc bước 22 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/41-practice.png)

42. Trong giao diện **Load Balencers**

- Click **Edit**

![Practice](/images/15-highlyavailable/15.3-practice/42-practice.png)

43. Trong giao diện **Practice**

- Đọc bước 23 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/43-practice.png)

44. Trong giao diện **Edit Security groups**

- **Security groups** : bỏ chọn **TravelAgencyWebServer**

![Practice](/images/15-highlyavailable/15.3-practice/44-practice.png)

45. Trong giao diện **Practice**

- Đọc bước 24 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/45-practice.png)

46. Trong giao diện **Edit Security groups**

- **Security groups** : chọn **TravelAgencyLoadBalancer**

![Practice](/images/15-highlyavailable/15.3-practice/46-practice.png)

47. Trong giao diện **Practice**

- Đọc bước 25 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/47-practice.png)

48. Trong giao diện **TravelAgencyWebServer-1**

- Copy **DNS name**

![Practice](/images/15-highlyavailable/15.3-practice/48-practice.png)

49. Trong giao diện **Practice**

- Đọc bước 26 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo


![Practice](/images/15-highlyavailable/15.3-practice/49-practice.png)

50. Trong giao diện **trình duyệt**
    
- Dán **DNS name** lên thanh tìm kiếm và xem kết quả 

![Practice](/images/15-highlyavailable/15.3-practice/50-practice.png)

51. Trong giao diện **Practice**

- Đọc bước 27 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/51-practice.png)

52. Trong giao diện **trình duyệt**

- Thêm vào cuối **DNS name**: ```/health```
- Xem kết quả

![Practice](/images/15-highlyavailable/15.3-practice/52-practice.png)

53. Trong giao diện **Practice**

- Đọc bước 28 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/53-practice.png)

54. Trong giao diện **Target groups**

- Chọn **TravelAgencyWebServers-1**
- Chọn **Health checks**
- Chọn **Edit**

![Practice](/images/15-highlyavailable/15.3-practice/54-practice.png)

55. Trong giao diện **Practice**

- Đọc bước 29 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/55-practice.png)

56. Trong giao diện **Edit health check settings**

- Gõ ```/health```
- Chọn **Advanced health check settings**

![Practice](/images/15-highlyavailable/15.3-practice/56-practice.png)

57. Trong giao diện **Practice**

- Đọc bước 30 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/57-practice.png)

58. Trong giao diện **Edit health check settings**

- **Healthy threshold  : 5**
- **Unhealth threshold  : 2**
- **Timeout  : 2**
- **Interval  : 5**
- Chọn **Save changes**

![Practice](/images/15-highlyavailable/15.3-practice/58-practice.png)

59. Trong giao diện **Practice**

- Đọc bước 31 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/59-practice.png)

60. Trong giao diện **Auto Scaling groups**

- Chọn **Auto Scaling Groups**
- Chọn **TravelAgencyWebServers**
- Kéo xuống và chọn **Edit**

![Practice](/images/15-highlyavailable/15.3-practice/60-practice.png)

61. Trong giao diện **Practice**

- Đọc bước 32 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/61-practice.png)

62. Trong giao diện **Activity history**

- Bỏ chọn **PublicSubnet1**
- Chọn **PrivateSubnet1**
- Chọn **Update**

![Practice](/images/15-highlyavailable/15.3-practice/62-practice.png)

63. Trong giao diện **Practice**

- Đọc bước 33 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/63-practice.png)

64. Trong giao diện **Instances**

- Chọn **TravelAgencyWebServers**
- Chọn **Networking**
- Review **Subnet ID**
- Chọn **Instance state**
- Chọn **Terminate**

![Practice](/images/15-highlyavailable/15.3-practice/64-practice.png)

65. Trong giao diện **Practice**

- Đọc bước 34 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/65-practice.png)

66. Trong giao diện **Instances**

- Sau vài phút , bấm vào **icon refresh**
- Chọn **TravelAgencyWebServers**
- Chọn **Networking**
- Review **Subnet ID**
- Review **TravelAgencyWebServers** đã **Terminated**


![Practice](/images/15-highlyavailable/15.3-practice/66-practice.png)

67. Trong giao diện **Practice**

- Đọc bước 35 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/67-practice.png)

68. Trong giao diện **Auto Scaling Groups**

- Chọn **TravelAgencyWebServers**
- Chọn **Activity**
- Kéo xuống

![Practice](/images/15-highlyavailable/15.3-practice/68-practice.png)

69. Trong giao diện **Practice**

- Đọc bước 36 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/69-practice.png)

70. Trong giao diện **Auto Scaling Groups**

- Review

![Practice](/images/15-highlyavailable/15.3-practice/70-practice.png)

71. Trong giao diện **Practice**

- Đọc bước 37 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/71-practice.png)

72. Trong giao diện **trình duyệt**

- Chọn **icon refresh**

![Practice](/images/15-highlyavailable/15.3-practice/72-practice.png)

73. Trong giao diện **Practice**

- Đọc bước 38 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/73-practice.png)

74. Trong giao diện **Auto Scaling Groups**

- Chọn **Auto Scaling Groups**
- Chọn **TravelAgencyWebServers**
- Chọn **Edit**

![Practice](/images/15-highlyavailable/15.3-practice/74-practice.png)

75. Trong giao diện **Practice**

- Đọc bước 39 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/75-practice.png)

76. Trong giao diện **EditTravelAgencyWebServers**

- Chọn **PrivateSubnet1** và **PrivateSubnet2**
- Chọn **Update**

![Practice](/images/15-highlyavailable/15.3-practice/76-practice.png)

77. Trong giao diện **Practice**

- Đọc bước 40 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo


![Practice](/images/15-highlyavailable/15.3-practice/77-practice.png)

78. Trong giao diện **Auto Scaling Groups**

- Chọn **Auto Scaling Groups**
- Chọn **TravelAgencyWebServers**
- Chọn **Edit**

![Practice](/images/15-highlyavailable/15.3-practice/78-practice.png)

79. Trong giao diện **Practice**

- Đọc bước 41 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/79-practice.png)

80. Trong giao diện **pop-up**

- **Desired capacity : 2**
- **Max desired capacity : 2**  
- Click **Update**

![Practice](/images/15-highlyavailable/15.3-practice/80-practice.png)

81. Trong giao diện **Practice**

- Đọc bước 42 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/81-practice.png)

82. Trong giao diện **Auto Scaling Groups**

- Chọn **TravelAgencyWebServers**
- Chọn **Activity**
- Kéo xuống

![Practice](/images/15-highlyavailable/15.3-practice/82-practice.png)

83. Trong giao diện **Practice**

- Đọc bước 43 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/83-practice.png)

84. Review

![Practice](/images/15-highlyavailable/15.3-practice/84-practice.png)

85. Trong giao diện **Practice**

- Đọc bước 44 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/85-practice.png)

86. Trong giao diện **Instances**

- Chọn **TravelAgencyWebServers**
- Chọn **Networking**
- Review **Subnet ID**

![Practice](/images/15-highlyavailable/15.3-practice/86-practice.png)

87.  Trong giao diện **Practice**

- Đọc bước 45 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/87-practice.png)

88. Trong giao diện **trình duyệt**

- Chọn **refresh**
- Review

![Practice](/images/15-highlyavailable/15.3-practice/88-practice.png)

89. Chúc mừng người chơi đã hoàn thành bài lab

![Practice](/images/15-highlyavailable/15.3-practice/89-practice.png)

