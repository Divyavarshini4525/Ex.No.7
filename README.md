# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Date:24.10.2025
# Register no.212222050012
# Aim: To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

#AI Tools Required:

ChatGPT

Lovable AI (optional integration for friendly reminders and notifications)

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

**Explanation:**

This experiment demonstrates how a prompt-based AI application can assist in study time management and concentration enhancement.
The system interacts naturally with the user, generates personalized study schedules, offers real-time motivation, and adjusts focus intervals according to productivity feedback.

By using prompt engineering techniques, we can make the AI dynamically organize tasks and adapt to user learning patterns.

**Prompt:**

Act as a study planner and focus coach for an engineering student. Create personalized study plans, schedule timed focus sessions, suggest short breaks, and give motivational messages. Adjust plans based on progress and user feedback.

**Procedure:**

**Step 1: Define Core Requirements**

I The Study Planner Assistant should be capable of:

II Creating structured study schedules with subjects and time slots.

III Managing short and long focus sessions (Pomodoro-style).

IV Suggesting rest breaks and productivity tips.

V Motivating users with quotes or progress updates.

VI Adjusting time allocation based on difficulty or user feedback.

<img width="991" height="602" alt="image" src="https://github.com/user-attachments/assets/4dfa8c46-7433-4a9d-aa33-c58eb831f79e" />

**Step 3: Simulate Natural Interaction (Example in Python)**

print("📚 Study Planner Assistant Activated!")

while True:

    user_input = input("You: ")
    
    if "plan" in user_input.lower():
    
        print("Assistant: Here’s your study plan for today! Stay consistent.")
        
    elif "focus" in user_input.lower():
    
        print("Assistant: Starting 25-minute focus session. Keep distractions away!")
        
    elif "break" in user_input.lower():
    
        print("Assistant: Time to relax! Stretch and hydrate for 5 minutes.")
        
    elif "quote" in user_input.lower():
    
        print("Assistant: 'Discipline is doing what needs to be done, even when you don’t feel like it.'")
        
    elif "exit" in user_input.lower():
    
        print("Assistant: Session ended. Great job staying productive! 👏")
        
        break
        
    else:
    
        print("Assistant: Let’s get back on track — what’s your next subject?")

**Step 4: Feedback and Adaptation**

I. The assistant collects user feedback (e.g., “Session felt too long”) and automatically adapts:

II. Shorter focus sessions for low-energy periods.

III. Longer breaks during fatigue.

IV. Increased motivational feedback when user progress declines.

V. It can also track consistency and display weekly study statistics.

**Step 5: (Optional) Adaptive Memory Integration**

A small preference memory can be stored as:

{

  "preferred_session_length": "25 minutes",
  
  "break_duration": "5 minutes",
  
  "subject_focus": ["Control Systems", "Power Electronics"],
  
  "motivation_style": "quotes"

}

This allows the assistant to deliver personalized plans and focus cycles automatically.

**✅ Expected Output (Example LLM Response)**

Study Planner & Focus Assistant Features

**📅 Daily Schedule Generator**

I. Creates dynamic study plans with balanced subjects.

II. Adjusts workload according to available time.

**⏰ Focus Timer System**

I. Uses short “Pomodoro” cycles (25 min work + 5 min break).

II. Alerts user when it’s time to rest or resume study.

**💬 Motivational Feedback**

I. Provides quotes, progress reports, and performance encouragement.

II. Responds empathetically to user frustration or stress.

**🧠 Adaptive Learning**

I. Tracks subject completion trends.

II. Adjusts future plans automatically (e.g., more focus on weak subjects).

**Example Conversation:**

**User:** “Plan my study time for tomorrow.”

**Assistant:** “📘 Here’s your plan: 9–10 AM Machines, 10:15–11:15 Control Systems, 11:30–12:30 Power Electronics.”

**User:** “Start focus mode for Control Systems.”

**Assistant:** “⏳ Focus mode started! You’ve got this — no distractions for 25 minutes!”

**User:** “I need a motivational quote.”

**Assistant:** “💡 ‘The future depends on what you do today.’ — Mahatma Gandhi.”

**User:** “End session.”

**Assistant:** “Session ended. Great effort! Review your progress before bed for best retention.


<img width="1024" height="1024" alt="qwert" src="https://github.com/user-attachments/assets/3795eed3-818a-490d-8382-8c13f25b27fa" />

**Result:**

The experiment successfully demonstrated a Study Planner and Focus Assistant application using ChatGPT.

Students were able to:

Build an interactive, adaptive scheduling assistant.

Apply prompt engineering to manage focus, motivation, and feedback.

Understand how LLMs can support learning discipline through adaptive dialogue.

Gain insights into human-AI collaboration for productivity enhancement.

# Result: 
The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:
 Understand how to tailor LLM prompts to real-life applications.
 Foster creativity by designing features suited to their personal or academic lives.
 Learn prompt engineering techniques for optimal interaction with AI tools.
 Experience the versatility and utility of generative AI in solving everyday problems.
