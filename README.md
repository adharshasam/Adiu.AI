# Adiu.AI

***The term 'adiu' - a homonym to 'audio' - is derived from the Latin word 'adiutor' which means 'assistant'.***

***We are a group of SUTD students currently developing a platform to assist speech therapists detect their patients' speech impairments with greater accuracy using AI. As the CTO of the startup, I am in-charge of discovering & deploying innovative yet feasible AI technologies for product development.***

**Initial Pretotyping Hypothesis:** A short-term product that detects stuttering would be appreciated by speech therapists as it would reduce their manual labour. 

**Validating the Technical Feasibility of the Initial Product Idea using Exploratory Data Analysis & Machine Learning:** (code can be accessed [here](https://github.com/adharshasam/Adiu.AI/blob/main/EDA_%26_Preliminary_ML_for_Pretotype.ipynb))

![download](https://user-images.githubusercontent.com/64684527/221039427-162f8a84-62a9-491b-aa56-90b2f9bd8144.png)

**Insight #1**: We can see that the variables 'Prolongation', 'Block', 'SoundRep' & 'WordRep' are strongly correlated with 'Stutter' which stores data on the correct labelling of stuttered words. However, 'Interjection' & 'NaturalPause' have little and negative correlation with 'Stutter' respectively.

<img width="818" alt="image" src="https://user-images.githubusercontent.com/64684527/221039299-d147086b-1b57-4190-9c19-5cb920253d02.png">

**Insight #2**: Our Logistic Regression Classification Model confirms that stuttering events can be detected with 99% accuracy with just the following variables: 'Prolongation', 'Block', 'SoundRep', 'WordRep', 'Interjection' & 'NaturalPause'.

**Citation:**

@misc{lea:2021,
    author       = {Colin Lea AND Vikramjit Mitra AND Aparna Joshi AND Sachin Kajarekar AND Jeffrey P. Bigham},
    title        = {{SEP-28k}: A Dataset for Stuttering Event Detection from Podcasts with People Who Stutter},
    howpublished = {ICASSP 2021},
}

**This AI product that deciphers whether a patient has stuttering issue based on the detection of these six variables - 'Prolongation', 'Block', 'SoundRep', 'WordRep', 'Interjection' & 'NaturalPause' - in audio files can be built using the following ML Techniques!**

<img width="660" alt="image" src="https://user-images.githubusercontent.com/64684527/227075391-b23170e9-0c7e-4326-b773-0f53803aea14.png">

**To test the Market Viability of this Product, we pitched this "Feasible Product Idea" as our MVP 1.0 to Early Adopters (Speech Therapists based in both Singapore & Australia). This idea of "Pitching without Product" was inspired by Jim Poss (Inventor of the BigBelly Solar Trash Compactor).** 

We learnt that this product could only be sold to doctors at Fluency Clinics which further reduces the sample size of our already small pool of target users. This means that we might not be able to build a profitable business in the long run. So, we chose to quickly **PIVOT** to a New Product Idea!

**Starting from Scratch...**

After gaining a better understanding of the pain points of our Early Adopters, we decided to create a **Speech Transcription Software** that assists speech therapists in annotating and transcribing patient audio files without autocorrecting mistakes, thereby reducing the overall time spent on monotonous manual tasks!

**To gain more Target User Feedback on this new idea, we designed a Product Survey with our MVP 2.0 (Product Demo Video) and a set of well-curated follow-up questions to gain insightful feedback. This idea of creating a "Product Demo Video" to gauge interest was inspired by Drew Houston's (CEO of Dropbox) Product Demo Video which he uploaded on Hacker News for Product Validation.**

Here are some promising survey results!

![image](https://user-images.githubusercontent.com/64684527/234145200-3c459dac-332e-49da-8a3f-f03bcb3405a2.png)

![image](https://user-images.githubusercontent.com/64684527/234145257-a70eb5bd-4578-45ae-84b7-76f10b1db769.png)

![image](https://user-images.githubusercontent.com/64684527/234145307-c208eafd-dae8-4c77-88b3-b16f2d6ad8e7.png)

![image](https://user-images.githubusercontent.com/64684527/234145361-b8dd2360-f808-4340-a409-ec2e8511b43b.png)

**THE FINAL PITCH!**

**We gave our Final Pitch to a panel of Angel Investors after 4 months of hard-work and our Adiu bagged the "Best Startup Award" among 11 total startups.**

<img width="413" alt="plague" src="https://user-images.githubusercontent.com/64684527/234146364-5b43c13c-df8c-4620-80d6-408349d8d2a4.png">

Adiu Company Website can be accessed [here](https://adiu.webflow.io/)
The Final Demo Video of our Product Idea can be accessed [here](https://www.youtube.com/watch?v=URTHdlVCIRM)
