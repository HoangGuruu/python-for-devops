Link video : https://youtu.be/7FVPn25mmEQ?si=ZueM6aXvVd_HJ8P3
Link tutorial : https://blog.futuresmart.ai/beginners-guide-to-fastapi-openai-chatgpt-integration


# TABLE OF CONTENTS
Step 1: Setup
Step 2: Creating the API
Step 3: Integrating with OpenAI ChatGPT
Step 4: Running the API and Making Requests
Accessing the Swagger UI Documentation

# Step 1: Setup
- Launch an instance : 
```
fastapi_demo
Amazon Linux 2023
Allow : 22 , 80 , 8000
```

```
python3 -m venv fastenv
source fastenv/bin/activate
# fastapi
# uvicorn
# openai
pip install -r app/requirements.txt
# or
python3 -m pip install -r app/requirements.txt
```
# Step 2: Creating the API

```
git clone {url}
```
```
uvicorn main:app --host 0.0.0.0 --port 8000
nohup uvicorn main:app --host 0.0.0.0 --port 8000 --reload &
nohup uvicorn app.main:app --host 0.0.0.0 --port 8000 --reload &
```