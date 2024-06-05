HOW TO RUN THE CODE 
1) Get the suitable Environment to run this project like visual Studio Code, jupyter 
notebook or Google collab 
2) install the packages  
! pip install langchain  
!pip install openai !pip install gradio  
!pip install huggingface_hub import os import re import 
3) Import the required packages 
import os 
import re 
import requests 
import json 
import gradio as gr 
from langchain import LLMChain, PromptTemplate 
from langchain.memory import ConversationBufferMemory 
from langchain.chat_models import ChatOpenAI 
3) Get the OpenAI API key from https://platform.openai.com/account/api-keys 
4) get the PlayHT User ID and playHT Key from https://play.ht/ , 
https://play.ht/studio/api-access 
5) Get the existing Voice Clone ID from  https://docs.play.ht/reference/api-list
cloned-voices 
6) set the template and logic for the chatbot 
7) Then run the given code upto the last shell after making sure that all the 
requirements available 
