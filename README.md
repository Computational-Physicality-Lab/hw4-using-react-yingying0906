[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/wH3jFylN)

# hw4-using-react

This is the starter code of [2023-Programming User Interface Homework](https://hackmd.io/@akairisu/ByGFeGdZh)

# 姓名

-   羅寶瑩
-   Po Ying, Law

# 網站連結

> 你 deploy 的網站連結
> https://graceful-parfait-e79644.netlify.app

# 加分作業項目

> 你所實作的加分作業項目，以及如何觸發它

## 新增功能

### Remove All

The "Remove All" button can be used when there are items in the shopping cart. Clicking it will prompt a confirmation message asking if you want to empty the cart. Upon confirmation, all items and accumulated amounts in the shopping cart will be cleared.

![](https://i.imgur.com/Fysb9Dd.gif)

# Specification

> 在前述可任意實作的情況下，你設計的行為，e.g.當使用者離開產品詳細資訊頁面又回來時、當使用者關閉網頁又重開時、當使用者開啟複數網頁時等等

No specification is defined. Each tab operates independently.

# 比較

> 重要：請討論使用 **React** 實作與作業一中使用純 **html/css/JavaScript** 實作有何不同。哪一個比較方便與為什麼？哪一個比較容易理解如何操作與為什麼？哪一個在實作同一個頁面時需要撰寫更多程式碼？

## Convenience (方便性)

I think **React** is more convenient because every component on the webpage is made up of custom components. If you want to edit them, you can directly go to the code of component on that page to make changes.

On the other hand, with **HTML/CSS/JavaScript**, you have to use `getElementById/classname` to access the entire DOM and append it back after making any changes or additions. In **HTML/CSS/JavaScript**, it is important to understand the inheritance relationship of each element, which can be relatively more complicated.

## Comprehensibility (理解性)

As a beginner, **React** may be easier to understand because its JSX syntax is quite intuitive and can be very concise, which increases readability.

However, as someone who has learned **HTML/CSS/JavaScript**, like myself, I find that it takes some time to learn **React**, as the way of thinking is different between them.

Additionally, understanding the behavior of **React** rendering and how to use hooks also requires time to understand.

Overall, **React** is still relatively easy to understand.

## Code complexity and code quantity (程式碼複雜度與數量)

When implementing the same page, **React** code is usually shorter. For example, in the case of a Product Detail page using **HTML/CSS/Javascript**, the elements that need to be generated depend on the user's click behavior, so when generating them, you need to fetch different areas of elements, create new ones, add various attributes to them, and finally append them.

In contrast, with **React**, you only need to define the framework and how to change the state based on the user's click behavior, and the page only needs to generate content according to the latest state. Therefore, **React** can be more efficient in terms of code compared to **HTML/CSS/JavaScript**.

## Conclusion

In summary, I believe the biggest advantage of **React** lies in its component-based structure, which allows for reusability and composition of different components.

Moreover, using **React** makes the code cleaner and reduces confusion when it comes to modification and development.

# 有趣之處

> 其他你所實作的網站的
> N/A

# Reminder

During the implementation, I realized at the very end that I had been pushing to my own GitHub repo all along, so I'll still include the link to my original pushed repo for reference.

https://github.com/yingying0906/SSUI-hw4
