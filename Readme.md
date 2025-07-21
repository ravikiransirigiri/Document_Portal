## Project Setup Guide

# Create Project Folder and Environment Setup

    # create a new project folder

    mkdir <project_folder_name>

    # move into the project folder
    
    cd <project_folder_name>

    # open the folder in vs code
 
    code .

    # create a new conda environment with python=3.10 -y

    # activate the new conda environment(use full path to the environment)
 
    conda actiavte <path_of_the_env>

# Install the dependencies from requirements.txt
pip install -r requirements.txt

# Intialize the Git 
 git init

# Stage all files
git add .
# commit chanegs
git commit -m "<write your commit message>"
# Push to remote(after adding the origin)
git push -u origin main

## Minimum Requirements of the project
## LLM Models
    Groq
    OpenAI
    GEMINI
    Claude
    HuggingFace
    Ollama
## Embeddding Models
    OpenAI
    Hugging Face
    Gemini

## Vector Databases
    In-Memory
    On-Disk
    Cloud-Based

## API Keys
    Groq API 
    Gemini API
    OpenAI API


