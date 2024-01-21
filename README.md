﻿# ResumeScreening for Competitive Job Application
 ![](manual-resume-screening-1110x577.jpg)
Screening resumes in accordance with the job description supplied by the business is a recruiter's first responsibility. This job posting may be for any industry, vertical, or geographic location. To obtain resumes, the recruiter must either publish it on any online job platform or search the database maintained by several sourcing firms. A job seeker might apply immediately for a position after seeing it posted on an online employment marketplace. But hundreds of resumes are sent in with this posting, which makes a recruiter's job very difficult and time-consuming. The resume screening procedure is done manually.
A recruiter must review each résumé in order to determine which one best fits the job description. This is a tiresome and time-consuming operation. Let's examine the backend operations of the resume screening process.
- A single job ad may receive up to 250 applications. Examining each résumé takes about ten minutes.
- Out of more than 250 resumes, 4–6 are shortlisted. These four to six resumes will result in a job offer.
- It is an enormous challenge to select 4-6 resumes from 250+ resumes. Since experienced resumes typically run two to three pages, it is nearly impossible for recruiters to review every single one. They therefore use keyword search.
  Not everyone is skilled at writing resumes, and each job description contains a unique collection of keywords that may or may not be found in a worthy application. As a result, strong resumes can occasionally be overlooked owing to    keyword   searches.
- Recruiters typically do not screen resumes further if, after reviewing the first 50 resumes, they identify four to six eligible resumes. This lowers the likelihood of having a strong resume selected even more.It takes a minimum of one day to manually screen fifty resumes. Therefore, it is nearly impossible for a recruiter to review every single résumé.It is quite normal to have some bias anywhere there is human involvement. It is so challenging to obtain an objective resume score.



In such cases ML based Resume screening model play a wise role and it can purify the submitted resumes based on various facts. **In this project we created a KNN and OnevsRest classifier based model( first we cleaned the resume contents to get rid of unnecessary annotations , spaces and also applied the NLP based TfidfVectorizer) which has attained 98.44% accuracy on test set. Here we tried to see the candidate's domain of expertise without raeding it explicitly.** 

## TFIDF( Great use in NLP):
In information retrieval, tf–idf or TFIDF, short for term frequency–inverse document frequency, is a numerical statistic that is intended to reflect how important a word is to a document in a collection or corpus.

tfidf score term for term i in document j=TF(I,j)*IDF(i)

where IDF:= Inverse document frequency

TF:=Term frequency

Let, a=Term i frequency in document j; and b=Total words in document j,then,TF(i,j):=a/b.

And let say d=total documents ; e=document with term i and f be log(base 2) operator, then,IDF(i):=f(d/e).i is the term and j is document.







