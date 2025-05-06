---
title : "DIY"

weight : 4
chapter : false
pre : " <b> 13.4 </b> "
---

{{% notice info %}}

After completing the lab, the player does **DIY**

{{% /notice %}}

1. In the **DIY** interface

- View **DIY ACTIVITIES**
- View **Solution Validation Method**

![DIY](/images/13-nosqldatabase/13.4-diy/1-diy.png?width=90pc)

2. In the **DynamoDB** interface
- Select **Tables**
- Select **UserVideoHistory**

![DIY](/images/13-nosqldatabase/13.4-diy/2-diy.png?width=90pc)

3. In the **Create item** interface
- Select **Actions**
- Select **Create item**

![DIY](/images/13-nosqldatabase/13.4-diy/3-diy.png?width=90pc)

4. In the **Create item** interface
- In **userId**, enter: ```12345-abcd-6785```
- In **lastDateWatched**, enter: ```1619156407```

![DIY](/images/13-nosqldatabase/13.4-diy/4-diy.png?width=90pc)

5. In the **Create item** interface
- Select **Add new attribute**, then select **Number**

![DIY](/images/13-nosqldatabase/13.4-diy/5-diy.png?width=90pc)

6. In the **DynamoDB** interface
- **Attribute name**, enter: ```rating``` *(note: must be lowercase)*
- **Value**, enter: ```5```
- Select **Create item**

![DIY](/images/13-nosqldatabase/13.4-diy/6-diy.png?width=90pc)

7. In the **UserVideoHistory** interface
- Review

![DIY](/images/13-nosqldatabase/13.4-diy/7-diy.png?width=90pc)

8. In the **Edit item** interface
- **Attribute name**, enter: ```rating```
- Select **Save and close**

![DIY](/images/13-nosqldatabase/13.4-diy/8-diy.png?width=90pc)

9. In the **UserVideoHistory** interface
- Copy the table name ```UserVideoHistory```
- Copy the userid ```12345-abcd-6789```

![DIY](/images/13-nosqldatabase/13.4-diy/9-diy.png?width=90pc)

10. In the **DIY** interface
- Paste the table name ```UserVideoHistory```
- Paste the userid ```12345-abcd-6789```
- Select **Validate**

![DIY](/images/13-nosqldatabase/13.4-diy/10-diy.png?width=90pc)

11. A green message appears: **you did it!..*** indicating completion

![DIY](/images/13-nosqldatabase/13.4-diy/11-diy.png?width=90pc)

12. Select **COLLECT**

![DIY](/images/13-nosqldatabase/13.4-diy/12-diy.png?width=90pc)

13. Congratulations on completing the **First NoSQL Database** lab

![DIY](/images/13-nosqldatabase/13.4-diy/13-diy.png?width=90pc)