# openinterpreter
Openinterpreter hackathon
Telegram Chatbot - codes generated by open-Interpreter using prompts connected to GPT-4 using interpreter.chat() open-Interpreter feature. 

<img width="1087" alt="Screen Shot 2023-10-13 at 11 13 36 AM" src="https://github.com/datasci888/openinterpreter/assets/119770980/9742e0fd-db80-4c27-8270-c65c45b7e74e">

# Video demo detailed:

[![Watch the video](https://img.youtube.com/vi/Im4DuIj74xg/0.jpg)](https://youtu.be/Im4DuIj74xg?si=zGgDCU5fcNgO_mtm)

# AISmartTaskTask
AI-powered task manager with notifications, document analysis, and task visualization developed using open-Interpreter tool. 

# Features:
-  Dynamic Task Management: Effortlessly add, edit, and organize tasks with due dates, tags, and project lists. 
￼
-  Task Prioritization: Never miss a beat with AI-driven task prioritization that ensures you focus on what matters most. 
￼
-  AI-Powered Task Suggestions: Personalized task recommendations that evolve with your preferences and needs. 
￼
-  Document Parsing: Manage information overload with text document summaries and essential keyword extraction. 
￼
-  Visualized Task Priorities: Get a crystal-clear view of your tasks, so you always know where to start. 
￼
-  Continuous Learning: Access knowledge modules through web scraping for lifelong learning. 
￼
-  Feedback Welcome: Interact and contribute to our constant system improvement.

# Dependencies:
- datetime
- time
- requests
- telegram
- openai
- matplotlib
- BeautifulSoup4
- re

# Configuration:
Before running the application:
- Replace Your OpenAI API Key with your OpenAI API key.
- Replace Your Telegram Bot Token with your Telegram bot token.
Class Structure:
- TaskManager: Handles adding, prioritizing, organizing, and retrieving tasks.
- Task: Represents a single task with name, deadline, and priority.

# To Run: Open the Telegram Bot:
```python
t.me/AI_Task_Manager_Bot
```
# Telegram Bot Commands:
- /start: Start the AI Task Manager.
- /help: Show available commands.
- /add_task: Add a new task (e.g., /add_task Buy groceries, 2023-12-31, 2)
- /list_tasks: List tasks.
- /delete_task: Delete a task by ID (e.g., /delete_task 1)
- /update_task: Update a task by ID (e.g., /update_task 1, New Task, 2023-12-31, 2)
- /document: Analyze a document with keywords (e.g., /document Sample document text. Keyword1; Keyword2; Keyword3)
- /feedback: Provide feedback on AI decisions.
- /upcoming_tasks: List upcoming tasks.
