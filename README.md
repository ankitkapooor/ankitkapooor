- 👋 Hi, I’m Ankit Kapoor
- :mortar_board: I'm studying at BITS Pilani, Dubai
- 👀 I’m interested in [programming](https://github.com/ankitkapooor?tab=repositories), [philosophy](https://drive.google.com/file/d/1QkIRKiBdjOmPYoiXYucs81Yi2WrMXGFr/view?usp=sharing), [literature and creative writing](https://www.instagram.com/kapooooooooor/)
- 🌱 I’m currently learning multiple subjects including AI, Data Science and Machine Learning
- 💞️ I’m looking to collaborate on projects based on NLP, or any other innovative ideas encompassing the concepts of AI and data science
- 📫 email me at ankitkapoor0406.ak@gmail.com, or hit me up on my [LinkedIn profile](https://www.linkedin.com/in/ankitkapooor/)
- :computer: Go **[here](https://github.com/ankitkapooor/ankitkapooor/blob/main/cv_example.ipynb)** to see the resume in action

~~~python
#Resume

class Ankit:
  def __init__(self):
    self.name = "Ankit Kapoor"
    self.age = 22
    self.gender = "Male"
    self.phone_number = 543030659
    self.email = "ankitkapoor0406.ak@gmai.com"
    self.github = "GitHub"
    self.linkedin = "LinkedIn"

    skills = ["Python", "Java", "C", "HTML", "Json",
              "MySQL", "KERAS", "NUMPY", "TensotFlow",
              "Natural Language Processing", "AI", "ML"]

  def education(school_name):
    school = {}

    school["BITS Pilani, Dubai"] = ["B.E.", "Computer Science", "N/A", "7.46", "2018 - 2020"]
    school["Hislop College"] = ["Class XII", "PCM", "Maharashta State", "78%", "2018"]
    school["Bhavans BP Vidya Mandir"] = ["Class X", "N/A", "CBSE", "96%", "2016"]

    return f'School Name: {school_name}\nCourse: {school[school_name][0]}\nSpecialization: {school[school_name][1]}\nBoard: {school[school_name][2]}\nScore: {school[school_name][3]}\nYear: {school[school_name][4]}'

  def work_experience(company_name):
    organisations = {
    "SustVest": ["Front End Development Intern", "Dubai, UAE", "June 2021 - August 2021"],
	#Project Intern for front end development, Coding in HTML/CSS, Figma, report writing
    "Ascent Business Solutions": ["RPA Intern", "Nagpur, India", "May 2020 - June 2020"],
    	#Project Intern for RPA (Robotic Process Automation) Projects, basic coding, report #writing
    "Infinite Space": ["Content Management Intern", "Nagpur, India", "July 2018"],
    	#Assistance with organization of events (seminars, guest talks etc.), handling social #media posts, writing passages for posts/blogs.
    "Ascent Business Solutions": ["Front End Development Intern", "Nagpur, India", "July 2018"]
    	#Project assistant for Websites & front end projects, Basic HTML/CSS, website debugging, #report writing

        }
    return f'Company Name: {company_name}\nPosition: {organisations[company_name][0]}\nLocation: {organisations[company_name][1]}\nDate: {organisations[company_name][2]}'

  def project():
    project_list = [
      "MedBot using GPT-2 (Sem VII)",
        #Created a smart chatbot that implements NLG through a distilled version of GPT-2. It can #hold conversations and generate replies based on medical #queries. Ongoing part of my #Thesis.
      "Smart Chatbot in Python (Self, 2021)",
        #A smart chatbot that uses NLP and neural network to communicate with the user. It is #completely voice activated and can scrape Google and #YouTube.
      "Smart Discord Bot (Self, 2021)",
        #A smart chatbot hosted on Discord, uses NLP to perform #basic human communication. It #also uses the bot also has multiple functions like displaying movie recommendations, #Wikipedia articles, jokes/memes.
      "NLG Bot in python (Self, 2022)",
        #Created a smart chatbot that implements NLG through a distilled version of GPT-2. It can #hold conversations through replies it generates by itself #based on user queries.
      "Heart Disease Prediction (Sem VII)",
        #Co-authored a research paper which explores and compares various machine learning #algorithms used to predict heart disease in patients.
      "Movie Recommender System (Sem VII)",
        #This is a movie recommender system that works on the basis of the KNN (K Nearest #Neighbors) algorithm. Recommends 20 movies based on user input #and user ratings.
      "BigF Compiler (Sem VI)",
        #BigF is a small step I took in designing my own computer programming language. Converts #BigF (my language) to C code.
      "Wordle Solver (Self, 2022)"
        #Programmed an automated way to tackle the popular puzzle #game called Wordle.
      "Collatz Conjecture (Self, 2021)"
        #Coded a program in Java and Python which uses the Collatz conjecture to procedurally #generate patterns.
        ]
    return '\n'.join(project for project in project_list)

  def extra():
      '''
          •	Written and published a fiction novel named “The Book of Destiny”, published by Notion Press Chennai in 2015
          •	Taught rural and underprivileged children in a village near the district Tons with INME in 2017
          •	Participated in Google Hashcode, 2019
          •	Completed a course on Philosophy on Coursera
          •	Wrote for Perspectives, the BPDC magazine in 2018
          •	Completed online courses for ML & AI, and English creative writing from MyCaptain in 2017
          •	Volunteered with Rotary Club of Nagpur North to distribute supplies and helped create makeshift
          •	tarpaulin ceilings for slums during monsoon
          •	Member of Quizzards, the BPDC quiz group (2018-present)
      '''
      return 'type help(Ankit.extra) to see hobbies'

~~~

<!---
ankitkapooor/ankitkapooor is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
