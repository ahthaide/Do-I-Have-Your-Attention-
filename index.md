##  Do I Have Your Attention?
**ABSTRACT:**

Studies show that the quality of the information collected during an elicitation interview, and consequently the quality of the software product that needs to be developed, highly depends on the interviewee's engagement. Because of social expectations, interviewees tend to hide if they are bored or not engaged. To overcome this problem and support the analyst during the interviews, this research uses biometric data and voice features, together with supervised machine learning algorithms, to predict the interviewee's engagement. We built our solution on an experiment consisted of interviewing 31 participants. We collected the data using an Empatica wristband and a default recorder from a laptop.  After preprocessing the data and segmented them into single question/answer segments, we used part of them to train different supervised machine learning algorithms and the remaining to test the algorithms in order to evaluate their effectiveness and select the one that performs better. Our results show that both biofeedback and voice, considered individually, and machine learning can be successfully used to predict participants' engagement.  The results of our work, in addition to being used to help the analyst conduct better interviews by steering the interview based on the participant's engagement, can also be used to prioritized requirements.


#  Experiment 
The experiment consisted of 3 main parts:
  1. Slideshow
  2. Simulated Interview 
  3. Self-assestment questionare
  
  **Slideshow**
  Each participant wacth a 35 picture slideshow. The slideshow consisted of calming (neutral), positive, and neagtive triggering pictures. At the end the participants were asked to answer the following questions:
  1. you are judging this image as 0 = Very Negative; 50 = Neutral; 100 = Very Positive
  2. Confronted with this image you are feeling 0 = Relaxed, 50 = Neutral, 50 = Stimulated
  
**Simulated Interview**
  The interview consited of 38 questions. The questions are grouped into severn topics which are: usage, habits, privacy, relationships, money, procedure, information, and ethics. Each section consisted of multiple questions to allow the participant to immersed in the topic.
  
  **Self-Assetmet Questionare**
  The participants were  asked to report their involvement using two 10-point rating scale questions.
  1.  How much did you feel involved with this topic? (1 = Not at all involved; 10 = Extremely involved)
  2.  How would you rate the quality of your involvement? (1 = Extremely negative; 10 = Extremely positive)


 
  
### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ahthaide/Do-I-Have-Your-Attention-/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
