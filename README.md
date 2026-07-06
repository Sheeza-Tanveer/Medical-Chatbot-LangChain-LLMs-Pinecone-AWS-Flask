# Medical-Chatbot-LangChain-LLMs-Pinecone-AWS-Flask

# Setting Up the Virtual Environment

Follow these steps to create and activate the Conda virtual environment for this project.

## 1. Create a Conda Environment

```bash
conda create -n medibot python=3.10 -y
```

## 2. Activate the Environment

### Windows (PowerShell, Command Prompt, or Anaconda Prompt)

```bash
conda activate medibot
```

### Git Bash

If you are using Git Bash for the first time, initialize Conda:

```bash
conda init bash
```

Close and reopen Git Bash, then activate the environment:

```bash
conda activate medibot
```

## 3. Install Project Dependencies

```bash
pip install -r requirements.txt
```

## 4. Verify the Installation

Check the installed Python version:

```bash
python --version
```

It should display:

```text
Python 3.10.x
```

## 5. Deactivate the Environment

When you're done working on the project:

```bash
conda deactivate
```