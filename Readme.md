# Multi-Agent Article Creation using crewAI

This project demonstrates how to use the crewAI framework to create a multi-agent system for researching, writing, and proofreading an article.

## Overview

The project consists of three agents: a Planner, a Writer, and an Editor, each with their own specific tasks:

1. **Planner**: Responsible for creating a detailed outline for the article.
2. **Writer**: Tasked with writing a comprehensive article based on the provided outline.
3. **Editor**: Responsible for proofreading and refining the article for clarity, coherence, and style.

The crewAI framework is used to manage the communication and coordination between these agents, ensuring a seamless collaboration process.

## Requirements

- Python 3.7 or higher
- crewAI library
- OpenAI API key

## Installation

1. Clone the repository:

```
git clone https://github.com/your-username/multi-agent-article-creation.git
```

2. Set your OpenAI API key as an environment variable:

```
export OPENAI_API_KEY="your-api-key-here"
```

## Usage

1. Open the Jupyter Notebook file:

```
jupyter notebook multi-agent-article-creation.ipynb
```

2. Run the cells in the notebook to create the agents, define the tasks, and kickoff the crew.

3. The resulting article will be displayed in the notebook output.

## Customization

You can customize the agents' backstories, goals, and task descriptions to fit your specific article creation needs. Additionally, you can modify the code to include more complex workflows or additional agents as required.


