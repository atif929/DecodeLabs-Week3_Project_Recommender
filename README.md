# Tech Stack Career Recommender

## Project Overview

This project is a Machine Learning-based Career Recommendation System that suggests suitable technology career paths based on a user's skills. The system uses TF-IDF (Term Frequency-Inverse Document Frequency) vectorization and Cosine Similarity to compare a user's skill set with predefined skill profiles of various technology roles.

The recommender analyzes the user's technical skills and identifies the most relevant career paths by calculating similarity scores between the user's profile and different job role descriptions.

This project was developed as part of the DecodeLabs AI Internship Program.

---

## Objectives

* Build an intelligent career recommendation system.
* Understand text vectorization using TF-IDF.
* Implement similarity-based recommendations using Cosine Similarity.
* Apply Natural Language Processing (NLP) concepts to career guidance.
* Help users identify technology career paths aligned with their skills.

---

## Features

* Interactive command-line interface.
* Accepts user skills as input.
* Supports skill validation and duplicate checking.
* Uses TF-IDF vectorization for skill representation.
* Calculates similarity scores using Cosine Similarity.
* Recommends the top 3 matching career paths.
* Displays ranking and match percentages.
* Includes a demo mode with sample user profiles.
* Covers multiple technology domains and job roles.

---

## Technologies Used

* Python 3.x
* Scikit-learn
* NumPy
* TF-IDF Vectorization
* Cosine Similarity
* Natural Language Processing (NLP)
* Recommendation Systems

---

## How It Works

The recommendation system follows a content-based filtering approach.

### Workflow

1. Store predefined technology job roles and associated skills.
2. Collect user skills through an interactive interface.
3. Convert job role descriptions into numerical vectors using TF-IDF.
4. Transform the user's skill profile into the same vector space.
5. Calculate similarity scores using Cosine Similarity.
6. Rank job roles based on similarity scores.
7. Display the top career recommendations.

### Recommendation Pipeline

```text
User Skills
     ↓
Skill Profile Creation
     ↓
TF-IDF Vectorization
     ↓
Cosine Similarity Calculation
     ↓
Role Ranking
     ↓
Top Career Recommendations
```

---

## Supported Career Roles

The system currently supports recommendations for:

* Data Scientist
* Machine Learning Engineer
* Data Engineer
* Backend Developer
* Frontend Developer
* Full Stack Developer
* DevOps Engineer
* Cloud Architect
* Cybersecurity Analyst
* AI Research Engineer
* NLP Engineer
* Computer Vision Engineer
* Android Developer
* iOS Developer
* Blockchain Developer
* Database Administrator
* System Administrator
* QA / Test Engineer

---

## Installation & Usage

### Clone the Repository

```bash
git clone https://github.com/atif929/DecodeLabs-Week3_Project_Recommender.git
```

## Sample Output

```text
==================================================
Tech Stack Career Recommender
==================================================

Enter your skills one by one.
Type 'done' when finished.

Skill 1: python
Skill 2: machine learning
Skill 3: tensorflow
Skill 4: sql
Skill 5: statistics
Skill 6: done

Your Skills:
['python', 'machine learning', 'tensorflow', 'sql', 'statistics']
```

### Recommendation Results

```text
==================================================
Recommended Career Paths
==================================================

1. Data Scientist
   Match Score: 0.8234 (82%)

2. Machine Learning Engineer
   Match Score: 0.7812 (78%)

3. AI Research Engineer
   Match Score: 0.7345 (73%)

--------------------------------------------------
Best Match: Data Scientist
Similarity Score: 0.8234
```

---

## Machine Learning Concepts Used

### TF-IDF Vectorization

TF-IDF converts textual skill descriptions into numerical vectors by measuring the importance of each skill within job role profiles.

### Cosine Similarity

Cosine Similarity measures the similarity between the user's skill profile and each job role profile by comparing their vector representations.

### Content-Based Recommendation

The system recommends careers based on skill similarity rather than user ratings or historical behavior.

---

## Future Improvements

* Add graphical user interface (GUI).
* Develop a web application using Streamlit or Flask.
* Allow resume upload and automatic skill extraction.
* Integrate LinkedIn profile analysis.
* Include job market demand analysis.
* Support personalized learning roadmaps.
* Recommend online courses for skill development.
* Expand the database with additional technology roles.

---

## Learning Outcomes

Through this project, the following concepts were practiced:

* Natural Language Processing (NLP)
* TF-IDF Vectorization
* Cosine Similarity
* Recommendation Systems
* Text Processing
* Feature Engineering
* Python Programming
* Machine Learning Fundamentals
* Content-Based Filtering

---

## Author

**Atif Rameez**
Software Engineering Student
Sukkur IBA University

GitHub: https://github.com/atif929

---

## License

This project is created for educational and internship purposes under the DecodeLabs AI Internship Program.
