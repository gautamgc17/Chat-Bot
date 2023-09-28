# Chat-Bot

## Objective
Create a conversational interface to collect user information. The chat agent should guide users naturally and persuade them to provide information.

## Features
Designed a coherent conversation flow to collect Name, Email, Phone Number, Address, Date of Birth, and Education of the user. Used OpenAI's language model: GPT-4 for chat responses and to implement multiple roles like "Introduction Agent," "Information Gathering Agent," "Validation Agent," and "Formatting Agent."

## Prerequisites
Before running the application, you'll need the following:

- Python 3.10 installed
- OpenAI API key (set as environment variable OPENAI_API_KEY or directly import in jupyter notebook)
- Other required Python packages (install using pip install -r requirements.txt)


## Getting Started

**Step 1. Clone the repository to your local machine and then switch to code directory**

```
git clone https://github.com/gautamgc17/Chat-Bot.git 
cd Chat-Bot
```

**Step 2. Create a Virtual Environment and install Dependencies**

```
pip install virtualenv
```

Create a new Virtual Environment for the project and activate it.

```
virtualenv env
env\Scripts\activate
```
Once the virtual environment is activated, the name of your virtual environment will appear on left side of terminal.

Next, we need to install the project dependencies in this virtual environment, which are listed in `requirements.txt`.

```
pip install -r requirements.txt
```

**Step3. Set your OpenAI API key as an environment variable named OPENAI_API_KEY**

Create a file named _.env_ and store your [OpenAI API Key](https://platform.openai.com/account/api-keys) credentials in this file.

```
OPENAI_API_KEY = 'sk-'
```
In current code, we are directly using it in the jupyter notebook file. So you can place it in the code directly.


**Step 4. Run the application**

After installation of necessary libraries and setting up your OpenAI API key, just the run the cells sequentially for desired output.

 - Run the Code: Run the provided code, which includes a Panel-based user interface.
 - Start Chat: Begin the conversation by typing messages. The chat agents will interact with you to collect information.
 - JSON Summary: When prompted, the chatbot will generate a JSON summary of the collected information, which is then saved as a CSV file.

## Sample Output

![1](https://github.com/gautamgc17/Chat-Bot/blob/503ed6d0e9ab6ba0e4bad013be3b3ba31e9b075c/assets/1.PNG)

<br>

![1](https://github.com/gautamgc17/Chat-Bot/blob/503ed6d0e9ab6ba0e4bad013be3b3ba31e9b075c/assets/2.PNG)

<br>

![1](https://github.com/gautamgc17/Chat-Bot/blob/503ed6d0e9ab6ba0e4bad013be3b3ba31e9b075c/assets/3.PNG)

<br>

![1](https://github.com/gautamgc17/Chat-Bot/blob/503ed6d0e9ab6ba0e4bad013be3b3ba31e9b075c/assets/4.PNG)

<br>

![1](https://github.com/gautamgc17/Chat-Bot/blob/503ed6d0e9ab6ba0e4bad013be3b3ba31e9b075c/assets/5.PNG)


