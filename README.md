# Prompt Engineering Hate Speech Detection for 2020 Presidential Election

For this project I engineered an prompt to detect hate speech from a study of tweets during the 2020 presidential election using OpenAI's GPT-4 in a python notebook.

I used data from a study entitled “Hate Towards the Political Opponent:
A Twitter Corpus Study of the 2020 US Elections on the Basis of Offensive Speech and Stance
Detection" in the Association for Computational Linguistics Journal by Laura Grimminger and
Roman Kingler. The data included tweets from the 2020 Election cycle regarding 3 candidates:
Donald Trump, Joe Biden, and Kanye West. The tweets were labeled across two dimensions:
Stance Detection (Favor, Against, Neither, Mixed, Neutral) and Hateful (Hateful, Not Hateful.)
For this project I wanted to see if I could reproduce or improve their results with a prompt I gave
to OpenAI’s GPT-4 as well as expanding the study across three new dimensions: Discrimination
Type (General, Sexist, Sexual Harassment, Homophobic, Racist, Transphobic, Ableist,
Intellectual, Ageism), Severity (Mild, Moderate, Severe), and Directedness (Implicit, Explicit.)
These new categories gave me new insights into the tweets as well as new ways to test the
model.

In this repository:

1. data_source: contains the original study details and the data-sets
2. analysis: contains my python code, input data, and model results
3. write-up: a description of the project, what I did and why.
