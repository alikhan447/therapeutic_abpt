# therapeutic_abpt
# Leveraging NLP to build a stronger therapeutic alliance between patient and therapist in online psychotherapy 

Online therapy has seen a significant increase in popularity post the COVID-19 pandemic, making it the preferred option for mental healthcare. Despite therapeutic interventions being pivotal in the mental health domain, it is often challenging to assess. Traditional evaluation methods are reliant on self-reports or expert opinions, both of which can be biased or subjective. Our proposed research is intended to fill the gap between mental health care and data-driven decision-making, contributing to the betterment of mental health services.  Our proposed research is intended to fill the gap between mental health care and data-driven decision-making, contributing to the betterment of mental health service.

# Contribution and Motivation
The proposed project is well-situated within existing research yet offers a novel application of NLP techniques. As highlighted above, existing research on the efficacy of psychotherapy is outcome driven. Also, existing work has been limited to analyzing full-length therapy sessions. With online chatting platforms becoming the norm for easy counseling, we aim to focus on driving efficacy for chat-based therapy. We want to focus on ensuring a stronger alliance between the patient and therapist by leveraging NLP to quantify the various pillars of this alliance- **empathy**, **actionability**, **clarity**, **relevance**.


# Dataset Description: 
We will utilize the dataset highlighted in the article ["Counsel Chat: Bootstrapping High-Quality Therapy Data"](https://towardsdatascience.com/counsel-chat-bootstrapping-high-quality-therapy-data-971b419f33da)  The dataset consists of approximately 2130 responses from therapists on questions asked by seekers across multiple domains from [counsel-chat](https://github.com/nbertagnolli/counsel-chat/blob/master/README.md)

There are **31 topics** on the forum, with the number of posted responses ranging from 317 for the topic of “depression” to 3 for “military issues”. There are **307 therapist contributors** on the site, most of whom are located on the West Coast of the US (Washington, Oregon, California). They range in licensing from Ph.D. level psychologists, social workers, and licensed mental health counselors


[Counselchat.com](https://towardsdatascience.com/counsel-chat-bootstrapping-high-quality-therapy-data-971b419f33da) is an example of an expert psychotherapy community. It is a platform to help counselors build their reputation and make meaningful contact with potential clients. On the site, therapists respond to questions posed by clients, and users can like responses that they find most helpful. 
The dataset is presented as a CSV with **10 columns** described below:

The columns contain:

Column | Header         | Description
:-----:|----------------|--------------------------------------------
1      | questionID     |  A unique question identifier which is distinct for every question
2      | questionTitle  | The title of the question on counsel chat
3      | questionText   | The body of the individual’s question to counselors
4      | questionLink   | A URL to the last location of that question 
5      | topic          | The topic the question was listed under
6      | therapistInfo  | The summary of each therapist, usually a name and specialty
7      | therapistURL   | a link to the therapist’s bio on counselchat
8      | answerText     | The therapist response to the question
9      | upvotes        | The number of upvotes the answerText received  
10     | views          | The number of views the answerText received

