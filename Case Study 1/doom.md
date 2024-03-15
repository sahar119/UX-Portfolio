#  Intervening Doomscrolling
![header](/Assets/doompic.jpg)
# Synopsis
Doomscrolling, or mindlessly consuming negative content, such as news, has major health consequences for users. As such, understanding the interventions that mitigate the overconsumption of negative content, such as news, is crucial. The project proposes that using emotional-based interventions that expose users to comic or humorous content will help doom scrollers engage less in the consumption of negative news by distracting them and inducing a positive mood in the users. To test the proposition, the present project incorporated user insights (both via interviews and surveys) to design and develop an intervention app. An app is a distraction recommender system (digital nudging) that can potentially guide users toward healthier digital behaviors and prevent excessive consumption of negative content. 
# Sampling and research procedure
This study explored the role of emotional interventions via a humorous content recommendation system in changing doomscrolling behaviors among young adults under 35. I chose this target group because they are digital natives and have turned to social media and other online news platforms to check the news instead of offline (Galan, Osserman, Parker, & Taylor, 2019). First, an interview and an online survey were used for user research. Second, an analysis was done on the data gained from user research to identify users' problems, emotions, and needs. Third, the prototype’s design and technical implementation were iterated. Several feedback sessions were held between iterations to complement the prototyping procedure. I conducted five one-to-one interviews and workshops with friends.
Additionally, I conducted an online survey with 15 participants. I included several multiple-choice and open-ended questions and asked them to answer similar questions as those offline users (5 friends). The figure below illustrates a summary of the sample and the procedure. 
![sampling](/Assets/sampling.png)
# User Research
## User data management
In compliance with GDPR, for the prototype, a privacy-by-design approach was taken throughout the steps of this project. The goal and topic of the project were clearly explained to the participants, both verbally and in writing, and all participants signed consent. Furthermore, the project did not include the doomscrolling recognition phase; therefore, no further details were required from them. To maintain the privacy of test users, all records of users' feedback and opinions have been safely stored in the Excel files and published anonymously in the research. Instead, numbers have been assigned to the users.
## Friendship group procedure
  A semi-structured interview was conducted with fifteen questions developed by the researcher. Participants were selected through the convenience sampling method, in which the researcher selects participants because this is the easiest way for them to access it (Nickolopoulou, 2022). This method was chosen because of the limited time frame of the project, so a friendship group of the researcher’s known friends or acquaintances was used to facilitate open and natural conversations. The criteria for the participants were: (1) to be between 18 and 35 years of age; (2) to have sufficient English language proficiency; (3) to have doomscrolling experience on online news platforms; or (4) to have excessive social media consumption.
