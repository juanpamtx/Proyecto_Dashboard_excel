

# AI Assistant Usage in student life #

## **AI Assistant Usage in Student Life** ##
Explore how students at different academic levels use AI tools like ChatGPT for tasks such as coding, writing, studying, and brainstorming. Designed for learning, EDA, and ML experimentation.

## **What is this dataset?** ##
This dataset simulates 10,000 sessions of students interacting with an AI assistant (like ChatGPT or similar tools) for various academic tasks. Each row represents a single session, capturing the student’s level, discipline, type of task, session length, AI effectiveness, satisfaction rating, and whether they reused the AI tool later.

## **Why was this dataset created?** ##
As AI tools become mainstream in education, there's a need to **analyze and model how students interact with them**. However, no public datasets exist for this behavior. This dataset fills that gap by providing a safe, fully synthetic yet realistic simulation for:

- EDA and visualization practice
- Machine learning modeling
- Feature engineering workflows
- Educational data science exploration
It’s ideal for students, data science learners, and researchers who want real-world use cases without privacy or copyright constraints.

## **How is the dataset structured?** ##
Column: - Description
- **SessionID:**	Unique session identifier
- **StudentLevel1:** Academic level: High School, Undergraduate, Graduate
- **Discipline:**	Student’s field of study (e.g., CS, Psychology, etc.)
- **SessionDate:**	Date of the session
- **SessionLengthMin:**	Length of AI interaction in minutes
- **TotalPrompts:**	Number of prompts/messages used
- **TaskType:**	Nature of the task (e.g., Coding, Writing, Research)
- **AI_AssistanceLevel:**	1–5 scale on how helpful the AI was perceived to be
- **FinalOutcome:**	What the student achieved: Assignment Completed, Idea Drafted, etc.
- **UsedAgain:**	Whether the student returned to use the assistant again
- **SatisfactionRating:**	1–5 rating of overall satisfaction with the session

All data is synthetically generated using controlled distributions, real-world logic, and behavioral modeling to reflect realistic usage patterns.

## **Possible Use Cases** ##
This dataset is rich with potential for:

- **EDA:** Visualize session behavior across levels, tasks, or disciplines
- **Classification:** Predict likelihood of reuse (UsedAgain) or final outcome
- **Regression:** Model satisfaction or session length based on context
- **Clustering:** Segment students by AI interaction behavior
- **Feature engineering practice:** Derive prompt density, session efficiency, or task difficulty
- **Survey-style analysis:** Discover what makes students satisfied or frustrated

## **Key Features** ##
- Clean and ready-to-use CSV
- Balanced and realistic distributions
- No missing values
- Highly relatable academic context