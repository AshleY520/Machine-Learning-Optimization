# Machine-Learning-Optimization Pre- class task

I successfully launched a FastAPI application locally and exposed it to the internet using ngrok.
When I visited the generated ngrok link, I got the expected response {"Hello": "World"} from the root endpoint.

Compared to the original Colab version, I made several changes:

1. Switched from Colab to local Jupyter Notebook
2. Replaced manual token input with .env and load_dotenv() for secure authentication
3. I completed the TODO by creating a function called vqa_predict(text, image) that takes text and a PIL image as input and returns the predicted answer from the VILT model. 
4. Used nest_asyncio and threading to run FastAPI inside a notebook


Everything works as expected so far.


<img width="497" alt="Screenshot 2025-06-26 at 10 14 59 PM" src="https://github.com/user-attachments/assets/cd7843e0-f2ed-4496-9481-62d9ff19ea8a" />
