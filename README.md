
# 🚀 ResumeSieve.ai — *Sift Smarter*  


[![Demo Video](https://img.shields.io/badge/Watch-Demo%20Video-red?logo=youtube&style=for-the-badge)](https://drive.google.com/file/d/1IB_5iu_c9TmkKagjNVzn5SgzOdY7Qvbk/view?usp=drive_link)

<br>

<p align="center">
  <img src="https://img.shields.io/badge/AI-Resume%20Filtering-blueviolet?style=flat-square"/>
  <img src="https://img.shields.io/badge/Python-Flask-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/React-Frontend-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/MongoDB-Database-brightgreen?style=flat-square"/>
</p>

> **Let us sort the resumes—smartly.**  
> An AI-powered tool designed to automate resume screening and ranking, saving recruiters time and boosting hiring accuracy.

---

## 📌 Table of Contents

- 🎯 Idea
- 🧠 About the Project
- 🚀 Getting Started]
- 🛠️ Technologies Used]
- ✨ Features
- 📊 Stats
- 🏗 Architecture
- 👩‍💻 Author

---

## 🎯 Idea

A regular day for a Recruiter consists of going through hundreds of resumes for a few specific roles to be hired. Only 10 to 15 percent of these resumes are relevant and suitable to the position they hire for. This takes up hours of a Recruiter’s time to filter out the top resumes out of the stack. So, the idea was to create an application that would screen and rank the resumes as per fitment with the help of AI.

---

## 🧠 About the Project

In a world where thousands of job listings are created daily, recruiters face a major challenge: identifying top candidates quickly.  
**ResumeSieve.ai** aims to eliminate that burden. Every day, thousands of Job Listings are created to help the companies meet the ever growing demand of market by recruiting fresh talent. The job of a Recruiter is a very hard and important. It’s like identifying a needle in a haystack. But in the age of Artificial Intelligence it can be eased out for them through our product, ResumeSieve.ai.

ResumeSieve.ai reduces the burden on a Recruiter by leaving the tedious and repetitive task of going through thousands of resumes, of which only are handful are relevant. Just upload all the CVs into the system and receive a list of names of candidates and their respective CVs in descending order of their relevance to the Job Description. Reduce your Recruitment Turn Around Time with just a click.



> Upload a batch of resumes + job description → Get a ranked list of the most relevant candidates.

✅ No more manual resume review  
✅ Reduced turnaround time  
✅ Scalable, AI-driven matching  

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Surbhijain00/ResumeSieve.ai.git
cd ResumeSieve.ai


## 🚀 Getting Started

Start developing locally.

#### Step 1: Clone the repo

Fork the repository. then clone the repo locally by doing -

```sh
git clone https://github.com/Surbhijain00/ResumeSieve.ai.git
```

#### Step 2: Install Dependencies

cd into the directory

```sh
cd ResumeSieve.ai
```

Install dependenices for Web-App

```sh
cd web-app/api
yarn install

cd ../client
yarn install
```

Install dependenices for Flask backend

```sh
cd middleware
pip install -r requirements.txt
```

#### Step 3: Setup .env

To run the server you will also need to provide the `.env` variables

- create a new file .env in the root
- open [.env.EXAMPLE](./webapp/api/.env.example)
- copy the contents and paste it to the .env with valid keys

#### And you are good to go

```sh
cd web-app/api
yarn dev
```

```sh
cd middleware
python app.py
```

## 🛠️ Technologies used

- Node
- Express
- MongoDB
- Typescript
- React
- Redux
- Ant Design
- Flask
- Numpy
- Docker

## 🚀 Features

- 2 Layer Filter Mechanism:
  - **Role-Based** – It features an AI classifier trained with 900+ resumes that can classify the resumes into 20 broad categories of Job roles with an accuracy of 95%.
  - **Similarity with Job Description** – It extracts the keywords from the inputted job description and maps them with resume based on cosine similarity(document similarity) to get a score percentage, which is used to sort and display the best resumes on top

- It can process up to 3000 resumes per hour
- Added Google OAuth and Password-based authentication to maintain the privacy
- Recruiters can export shortlisted candidates details, scores as CSV

## Stats
- Achieved an classification accuracy of 95%
- Tested on 20 classes of broad job categories and 900+ resumes
- Can process up to 3000 resumes per hour

## Architecture
- [Dataset Used](https://www.kaggle.com/gauravduttakiit/resume-dataset)
- [Architecture Design](https://user-images.githubusercontent.com/46809038/126433985-b84b832a-a029-479f-922c-c344ee88a21e.png)

## Author

- Surbhi Jain
