##  Predicting Users' Engagement Using Biofeedback, Voice and Machine Learning?
**ABSTRACT:**

Studies show that the quality of the information collected during an elicitation interview, and consequently the quality of the software product that needs to be developed, highly depends on the interviewee's engagement. Because of social expectations, interviewees tend to hide if they are bored or not engaged. To overcome this problem and support the analyst during the interviews, this research uses biometric data and voice features, together with supervised machine learning algorithms, to predict the interviewee's engagement. We built our solution on an experiment consisted of interviewing 31 participants. We collected the data using an Empatica wristband and a default recorder from a laptop.  After preprocessing the data and segmented them into single question/answer segments, we used part of them to train different supervised machine learning algorithms and the remaining to test the algorithms in order to evaluate their effectiveness and select the one that performs better. Our results show that both biofeedback and voice, considered individually, and machine learning can be successfully used to predict participants' engagement.  The results of our work, in addition to being used to help the analyst conduct better interviews by steering the interview based on the participant's engagement, can also be used to prioritized requirements.


#  Experiment

  The interview consited of 38 questions. The questions are grouped into severn topics which are: usage, habits, privacy, relationships, money, procedure, information, and ethics. Each section consisted of multiple questions to allow the participant to immersed in the topic. Each interview lasted about 15 minutes in average. We collected the data using Empatica wristbands and a default recorder from the laptop.
   We analyzed the  interviews and separated them into question/ answer segments. We used 70% of our data to train the different machine algorithms  and the remaining to test in order to evaluate their effectiveness and select the ones that perform better.
  
# Results
 
  
![image](https://user-images.githubusercontent.com/49622433/116079738-2b675780-a666-11eb-903e-eb20f791ea52.png)

Our results show that we can predict user engagement! Better yet voice alone give us desirable results.



Our Replication Package can be found here.
 [Replication Package](https://github.com/alessioferrari/VoiceBiofeedEmo)
