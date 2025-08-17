# AIstuff
create envorment for local run then 
# Install required packages
pip install langchain-google-genai
# langchain not install then
pip install langchain

create gemeni api key from google AI Studio with run setting like(gemini-2.5-flash, gemini-2.5-pro...etc)

import package of google 
# from google import genai

set api key in env file or directly

# client = genai.Client(api_key="GEMINI_API_KEY")

Ask questions 

response = client.models.generate_content(
    model="gemini-2.5-flash", contents="what is capital of india"
)
Predition answer of question 
# print(response.text)

The capital of India is **New Delhi**.


