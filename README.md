# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

## LOKESHVARAN S
## Register no : 212223040105

## Aim:

# To develop a prompt-based application using ChatGPT to assist students in managing academic activities, organizing tasks, planning study sessions, tracking progress, and generating personalized productivity plans through natural-language interaction.

---

# AI Tool Used

**ChatGPT** – Used for creating daily plans, analyzing task importance, organizing study sessions, suggesting breaks, handling schedule changes, tracking progress, and generating personalized academic plans.

---

# Use Case Scenario

A college student needs to manage classes, assignments, programming practice, project activities, examination preparation, and personal activities within a limited amount of time. The Personal Productivity Assistant helps the student convert these activities into an organized daily plan.

The assistant considers deadlines, task difficulty, available time, study preferences, and task completion status. The student can communicate naturally without using predefined commands.

---

# Explanation

A Personal Productivity Assistant is a prompt-based application that uses a Large Language Model to help students manage their academic and personal activities efficiently.

The assistant can:

1. Accept daily activities using natural language.
2. Separate fixed activities from flexible tasks.
3. Identify urgent and important tasks.
4. Arrange activities according to deadlines.
5. Create time-based study schedules.
6. Divide large study tasks into smaller sessions.
7. Suggest suitable breaks during study.
8. Provide simple productivity suggestions.
9. Update the schedule when tasks are completed or delayed.
10. Generate personalized plans based on user preferences.

---

# Initial Prompt

"Act as a personal productivity assistant for a college student. Help me organize my classes, assignments, project work, examination preparation, programming practice, and personal activities. Consider deadlines and available time while creating a practical schedule. Modify the schedule whenever I provide new tasks, progress updates, or preferences."

---

# Procedure

1. Identify the requirements of the Personal Productivity Assistant.
2. Design an initial prompt for managing academic activities.
3. Provide a list of daily tasks to ChatGPT.
4. Ask the LLM to organize the tasks according to deadlines and importance.
5. Add time constraints and study preferences to improve the generated plan.
6. Ask the assistant to divide lengthy study activities into smaller sessions.
7. Generate productivity and break suggestions.
8. Provide information about completed and unfinished tasks.
9. Ask ChatGPT to update the remaining schedule.
10. Provide personal study preferences and generate a customized plan.
11. Observe and evaluate the changes in the responses.

---

# Expected Output

The expected output is a prompt-based Personal Productivity Assistant capable of:

- Organizing academic and personal activities.
- Identifying urgent and important tasks.
- Creating realistic daily schedules.
- Managing assignment deadlines.
- Generating personalized study plans.
- Dividing study time into focused sessions.
- Suggesting suitable breaks.
- Updating pending tasks based on progress.
- Handling changes in available time.
- Adapting future plans according to user preferences.

---

# Output (Example Response by LLM)

## Personal Productivity Assistant Features

### 1. Academic Task Organizer

- Accept academic tasks through natural language.
- Arrange activities according to deadlines.
- Separate completed and pending tasks.
- Provide a clear daily task list.

### 2. Priority Manager

- Identify urgent assignments and upcoming examinations.
- Classify activities according to priority.
- Give higher priority to tasks with closer deadlines.
- Move flexible activities when necessary.

### 3. Study Schedule Generator

- Create time-based study plans.
- Divide long sessions into smaller study periods.
- Add breaks between focused sessions.
- Allocate more time to difficult subjects.

### 4. Progress Monitor

- Record completed activities.
- Identify unfinished tasks.
- Reschedule pending work.
- Adjust the workload based on available time.

### 5. Preference-Based Planner

- Consider preferred study timings.
- Follow the user's preferred session duration.
- Avoid unnecessary workload.
- Generate future schedules based on stated preferences.

---

# Algorithm Overview

The Personal Productivity Assistant receives the student's activities as input and analyzes their deadlines, importance, and available time. The assistant then assigns suitable priorities and generates an initial schedule.

When the student provides feedback, the assistant updates the task status and rearranges unfinished activities. The assistant also considers study preferences such as preferred study time, session duration, and break intervals to produce a personalized schedule.

---

# Input

### User Tasks:

1. Attend college lecture from 9:00 AM to 1:00 PM.
2. Submit Python assignment by 3:00 PM.
3. Revise Computer Networks for 1 hour.
4. Practice SQL queries.
5. Complete project documentation.
6. Prepare for an upcoming internal test.
7. Take a short evening break.

