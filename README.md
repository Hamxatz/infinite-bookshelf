![License](https://img.shields.io/badge/license-MIT-green)

# Groqbook: Generate entire books in seconds using Groq and Llama3
 
Groqbook is a streamlit app that scaffolds the creation of books from a one-line prompt using Llama3 on Groq.


## Features

- 📖 Scaffolded prompting that strategically switches between Llama3-70b and Llama3-8b to balance speed and quality
- 🖊️ Uses markdown styling to create an aesthetic book on the streamlit app that includes tables and code 
- 📂 Allows user to download a text file with the entire book contents

### Technologies

- Streamlit
- Llama3 on Groq Cloud



[Demo of Groqbook](https://github.com/Bklieger/groqbook/assets/62450410/3adb11cd-8264-4289-a28a-49dc5b3cf453)
> Demo of Groqbook fast generation of book content


[Second Part of Demo of Groqbook](https://github.com/Bklieger/groqbook/assets/62450410/5b0147fb-90f3-4584-8572-fa452545d833)
> Demo of Groqbook downloading markdown-styled book


> [!IMPORTANT]
> To use Groqbook, you can use the hosted version at [groqbook.streamlit.app](https://groqbook.streamlit.app)
> Alternatively, you can run groqbook locally with streamlit using the quickstart instructions.


## Quickstart

### Hosted on Streamlit:

To use Groqbook, you can use the hosted version at [groqbook.streamlit.app](https://groqbook.streamlit.app)

### Run locally:

Alternative, you can run groqbook locally with streamlit.

#### Step 1
First, you can set your Groq API key in the environment variables:
GROQ_API_KEY = ```gsk_yA...```

This is an optional step that allows you to skip setting the Groq API key later in the streamlit app.

#### Step 2
Next, you can set up a virtual environment and install the dependencies.

~~~
python3 -m venv venv
~~~

~~~
source venv/bin/activate
~~~

~~~
pip3 install -r requirements.txt
~~~


#### Step 3
Finally, you can run the streamlit app.

~~~
python3 -m streamlit run main.py
~~~


## Example Generated Books:

| Example                                      | Prompt                                                                                                                                |
| -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| [LLM Example](Example_1.md)             |  The Basics of Large Language Models                                       |
| [Storytelling Chatbot](Example_2.md) | Data Structures and Algorithms in Java                                            |