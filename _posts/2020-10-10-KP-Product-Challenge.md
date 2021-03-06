---
title: "Kleiner Perkins 2021 Product Fellowship — Bitesnap, Photo Food Journal"
tags: products
---

When I finally graduated in April 2020, like every other student I had to take the graduation pictures. Meanwhile, the COVID-19 pandemic was rising in New York and it was definitely not easy to find a photographer during such times. However, something even more difficult was to look at those pictures the day after. Transferring from a community college to an Ivy League and wanting to graduate just in 2 years while being a startup founder, I spent most of my time sitting in a library, without any physical exercise, and with unhealthy food habits. When I looked at those pictures, I finally became aware of the 23 pounds that I gained over the last two years. Before transferring to Columbia, I was playing college football and probably I was at the peak of my shape. Now, it was the opposite and I had to take my body back.

Having been an athlete for most of my life, I had a lot of knowledge about nutrition. I was not going to follow any specific diet, but just eating fewer calories than the ones I burned. After I calculated my TDEE[[Total Daily Energy Expenditure::lsn]], I know I just had to eat less than 1300 calories to lose weight. You do not need any other special or trendy technique.  [It is so simple, but where many people fail is to accurately track calories.](https://physiqonomics.com/eating-too-much/ "Physiqonomics' Article about Tracking Calories")

For the first month of my diet, I was using traditional fitness apps: MyFitnessPal and LoseIt. However, I quickly noticed that there was much unreliable information about the calories of the food I was eating. Without accurate tracking, my plan was going to fail: I needed to find a more reliable tool. I started to try every possible fitness and calorie tracking app. One day, while reading Hacker News, I found an article about "Deep Learning Meets Food Logging". At that moment I discovered Bitesnap, but I never imagined that would be the most useful app that will lead me to lose 25 pounds in 2 months.

---

## Table of Contents

- [[What is Bitesnap?::#what]]
- [[Why am I obsessed with Bitesnap?::#why]]
- [[What can be improved?::#improvements]]
- [[Conclusion::#conclusion]]


---

{:#what}
## What is Bitesnap?

![Logo](/assets/img/kp-challenge/logo-with-text.png)

Bitesnap is a mobile app that uses deep learning to recognize food in your pictures and automatically calculate calories and nutrients. 

There are three main features that Bitesnap offers to its users:
1. **Logging a meal by just taking a picture** — When taking a picture of the food through the app, it suggests you on what you are eating and automatically find all the calories and nutrients of that food — the process does not take more than 10 seconds.

2. **Explore eating patterns visually** — There are two visual ways that Bitesnap shows eating patterns to the users. The first is through the photo journal, which a user can visualize by scrolling the homepage and seeing all the meals they had in the past days. The second is through the data charts available in the menu, where a user can look not only at the calories they had in the past days, but also at the amount of protein, fiber, vitamin D, and every other possible nutrient.
a
3. **Personalized Predictions** — Bitesnap uses machine learning to customize itself for each user. This means that the app visually learns the user's habits over time, and it is able to provide predictions on what the user is eating. In fact, the more the user uses the app, the better the algorithms become at identifying the food in the pictures.

---

{:#why}
## Why am I obsessed with Bitesnap?

![Bitesnap uses deep learning to recognize the food in the picture](/assets/img/kp-challenge/bitesnap-og-image.jpg)

I have been using MyFitnessPal for over 3 years. After, I switched to LoseIt for 2 years. However, it took me one day of using Bitesnap to make me switch to this app without absolutely any single doubt. At the time I'm writing this article, I have lost 25 pounds in two months. While my motivation and discipline played an important role, I would have not been successful with my strategy if it was not for Bitesnap. I identified two main reasons why, out of thousands of calorie-tracking apps that have hundreds of employees and years of development, I stuck with Bitesnap, built by just two people a few years ago.

#### It does the most important thing, and it does it seamlessly.

![Most used features of MyFitnessPal through user interviews, by uxdesign.cc](/assets/img/kp-challenge/screenshots.jpg)

When I found MyFitnessPal, I just wanted to track my calories. I downloaded it because it was the most popular one. However, every time I was opening the app I had to go through the "Blog", the "Water Log", the "Exercises" and much more. I had to click a few buttons and spend more time than I wanted just to add what I ate that day and how many calories I still have left. The second most important thing for me was to track the number of carbs because I did not want to eat more than 35% of carbs during a day. It was so hard to find how to visualize my macro, that for the first months I believed MyFitnessPal did not have such a feature.

After a long pause, I started a ketogenic diet and I needed to track my food again. This time, I was done with MyFitnessPal's User Experience, and I wanted something simpler, that would not steal more than five minutes of my day. I found LoseIt, which had a much quicker experience to add new food. With just two clicks, I was able to add what I ate directly from the homepage. There were other features such as exercise and waterlog, but they were hidden or not on the homepage. However, the business model of LoseIt was terrible for me: to look at some data, you needed to buy the subscription. The worst thing is that one of the data restricted for the premium users was the macronutrients! I was unable to see how many carbs, proteins, and fat I was eating each day, and that was a huge limit, especially when doing a ketogenic diet [[A ketogenic diet consists of reducing the amount of carbohydrate intake to less than 50 grams a day.::rsn]]. As with MyFitnessPal, I struggled to be consistent and I found myself forgetting to use the app over and over again.

When I downloaded Bitesnap, I was amazed by how everything I needed was right there where I wanted it: the first two things that appear on the main screen are calories and macronutrients. It is a simple and intuitive UI that gives me all the information I want in the quickest way possible. An important thing to consider for calories tracking app is that users want to use them as less as possible: tracking calories can already be a time-consuming activity, and users need a quick and seamless experience just to find out how much left they have to eat; they do not want to spend even more time just add a food item on an app, or go through dozens of features they are never going to use it.

With Bitensap, I open the app, click on the camera, take a picture of the food, and confirm. I was a skeptic on the deep learning, but in two months I only had one or two meals not recognized. Surprisingly, it was able to recognize the meals even under poor light conditions or slightly blurry pictures. I was looking for a tool to track calories, and Bitesnap does it, most quickly and seamlessly.

#### I can trust its accuracy.

![In the homepage you can keep track of your calories and macronutrients](/assets/img/kp-challenge/product-2.jpg)

Back when I was tracking my calories with MyFitnessPal or LoseIt, I was always double-checking the calories that the app was telling me with some reliable source online. This is because both apps use a crowdsourced database, where everyone can create a meal with its information and add it to the database. Therefore, when I am adding a food item, it is possible that I'm using one added by another person, and that's not always reliable. For this reason, I had to double-check online (and therefore wasting more time), and I was always adding ~100 calories to my total at the end of the day, to capture any miscalculation and underestimation. 

Bitesnap does not use crowdsourcing: instead, it only retrieves food nutritional facts from official databases, such as the governmental USDA FoodData Central. When I take a picture of the food and the app understands which one is it, I just need to confirm its quantity. I do not need to double-check or adjust the nutritional facts. At the end of the day, I'm completely confident of how many calories I ate [[And, as we have seen in the article linked in the introduction, this is one of the most common mistakes people do when tracking calories.::rsn]], and what are my macronutrients percentages. 

While the lack of crowdsourcing can be perceived as a limiting factor, I would say that it has been the main reason why I stuck with Bitesnap. Crowdsourcing helps to have every information about every single item, while official databases have information only about the most common food. They do not have the nutritional facts about some south Asian traditional dish or northern Italian home-made recipe, but if you use crowdsourcing, someone will be adding them. However, that was not what I needed: I needed a reliable source of information. When Bitesnap does not have a specific food item (it did not happen more than eight items in the last two months), I can easily create a new one, manually adding the nutritional facts. That item is not shared with other people, so that when you search you can only find food information from the official databases or the ones you created. Most importantly, official databases provide additional facts such as vitamins, minerals, caffeine, etc. This is a gamechanger because until now I was only able to track calories.; however, I had no idea about the vitamins that I was lacking or the amount of caffeine drunk each day. That is because when you use crowdsourcing, people do not insert that information when adding a new item. With Bitesnap, I can look at the number of vitamins I'm eating each day, I can instantly see any lack through data charts, and I can set daily targets for those more specific nutritional facts. Being all retrieved from the official governmental database, I feel confident about its accuracy.

---
{:#improvements}
## What can be improved?

![Bitesnap's UI when adding a food item](/assets/img/kp-challenge/screenshot-feed.jpg)

#### Crowdsourced Barcode
While it has been inserted in the most recent update, the feature of scanning the barcode does not work consistently with many items. One should not use deep learning for packaged food: it is not only stupid, but it can also return the wrong predictions. While it is important to not have a crowdsourced database for general food items, it is different for the items that have been scanned through barcodes. In fact, it can be useful to have a shared database with such items, where the nutritional facts are not manually inserted by the user but retrieved by official sources. Instead of adding all the products manually, users will add them when scanning through with the barcode: in this way, if now I'm eating a Snickers, I can just search it and find it if someone else already scanned its barcode. Scanning barcode is not a funny experience after the first time, so it is important that Bitesnap does not stress the user requiring him to scan every time an item that has already been previously scanned by other users.

#### Additional Serving Sizes
One of the only things that deep learning cannot accurately predict [[For now.::rsn]] is the quantity of the food. There are way too many difficulties to understand how much of an item is present on a picture, so you often have to set it yourself. Bitesnap does a good job with predictions so that most of the time it already suggests you the right size. However, the serving sizes are often limited to a metric that users cannot be familiar with. In my example, as a European, I have no idea how much one ounce is. While I understand that these measurements are probably obtained directly from the official databases, they can be easily converted into other measurements. This is critical if the app wants to expand to other states or nations, where people are used to measuring food with different scales or countries use a completely different metric system.

#### Goal-Oriented UX
I would assume that a significant percentage of users who are active on a calorie tracking app have goals and objectives they want to achieve in terms of nutrition. Whatever this is losing weight, gaining muscle, or eating more healthy. The app is tackling this need in two ways: the *challenges* and the *nutrition goals* features. However, both of them are underwhelming and have a lot of room for improvement.
The *challenges* feature offers only one challenge that consists of tracking your meal seven days in a row. Even after you completed it, the challenge does not get more difficult, and you can only repeat the same one.
The *nutrition goals* let you set what is the amount of quantity you want to get each day for each nutrient: proteins, carbs, but also riboflavin, vitamin C, and everything else you can think of. While this sounded amazing for me when I was trying to track my Vitamin B12 intake, I found myself never looking at the feature anymore. To look at the nutrients you are eating every day, you need to navigate to a slightly hidden menu, find the data charts of all the nutrients, and see much you are getting every day for each of them. I do not receive any notification about my intake, and I need to spend a lot of time during the day to understand what I'm missing, but also to find online the food that can provide me with what I'm lacking.
The improvement of both features can be extremely helpful to help users achieve their objectives. The *challenges* and *nutrition goals* features can be combined in the same one, which consists of weekly goals that you can set for yourself. In this way, they would be meaningful ones that the user cares about and is trying to accomplish. These challenges can be calories intake, the limit of sugar consumption, caffeine threshold, and much more. The app can also use the data of the user to suggest during the day what food he can eat to reach his goal. For example, if a user often ate salmon the previous week and today he is far from his protein intake goal, the app can send a notification before dinner, suggesting that he could eat two fillets of salmon to get 30 grams of proteins and reach his goal.

---

{:#conclusion}
## Conclusion
![Main menu of Bitesnap](/assets/img/kp-challenge/finalpic2.jpeg)

Bitesnap has been the most accurate and user-friendly calorie tracking app I used. It helped me a lot to track my calorie intake in the last two months where I lost 25 pounds. Most importantly, I did not spend more than 3 minutes a day to track the food. This is exactly what I was looking for. It is obvious how Bitesnap has been customer-obsessed during their development: the UI is extremely intuitive and all the numbers are where you expect them to be; also, there aren't any features you probably are not going to use. Because I am not active on Instagram and I rarely post pictures on Facebook, at first I thought I would never use the photo journaling feature of the app. Instead, after a few weeks, I found myself looking at what I ate days ago and wandering through the beautiful memories I had that day. I realized how powerful it is food when remembering experiences and moments. However, while some other features have a lot of potentials, they seem underdeveloped and hidden from the user's experience: as a calorie tracking app, it is critical to support and help the user's nutrition objectives. Also, to support the growth of the app, it is important to be considerate of the different serving sizes that other countries use. Last but not least, the app is free and still does not have a business model — it is decisive to develop a monetization that does not interfere with what is the most powerful aspect of Bitesnap: user-friendliness.