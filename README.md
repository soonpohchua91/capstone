<img src="http://imgur.com/1ZcRyrc.png" style="float: left; margin: 20px; height: 55px"> 

# Capstone: Project Elimi-'Hate'

## 1. Problem Statement

Recognising the adverse impact of hate speech worldview, the United Nations launched its [United Nations Strategy and Plan of Action on Hate Speech](https://www.un.org/en/genocideprevention/documents/advising-and-mobilizing/Action_plan_on_hate_speech_EN.pdf) campaign on 18 June 2019 with the mission to address the root causes and drivers of hate speech, and to enable effective responses to the impact of hate speech on societies. Part of its key commitments is to leverage on technology and to use education as a tool to counter and address hate speech. 

This project, titled **Project Elimi-'Hate'**, sees the potential of data science to combat against hate speech. In particular, with the rise of social media, the far-reaching damaging impact of hate speech is just one post away. Moreover, much existing efforts have been focused on censorship. While there is certainly a place for censorship, it is not a long term solution as users can always seek alternative platforms or different wordings to post hateful comments. Echoing the approach of UN, this project believes that much more can be done in the sphere of education to combat against hate speech. More specifically, this project aims to :-

1. **Increase empathy towards others in the social media space**; and 
2. **Cultivate better awareness of unhelpful written expressions.**

## 2. Dataset

The current project references to a dataset provided by the [Social Science Data Laboratory](https://matrix.berkeley.edu/research-center/social-science-data-laboratory-d-lab/) of University of California, Berkeley measuring hate speech. While it is possible to scrap data from various online social media platforms, labour for human annotating is expensive. The alternative of self-annotating is also time-consuming and biased. Hence, the project landed on the approach to reference to a robust dataset from a reputable institution.

Most descriptions of the dataset can found via the [hugging face website](https://huggingface.co/datasets/ucberkeley-dlab/measuring-hate-speech) and the [research paper published](https://arxiv.org/abs/2009.10277). Nevertheless, for those areas which the dataset is uncleared on, the project shall omit them from analysis (see under [dataset card](https://huggingface.co/datasets/ucberkeley-dlab/measuring-hate-speech): "This dataset card is a work in progress and will be improved over time.").

## 3. Approach

Using the dataset, the project seeks to produce a reliable multi-label classification model. The dataset will then be published online via [Steamlit](https://streamlit.io/). Existing resources, such as [Perspective API](https://perspectiveapi.com/) produced by Google, focus on screening out unhelpful comments. This project aims to do the opposite. Instead of tackling the hate speech from a receiver's point of view, the project's Streamlit API is meant to engage writers before they post any comment. 

Of course, there is no guarantee that such a service would be welcomed by many. Nevertheless, this project hopes that such a service will appeal to two groups of people :-

1. **Those who wants to err on the safe side**

Those who are sensitive to what they post online may appreciate a readily available platform to check their writings in order to avoid regrets or causing hurts to others. 

2. **Youths & Children**

More importantly, given the accessibility of social media today, youths and children in particular may not have the maturity to embrace these online social platforms. While treating others with respect and saying no to bullying should rightly be part of civic moral education, moral education should not contained within the walls of schools. This project seeks to bring education to where it is most needed, the social media platforms themselves. 

An overview of the project's approach is provided in the image below: 

![image](image.png)
