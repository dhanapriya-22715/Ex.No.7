# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Date:22-05-2026
# Register no:212224230056
# Aim:
To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.


# Explanation: 
Prompt:
"Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time."
Procedure:
1. Define the core requirements of a personal productivity assistant.
2. Identify and construct appropriate prompts for each task using an LLM (e.g., ChatGPT).
3. Simulate natural user interaction through a simple interface or command-line system.
4. Collect feedback or inputs from users and adapt responses accordingly.
5. (Optional) Integrate basic memory to simulate preference adaptation.
EXPECTED OUTPUT: - (attached the drive link)
Output (Example Response by LLM):
Personal Productivity Assistant Features:
1. Daily Task Manager:
o Accept tasks via natural language (e.g., "Remind me to call mom at 6 PM").
o Organize tasks by priority and deadline.
o Provide daily summaries and pending items.
2. Smart Scheduler:
o Schedule events and set reminders using contextual understanding.
o Notify user of overlapping appointments or free time slots.
3. Wellness Tips Generator:
o Suggest daily wellness advice (hydration, exercise, screen-time breaks).
o Adapt suggestions based on past user preferences and responses.

<img width="800" height="600" alt="wkrSthLSeUCsSBXp9DiK_3_ADwEk84MvyykaKBzewXUMSWwAx3eGYmmy3ynnz231HceuyhWiPWSmhq3B3b_GUN9Tld6ysel7nza3DchpKNU3_mUoVPPLaFxOHqofnBwFLkqXXrXqipxkV5Fpvi2cNju-1XRp8cx86SWBTEQUqb9H6UO7drCjJ1PI1ofdLXOP" src="https://github.com/user-attachments/assets/47013a29-5b38-4393-a178-8869d39e9f57" />

# Objective

The main objectives of this experiment are:

1. To understand the concept of prompt engineering.
2. To design prompts for different user requirements.
3. To create a productivity assistant capable of natural language interaction.
4. To simulate intelligent responses using a Large Language Model.
5. To demonstrate adaptive and personalized AI assistance.
6. To explore the practical applications of LLMs in everyday productivity tasks.

# AI Tools Required

