# Adiu.AI

**Initial Pretotyping Hypothesis:** A short-term product that detects stuttering would be appreciated by speech therapists as it would reduce their manual labour. 

**Key findings on EDA & preliminary Machine Learning:** (code can be accessed [here](https://github.com/adharshasam/Adiu.AI/blob/main/EDA_%26_Preliminary_ML_for_Pretotype.ipynb))

![download](https://user-images.githubusercontent.com/64684527/221039427-162f8a84-62a9-491b-aa56-90b2f9bd8144.png)

**Insight #1**: We can see that the variables 'Prolongation', 'Block', 'SoundRep' & 'WordRep' are strongly correlated with 'Stutter' which stores data on the correct labelling of stuttered words. However, 'Interjection' & 'NaturalPause' have little to negative correlation with 'Stutter'.

<img width="818" alt="image" src="https://user-images.githubusercontent.com/64684527/221039299-d147086b-1b57-4190-9c19-5cb920253d02.png">

**Insight #2**: Our Logistic Regression Classification Model confirms that stuttering events can be detected with 99% accuracy with just the following variables: 'Prolongation', 'Block', 'SoundRep', 'WordRep', 'Interjection' & 'NaturalPause'.

**Citation:**

@misc{lea:2021,
    author       = {Colin Lea AND Vikramjit Mitra AND Aparna Joshi AND Sachin Kajarekar AND Jeffrey P. Bigham},
    title        = {{SEP-28k}: A Dataset for Stuttering Event Detection from Podcasts with People Who Stutter},
    howpublished = {ICASSP 2021},
}
