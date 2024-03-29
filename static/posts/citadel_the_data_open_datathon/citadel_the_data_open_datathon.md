title:    "Citadel The Data Open Datathon"  
date:    2018-02-11  
time:    "22:16"  
location:    Austin, TX  
country:    United States  
author:    Yu Lu  
category:    activities  
cover:    cover.jpg  
abstract:  This is the first datathon in my life! [The Data Open] is a datathon competition taking place throughout the year at the series of top universities, by Citadel. At each event, participants work in teams to work through a large and complex dataset and then present their findings to a panel of judges. 

# Citadel [The Data Open] Datathon  
![cover](/static/posts/citadel_the_data_open_datathon/cover.jpg)  


### The Story  
---  

> "Hey, did you know this was happening ?"   

Message from my friend Juan Trejo with a link attached.  

I was in the lab with both hands covered with tight gloves and filled with bunch of allen wrenches. Apple did quite good job in showing paritial of the linked content in the imessage. I saw "*Apply for The Data Open - Citadel*".  

I got to know Juan when we were in the class of *Elements of Software Engineering*, during which we teamed up to work on a web app called [*Nettunes*](https://github.com/SuperYuLu/cs329e-idb "Nettunes on Github"), with other three teammates from different background. Juan is from Department Electrical and Computational Engineering, also an enrolled Ph.D. student in UT. We shared the same interests in Data Science / Machine Learning projects, he knows I'd like to take this kind of challenges.  
> "Wow this looks awesome !"  

I replied after took a glance of the content.   

Having no idea about what datathon and Citadel is, I put down some vacuum equipment in my hand and clicked the link. It was a well-polished webpage of a company called *Citadel*, yes, I started seeing webpages as big collecion of htmls CSV, Javascripts since exposed with web development. Um...What I'm looking for here? Oh, the datathon ! The splash page was showing a flash video of a few professonal-looking people sitting in front of laptops and discussing, With capitalized sentence:   

> [Where the World's Best Intellectual Athletes Come to Compete]  

Scrolling down there come more inspiring words like "*If you are a peak performer in math, computer science, or technology, then The Data Open is your next big challenge.*"    

This fit my heart so well ! I was excited, quickly checked the deadline and found that it was about a week and half later, great !   

> "I'm in, will you? "

> "Sure."  

The journey starts.  

### The Assesment Test and application   
---  

The night we I got back to my apartment, I started working the application. After filling in some registration forms, I received an email link to the online assesment test, a 60 min quiz from which the applicant's performance will be evaluated to get a spot in the competition.  

There were 15 mutiple-choices problems in the test, covering knowledge of  basic python libraries (based on prior survey of programmaning langurage preference) like pandas, statistics like probability, maching learning algorithims (such as SVMs, KNN, Decision Trees, L1 L2 regularization, Cross-Validation, etc). I would say it will be challenge if one doesn't even know the meaning of these words. Later during the pre-mix of the even we were told that they selected 100 participants out of more than 400 by evaluating  the assesment.   

Luckily I got in, so as my friend Juan. The following events were then invitation-only.  


### Team up and the pre-mixer  
---  

Since the datathon requires people to team up with four people in each team, there was a Slack channel for participants who got invited to chat and form teams. Juan and I were thinking about looking for another two people to team up early that week, but we didn't got chance to have our hands on it until the deadline of team registration.  

I posted our information on the datathon Slack channel, soon after which we got our team formed with the other fantastic teammates: Keyur Muzumdar and Kurtis David. We give our team an awesome name: *The Team-X*.  

![The team X](/static/posts/citadel_the_data_open_datathon/group_photo.jpg "The team-X")  

### The Datathon Schedual  
---  

The event was on Saturday, Feb. 10, 2018, from 8 a.m. to 6 p.m.   

- 8:00 - 8:15am Check-in & Event Kick-Off 
- 8:15 - 8:30am Welcome & Datathon Overview 
- 8:30am Hacking Begins!
- 11:30am Lunch 
- 3:15pm Submission Hard Stop Deadline Announced 
- 3:30 - 3:45pm Submission and Post Datathon Survey 
- 3:45 - 5:30pm Post Datathon Reception
- 5:30 - 6:00pm Winners Announced 
- 6:00pm Event Close  

Location: AT&T Conference Center, 1900 University Ave, Austin, TX.   

The event requires participants to bring their own laptop, which at least 1GB RAM memeory. Internet access is allowed, but online-chatting is prohibited.   

The winners (top 3 teams) will receive $25,000 as reward.  


### The Competition Day   
---  

After check-in, we got our name badge and assigned team number:  
![badge](/static/posts/citadel_the_data_open_datathon/badge.jpg "My badge !")  

Teams were assined into a big dinning hall with round tables for each individual team, we quickly found ours and started chatting about our strategy. we are team 22!  

![team22](/static/posts/citadel_the_data_open_datathon/team-number.jpg "team 22 !")  

![team22](/static/posts/citadel_the_data_open_datathon/environment.jpg "the environment !")  

I was surprised how well people were prepared for this competition: a few participants even brought extral monitor for multi-tasking !  

Sitting by the table, we were allowed to start looking through the documents on the table, which includes the datathon schedual, the problem statement and the data schema. By this time we should know what the problem is about and how the data structure looks like, but we didn't  have the real data yet.   

![team22](/static/posts/citadel_the_data_open_datathon/documents.jpg "hand-outs")  

The problem statements explains the topic of the Datathon, important details about the datasets we'll be using, and guidance on how to submit the results.   

The background is about Uber's splashing in New York City (NYC) and it's hit to local traditional for-hire vehicle (FHV) industry. Provided the Uber trip data (year 2014 and 2015, including pickup time/locations, drop-off time/locations, base, etc), yellow cab trip data (similar to Uber datasets), green taxi data (similar to above), NYC public subway trips data (MTA trips), as well as NYC demographics, NYC geogaphic, and the weather data during the time period. Any extral online datasets are allowed but one has to guarantee the realiability of the data and the unziped size has to be less than 2GB.   

The goal is to analyze the NYC Uber trip data, potentially in combination with supplementary datasets, in order to increase understanding of how developments in the NYC for-hire transport industry relat to broader trends in the public and private transportation industries at large.   

The participant team were asked to pose their own question and answer it using the available datasets in the available time. What is important is both the creativity of the posed question and hte quality of hte data analysis.   

There were few provided sameple questions: How have trip trends over time differed between these two classes of taxis in relation to Uber ridership ? Is there a relationship between the NYC weather and vehicle pickup times and endpoints ? What sorts of dynamics exist between Uber and taxi trip trends and NYC public subway trip trends ?   

### The Hacking  
---  

The hacking begins, we got the data and started plan our hacking.  

The first thing came to us was to pose a creative question based the the datasets. Since the problem statement says that the creativity is part of the aspect that will evaluated, we started brainstroming anything interestig related to the problem. Our proposed questions include:
- Does the Uber ridership help on reducing the crime rate in NYC ? 
- Does the splash of Uber related to lack of public transportation stations in a certain region ?
- How was the influence of traffic in NYC influenced by rides such as Uber and other taxi riderships ? 
- NYC suffers severe weather conditions evey year during late Janurary, how can we extract information from the Uber and taxi driving records to study  people's react to these special weather conditions ? 

After some disscussion, we finally decided to go with the last idea, as leasted above, and it was already 11am already. Later when we recall our time planning, we regrate spending too much time on coming up the idea which we is supposed to be "creative".  

First, we found there was blizzard from Jan. 23 to Jan. 31, 2015 in NYC, we did notice that the three all fell close to zero during the night of the 26th, morning of the 27th, and found that this was because the city imposed a curfew at the time (11pm, 1/26).However, the trend line found for MTA did exhibit a difference in behavior. The data supports that people were more likely to ride the subway than for-hire transportation at the time, as seen in the figure.   

![teamwork](/static/posts/citadel_the_data_open_datathon/work1.jpg)    

This motivated our further analysis of this time frame on a demographic level, leveraging locality of the rides. We found that Ubers often were taken by higher median income brackets, and while the data is still noisy a bias can be seen and with times of severe weather a disparity in where for-hire media are going are skewed.

The next question is, how does the transportation (including subway, Ubers, taxis) react to the curfew, when all transportation was restarted ?  

![teamwork](/static/posts/citadel_the_data_open_datathon/work2.jpg)    

We definitely saw the flux of transportation from subway spikes up right after the ban was cancelled, while the taxis and Uber transportation volumn stayed low. This could be understanded as either the severe weather kind influenced the decition of people or the traffic condition for driving is still a main factor that prohibits drivers from taking panssangers.   

We also analyzed the accident heat map after the blizzard:  
![teamwork](/static/posts/citadel_the_data_open_datathon/work3.jpg)    

We were also trying to correlate these effect to the demographics of NYC, but due to the time limit we were not able to good analysis from this aspect.  

Since each team has to write down their work for submittion, together with the codes, we all started focusing on writting the report by aroud 2:30pm, summarized what we've done and our findings.  
### The results  
---  

Unfortunately we didn't get to the top 3 team by the end, the final results were announced around 5:30pm, winner team received everyone's applaud. There were three judges working on all the teams anslysis, however, they didn't release the winner teams' work to others, so we didn't get chance to learn from them. Contratulations to the winner teams !   

### What I've Learned   
---  

Although this is my first datathon, I feel like I learned a lot from it. First, I got chance to meet and chat with so many awesome people, especially my teammates, this was a great experience. Second, I learned that there could be varities ways to apply whatever you've learned from text and classroom to practial problems, knowledge doesn't only stay in the classroom. Also I realized how to make use of my coding skills in the competitive environment and produce realiable analysis for my team. Finally, the power of single person is limited, but the teamwork can create magic! Thanks to my teammates for their efforts and the time I spent with them.  

  
  

