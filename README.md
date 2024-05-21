# RECIPE4U 
This is an official repository of [RECIPE4U: Student-ChatGPT Interaction Dataset in EFL Writing Education](https://arxiv.org/abs/2403.08272) (LREC-COLING 2024) and [Exploring Student-ChatGPT Dialogue in EFL Writing Education](https://gaied.org/neurips2023/files/19/19_paper.pdf) (GAIED @ NeurIPS 2023)

## Dataset 

### Attributes

| Column Name    | Type    | Description                                                                                                                                    |  
|:--------------:|:-------:|:-----------------------------------------------------------------------------------------------------------------------------------------------|
| sample_id      | String  | A unique identifier with the composition of student_id, course, week, session, and idx.                                                        |
| course         | String  | A course information that a student is enrolled in. IRW for Intermediate Reading & Writing, AW for Advanced Writing, SW for Scientific Writing.|
| student_id     | Integer | A numerical value to identify student.                                                                                                         |
| week           | Integer | The week number that the conversation is done                                                                                                  |
| session        | Integer | The session number that the conversation is done within the week.                                                                              |
| idx            | Integer | The utterance number within one session.                                                                                                       |
| chatgpt_before | String  | An utterance of ChatGPT before a student's utterance                                                                                           |
| user           | String  | An utterance of a student after receiving ChatGPT response                                                                                     |
| chatgpt_after  | String  | An utterance of ChatGPT after a student's utterance                                                                                            |
| rating         | Integer | A student's self-rated satisfaction on ChatGPT response on a 5-Likert scale                                                                    |
| intent_final   | String  | An annotation of students' intention based on a student's utterance                                                                            |
| is_quiz | Boolean | Whether a student asked ChatGPT for the answer to the quiz.                                                                                           |
| is_essay_edit  | Boolean | Whether a student made edits on their essay after receiving a response from ChatGPT.                                                           |
| essay          | String  | A student's written essay.                                                                                                                     |

### Statistics

|                       | # of Samples   |
|:---------------------:|:--------------:|
| # of dialogues        | 504            |
| Total # of utterances | 4,330          |
| Total # of tokens     | 380,364        |
| Total unique tokens   | 16,118         |

### Languages
English, Korean  

## How to download? 
- Please submit the [consent form](https://forms.gle/4p2tq93prsdH4Dc5A). After reviewing your consent form, we will send you the dataset link soon through email.

## Ethical Consideration
- We do not condone any malicious use of our dataset. To prevent the potential risk associated with student-written essays, only researchers or practitioners who submit a consent form can access our data. RECIPE4U is available for **research purposes only**.

## BibTex
```
@inproceedings{han-etal-2024-recipe4u-student,
    title = "{RECIPE}4{U}: Student-{C}hat{GPT} Interaction Dataset in {EFL} Writing Education",
    author = "Han, Jieun and Yoo, Haneul and Myung, Junho and Kim, Minsun and Lee, Tak Yeon and Ahn, So-Yeon and Oh, Alice",
    booktitle = "Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)",
    month = may,
    year = "2024",
    address = "Torino, Italy",
    publisher = "ELRA and ICCL",
    url = "https://aclanthology.org/2024.lrec-main.1193",
    pages = "13666--13676",
}
```
