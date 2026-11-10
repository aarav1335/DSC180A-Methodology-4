---
layout: default
---

# DSC 180A Methodology Assignment 4

**Name:** Aarav Agrawal

**UCSD email:** a7agrawal@ucsd.edu

**Section:** Tritons Roster Optimization Project: D15

**Mentors:** Rayan Saab, Bradley Voytek

## Quarter 2 Project Reflections

**1. What is the most interesting topic covered in your domain this quarter?**

I think the main objective of this sports analytics domain was to focus on recruiting amongst the different sports UCSD participates in at the Division 1 and Division 2 levels. An interesting and important topic for this, regardless of which sport, was that of identifying quality in players that is not reflected in traditional statistics. As soccer was the sport of choice for me and my project partner, I found it really interesting to identify player quality by quantifying the quality of their participated events. For example, when a midfielder plays a dangerous pass into the box leading to a second pass and a goal, the stats do not showcase the importance of the midfielders pass. However, using an event-level analysis of each player we are able to identify which events change the probability of a team scoring, by how much, and which players are responsible for said event. 

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

I think an interesting area for investigation is being able to estimate the quality of players who have not received much playing time. This is especially relevant to recruitment, as there could be good players who are overlooked simply because they have not had enough opportunities to showcase their true ability. However, this wouldn't be as simple as extrapolating their statistics to a full 90 minutes, as that can be misleading for several reasons. For example, a player who takes two shots in a ten-minute appearance would have a very high shots-per-90 rate, even though we wouldn't necessarily expect them to maintain that rate over a full match. Therefore, I would like to investigate whether we can make more reliable estimates by considering their playing time and the performances of similar players that may have gone from lower minutes for a few matches to getting good minutes consistently. Using our Wyscout data, we could compare these estimates with how such players' stats from their low-minutes matches translate to their performance in higher minutes matches so that we can form a transformation that takes new players with low minutes and predicts their stats assuming they played higher minutes. This would help us understand whether we can identify promising players from limited observations and how much confidence we should place in those estimates, making it crucial to recruitment at UCSD's Soccer Teams.

**3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**

One change I would like to make is to extend our work on possession adjustment to individual player comparisons. I think an important part of evaluating a player is understanding the opportunities they have had to participate in certain events. For example, a defender on a team that spends most of the match without the ball (therefore defending more) might record more interceptions than a defender on a team that usually controls possession. However, this does not necessarily mean the first defender is better at making interceptions, as they may simply have more opportunities to do so. Our current work explores ways to account for possession at the team level where we use the team's possession over the course of the whole match. However, this might not be an accurate representation of the team's possession during the stint of our player of interest. Therefore, I would like to expand our approach and incorporate the possession percentage during the player's stint in order to make comparisons more fair amongst players and also better normalize their stats to account for their opportunities.

**4. What other techniques would you be interested in using in your project?**

I would be interested in exploring optimal transport further as a way to estimate performance for players with limited minutes. This idea was shared to us by our mentors as an approach we should consider for our low-minutes extrapolation problem. The idea that interests me here is using the statistical profiles of players with more playing time as a reference for interpreting the noisier statistics of players with fewer minutes. I would like to see whether this gives us more reliable estimates than simply using their raw per-90 statistics, while being careful that we are comparing players with similar roles.

Another technique I would be interested in is clustering players based on the types of actions they perform. Players listed in the same position can contribute in very different ways. For example, one midfielder might focus on winning the ball back, while another might contribute more through progressing the ball and creating chances. Identifying these different player profiles amongst players of the same position could help us look beyond labels and incorporating their playing style when considering recruitment. This would connect well with our broader goal of finding players who can fill a specific need within our team.
