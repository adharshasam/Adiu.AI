# Adiu.AI

**Key findings on EDA & preliminary ML**

<img width="368" alt="image" src="https://user-images.githubusercontent.com/64684527/221038622-95f3ba7c-de04-421f-a525-990e26eb4321.png">

**Insight #1**: We can see that the variables 'Prolongation', 'Block', 'SoundRep' & 'WordRep' are strongly correlated with 'Stutter' which stores data on the correct labelling of stuttered words. However, 'Interjection' & 'NaturalPause' have little to negative correlation with 'Stutter'.

<img width="578" alt="image" src="https://user-images.githubusercontent.com/64684527/221038992-20b07154-284e-46a6-a5c4-e465bdf62e6c.png">

**Insight #2**: Our Logistic Regression Classification Model confirms that stuttering events can be detected with 99% accuracy with just the following variables: 'Prolongation', 'Block', 'SoundRep', 'WordRep', 'Interjection' & 'NaturalPause'.

**Citation:**

@misc{lea:2021,
    author       = {Colin Lea AND Vikramjit Mitra AND Aparna Joshi AND Sachin Kajarekar AND Jeffrey P. Bigham},
    title        = {{SEP-28k}: A Dataset for Stuttering Event Detection from Podcasts with People Who Stutter},
    howpublished = {ICASSP 2021},
}
