### &nbsp;**AI Career Coach**



!\[Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)

!\[Flask](https://img.shields.io/badge/Flask-WebApp-lightgrey?logo=flask)

!\[OpenAI](https://img.shields.io/badge/OpenAI-GPT--4o-blueviolet?logo=openai)

!\[Hosted on AWS](https://img.shields.io/badge/Deployed-AWS%20EC2-FF9900?logo=amazon-aws)



🎯 A smart, AI-powered career coaching assistant that reads your resume and provides personalized suggestions, answers questions, and summarizes your experience — all in one click.



🔗 \[Live Demo][click here to see](http://16.171.148.139:8082)---



&nbsp;**📸 Screenshot**



!\[Project Screenshot](career-coach-preview.jpg)







#### &nbsp;Features:



\-  Upload your resume in PDF format

\-  Uses LangChain + GPT-4o to understand and summarize your resume

\-  Ask questions about your resume (e.g. "What are my strengths?", "Suggest roles that suit me")

\-  Get AI-generated improvement tips

\-  Flask backend deployed to AWS EC2







#### &nbsp; Tech Stack :



\- Python 3.9

\- Flask

\- OpenAI GPT-4o (via API)

\- LangChain

\- FAISS (Vector Store)

\- PyMuPDF for PDF parsing

\- HTML/CSS for front-end (Jinja templates)

\- Hosted on AWS EC2 (Ubuntu instance)



---



##### &nbsp;How It Works:



1\. Upload a PDF version of your resume.

2\. Text is extracted and chunked.

3\. LangChain + FAISS builds a searchable knowledge base.

4\. GPT-4o answers questions and gives suggestions.

5\. Everything is served via Flask and available online via an EC2 public URL.



---



##### Local Setup:



1.Clone the repo:



```bash

git clone https://github.com/AnushkaSingh80/AI-Career-Coach.git

cd AI-Career-Coach

2.Create a virtual environment:

``bash

python -m venv venv

source venv/bin/activate  # On Windows: venv\\Scripts\\activate

3.Install requirements:

``bash

pip install -r requirements.txt

4\. Set your OpenAPI key in a .env file:

OPENAI\_API\_KEY=(your generated key)

5\. Run the app:

``bash

python app.py

VISIT: http://localhost:5000 in your browser

----

#### Deployment:



This project is deployed on an AWS EC2 Ubuntu instance using:



Gunicorn + Flask



Nginx reverse proxy



.env for API key management





For help deploying your own Flask app to EC2, message me .

#### 

### AUTHOR:

ANUSHKA SINGH

[Linkedin](https://www.linkedin.com/in/anushka-singh-b93436323)



