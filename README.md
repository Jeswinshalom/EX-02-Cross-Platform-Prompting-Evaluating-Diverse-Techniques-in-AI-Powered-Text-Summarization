# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of different prompting techniques—zero-shot, few-shot, chain-of-thought, and role-based—across various AI platforms (ChatGPT, Gemini, Claude, and Copilot) for the specific task of summarizing a technical article on “The Basics of Blockchain Technology.” 

## Scenario:
You are part of a content curation team for an educational platform. The platform delivers concise, beginner-friendly summaries of technical research papers to undergraduate students. Your task is to summarize a 500-word technical article titled "The Basics of Blockchain Technology" using four different AI platforms and four prompting techniques. The goal is to determine which prompting strategy + platform combination generates the best summary in terms of: 
• Accuracy (faithful to the original content) 
• Coherence (logical flow of ideas) 
• Simplicity (easy for undergraduates to understand) 
• Speed (response time) 
• User Experience (interface usability, output clarity) 

## Prompting Techniques Used 
| Prompt Type	| Description |
|-------------|-------------|
| Zero-shot	| Direct request without any example or explanation. |
| Few-shot	| Includes 1–2 example summaries before the main request. |
| Chain-of-Thought (CoT)	| Encourages the model to reason before summarizing. |
| Role-based	| Assigns a role like "You are an expert educator. Summarize the following..." |

## Platforms Evaluated
1.	ChatGPT (OpenAI)
2.	Claude (Anthropic)
3.	Gemini (Google)
4.	Copilot (Microsoft / GitHub)

## Algorithm
**1. Prepare Input Article**  
Use a ~500-word technical write-up on “The Basics of Blockchain Technology.”

**2. Design Prompts**  
Create four distinct prompts corresponding to each prompting technique.

**3. Run on All Platforms**  
Input the same article with each of the four prompts on all four platforms (16 total runs).

**4. Record Responses**  
Log outputs, note completion time, and collect platform interaction observations.

**5. Evaluate Summaries**  
Manually assess each summary based on the five criteria using a 1–5 scale.

**6. Calculate Scores**  
Average the scores for each strategy-platform combination.

**7. Analyze Results**  
Identify the best-performing combinations and patterns.

## Result Table (Sample Evaluation Summary)

| Platform | Prompting Technique | Accuracy | Coherence | Simplicity | Speed | UX | Avg Score |
|----------|----------------------|----------|-----------|------------|-------|----|-----------|
| ChatGPT  | Chain-of-Thought     | 5        | 5         | 4          | 5     | 5  | 4.8       |
| Claude   | Role-based           | 5        | 4         | 5          | 4     | 5  | 4.6       |
| Gemini   | Few-shot             | 4        | 4         | 4          | 5     | 4  | 4.2       |
| Copilot  | Zero-shot            | 3        | 3         | 3          | 4     | 4  | 3.4       |

## Result (Observations)  
•	The Chain-of-Thought prompt on ChatGPT provided the most accurate and logically structured summary, with a clear step-by-step thought process.  
•	Claude produced highly readable summaries using Role-based prompting, ideal for non-expert audiences.  
•	Gemini performed best with Few-shot prompting, but occasionally missed deeper technical nuances.  
•	Copilot, while fast, lacked summarization depth under zero-shot prompting and needs more tailored inputs.  

## Conclusion
The most effective combination for summarizing technical educational content was:  
 **ChatGPT + Chain-of-Thought prompting**  
This approach yielded the most accurate, coherent, and user-friendly summaries, making it ideal for delivering complex topics to undergraduate students.


