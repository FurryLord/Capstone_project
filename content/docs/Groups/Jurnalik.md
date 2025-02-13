# Week 1
## **Team Formation and Project Proposal**
### Team Members

| Team Member        | Telegram ID                                          | Email Address                       |
| ------------------ | ---------------------------------------------------- | ----------------------------------- |
| Nikita Semeritskiy| [@FatM1nd](https://t.me/FatM1nd)                 | n.semeritskiy@innopolis.university      |
| Nikita Fedorovich    | [@Fedorovich_Nikita](https://t.me/Fedorovich_Nikita) | n.fedorovich@innopolis.university     |
| Yana Pavlova| [@pavlova_yana_1](https://t.me/pavlova_yana_1)                   | y.pavlova@innopolis.university     |
| Valeria Kharina    | [@exemplerie](https://t.me/exemplerie)                     | v.kharina@innopolis.university     |
| Dilyara Farkhutdinova| [@d_farkhutdinova](https://t.me/d_farkhutdinova)| d.farkhutdinova@innopolis.university |
| Oksana Konovalova   | [@ksko02](https://t.me/ksko02)     | o.konovalova@innopolis.university    |
| Adelina Kildeeva   | [@yumiue](https://t.me/yumiue)     | a.kildeeva@innopolis.university    |

### Value proposition

**Jurnalik** is a mobile application, an electronic "**newspaper**" that collects and provides the user with the latest news, posts and photos from their social networks, news channels and subscriptions. The main purpose of the project is to solve the problem of **information overload** and inefficient use of users' time in social networks. We strive to provide a convenient and unique resource that allows users to **focus** on each piece of content, **avoid holding back algorithms** and get only the most important information.

Our app provides several benefits. Firstly, it helps users reduce the time they spend on social media by limiting the information they publish and consume. This allows users to be more focused and concentrated on the topics of interest to them. Secondly, the app provides protection from corporate retention algorithms by offering a more independent and objective source of information. Finally, our app offers users a lot of interesting content and news tailored to each user, allowing them to stay up-to-date with the latest news and events of interest.

Users of our app will enjoy several benefits. Firstly, they can manage their time more efficiently, avoiding endless scrolling and information overload in social networks. They will only receive information that is relevant and interesting to them. This contributes to increased productivity and focus in users' daily lives. In addition, users will have access to varied and high-quality content selected specifically for them, allowing them to stay up-to-date with the latest news and events of interest.

Our application differs from competitive solutions in several aspects. Firstly, we offer a unique combination of collected content, combining it from various sources of the user. This creates a more complete and comprehensive picture of what is happening. In addition, we focus on personalisation of content for each user, which creates a unique and optimised user experience. Our app also protects users from retention algorithms, which sets it apart from social media platforms.

Our project is expected to have a positive impact on users and stakeholders. Users will be able to manage their time more efficiently by avoiding endless scrolling and information overload on social media. They will only receive information that is relevant and interesting to them. This contributes to increased productivity and focus in users' daily lives. In addition, users will have access to varied and high-quality content tailored specifically to them, allowing them to stay up-to-date with the latest news and events of interest. Our app also provides an independent and objective source of information

## **Lean Startup Questionnaire**

1. `What problem or need does your software project address?`
    
    Our mobile app solves the problem of information overload and inefficient use of users' time on social media. It provides a resource in the form of an electronic 'newspaper' that aggregates all news, updates, and photos from various sources such as social media, news feeds, and subscriptions. Users now don't have to switch between different platforms to get up-to-date information.
    
2. `Who are your target users or customers?`
    
    Our target users are people who actively use social media, news and information resources but face information overload and distracting algorithms. They can be both ordinary users and professionals who need to keep abreast of the latest developments in their field.
    
3. `How will you validate and test your assumptions about the project?`
    
    To test and verify our assumptions, we may use different methods, such as surveys and interviews with target users, conducting focus groups, analyzing user behavior in the app, and collecting feedback. We will be able to examine how well the app addresses the problem of information overload and assess user satisfaction with its functionality and usability.
    
4. `What metrics will you use to measure the success of your project?`
    
    We can use the following metrics to measure the success of our project:
    
    - Number of app downloads and active users.
    - Time spent by users in the app.
    - Level of user engagement: number of posts, photos, news they consume in the app.
    - User feedback and feedback on the app.
5. `How do you plan to iterate and pivot if necessary based on user feedback?`
    
    We plan to actively collect feedback from users through various channels,
    
    such as the in-app feedback feature, email, social media, etc. We will listen and analyse user feedback carefully, and if necessary, we will be ready to make changes and adjust our development strategy and app functionality. This may include adding new features, optimising the user interface or changing content sources to better meet the needs of our users.
    
## **Leveraging AI, Open-Source, and Experts**
Our team plans to use AI technology to develop and train our model to identify and classify news/advertisements. We will use open standards and web libraries to ensure our projects are accessible and affordable. We will also continue to improve our AI algorithms by following the latest developments in the study.

We are aware of the importance of having experts in our team, but we cannot find experts due to time constraints. However, we plan to seek advice and input from experts in the field through University.

## **Inviting other students**

Of course, we are open to inviting other students to join our project. We believe in the power of collaboration and are keen to expand our team in the future.

## **Vision for Your Project**

### Project overview
Our project is a mobile application, an electronic "newspaper" that collects and provides the user with the latest news, posts, and photos from their social networks, news channels, and subscriptions. The main purpose of the project is to solve the problem of information overload and inefficient use of the user's time on social networks. We aim to provide a user-friendly and unique resource that allows users to focus on each piece of content, avoid holding back algorithms and get only the most important information.
### Schematic Drawing
![Structure](/Jurnalik/structureJurnalik.svg)
### Value Proposition
Our app offers a number of meaningful benefits. First, it helps users reduce the time they spend on social media by limiting the information they post and consume. This allows users to be more focused and concentrated on a topic of interest to them. Secondly, the app provides protection from corporate retention algorithms by offering a more independent and objective source of information. Finally, our app offers the user lots of interesting content and news tailored to each user, creating a personalized and unique experience.

### Tech Stack
 - Frontend
	 - Figma
	 - Flutter
 - Backend
	 - Python
	 - Flask
	 - FastAPI
	 - PostgreSQL
 - ML
	 - Python
	 - numpy
	 - pandas
	 - sklearn
	 - SQL
 - DevOps
	- GitHub Actions
	- Docker
	- Kubernetes
### Anticipating Future Problems
Now we've already found some possible problems that we should overcome during development.
1. Services integration
   Purpose of app is to pull news from different sources. API or other integration tools would provide pulling. But some services (like Instagram) have strict rules for registring new apps which would use service info (posts in Instagram). 
2. Comparing posts for clones
   User can read news from different resources, but sometimes aggregators could post equal news but in the different presentation of the text. Purpose of app to reduce time-spending in smartphone, so we should implement method for identifing "clones"
3. Rethinking the Newspaper
   The goal of designers to rethink old "newspaper" to new modern mobile app.
4. An obstacle to the expansion of mind horizons
   By limiting the user, we really allow him to save time, but at the same time the user loses the opportunity to learn about a new source of information. Thus, the problem is to find a balance between limiting and expanding horizons

### Elaborate Explanations

We divided responsibilities between teammates. There are similar divisions in our team: frontend, backend, ML and devops. There are 1-2 people in each unit. Also we will use agile practices and Notion for developing and communicating.