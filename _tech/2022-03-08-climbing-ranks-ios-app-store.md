---
layout: post
title: "Climbing the Ranks of the iOS App Store"
description: "Understanding the paths leading to Apple’s top charts."
date: 2022-03-08
feature_image: https://miro.medium.com/max/1400/1*ExQL2D4oM3tYKmEEV2HmOg.gif
tags: []
author: daniel_pickett
share: false
about: false
---

## Understanding the paths leading to Apple’s top charts

Apple’s App Store is a marketplace where anyone can share their software globally, from large corporations to small teams and solo developers. As of September 2021, over 2.2 million apps are available on the App Store.⁸ Meanwhile, the top charts now only showcase twenty apps for each category. This selectivity raises the question of what makes those apps stand out?

Many, including Instagram, Snapchat, and YouTube, are backed by billion-dollar companies, boast a colossal network of users, and have hundreds to thousands of employees building out new features to stay ahead. Yet despite this, smaller teams and even individual developers lacking those resources are still occasionally able to make it to the top charts.

This article will attempt to examine how this all happens, including researching the history of the App Store, showing how it has evolved, and looking in-depth at an example to try to identify patterns in what makes apps popular.

**Table of Contents**

1.  [Evolution of the App Store](#1-evolution-of-the-app-store)
2.  [Learning from Past Developers](#2-learning-from-past-developers)
3.  [Analyzing Paths to Popularity](#3-analyzing-paths-to-popularity)
4.  [Conclusion](#4-conclusion)

# 1\. Evolution of the App Store

![Four variations of the App Store icon over the years.](https://miro.medium.com/max/1166/1*juAqWiFhwOUdIc51HNn2eA.png)

The App Store Icon over the years, Source: [RankMyApp](https://www.rankmyapp.com/market/10-years-of-ios-app-store-history-data-lessons-and-trends/)

The App Store hasn’t always operated the same. It has been around for nearly 14 years since its creation in 2008.¹ It is important to note its evolution as the best way to increase discoverability isn’t the same today as it was in the past, and it will continue to change.

Apple has an archive ([https://www.apple.com/newsroom/archive](https://www.apple.com/newsroom/archive/)) of all their press releases dating back to 2000, searchable by year, month, and topic. This archive is helpful to verify these events as well as find additional information on each of them. Here are some notable milestones.

**2007 —** Apple announced they are building a Software Development Kit (SDK) to allow developers to build applications for the iPhone.¹

**2008 —** The App Store is unveiled with 500 applications.⁶ Apps were either free or installed with a one-time payment.

**2009 —** The ability for developers to add in-app purchases is added.³ This helps apps, especially games, monetize more effectively.

**2010 —** The Mac App Store was created, allowing developers to build and publish apps for Apple computers.⁷

![](https://miro.medium.com/max/1400/1*8uxNvnXgkjcDTihzN4IsEA.png)App Store front page 2008 vs 2012, Source: [MacStories](https://www.macstories.net/links/apples-phill-schiller-on-app-store-curation-and-promotion-for-developers/)

**2013 —** One million apps are available in the App Store.¹¹

**2016 —** Apple Search Ads allows for paid advertising in the App Store. Developers can pay directly for downloads or to appear in search results.⁵

**2017 —** App Store major design changes are implemented. An affiliate program is created which allows people to refer others to apps and get a 7% commission on sales.⁹

![](https://miro.medium.com/max/1400/1*lIvDchv8nu6S_j3GmAP1PA.png)App Store 2017 redesign, Source: [Apple](https://www.apple.com/newsroom/2017/06/apple-unveils-all-new-app-store/)

**2019 —** The App Store facilitated $519 billion in global sales in 2019.⁴

**2020 —** Total sales grew to $643 billion for 2020.² Apple introduced a small business program lowering their cut from 30% to 15% for apps with less than $1 million in annual revenue.

It’s clear how quickly the App Store has changed over time. New features implemented by Apple can change how apps are discovered and installed. For example, Apple Search Ads introduced in 2016 are still widely used today [(https://searchads.apple.com](https://searchads.apple.com/)). While other features, such as the affiliate program, were discontinued shortly after being introduced.

Another crucial area constantly changing is the app approval process. Apple consistently updates its terms on what is and is not allowed within an app. After developing an app, it can’t be released directly to the store. Instead, Apple will take several days to review the app and ensure it follows the guidelines and doesn’t serve a malicious purpose. As new policies are introduced, many older apps are removed.

# 2\. Learning from Past Developers

![Flappy bird gif moving between the pipes.](https://miro.medium.com/max/1400/1*Q8f5FCSQe37-lnaMDLLFyw.gif)Source: [Julio Bohigues](http://illuecaesdiferente.blogspot.com/2017/02/ejercicio-11.html)

Despite the difficulty of navigating this ever-adapting space, and fortunately for anyone looking to create the next successful app, it has been done and documented many times before. Developers often create blogs and videos describing their challenges and success. This section will attempt to summarize and showcase one of these stories.

It’s important to note that depending on the type of app, the skills, experience, and resources necessary to create it can vary drastically. Video hosting, for example, is notoriously expensive, and many types of apps leveraging this are out of reach for even most startups. In contrast, single-player games can be relatively easy to program, and there’s an abundance of tutorials around the internet walking through examples. Unfortunately, however, games are also the most saturated category in the App Store.

![](https://miro.medium.com/max/1400/1*V6OiWamiurvwX25qdKm5mA.png)
Top ten App Store categories by share of availability, June 2021 Source: [statista](https://www.statista.com/statistics/270291/popular-categories-in-the-app-store/)

Games can be easy to create, but creating a good game interesting enough to stand out from the hundreds of others released every day is not. However, for an app to reach the top charts, it doesn’t necessarily have to be the best. The app I want to discuss further in this section is _Frantic Architect_. This highly simplistic mobile game released in 2016 was created by a college student and amassed around 350k downloads in a week before quickly fading out of popularity.¹²

In some ways, this app was a success for receiving hundreds of thousands of downloads (as any developer would want), but in other aspects, it wasn’t. Regardless, there’s a lot to learn from its story of rapid growth and decline.

**Frantic Architect**

![](https://miro.medium.com/max/1200/1*lVt7odaTcxD8YEcunySbBQ.gif)
Frantic Architect Gameplay, Source: [BulkyPix](https://www.youtube.com/watch?v=hkLiQ17KNRE)

The app is simple. An indicator moves around random positions, and the user can tap the screen to place a block there. The player can continue stacking blocks to build a tall tower until the structure loses balance and collapses. The game is free and profits from advertisements.

The developer, William Kwan, is extremely transparent in explaining this app’s story, despite moving on from the project. He states that he created the prototype in only one day. Unity, the game engine, handles all of the physics, meaning he just needed to program the placement of the blocks and the user interface.¹²

He then sent off his prototype to a publisher called BulkyPix. The idea of a game publisher is to team up with developers and provide specialized knowledge to release and market their game while, in return, taking a share of the profits. The largest mobile game publisher today is [Voodoo](https://www.voodoo.io/games). Their apps have received over [5 billion](https://blog.voodoo.io/articles/5-bn-downloads) downloads. A publisher is an entirely optional step to take. In this case, the publisher accepted the game, and shortly after releasing it, Apple had featured the game on their front page.

![](https://miro.medium.com/max/1400/1*2NiNLElSfh_FYDzQTIEKLw.png)Frantic Architect downloads over time, Source: [William Kwan](https://www.freecodecamp.org/news/how-my-mobile-game-got-365k-app-store-downloads-in-2-weeks-and-why-i-quit-indie-game-dev-a3ebd1fa3229/)

This led to a massive influx of downloads. The app made it to the top charts, but even at its peak was only generating a few hundred dollars a day as the only monetization was the occasional ads. Furthermore, since there’s not much to the game, the retention was low, and the downloads started plummeting just as quickly as they had grown. The developer, a college student at the time, had other things to focus on and wasn’t interested in working on it anymore. A few months later, the publisher BulkyPix declared bankruptcy, and the app was removed from the App Store.

The app’s quick rise to popularity was derived entirely from Apple’s feature. It was even released in the Google Play Store simultaneously but was never featured and only totaled 3,817 all-time downloads.¹²

But receiving this feature from Apple and even having hundreds of thousands of users wasn’t enough. The story of this app, from start to finish, helps showcase that the perceived value of reaching Apple’s top charts can be misleading. William Kwan, the developer, stated this:

> Too many people look at the apps at the top of the App Store and mistakenly think that those are the the most successful. But targeted customers are worth way more than random customers, and the businesses which understand this are the ones worth learning from, even if they aren’t in the spotlight.

Being in the top charts doesn’t guarantee anything more than a temporary boost in downloads; Even then, it doesn’t lead to targeted downloads, as stated above. It can certainly be helpful to grow, but if the actual app doesn’t consistently provide value, then the growth won’t be sustainable.

# 3\. Analyzing Paths to Popularity

![A graphic of various interconnected screens and apps.](https://miro.medium.com/max/1400/1*1WtezW33XneJJnGiUbXKQQ.gif)Source: [Apple](https://www.apple.com/ca/newsroom/2021/04/apples-ios-app-economy-drives-economic-growth-and-opportunity-across-canada/)

Developing a useful app that does provide value is difficult. It often requires intermediate to advanced programming knowledge and knowledge of design tools to build out the user interface. Combine this with marketing experience so people can find and install it, and it becomes clear that creating a successful app requires an extremely diverse skill set.

This is why many, such as the developer of _Frantic Architect,_ are drawn to publishers and seek outside help when it comes time to release. But publishers will only take on a handful of apps, and many developers don’t want to give up ownership or be locked into a contract, and for a good reason. After the publisher for _Frantic Architect_ declared bankruptcy, the developer never received any of the ad revenue.

It’s useful for developers to understand how to position their app to increase visibility. For example, developers can build specific features into their apps to make them more shareable. Binh Dang, head of App Store Optimization at a publishing company, states that organic growth is most effective when the users themselves are the facilitators.¹⁰ All of the biggest social networking apps, such as Snapchat, Facebook, and Instagram, have features like this. For example, these apps will connect with your contacts and show you friends that haven’t installed them yet, prompting you to invite them. Features like this can lead to organic growth and scale in effectiveness as more users join.

**Purchasing Ads**

Purchasing ads is another way to find potential users. Social media sites such as TikTok, Facebook, Snapchat, and more all have advertising platforms that allow people to promote their app or any product. Some apps even choose to pay individual influencers directly for promotion. Effectively purchasing these ads is an entire topic of its own, but the standard metrics across all advertising platforms tend to be cost per install (CPI) or cost per mille (CPM), which is the cost per 1,000 impressions.

A conversion rate is calculated to find the percentage of impressions that convert, or in this case, lead to an install. A higher conversion rate indicates a more effective ad, and targeted ads tend to have higher conversion rates. Going back to the topic of Apple’s changing guidelines, recently, Apple has given users more control over their data. The prompt seen below enables users to opt-out of data tracking, making ads less effective and therefore more expensive but improving user privacy.

![The prompt asking iPhone users if they would like to be tracked.](https://miro.medium.com/max/1400/1*OFjGHPOYQZd4tHbkUncUMw.png)Source: [Mahmoud Itani](https://www.xda-developers.com/apple-app-tracking-transparency-policy-hurting-platforms/)

The final example of a step that app developers can take is applying directly to Apple to be featured. It’s in Apple’s best interest for its developers to be successful, and part of this is highlighting valuable apps. Developers can apply by signing into a developer account here ([https://developer.apple.com/contact/app-store/promote/](https://developer.apple.com/contact/app-store/promote/)).

![](https://miro.medium.com/max/1400/1*s49qa013Dyh9dqk_Ac6drw.png)Feature Apps Page, Source: [appfigures](https://appfigures.com/resources/guides/how-to-get-featured-app-store)

Filling out a few text fields about the app’s details, the marketing plans, and the story behind it is all it takes to have a shot at being featured. They even give guidelines on what they are looking for, ranging from high-quality UI to supporting multiple languages, no publisher or marketing team necessary.

# 4\. Conclusion

![A graphic showing a few people interacting with an app.](https://miro.medium.com/max/1400/1*GB1gsksb7hApamR1QKJqPQ.gif)Source: [Apple](https://www.apple.com/newsroom/2021/06/apple-developers-grow-app-store-ecosystem-billings-and-sales-by-24-percent-in-2020/)

There are specific steps that developers and small businesses can take to help position their apps to grow. But most importantly, it has to be exciting and valuable enough to retain some number of these users. Being in the top charts is not necessarily something to strive for, but instead creating an experience that users enjoy and benefit from, which will prompt them to share it on their own. Each time a new app moves into the top charts, another must fall from it. As recent trends emerge, there will always be apps that cycle in and out of popularity. It’s the apps that provide real value that can hold their place among the top charts.

---

\[1\]: Apple. “Apple Announces IPhone 2.0 Software Beta.” Apple Newsroom, December 2, 2021. [https://www.apple.com/newsroom/2008/03/06Apple-Announces-iPhone-2-0-Software-Beta/.](https://www.apple.com/newsroom/2008/03/06Apple-Announces-iPhone-2-0-Software-Beta/.)

\[2\]: Apple. “Apple Developers Grow App Store Ecosystem Billings and Sales by 24 Percent in 2020.” Apple Newsroom, December 2, 2021. [https://www.apple.com/newsroom/2021/06/apple-developers-grow-app-store-ecosystem-billings-and-sales-by-24-percent-in-2020/.](https://www.apple.com/newsroom/2021/06/apple-developers-grow-app-store-ecosystem-billings-and-sales-by-24-percent-in-2020/.)

\[3\]: Apple. “Apple Previews Developer Beta of IPhone OS 3.0.” Apple Newsroom, December 2, 2021. [https://www.apple.com/newsroom/2009/03/17Apple-Previews-Developer-Beta-of-iPhone-OS-3-0/.](https://www.apple.com/newsroom/2009/03/17Apple-Previews-Developer-Beta-of-iPhone-OS-3-0/.)

\[4\]: Apple. “Apple’s App Store Ecosystem Facilitated over Half a Trillion Dollars in Commerce in 2019.” Apple Newsroom, December 2, 2021. [https://www.apple.com/newsroom/2020/06/apples-app-store-ecosystem-facilitated-over-half-a-trillion-dollars-in-commerce-in-2019/.](https://www.apple.com/newsroom/2020/06/apples-app-store-ecosystem-facilitated-over-half-a-trillion-dollars-in-commerce-in-2019/.)

\[5\]: Apple. “Search Ads Now Available.” Apple Developer, September 28, 2016. [https://developer.apple.com/news/?id=09282016a.](https://developer.apple.com/news/?id=09282016a.)

\[6\]: Apple. “The App Store Turns 10.” Apple Newsroom, December 2, 2021. [https://www.apple.com/newsroom/2018/07/app-store-turns-10/.](https://www.apple.com/newsroom/2018/07/app-store-turns-10/.)

\[7\]: Bilton, Nick. “Apple to Open Its Mac App Store in January.” The New York Times, December 16, 2010. [https://bits.blogs.nytimes.com/2010/12/16/apple-plans-mac-store-opening-in-early-january/.](https://bits.blogs.nytimes.com/2010/12/16/apple-plans-mac-store-opening-in-early-january/.)

\[8\]: Ceci, L. “Number of Apps Available in Leading App Stores 2021 .” Statista, September 10, 2021. [https://www.statista.com/statistics/276623/number-of-apps-available-in-leading-app-stores/.](https://www.statista.com/statistics/276623/number-of-apps-available-in-leading-app-stores/.)

\[9\]: Clover, Juli. “Year in Review: Everything Apple Introduced in 2017.” MacRumors. MacRumors, December 28, 2017. [https://www.macrumors.com/2017/12/28/everything-apple-introduced-in-2017/.](https://www.macrumors.com/2017/12/28/everything-apple-introduced-in-2017/.)

\[10\]: Dang, Binh. “What’s the Deal with Viral Apps?” Medium. Start it up, January 5, 2021. [https://medium.com/swlh/whats-the-deal-with-viral-apps-79a41bf75ca5.](https://medium.com/swlh/whats-the-deal-with-viral-apps-79a41bf75ca5.)

\[11\]: Ingraham, Nathan. “Apple Announces 1 Million Apps in the App Store, More than 1 Billion Songs Played on ITunes Radio.” The Verge. The Verge, October 22, 2013. [https://www.theverge.com/2013/10/22/4866302/apple-announces-1-million-apps-in-the-app-store.](https://www.theverge.com/2013/10/22/4866302/apple-announces-1-million-apps-in-the-app-store.)

\[12\]: Kwan, William. “How My Mobile Game Got 365K App Store Downloads in 2 Weeks (and Why I Quit Indie Game Dev…” freeCodeCamp.org. freeCodeCamp.org, November 19, 2017. [https://www.freecodecamp.org/news/how-my-mobile-game-got-365k-app-store-downloads-in-2-weeks-and-why-i-quit-indie-game-dev-a3ebd1fa3229/.](https://www.freecodecamp.org/news/how-my-mobile-game-got-365k-app-store-downloads-in-2-weeks-and-why-i-quit-indie-game-dev-a3ebd1fa3229/.)
