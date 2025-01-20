# Prompting
This is a basic sheet to help me create better prompts for LLMs. Its a personal refrence but feel free to use and share. 
ALWAYS BE ITERATING

## Task
To get the best results from a prompt when we give an LLM a task we want to do the following:

1. Add a persona. For example, tell the LLM that it is a "Gym Manager" at the start of the promt to make the LLM look through the lens of that Persona
- I am a Gym Manager
2. Give the task to the LLM. This is the meat and potatoes that everything else is built around. 
- Write an email informing our staff of the new schedule.
3. Give the format of the output. Usually an LLM will give you info in bullet points but you can promt it for different formats such as creating tables or even markup.
- Make the email professional, friendly and short so people can skim it. Also include a graphic of our new schdule. 
4. Give as much Context as possible. If you need to make a new gym schedule, provide the relevant information.
- We have a new Gym schedule and this is what it is (schedule.csv)
5. Try to include refrences to past experiences. LLMs can usually incorperate your refrences into their ideas or think of creative new ones based off of the information provided
6. Evaluate the result. If it's not exactly right, move to the next step.
7. Iterate on your prompt
8. Ask the AI to explain its thought processes. This will help you find flaws in the logic or just give you insights for future prompts

---

## Itteration Methods
The initial prompt may get us 80% of the way there, but the other 20% relies on iteration. These are some methods to get us that other 20%

1. Go back to the initial task framework. Sometimes a simple lookover can be an easy fix to your prompt problem
2. Break it up into shorter sentences. AI info overload is a thing. Instead of throwing 100 things at once, break it down into smaller bits for the Model to understand
3. Try different phasing or switch to an analogous task. For example if you are marketing something, instead of asking write a "toilet paper ad", tell it to "write a compelling story about how our product fits into the lives of our customers".
4. Introduce constraints. Too much creative freedom is no freedom at all. When you give the LLM a constraint it has to think of creative ways to solve your problems.

---

## Prompt Examples
![Screenshot 2025-01-20 at 11-12-09 i took googles 9 hour ai promt course - Google Search](https://github.com/user-attachments/assets/fbd72347-8ca9-4a74-a11e-023a350edddc)
![Screenshot 2025-01-20 at 11-12-42 i took googles 9 hour ai promt course - Google Search](https://github.com/user-attachments/assets/709e0cc9-099d-483f-9f86-5b9c0baa9da2)
<img width="514" alt="Screenshot 2025-01-20 111830" src="https://github.com/user-attachments/assets/18d07157-ac8a-4227-954f-bd79a4dd55c6" />

---

## Prompt Chaining
When you want to use an LLM as a creative partner, Prompt Chaining comes in handy. Its essentially when you take your prompt and ask the LLM about it to get more info or new insights on your initial idea. For example you could give it your book and ask the most common themes in the book or to write a catchy tagline based off of the information put into the prompt. 

So if you were to ask for a summary and wanted to refine the prompt to get a better tagline, use something like the example below

<img width="566" alt="promptchainex" src="https://github.com/user-attachments/assets/aaa8e9a9-8741-4d5f-aa4b-cd9bf54a4517" />

---

## Agents
One of the most impressive things you can do is create an agent SIM based on your prompt. Here is a generic template for an Agent

<img width="554" alt="Agent Template" src="https://github.com/user-attachments/assets/37cce539-1868-428b-93fa-0e7ad07c37dc" />

In the example below, we create an agent that is a Career Development Trainer. This simulation will continue until the person talking to the agent meets the stop rule. In the example the stop rule is "JAZZ HANDS".
After this prompt, you can communicate just like they were the person you prompted. So you can do something like give it a project you have been working on and have it ask you sample interview questions based off of your work. 

<img width="563" alt="Agent example" src="https://github.com/user-attachments/assets/136bb77c-cabb-419c-bc30-33ad0163d42d" />

Here is another example of an agent

<img width="565" alt="Agent Design Example" src="https://github.com/user-attachments/assets/a772a38a-4c37-4f27-a5f5-1adad18b5fd6" />