### User Preferences:

- Prefer studying after college.
- Prefer focused study sessions.
- Take a short break between study sessions.
- Give more time to difficult subjects.
- Avoid completing too many difficult activities continuously.

---

# Output

The assistant generates:

- A prioritized daily task list.
- A time-based productivity schedule.
- Deadline-oriented task arrangement.
- Focused study sessions.
- Break recommendations.
- Completed and pending task information.
- Updated schedules after feedback.
- Personalized study plans.

---

# Step-by-Step Algorithm

1. **Start**
2. Initialize the Personal Productivity Assistant.
3. Receive the student's daily activities.
4. Identify fixed activities and flexible activities.
5. Identify deadlines and available time.
6. Analyze the importance and urgency of each task.
7. Assign High, Medium, or Low priority.
8. Generate the initial daily schedule.
9. Divide lengthy study activities into focused sessions.
10. Add suitable breaks between study sessions.
11. Generate productivity suggestions when requested.
12. Receive the student's progress update.
13. Mark completed tasks as completed.
14. Identify unfinished tasks.
15. Reschedule unfinished activities.
16. Apply the user's study preferences.
17. Generate the updated personalized schedule.
18. Display the final productivity plan.
19. **Stop**

---

# Step-by-Step Prompt Evolution

## Step 1: Basic Task Planning

### Prompt:

"You are a productivity assistant for a college student. I have the following activities today:

1. Attend college lecture from 9:00 AM to 1:00 PM
2. Complete my Python assignment by 3:00 PM
3. Revise Computer Networks
4. Practice SQL
5. Work on project documentation
6. Prepare for an internal test
7. Take an evening break

Create a practical schedule for today while considering the assignment deadline."

### Output:

The assistant identifies the college lecture as a fixed activity and the Python assignment as the most urgent academic task.

### Today's Schedule:

- 9:00 AM – 1:00 PM: Attend college lecture
- 1:00 PM – 1:30 PM: Lunch and rest
- 1:30 PM – 2:30 PM: Python assignment
- 2:30 PM – 2:45 PM: Short break
- 2:45 PM – 3:00 PM: Finalize and submit Python assignment
- 3:00 PM – 3:30 PM: Rest
- 3:30 PM – 4:15 PM: Computer Networks revision
- 4:15 PM – 4:25 PM: Break
- 4:25 PM – 5:10 PM: SQL practice
- 5:10 PM – 5:40 PM: Evening break
- 5:40 PM – 6:40 PM: Project documentation
- 6:40 PM – 7:30 PM: Test preparation

### Priority Order:

1. Python assignment
2. College lecture
3. Internal test preparation
4. Computer Networks revision
5. SQL practice
6. Project documentation
7. Evening break

**Key Feature:** Basic daily task organization.

---

## Step 2: Deadline-Based Prioritization

### Prompt:

"The Python assignment must be submitted by 3 PM. The internal test is approaching, while SQL practice and project documentation can be completed later. Rearrange my tasks into High, Medium, and Low priority."

### Output:

The assistant reorganizes the activities according to urgency.

### Priority List:

**High Priority**

1. Python assignment - deadline at 3 PM
2. College lecture - fixed activity
3. Internal test preparation

**Medium Priority**

4. Computer Networks revision
5. SQL practice

**Low Priority**

6. Project documentation
7. Evening break

### Adjusted Plan:

- The Python assignment is completed before the 3 PM deadline.
- Test preparation receives higher priority because of the approaching examination.
- Computer Networks revision is placed after the urgent activities.
- SQL and project documentation are treated as flexible tasks.
- The evening break remains available for relaxation.

**Key Feature:** Deadline-aware task prioritization.

---

## Step 3: Focused Study Planning

### Prompt:

"I find it difficult to study continuously for a long period. Create a study plan using shorter sessions. Give more attention to Computer Networks because I need additional revision for that subject."

### Output:

### Focused Study Plan:

- 3:30 PM – 4:10 PM: Computer Networks - Session 1
- 4:10 PM – 4:20 PM: Break
- 4:20 PM – 5:00 PM: Computer Networks - Session 2
- 5:00 PM – 5:15 PM: Break
- 5:15 PM – 5:55 PM: Internal Test Preparation
- 5:55 PM – 6:05 PM: Break
- 6:05 PM – 6:45 PM: SQL Practice

The assistant gives additional attention to Computer Networks while maintaining short study sessions.

