**Final Team Name**

YCC

**POV**

- Contains user, need, and inspiration?
- Unique?
- Non-trivial?

Users: Family Visitors to KAIST for various purposes.

Need: Location of landmarks of KAIST, the location to satisfy of specific needs such as visiting toilets or having dining and where is the department they are looking for if they stop by KAIST to visit there.

Insight: we need to provide information about landmarks, what are inside a specific building and detailed information on most things that are people are expected to want to know. Also we might try to make a list of department in the building and provide a search tool to help some users satisfy the visiting purposes.

**Persona**

- Concrete demographic information?
- Photo or image?
- Motivations, beliefs, preferences, and goals?
- Brief story or scenario?

![figure1](https://raw.githubusercontent.com/JaeRyoungKa/CS374_image/master/3741.png)

Demographic information: Koreans who live in nearby KAIST. They are one family, consisting of age from 4 to 70.

Motivations: They visit KAIST to submit admission documents for their son, and after that they are very excited about their plan where they&#39;ll enjoy the cherry blossom of KAIST main campus to make memorable experience.

Beliefs: They firmly believe that a helper tool will help them find the wanted places and enjoy cherry blossoms.

Preferences: They so love the Dunkin Donuts that their journey should have one or more visits to there.

Brief Story: Our persona is family visitors, who visit KAIST to submit something and enjoy excursion. They are expected at first to want to know where is a parking lot near the Admission Team. After submitting that, they will be longing to know what places are renowned for watching. As time goes by enjoying cherry blossom, they would also want to know somewhere to satisfy specific needs such as toilets, dining places and so on, especially Dunkin Donuts.

**7 HMW Questions**

- 10+ HMWs submitted?
- Scope not too broad or narrow?
- Distinct, broad, and creative?

HMW make it online on map.kaist.ac.kr to make it accessible on every visitor easily?

HMW provide some suggested routes traveling here?

HMW place functions on a chronological order by expecting what a person might experience as time goes by?

HMW try to instantly change the altered information to make less confusion of visitors?

HMW use API of NLP and ML to translate what a user speaks to what a user needs?

HMW firstly make it on web and transport into app if lots of users use it?

HMW let them know whether they can enter the specific building?

**Ta-Da! Top 3 HMW Questions and why we chose them.**

- Selection process clearly described?

We chose top 3 HMW Questions with the following criteria:

- --Can we export many useful solutions from it?
- --Is it not too specific?
- --Does it represent our team&#39;s emphasized values?

HMW help them reduce annoyingness and save bother during the visit?
- People can be confused in the situation like this where they are visiting unfamiliar place. Also people usually want to reduce bothers like unwanted time waste. We have value that saving bother in the modern people who lacks time is important; It will be nice if we can realize the value using our service.

HMW give visitors what is inside the building?

- some visitors visit KAIST to stop by some departments in it. They may have hard time even after the entrance; Where is the department we&#39;re looking for? Where&#39;s caf? or toilet to solve the specific needs? Once they enter the building, the information of the building would be a good usher to explore it. Furthermore, some departments close early or does not open in some special day, which is vary between departments. so noticing that would be important to prevent users from returning home without fruits.

HMW capitalize on existing good services in both non-technical and technical sides?
 - We enjoy technically challenging experience and think using it would be proper way to improve our service. It also would be a good chance to practice HCI knowledge we&#39;ve learned in this class or CS one we&#39;ve learned in KAIST.

**9 Solutions for Each HMW**

- 10+ solution ideas submitted for each HMW?
- Distinct, broad, and creative?

- Recommend pre-set travel paths for excursion.
- Provide a detailed map inside the building.
- Provide a search tool where map-user interaction occurs.
- Mark the location of transportation tools such as bicycles and OLEV.
- Use Daum/Naver Map API to show the shortest way towards their goal from current position.
- Provide weather information on map so that they can prepare for it.
- Provide the timetable of external shuttle bus.
- Show opening/closing hours of each building tenants to prevent visitors from returning their home with no fruits.
- Check whether there is taxi besides E7-3 building to provide more comfortable experience of going back home.

- Provide a web link towards a proper site to elicit better understandings. (such as cs.kaist.ac.kr)
- If one cannot enter somewhere as a visitor, alert that.
- Show the list of departments in that building.
- In the list of departments in the building, show whether they&#39;re closed or not as of current time.
- If the visit is pre-planned, get the date of visit and alert that if the department is to be closed at the day of visit.
- Locational information of EV should be provided in order to make people move faster without much effort.
- If there is store(s) inside the building, (such as N1, E7-1) let them know on them.
- If available, provide phone number of each department in it to help them directly contact to it.
- Consider make it automatic by getting user&#39;s device location.

- We may make the use of KAIST bus web to save our bother to develop some functions of our map.
- In that aspect, นได๋ปý would be the great app to show information on restaurants.
- On returning home, Kakao Taxi app would be good again to provide refined experience.
- Use the Android/iOS tracking location services to provide exact locational information.
- Capitalizing on some renowned tools and services, we may get some data to get more accurate user pattern and by using it on Machine Learning we could provide better experience on both using map and also visiting KAIST.
- We may use statistical tools/services to keep track of how many people visit us and how long they use the map.
- make use of javascript library (such as Jquery)
- we may consider using Node.js and MongoDB and their byproducts to constitute the server part.
- frontend may be coded and delivered in ejs format, capitalizing mostly on the strength of node.js.

**TOP 3 Solutions and why we chose them, and storyboard**

- Selection process clearly described?
- 3 storyboards submitted?
- Flow easy to follow and understand?
- Easy to read (thick pen used)?
- Not solution-driven but user- and scenario-driven?

We chose our TOP 3 solutions by following criteria:
- Does it represent our team&#39;s emphasized values?
- Does it solve problems with strong impact?

Mark the places where they can enter.
- Many, many KAIST students are repeatedly talking about it. They really want to draw the line between where outsiders enter and cannot enter; We may contribute to student society by partly solving it, what is one of our emphasized value, by providing the possibility of enter on the map.

![figure1](https://raw.githubusercontent.com/JaeRyoungKa/CS374_image/master/3742.png)

Provide information about the location of convenient facility (toilet, place for caring baby, and so on).

- --According to our interview, many people are longing for the convenient facility such as toilet. Although it is not true that most people&#39;s main visit purpose is using that facilities, however, without it we cannot satisfy our human&#39;s basic needs.
- --
![figure1](https://raw.githubusercontent.com/JaeRyoungKa/CS374_image/master/3743.png)

Using Map APIs to help find the shortest way towards their goal will be fine.

- --Capitalizing on our technical competence, we may make users convenient by recommending shortest path toward their goal. Direct implementation would be difficult for undergraduates, so we would use APIs supported by many internet companies.

![figure1](https://raw.githubusercontent.com/JaeRyoungKa/CS374_image/master/3744.png)


**Studio Reflections**

- Is feedback well summarized?
- Is feedback addressed, or is the plan for addressing feedback concrete?

We have six feedbacks, and following things are how we addressed that:

1. Using thick pen: We re-drawn cartoons with a think pen.

2. Solutions are not related to family: Thanks for your opinion. We&#39;re looking for new features to make family visitors more convenient as of now!

3.make the solutions more suitable to web: We&#39;ve got it. Our future prototype will be more suited for web environment.

4.places for baby: We added that in the needs and solutions.

5.narrow down persona: We fixed that problem, writing more detailed version of persona.

6.parking information: That&#39;s a good idea. We&#39;ll show parking lots when we actually implement it.