* [ChatGPT](https://chatgpt.com?utm_source=chatgpt.com)
* Python Programming Language
* Visual Studio Code / Jupyter Notebook
* Streamlit or Flask (Optional for UI)
* OpenAI API / Gemini API (Optional)
* Internet Connection

# LLM :

Large Language Models (LLMs) are advanced AI systems trained on massive amounts of text data to understand and generate human-like responses. Prompt engineering is the process of designing effective instructions or queries that guide the AI model to produce accurate and meaningful outputs.Large Language Models (LLMs) are powerful AI systems capable of understanding and generating human language. They play an important role in modern AI applications such as chatbots, virtual assistants, education systems, and productivity tools. In this experiment, LLMs enable the productivity assistant to interact intelligently and provide personalized assistance.

<img width="1000" height="512" alt="image" src="https://github.com/user-attachments/assets/db88fdc5-e76a-4840-835f-48529c658d47" />

Prompt-based applications are increasingly used in:

* Education
* Healthcare
* Customer support
* Personal productivity
* Software development
* Content generation

In this experiment, a **Personal Productivity Assistant** is developed using prompt engineering concepts. The assistant helps users organize their daily routines and provides intelligent suggestions using natural language understanding.


# Problem Statement

People often struggle to:

* Manage daily tasks efficiently
* Remember important events and reminders
* Maintain healthy habits
* Organize study or work schedules
* Stay productive consistently

Traditional productivity applications require manual input and lack intelligent interaction. Therefore, an AI-powered productivity assistant can simplify these activities through conversational communication and personalized assistance.


# Proposed Solution

The proposed solution is a prompt-based AI assistant that:

* Accepts user instructions in natural language
* Understands user intent using LLMs
* Organizes and schedules tasks
* Provides reminders and productivity suggestions
* Generates wellness and motivational advice
* Adapts to user preferences over time

The system uses prompt engineering techniques to communicate effectively with the AI model.


# Explanation of the Prompt

## Main Prompt

“Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time.”

<img width="850" height="560" alt="image" src="https://github.com/user-attachments/assets/80150145-4a66-4e91-9271-e3c9c95027da" />


# Breakdown of the Prompt

| Prompt Component                           | Purpose                                 |
| ------------------------------------------ | --------------------------------------- |
| “Design a personal productivity assistant” | Defines the AI role                     |
| “help manage daily tasks”                  | Specifies task management functionality |
| “schedule reminders”                       | Enables scheduling features             |
| “suggest wellness tips”                    | Adds health-related assistance          |
| “answer general queries”                   | Enables conversational support          |
| “interact using natural language”          | Ensures user-friendly communication     |
| “adaptable to user preferences”            | Adds personalization capability         |



# System Architecture

## Components of the Application

1. User Interface
2. Prompt Processing Module
3. Large Language Model
4. Task & Reminder Manager
5. Wellness Suggestion Engine
6. Memory/Preference Storage


# Workflow of the Application

1. User enters a query or instruction.
2. The system converts the instruction into a structured prompt.
3. The prompt is processed by the LLM.
4. The AI generates a contextual response.
5. The response is displayed to the user.
6. User preferences are optionally stored for future interactions.

<img width="790" height="460" alt="image" src="https://github.com/user-attachments/assets/4be831a2-c0a6-4ec3-9e57-28fc736fb1a3" />


# Procedure

## Step 1: Requirement Analysis

Identify the features needed in the productivity assistant:

* Daily task management
* Reminder scheduling
* Wellness recommendations
* General-purpose query answering
* Adaptive response generation


## Step 2: Prompt Design

Construct prompts that guide the LLM effectively.

### Types of Prompts Used

## 1. Instruction Prompt

Used to directly instruct the AI to perform a task.

### Example

> “Create a to-do list for my college assignments.”

### Expected Output

* Assignment list
* Priority ordering
* Deadline reminders



## 2. Role-Based Prompt

Defines the role of the AI assistant.

### Example

> “Act as a productivity coach and help me plan my day.”

### Expected Output

* Motivational suggestions
* Time management advice
* Daily schedules


## 3. Contextual Prompt

Provides background information for personalized responses.

### Example

> “I am a student preparing for semester exams. Create a balanced study schedule.”

### Expected Output

* Subject-wise timetable
* Break periods
* Revision plans


## 4. Conversational Prompt

Used for natural interaction.

### Example

> “What tasks do I have pending today?”

### Expected Output

* List of pending tasks
* Reminder notifications


## Step 3: Develop User Interaction

A command-line or graphical interface is created where users can:

* Enter prompts
* Receive responses
* Add tasks
* View reminders


## Step 4: Process User Input

The entered text is analyzed and matched with appropriate actions.

### Example

If user enters:

> “Remind me to attend the meeting at 5 PM.”

The system identifies:

* Task: Attend meeting
* Time: 5 PM
* Action: Set reminder


## Step 5: Generate AI Response

The LLM generates meaningful and context-aware responses.

### Example Output

> “Reminder added successfully for 5 PM: Attend meeting.”


## Step 6: Preference Adaptation (Optional)

The system can remember:

* Preferred study times
* Frequently repeated tasks
* Wellness preferences
* Productivity habits

This helps provide personalized recommendations.



# Features of the Personal Productivity Assistant



# 1. Daily Task Manager

## Functions

* Add tasks
* Delete tasks
* Update task status
* Set priorities
* Display pending work

### Example Interaction

**User:**
“Add assignment submission tomorrow at 10 AM.”

**Assistant:**
“Task added successfully.”

# 2. Smart Scheduler

## Functions

* Schedule meetings
* Set reminders
* Detect schedule conflicts
* Suggest free time slots

### Example Interaction

**User:**
“Schedule gym at 6 PM daily.”

**Assistant:**
“Daily gym reminder scheduled for 6 PM.”


# 3. Wellness Tips Generator

## Functions

* Suggest hydration reminders
* Recommend exercise breaks
* Encourage healthy habits
* Provide stress-relief advice

### Example Interaction

**User:**
“Give me a wellness tip.”

**Assistant:**
“Take a short walk after every hour of screen time to reduce eye strain.”


# 4. General Query Assistant

## Functions

* Answer questions
* Provide productivity advice
* Motivate users
* Offer learning support

### Example Interaction

**User:**
“How can I improve focus while studying?”

**Assistant:**
“Use the Pomodoro technique and avoid distractions during study sessions.”


# Sample Prompt Scenarios

| User Prompt                               | Purpose               | AI Response                        |
| ----------------------------------------- | --------------------- | ---------------------------------- |
| “Remind me to drink water every 2 hours.” | Wellness reminder     | Sets recurring hydration reminders |
| “Plan my study schedule for exams.”       | Productivity planning | Creates timetable                  |
| “What are my pending tasks?”              | Task tracking         | Displays pending tasks             |
| “Suggest stress relief activities.”       | Wellness assistance   | Suggests breathing exercises       |

---

# Sample Python Program

```python id="n6fr4a"
tasks = []

print("=== Personal Productivity Assistant ===")

while True:

    print("\n1. Add Task")
    print("2. View Tasks")
    print("3. Wellness Tip")
    print("4. Exit")

    choice = input("Enter your choice: ")

    if choice == "1":
        task = input("Enter task: ")
        tasks.append(task)
        print("Task added successfully!")

    elif choice == "2":
        print("\nPending Tasks:")
        for t in tasks:
            print("-", t)

    elif choice == "3":
        print("Wellness Tip: Drink enough water and take short breaks.")

    elif choice == "4":
        print("Thank you for using Productivity Assistant.")
        break

    else:
        print("Invalid choice.")
```

---

# Sample Output

```text
=== Personal Productivity Assistant ===

1. Add Task
2. View Tasks
3. Wellness Tip
4. Exit

Enter your choice: 1
Enter task: Complete DBMS assignment
Task added successfully!

Enter your choice: 2

Pending Tasks:
- Complete DBMS assignment

Enter your choice: 3
Wellness Tip: Drink enough water and take short breaks.
```

---

# Expected Output

<img width="1000" height="750" alt="image" src="https://github.com/user-attachments/assets/3d7e4b9f-c814-4c95-a204-4e5f3c79f1f4" />


## Personal Productivity Assistant Features

### Daily Task Manager

* Accepts tasks using natural language
* Organizes tasks based on deadlines
* Displays summaries and pending work

### Smart Scheduler

* Schedules events intelligently
* Detects overlapping tasks
* Suggests available timings

### Wellness Tips Generator

* Provides personalized wellness suggestions
* Encourages healthy habits

### Conversational Interaction

* Responds naturally to user queries
* Provides contextual assistance

### Adaptive Preferences

* Learns user habits gradually
* Generates personalized responses


# Advantages

1. Saves time and effort
2. Improves productivity
3. Encourages healthy routines
4. Provides intelligent assistance
5. Supports natural language communication
6. Enhances user engagement
7. Demonstrates practical use of AI and LLMs



# Limitations

1. Requires internet connectivity for cloud-based AI
2. AI responses may occasionally be inaccurate
3. Advanced features require API access
4. Memory adaptation may need database integration


# Applications

* Student productivity management
* Office task scheduling
* Personal wellness tracking
* Smart reminder systems
* AI-powered digital assistants

# Future Enhancements

1. Voice-controlled interaction
2. Mobile application integration
3. Calendar synchronization
4. AI mood analysis
5. Multi-language support
6. Email and notification integration
7. Cloud-based task storage



# Conclusion

The experiment successfully demonstrated the development of a prompt-based Personal Productivity Assistant using Large Language Models and prompt engineering techniques. The application effectively manages tasks, schedules reminders, provides wellness tips, and interacts naturally with users. This project highlights how LLMs can improve creativity, personalization, and practical problem-solving in daily life applications.


# Result

Thus, the prompt-based Personal Productivity Assistant was successfully designed and implemented using prompt engineering concepts and Large Language Models. The system demonstrated intelligent natural language interaction, personalized productivity management, and practical AI-based assistance. 
The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:
 Understand how to tailor LLM prompts to real-life applications.
 Foster creativity by designing features suited to their personal or academic lives.
 Learn prompt engineering techniques for optimal interaction with AI tools.
 Experience the versatility and utility of generative AI in solving everyday problems.
