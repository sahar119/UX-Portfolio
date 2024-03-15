#  Intervening Doomscrolling
![header](/Assets/doompic.jpg)
# Synopsis
Doomscrolling, or mindlessly consuming negative content, such as news, has major health consequences for users. As such, understanding the interventions that mitigate the overconsumption of negative content, such as news, is crucial. The project proposes that using emotional-based interventions that expose users to comic or humorous content will help doom scrollers engage less in the consumption of negative news by distracting them and inducing a positive mood in the users. To test the proposition, the present project incorporated user insights (both via interviews and surveys) to design and develop an intervention app. An app is a distraction recommender system (digital nudging) that can potentially guide users toward healthier digital behaviors and prevent excessive consumption of negative content. 
# Sampling and research procedure
This study explored the role of emotional interventions via a humorous content recommendation system in changing doomscrolling behaviors among young adults under 35. I chose this target group because they are digital natives and have turned to social media and other online news platforms to check the news instead of offline (Galan, Osserman, Parker, & Taylor, 2019). First, an interview and an online survey were used for user research. Second, an analysis was done on the data gained from user research to identify users' problems, emotions, and needs. Third, the prototype’s design and technical implementation were iterated. Several feedback sessions were held between iterations to complement the prototyping procedure. I conducted five one-to-one interviews and workshops with friends.
Additionally, I conducted an online survey with 15 participants. I included several multiple-choice and open-ended questions and asked them to answer similar questions as those offline users (5 friends). The figure below illustrates a summary of the sample and the procedure. 
![sampling](/Assets/sampling.png)
# User Research
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
# Analysis of User Research Data
The affinity map demonstrates the core insights from both groups of users (face-to-face interviews and online participants). More specifically, I summarized the participants' answers for each category of questions: main intention or motivation to scroll, feelings during scrolling, hacks, and their needs or reasons for having an intervention app that can interrupt their mindless scrolling habits. The analysis has been done to identify the main users’ problems and find key insights from the user research to apply in the prototype design process. Most participants had experienced negative feelings while scrolling through negative news or content on the Internet, leading them to become even more engaged while scrolling through negative content.
![map](/Assets/coreinsights.jpg)
Overall, the user research provided important insights about users' intentions in scrolling online negative content, such as news, and users' emotions during scrolling. Such insights are important, as they were critical to being considered in the prototyping process to design and develop an app that could benefit users with doomscrolling problems. The table below shows the emotional response toward doomscrolling analysis.
![analysis](/Assets/33.jpg)
### Problem statements
![problems](/Assets/44.jpg)
# Prototyping
## First Iteration
The prototype creation process began with designing three different interventions based on emotion, meditation, and notification to investigate different effects on target users, with ideas extracted from insights from the theoretical framework and analysis from user research. 
### First Iteration User Testing: Feedback Sessions
The intervention designs were tested in a 90-minute feedback session with five participants (four females and one male) to identify problem areas and reveal opportunities. During the sessions, participants tested three intervention designs. They were then asked about the effectiveness of the interventions.
### Findings First Iteration
An important takeaway from the feedback sessions was that participants found the meditation intervention equally effective as the notification. At the same time, they stated that comic intervention should be improved.
#### "The idea behind viewing a cartoon might be vague for users; they need to be informed of why it pops up." 
#### “It's an interesting idea. However, it should probably be forceful on the user instead of simply being a notification. Something like hiding away the browser for a while to let the comic take up the space to distract the user.” 
## Second Iteration
Based on findings from the first iteration, user research, and a theoretical framework, a design for a recommender system in two parts—design and technical implementation—was developed in the second iteration. The primary aim of this iteration was to design an emotional-based recommendation system for the project target group to identify their emotional state and, if the App finds that they are in a negative emotional mood (sad, anxious, or stressed), recommend them comic content.
### UX design 
Based on the theoretical framework, there were three main emotional contributing factors related to doomscrolling: sadness, anxiety, and stress. In addition, based on project user research analysis, filling up spare time was one of the third main motives for intentional online news consumption. Time-filler moments are constant throughout the day on the train, in the bathroom, or taking a break when people want entertainment by consuming news on online media platforms (Taylor, 2019b). Therefore, an intention tracker was designed to identify the current users` motive for opening X. 
### Technical implementation
A recommender system was developed that gives the current emotional state of the user, checks if it is more than 30 minutes, and then recommends three cartoons. This recommendation system is Non-personalized and works based on weightage average technique. 

(v/(v+m) * R) + (m/(m+v) * C)
                                             W= weightage rating
                                             C= C is the mean vote 
                                             V= number of votes to the cartoons 
                                             m= m is the minimum votes required to be considered
                                             R= Average for the cartoon as a number from 0 to 10












  
                                                  







