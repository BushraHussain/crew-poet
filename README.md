# Poem Agent

**Poem Agent** is an intelligent, creative AI-driven agent developed using Crewai and UV. It generates beautiful, meaningful, and context-aware poems on demand. Whether you're looking for a personalized poem, exploring different poetic styles, or seeking inspiration, Poem Agent delivers remarkable results with cutting-edge AI technology.

## Features

- **Creative Poetry Generation**: Generate poems as per given sentence count
- **Export Options**: Save poems in text file

## How It Works

1. **Input**: Provided hard coded input for learning purpose.
2. **Processing**: Poem Agent uses Crewai and UV to analyze the input, sentence count and craft a unique, high-quality poem.
3. **Output**: The generated poem is displayed in the terminal and saved in the poem.txt file.

## Installation

To use Poem Agent, follow these steps:

### Prerequisites

- Python 3.8+
- Crewai and UV libraries installed

### Clone the Repository
```bash
$ git clone https://github.com/your-username/poem-agent.git
$ cd poem-agent
```

### Set Up Environment Variables
Create a `.env` file in the root directory and include the following variables:

```env
OPENAI_API_KEY=your_openai_key
```

### Run the Application

#### Backend
```bash
$ uv run kickoff
```
### Output
Please review poem.txt file for output poem generated by poem agent

## Technologies Used

- **Backend**: UV, Crewai, OpenAI API
---

Enjoy creating poetry with **Poem Agent**!
