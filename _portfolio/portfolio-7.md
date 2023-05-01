---
title: "SUSTECH Delivery System"
excerpt: "<br/><img src='/images/mt.png' style='zoom:30%'> <img src='/images/kj.png' style='zoom:25%'>"
collection: portfolio
---



As we all know, the canteen of SUSTech has a lot to improve. Therefore, there is a great demand for students to enjoy takeaway(外卖). At the same time, the place of takeaway is very limited. At present, most of the takeout can only be delivered to the school gate, while the students usually study and live in a long distance from the school gate. As a result, there is a high demand for takeaway agent service. At the same time, there are no takeaway websites or applications for students to use. So, in order to solve this problem and help students reduce the time of taking delivery,our goal is to build a website for takeaway.

 Students and faculty members of SUSTech can publish the demand for takeout on this website, and can also receive certain rewards or income by taking orders. In addition, this website also has takeaway collection, takeaway recommendation, friend system and payment system for us to use.



This website serves all students and faculty members of SUSTech. Each user has two identities, **User** and **Manager**. **User** can divide into two roles: one is **server** ,the person who needs to help agent to pick up the takeaway(外卖), and the other is **agent**, the person submit the order. **Agent** posted his/her needs on the website, including takeaway information, takeaway address, delivery address, delivery time, order price and other remarks. **Server** can select the demand and complete it on the website. **Manager** is the administrator of the system,it has privileges that ordinary users do not have, and is able to delete unfriendly posts, manage the ethos of the discussion forum, etc.

###### 

### Order management interface

The order taking page is a very important interface in the campus take-out system, as it directly affects the user experience. This page needs to present clear and easy-to-understand order information, including order number, order status, product information, delivery address and delivery time, etc. We different colors and flags to distinguish the status of the order (e.g., order pending, delivery in progress, completed, etc.). We also provide a nice background for the entire order taking interface to improve the visual experience of the user, and can use the background to stimulate the appetite of the user

To make it easier for riders to take orders, you can provide a public list of issued orders on which everyone can issue orders, so that riders can easily find the orders they need. And we use colorful buttoms to enhance the design of this pickup hall page.

![pc](/images/Delivery/pc.png)

Next is the interface for order management, which has brightly colored buttons to indicate the status of the order, and clear icons to show the real-time status of the delivery shi shi to help the order taker as well as the delivery person to quickly understand the current order information and easily respond, such as completing the delivery order and initiating a private chat.

![mt](/images/Delivery/mt.png)

![mo](/images/Delivery/mo.png)



### Online chat interface:

For the chat interface, we used a simple and clear dialogue bubble design. First, you can easily see who you are chatting with at the top of the chat room after creating a chat link. Once the chat is started, both the user's and the other user's chat messages are wrapped in different colored bubbles for a clear and comfortable look. The chat text input box is at the bottom of the interface, which makes the entire chat sending process look very smooth.

![lt](/images/Delivery/lt.png)



### Recommendation page:

The recommendation page is a very important interface in your campus delivery system because it helps users share information about food, restaurants, delivery, etc. and facilitates communication between users. The page is designed as an easy to use and interactive interface so that users can easily enter the content and posting time of their posts. You can add comments to the page, and other users can post and see everyone's comments and opinions below the post. More compact and properly arranged so that users can quickly locate the information they want. And each post has a picture display function to show the maximum information about the food to attract users

![kj](/images/Delivery/kj.png)



### Scrabble interface:

This interface provides a chunked view, which allows users to see at a glance the current information of the pooling, and can click into the pooling group they need to pool, after clicking into the pooling group can clearly see some information of the pooling, the overall process is very smooth and intuitive, convenient for users to quickly start using

![sh](/images/Delivery/sh.png)



### DataBase Design:

![db](/images/Delivery/db.png)



#### The Tool we use:

###### 1.Springboot  2.Vue2  3.Mysql 4.MongoDB 5.MINIO
