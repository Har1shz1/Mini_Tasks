# Mini_Tasks

# Task 1.0
1. Obtain the Google Gemini API Key.
2. Set up the Python environment by installing the required libraries. (gemini, .)
3. Write simple Python code to call the Gemini API.
4. Explore and understand the different parameters of the Gemini API to control the output.
- Experiment with these parameters to learn how they work.
5. Learn how simple prompting works.
6. Finally, create a Python script to:
- Load text files.
- Summarize the content of the text files from Gemini (use publicly available text files from the internet).
  # Task 1.1
We don't add API keys to the code and we don't push them to GitHub.

T1.2.1: Create a '.env' file and store API keys there. Here it is the GEMINI API KEY.

T1.2.2: You have used the "gemini-pro" model. Refer to what LLM models are available with Google.

T1.2.3: Compare the output of at least two models and prepare a table for comparison (use the same temperature, top-k, and top-p values for each model). Things to consider:
- Speed of generation / Token per second
- Number of input tokens and number of output tokens for each model (I think you might know the term "token" from the previous task)
- Accuracy (To check accuracy, ask a question that you know the answer to, like "2+3 = ?" for math questions)Identify
- Try to identify what are the strong areas and areas lacking on those models.

Ex Output : (Don't need to stick to this)


|Model Name| Speed of Generation | Input Tokens | Output Tokens | Accuracy     |

--------------------------------------------------------------------------------
|Model 1   |     ..             |         ..     |         ..      |      ..       |


|Model 2   |         ..            |       ..       |        ..       |     ..        |

T1.2.E1: Learn the common vocabulary used with LLMs (Token, embedding, RAG, etc.)
https://www.vectara.com/glossary-of-lIm-terms

[GitHub Repo]

Create a separate folder for each task and add separate README.md files for each task where you write the results of those tasks.
platform enterprises
Glossary of LLM Terms
www.vectara.com

# Task 2.0

Second task might be challenging;
Focus on one step at a time. I will further breakdown the tasks

T2.0.1 Find feedback dataset from Kaggle or anywhere in the internet.
If you couldn't able to find on publicly available sources from ChatGPT Ul generate it.
Collect at least 100 feedbacks.

T2.0.2 first try to identify 'POSITIVE, NEGATIVE, and NEUTRAL sentiments just by prompt.
Example Prompt:
You are a expert sentiment analysis agent. You need to identify the sentiments of the given user feedbacks.
(feedback}.
Then categorize the sentiment into POSITIVE, NEGATIVE, or NEUTRAL.
*USE GEMINI API

T2.0.3 Then you should prepare a excel file with columns

feedback | LLM response


1. good service | POSITIVE
2. .....


T2.0.3 Then you should iteratiyely change the prompt until you get a satisfactory results 

Prepare separate excel files for each prompt with significant changes.

In excel First sheet should be the feedback | LLM response table 

Second sheet should be the prompt used

We will start from this

# Task 2.1

Task 2 - Create Sentiment Analysis Tool
You need to identify the POSITIVE, NEGATIVE, and NEUTRAL sentiments from given feedback.
Feel free to add modifications you think are necessary.
Here are some suggestions from me:

1. Additional Sentiments:
- IRRELEVANT: Feedback that doesn't pertain to the topic.
- HARMFUL: Feedback that contains offensive or harmful content.
- SUGGESTIVE: Feedback that provides suggestions or improvements.

2. Rating System:
- Suggest a rating based on the feedback (5 is best; 1 is low).

3. Emotion Detection:
- Identify specific emotions like happiness, anger, sadness, etc.

4. Presentation:
- Create a user interface where users can enter feedback and see the output.
- [Optional] If possible, create a simple GUI using any library you are familiar with.
- [Optional] Add pie charts and visualizations to the Ul.

[TASKS]

T2.1.1: Study Pydantic to get a structured output from LLM.

T2.1.2: Study Gemini Function calling to get structured output.

T2.1.3: Study LangChain to get structured output.

Use any of these methods to complete the project.