The procedure was divided into two parts:
- 75-minute one-on-one interviews with 5 participants.
- A 60-minute collaborative workshop where participants were asked to explain their opinions about the two types of comics.
### The table below shows the convenience sampling group demographics of participants.                            
![sampling2](/Assets/11.png)
## Online recruited group procedure
To prevent potential biases in the user research sampling and gain as many diverse insights as possible, I collected data from 15 participants via an online survey using the same friendship group criteria and questions.
The table below illustrates the demographics of the online recruited groups. 
![samle online](/Assets/22.png)
# Analysis of user research data
The affinity map demonstrates the core insights from both groups of users (face-to-face interviews and online participants). More specifically, I summarized the participants' answers for each category of questions: main intention or motivation to scroll, feelings during scrolling, hacks, and their needs or reasons for having an intervention app that can interrupt their mindless scrolling habits. The analysis has been done to identify the main users’ problems and find key insights from the user research to apply in the prototype design process. Most participants had experienced negative feelings while scrolling through negative news or content on the Internet, leading them to become even more engaged while scrolling through negative content.
![map](/Assets/coreinsights.jpg)
Overall, the user research provided important insights about users' intentions in scrolling online negative content, such as news, and users' emotions during scrolling. Such insights are important, as they were critical to being considered in the prototyping process to design and develop an app that could benefit users with doomscrolling problems. The table below shows the emotional response toward doomscrolling analysis.
![analysis](/Assets/33.jpg)
## Problem statements
![problems](/Assets/44.jpg)
# Prototyping
## First Iteration
The prototype creation process began with designing three different interventions based on emotion, meditation, and notification to investigate different effects on target users, with ideas extracted from insights from the theoretical framework and analysis from user research. 
### Intervention 1: Notification
![notification](/Assets/Notification.gif)
### Intervention 2: Comic
![comic](/Assets/comic.gif)
### Intervention 3: Meditation
![medi](/Assets/meditation.gif)
### First Iteration User Testing
The intervention designs were tested in a 90-minute feedback session with five participants (four females and one male) to identify problem areas and reveal opportunities. During the sessions, participants tested three intervention designs. They were then asked about the effectiveness of the interventions.
### Findings First Iteration
An important takeaway from the feedback sessions was that participants found the meditation intervention equally effective as the notification. At the same time, they stated that comic intervention should be improved.
##### "The idea behind viewing a cartoon might be vague for users; they need to be informed of why it pops up." 
##### “It's an interesting idea. However, it should probably be forceful on the user instead of simply being a notification. Something like hiding away the browser for a while to let the comic take up the space to distract the user.” 
## Second Iteration
Based on findings from the first iteration, user research, and a theoretical framework, a design for a recommender system in two parts—design and technical implementation—was developed in the second iteration. The primary aim of this iteration was to design an emotional-based recommendation system for the project target group to identify their emotional state and, if the App finds that they are in a negative emotional mood (sad, anxious, or stressed), recommend them comic content.
### UX design 
Based on the theoretical framework, there were three main emotional contributing factors related to doomscrolling: sadness, anxiety, and stress. In addition, based on project user research analysis, filling up spare time was one of the third main motives for intentional online news consumption. Time-filler moments are constant throughout the day on the train, in the bathroom, or taking a break when people want entertainment by consuming news on online media platforms (Taylor, 2019b). Therefore, an intention tracker was designed to identify the current users` motive for opening X.

![emotional](/Assets/EmotionalRS.gif)
### Technical implementation
A recommender system was developed that gives the current emotional state of the user, checks if it is more than 30 minutes, and then recommends three cartoons. This recommendation system is Non-personalized and works based on weightage average technique. 
##### (v/(v+m) * R) + (m/(m+v) * C)
                                             W= weightage rating
                                             C= C is the mean vote 
                                             V= number of votes to the cartoons 
                                             m= m is the minimum votes required to be considered
                                             R= Average for the cartoon as a number from 0 to 10
![tec1](/Assets/teck1.jpg)
![tec2](/Assets/tec2.jpg)

[See recommender system codes here.](https://github.com/sahar119/UX-Portfolio/blob/main/Case%20Study%201/RecommenderSystem.ipynb)

## Second Iteration User Testing
Some of the participants gave some valuable feedback. One participant stated that to prevent more content from being consumed, there should be a limited number of comic suggestions. The other participant's feedback was that it would be efficient if a customization interface existed for users to customize nudges on the App. 
##### “Putting several cartoons in the app for users to view would keep them on their phone for just as long and provide more content to consume.”
##### “There should be customization by the user that allows for customized nudges.”
## Third Iteration
The third iteration aimed to finalize the prototype in the form of a nudging app for iPhone mobile phones. The App was named Unhooked, and an icon was designed for that. To use this App, the user should create an automation in Shortcuts. Shortcuts is a default installed feature on Apple mobile phones that allows
users to create macros for specific tasks on their phones.
### UX design
In this iteration, some improvements were made based on feedback comments from the second iteration and some users` identified needs from the user research section, such as setting a time-limit app and a downtime schedule.

![setting](/Assets/setting.gif)
### Technical implementation
A report creator was developed with Python for the App. The primary purpose for creating this feature was to provide a report that included Total Opening Attempts, Average Time Spent on the App (Twitter), Preventions, and Time Saved. This report is accessible in the Settings of the App.
This code calculates the total attempts that the user makes to open a social media site, the average time spent on it, the prevention times by the intervention app, and the total time saved as a result of not opening the social media (App). Time saved is calculated based on the following formula:
#### Time saved = The numbers of Prevention * Mean spend time (on a social media App)
![tec3](/Assets/tec3.jpg)
![tec3](/Assets/report.jpg) 

