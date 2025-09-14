# Build project:
Vì kích cỡ dự án quá lớn nên sẽ để link ở Drive.
Download : https://drive.google.com/drive/folders/1_xFmFWDMO6j5pCyokuJ3RAF8yAIvWauM?usp=sharing
## Step 1: Create virtual environment
`python -m venv venv`
## Step 2: Activate virtual environment
`.\venv\Scripts\activate`
## Step 3: Install library
`pip install -r .\requirements.txt`
## Step 4: Load database 
Go to link below to download sql file add to PostgreSQL
https://drive.google.com/drive/folders/10q2MExkVMS3LgR9sUOJYp_aDVxC5Sq63?usp=sharing
or file dump-postgres-202403130754.sql
## Step 5: Connect database 
Create .env file
Config connection to database with information from file .env.example 
Besides, add OPENAI_API_KEY in .env file
## Step 5: Run local project
`streamlit run Chatbot.py`
## Step 6: Upload files and use if necessary

![Result](image.png)

### Các câu hỏi dùng để thử hỏi:
1. Không đội mũ bảo hiểm đúng cách khi lái xe bị phạt bao nhiêu?
2. Vượt đèn đỏ bị phạt bao nhiêu?
3. Đi ngược chiều bị phạt bao nhiêu?

