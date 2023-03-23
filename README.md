# Adiu.AI

**Initial Pretotyping Hypothesis:** A short-term product that detects stuttering would be appreciated by speech therapists as it would reduce their manual labour. 

**Initial Idea Validation using Exploratory Data Analysis & Machine Learning:** (code can be accessed [here](https://github.com/adharshasam/Adiu.AI/blob/main/EDA_%26_Preliminary_ML_for_Pretotype.ipynb))

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

**We pitched this "Feasible Product Idea" as MVP 1.0 to early adopters. This idea of "Pitching without Product" was inspired by Jim Poss (Inventor of the BigBelly Solar Trash Compactor).** 

We learnt that this product could only be used by doctors at Fluency Clinics which reduces the sample size of our target users. This means that we might not be able to build a profitable business in the long run. So, we chose to quickly **pivot** to a New Product Idea!

**MVP 2.0 (Product Demo Video) was inspired by Drew Houston's (CEO of Dropbox) Product Demo Video that he uploaded on Hacker News for Product Validation.**

Product Demo Video can be accessed [here](https://www.youtube.com/watch?v=IkgEH5qoHD0)

Adiu Company Website can be accessed [here](https://adiu.webflow.io/)