[See a sample of the weekly report code here.](https://github.com/sahar119/UX-Portfolio/blob/main/Case%20Study%201/Report.ipynb)

[See a sample of the intention report tracker here.](https://github.com/sahar119/UX-Portfolio/blob/main/Case%20Study%201/intentionReport.ipynb)
## Third Iteration User Testing
The last feedback session led to the final iteration design. A piece of feedback received was a suggestion for creating a report for emotional state and time-filler, as mentioned below by one of the participants: 
##### "I like the idea of an intention tracker; it would even be better if it could produce a report for emotional states and time-filler as well for someone who wants to know.”
## Final Design
An intervention nudging The app was developed based on insights from the theoretical review and user research analysis. The prototype consists of the design part and technical code components. In the design part, three interventions were designed based on emotion, meditation, and notification. Moreover, an app customization part was designed that consisted of different parts such as setting app limitations, setting downtime schedules, adding and customizing interventions, and an overview of reports. In the technical implementation part, the emotional-based recommender system is intended to function as a data-driven feedback loop with the following steps: (1) It learns the users' intentions by receiving responses from the intention tracker; (2) It analyzes the users' responses in a conditional state if it finds that their responses relate to their emotional status; and (3) It recommends comic cartoons to the users. In addition to the recommendation system, some codes were written to produce prevention and time-saving reports. 
## Controlled experiment: perceived effectiveness of the final prototype 
Sixty participants (Age mean = 28, 22 males, 38 females, 68% employed, 32% either unemployed or active job seekers) were recruited online to participate in the experiment. The main goal of this final experiment was to explore users’ perceptions of the prototype's effectiveness in changing doom scrolling behavior. Notably, the goal was to study whether the prototype of the emotional-based intervention is perceived as equally or differently effective as other established interventions such as mediation and notification (time screen reminder).  
Participants were randomly assigned to one of the three experimental conditions: emotional, mediation, and notification. In mediation and notification conditions, I adopted the same design (concept) from the current literature (Grüning et al., 2023; Zimmermann, 2021). In emotional condition, I used the prototype, which incorporated user feedback in the last iterations. In all the conditions, participants were asked first to read a short description of the prototype and show their agreement or disagreement (on a 7-point scale, 1= strongly disagree, 7 = strongly agree) with a few statements. The measures included perceived effectiveness (“This intervention APP is very effective for helping people reduce screen time, especially for people with doom-scrolling problems.”), recommending to friends (“I would recommend this intervention APP to my friends or family members with doom-scrolling problems.”), and overall preference (“I would be interested in using this intervention APP.”). After answering these measures, they reported their hourly use of online media and their past willingness to control their screen time (“Have you ever wished there was something on your screen to distract you from doom scrolling or discourage you from spending more time on social media or news platforms?”), time on social media (“How many hours, on average, do you use for reading or scrolling content on social media?”), and responded to demographics. 
## Results 
Overall, participants perceived the emotional-based intervention (comic) as equally effective as the other two interventions (Mean comic= 4.91, Mean notification = 4.89, Mean meditation = 5), p s > 0.7. similarly, in all three conditions, they reported equal willingness to recommend the intervention to their friends or family members (Mean comic= 4.68, Mean notification = 4.90, Mean meditation = 4.68), p s > 0.6. A similar pattern was observed in their overall intervention preferences (Mean comic= 4.27, Mean notification = 4.89, Mean meditation = 4.10), p s > 0.2. Further analysis showed that users who have never wished to have something to control their screen time, on average, perceived the three intervention APPs as less effective than users who sometimes wished to control their screen time or had tried to do so (Mean Yes= 5.17, Mean never = 3.28, Mean sometimes = 5.04), p <. 01). Surprisingly, users who never wished to control their time screen perceived the emotional intervention (comic App) as more effective (Mean comic= 4.16) than the other two interventions (Mean meditation = 3.3, Mean notification = 3.5). Users willing to have something to control their screen time perceived all three interventions as equally effective. Please see the following figure for the means in each other study condition.

![result1](/Assets/results1.png)
## Discussion of the results
The results provided initial evidence that the proposed intervention in the present thesis is perceived equally positively as the other two established interventions. More interestingly, the users who never thought about controlling or using intervention to control their screen time found the proposed intervention (comic) more effective in reducing screen time than the mediation or notification intervention. The reason for such an observation might be that the users who never thought of controlling their screen time were those who spent less time on social media. To test this, I also looked at the time spent on social media reported by users based on their past willingness to control their screen time. As shown in the below figure, users who said they never thought of controlling their screen time have the lowest online content usage. Nevertheless, it would be interesting to explore such a finding in the future to understand the underlying reasons for different groups of users adopting emotional (comic in the present thesis) or time-based (notification, meditation) interventions. 
![result2](/Assets/result2.png)
## Reflection:
Despite the limitations of the present research, it offers a novel proposition that recommender systems can not only be used to suggest to users or consumers, for example, products, better choices, or less harmful choices, but recommender systems can also be used as distraction systems. Specifically, it is possible to distract users from maladaptive consumption in the context of unhealthy online media consumption by suggesting comic content (based on their prior self-reported emotions or intentions) that can eventually evoke positive emotions in users and distract them from their harmful habit. Understanding human emotions and behaviors is a complex one. Further exploration of the effectiveness of the proposed emotional-based intervention awaits future research. 








                                             
                                             









  
                                                  







