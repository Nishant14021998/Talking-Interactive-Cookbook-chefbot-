# Title: Talking-Interactive-Cookbook-chefbot-

## Group 15  
- **Nishant Pandey**  
- **Ayush Chakraborty**  
- **Vikram Pathak**

---

## Project Overview

This project is an **Interactive Cookbook** that allows users to explore recipes, ingredients, and step-by-step instructions interactively. Additionally, users can ask questions related to the recipe, and the ChefBot responds with the help of Google Generative AI (gemini-1.5-flash) to provide contextual answers. The bot can also direct users to YouTube and Google search results for further learning.

### Key Features:
- **Recipe Exploration**: Users can input a recipe URL and view the ingredients and step-by-step instructions.
- **AI-Powered Q&A**: Users can ask recipe-related questions, and the ChefBot will provide AI-generated answers.
- **YouTube and Google Integration**: Users can get links to YouTube tutorials and Google search results for further guidance.
- **Interactive Conversation**: The system enables a dynamic conversation, allowing users to choose different options like viewing ingredients, steps, asking questions, or exiting the conversation.

### Tech Stack:
- **Python**: Core logic and interaction
- **Google Generative AI**: Used for answering questions based on recipe context
- **BeautifulSoup**: Used for web scraping the recipe content from supported websites
- **Requests**: For making HTTP requests to fetch recipe data
- **Command-line Interaction**: Allows users to interact with the bot in real-time

---

## Usage

1. **Fetch Recipe Data**: Input the URL of a recipe from a supported website.
2. **Explore Recipe**: Choose to explore the ingredients, steps, or ask questions.
3. **Get AI Answers**: Ask ChefBot any questions about the recipe context and receive AI-generated responses.
4. **Further Learning**: ChefBot provides relevant YouTube or Google search links for questions starting with "how to" or "what is".

### Example Commands:
- View ingredients: `1` or `ingredients list`
- View steps: `2` or `step-by-step instructions`
- Ask a question: `3` or `ask a question`
- Exit: `4`, `quit`, or `exit`

---

## Requirements

To run the Interactive Cookbook, install the following Python dependencies:
beautifulsoup4==4.9.3
requests==2.25.1
google-generativeai==0.1.0


To install the required packages, run:

```bash
pip install -r requirements.txt

python interactive_cookbook.py

