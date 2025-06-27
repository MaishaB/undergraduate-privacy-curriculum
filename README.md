# Reshaping the Privacy Mindset of Computer Science Undergraduates

>Software applications, while being an integral part of the modern world, pose significant threats to end-user privacy. Thus, computer professionals require knowledge and skills to develop privacy-aware software. However, undergraduate computing degree programs often lack privacy-focused curricula that can cultivate this ability in the future workforce. Therefore, we designed a privacy curriculum informed by the common challenges that computing professionals face when developing privacy-embedded software. It guides students in realising the need for privacy, identifying privacy protection mechanisms and programming Privacy Enhancing Technologies (PETs). We piloted the curriculum for third-year Computer Science undergraduates at the University of Auckland, New Zealand. The curriculum was evaluated using course assessments and surveys conducted before and after the lessons. Overall, the students improved their understanding of privacy, especially technical aspects. Most of them valued the applied learning experience of the programming lessons yet showed distinct views on task completion difficulty and motivation to do programming. Students recognised that privacy should be integral to their skill set by confirming the importance and relevance of the lessons. However, their perceived responsibility in privacy protection varied depending on their intention to take proactive measures. Based on the results, the paper suggests improvements to the proposed curriculum.

## Folder Structure
### 1. Lessons
The lessons in the curriculum guide students in understanding the need for privacy, identifying existing privacy protection mechanisms, and programming PETs (K-anonymity, Pseudonymisation and Differential Privacy). The lecture slides of the following lessons are included in the "Lessons" folder.

* Lecture 1 - Introduction to Privacy
* Lecture 2 - Data Privacy Protection
* Lecture 3 - Privacy Enhancing Technologies
* Lecture 4 - Pseudonymisation and K-Anonymity 
* Lecture 5 - Differential Privacy

### 2. Programming Exercises
Programming excercises related to Pseudonymisation, K-Anonymity and Differential Privacy were conducted in Jupyter. These excercises are available in the "Programming Exercises" folder. The datasets required for these excercises are also included in the folder. Use Jupyter Notebook or JupyterLab to run the provided notebooks.

### 3. Tutorial
The tutorial session was a revision of the lectures, in which the students were given time to complete eight questions: six multiple choice and two essay type. Please note that Question 7 ("Tracking John") is a key exercise in this tutorial, designed to show the real-world privacy risks of data sharing. To complete Question 7, use the given notebook and the dummy GPS dataset. Visualizing the location data and answering the questions in the notebook will demonstrate how much people are exposed when sharing data.

### 4. Assessments
The curriculum uses four types of assessments to evaluate the learning outcomes: optional exercises, mid-semester test (MST), assignment and the final exam. The "Assessments" folder includes all of these assessments. The assignment can be opened using Jupyter Notebook or JupyterLab. The folder includes assessment questions only. For answers or guidance, kindly reach out to the authors. The following table includes the learning outcomes assessed by the assessments.

![image](https://github.com/user-attachments/assets/2dc3807c-6db7-4dba-9aa2-1507611fdf7d)

## Install Anaconda
The Anaconda package includes Jupyter Notebook and JupyterLab. Installation instructions are available in : [Click here](https://docs.anaconda.com/anaconda/install).

### Start Jupyter Notebook / JupyterLab
- Windows: Launch the "Anaconda Prompt" from the start
  menu and run `jupyter notebook` for Notebook or `jupyter lab` for JupyterLab
  
- MacOS / Linux: Launch a terminal and run the `jupyter notebook` for Notebook or `jupyter lab` for JupyterLab

## License
This repository uses **two licenses**:

- **MIT License** for source code and programming exercises. See [LICENSE](./LICENSE).
- **Creative Commons Attribution 4.0 (CC BY 4.0)** for other educational materials (e.g., slides). See [LICENSE-DOC](./LICENSE-DOC).

You are free to use, adapt, and redistribute these materials with proper attribution.
