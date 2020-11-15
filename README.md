![Intro page](https://drive.google.com/uc?export=view&id=1aAQLFDY4FuCMENuihkTfaIm7Igycy306)

<h1>TeToAI <br>[Testing through Artificial Intelligence]</h1>

<p>A Virtual Interviewing Platform made to make the task of Talent Acquisition Managers easier in the Industrial Sectors. </p>

<h2>Problem Statement<h/2>

<p>Since the whole world is moving ahead to Digitisation in every sector, the Hiring Managers in several sectors are facing problems in hiring candidates suitable for their respective roles. The only source of communication is through several video call platforms where the candidates have the utmost advantage.</p>

<h2>About TeToAI</h2>

<p>To the above problem statement we present you TeToAI [pronounced as 'te' from 'Teach' + 'to' from 'Today' + 'AI' from 'i'] whose full form is "Teaching Through Artificial Intelligence". <br>The Virtual Interviewing platform tends to assess the Facial Expressions of the Candidate into a statistical output to the respective Hiring Manager.</p>

<h2>Inspiration</h2>

<p>So how did we come up with this Idea ? <br> Well one of our team member's father is in the Hiring Field and we got to know how difficult it is to select the candidates through Virtual Platform with the physical absence of candidates. Due to this there have been less production in the company and no trust bonding is developed between the Hiring Manager and the Candidate. The candidates may tend to make false claims about their profile.<br>So the best possible way was to make a model and train it in such a way that it tends to identify the expressions of the candidate. </p>

<h2>So, What all can our Model Identify ?</h2>

| --> | 1| 2 | 3 | 4 | 5 | 6 | 7 |
| ------------ | ------|----|----|----|----|----|---|
| <b>Emotions</b> | Nervous | Unsure  | Happy |Disinterested| Confident | Neutral| Confused |

<b>Why have we taken only these Expressions ?</b>
So after a lot of research and analysis we came up with these 7 most basic yet most descriptive expressions which is taken under observation by the Hiring Manager or Recruiter.

<h2>The Secrets, well the Working XD</h2>

<p>So currently how our backend works, We used Computer Vision framework opencv and used the datasets and integrated it with an existing pre-trained model called Xception Model developed by google researchers.<br> Then we wanted to store the emotional percentage values throughout the interview process to the database and then further went to plot it in a bar graph. To make the recruiters much more clear we also compared the results of the candidate with the average results of the past candidates. We also provided a graph in the dashboard section where the recruiter can see the  the emotional expression of the candidate at each interval of time.<br>
We used Flask as a web framework. We also took help from Nicepage to design the overall layout of our website.
For time being the model tends to record and analyse the 45 seconds which can be further increased.
</p>

<h2>Problems that we faced ... Poof !!</h2>

<p>So, the problems that we were facing was we were not able to store the emotional probability in the db and then further we were not able to plot the graph via JS.</p>

<h2>Datasets</h2>

<p>So the following datasets were used </p>

 1. face_landmarks
2.  padding.pickle
3.  Personality_traits_NN.h5
4.  Personality_traits_NN
5.  Personality_traits_SVM
<br>
<p>Since, we were not able to upload the datasets for the model so we have provided the google drive link below<br></p>

[Click here for the datasets](https://drive.google.com/drive/folders/1MfXn-GFqrw1LRZ1Y3bEZXoJbu8iQIAEN?usp=sharing)
You can access all the datasets here.. Cheers !!

<h3> 🤝🏻 Connect with Team Pi </h3>
<p>
&nbsp; <a href="https://www.youtube.com/channel/UCtod0cyzPDfuv5WIpytDDNw" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/plasticine/100/000000/youtube.png"  width="50" /></a>
&nbsp; <a href="mailto:indianteampi@gmail.com" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/plasticine/100/000000/gmail.png"  width="50" /></a>
</p>

:star: Member of Team Pi