**Key Feature:** Focused and personalized study planning.

---

## Step 4: Productivity Suggestions

### Prompt:

"I have completed two study sessions and want to refresh before continuing. Give me a few simple productivity suggestions that will help me return to studying with better concentration."

### Output:

### Productivity Suggestions:

**1. Take a short break**

Step away from the study material for a few minutes.

**2. Rest your eyes**

Look away from the screen and allow your eyes to relax.

**3. Move around**

Stretch or take a short walk before beginning the next session.

**4. Set one clear goal**

Decide exactly what topic or task you want to complete in the next study session.

**Key Feature:** Productivity and break management.

---

## Step 5: Progress-Based Schedule Update

### Prompt:

"I have submitted my Python assignment and completed Computer Networks revision. I could not complete SQL practice and project documentation. I have only 90 minutes remaining today. Update my plan and avoid making it too busy."

### Output:

### Updated Task List:

| Task | Status | Priority |
|---|---|---|
| College Lecture | Completed | High |
| Python Assignment | Completed | High |
| Computer Networks Revision | Completed | High |
| SQL Practice | Pending | Medium |
| Project Documentation | Pending | Low |
| Internal Test Preparation | Pending | High |

### Revised 90-Minute Plan:

- 40 minutes: Internal Test Preparation
- 10 minutes: Break
- 30 minutes: SQL Practice
- 10 minutes: Review pending project work

The assistant keeps the more important examination preparation ahead of lower-priority project work.

**Key Feature:** Progress-based schedule adaptation.

---

## Step 6: Preference-Based Personalization

### Prompt:

"My preferred study time is between 6 PM and 9 PM. I like studying difficult subjects first and taking a short break after each focused session. Use these preferences when creating my future study plans."

### Output:

### Personalized Planning Rules:

- Schedule major study activities between 6 PM and 9 PM.
- Place difficult subjects at the beginning of the study period.
- Use shorter focused sessions.
- Include short breaks between sessions.
- Give priority to upcoming examinations.
- Move flexible tasks to another available period when the schedule is overloaded.

### Personalized Study Example:

- 6:00 PM – 6:40 PM: Difficult Subject Revision
- 6:40 PM – 6:50 PM: Break
- 6:50 PM – 7:30 PM: Practice Questions
- 7:30 PM – 7:40 PM: Break
- 7:40 PM – 8:20 PM: Programming Practice
- 8:20 PM – 8:30 PM: Break
- 8:30 PM – 9:00 PM: Quick Revision

**Key Feature:** Preference-based personalized scheduling.

---

# Feedback Loop

The Personal Productivity Assistant follows a continuous feedback process:

Student provides activities
        ↓
Assistant analyzes deadlines
        ↓
Tasks are prioritized
        ↓
Initial schedule is generated
        ↓
Student provides progress
        ↓
Completed tasks are removed
        ↓
Pending tasks are rescheduled
        ↓
User preferences are applied
        ↓
Personalized schedule is generated

---

# Summary Table

| Step | Prompt Type | Purpose | Main Feature |
|---|---|---|---|
| 1 | Basic Task Planning | Organize daily activities | Task Management |
| 2 | Priority Prompt | Analyze urgency and deadlines | Prioritization |
| 3 | Study Planning | Divide study into focused sessions | Personalization |
| 4 | Productivity Prompt | Suggest useful breaks | Productivity Support |
| 5 | Progress Prompt | Update unfinished activities | Adaptive Scheduling |
| 6 | Preference Prompt | Apply study preferences | Personalized Planning |

---

# Conclusion

The Personal Productivity Assistant was successfully developed as a prompt-based application using ChatGPT. The application demonstrated how different levels of prompt design can improve the management of academic and personal activities.

Starting from basic task organization, the prompts were progressively enhanced to support deadline-based prioritization, focused study planning, productivity suggestions, progress tracking, and preference-based scheduling.

The experiment demonstrates that Large Language Models can be effectively used with well-designed prompts to create practical applications for student productivity and everyday problem-solving.

---

# Result

The prompt-based Personal Productivity Assistant was successfully designed using ChatGPT. It was able to organize daily activities, prioritize tasks, create personalized study schedules, provide productivity suggestions, track progress, reschedule unfinished activities, and adapt future plans according to user preferences.

Thus, the experiment successfully demonstrated the practical application of prompt engineering with Large Language Models.
