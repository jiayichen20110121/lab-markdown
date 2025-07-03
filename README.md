**Name:** Jiayi  
**Date:** July 2, 2025

## What I Learned Today
- **Tokenization in AI**  
  - Tokenization is the process of converting raw text into smaller, manageable chunks called tokens. These tokens help the AI model understand and process text.
  - Tokens could be whole words, parts of words, or even punctuation marks, depending on the model's design.
  - **Tiktokenizer** is one tool used to tokenize text, such as with the cl100k_base encoding, which has 100,277 possible tokens.


- **How Words Become Tokens in AI Models**  
  - Models are trained using vast datasets (e.g., Common Crawl with 27 billion webpages), and tokenization is the first step in preparing the data.
  - After tokenizing, the model trains on these tokens through a neural network by assigning probability values to possible tokens that could come next in a sequence.
  - During training, the model adjusts its parameters (weights), which are like knobs that influence predictions. These weights are adjusted based on the token sequences the model processes.
 
- **Vibe Coding**  
  - In vibe coding, you work with AI as a mentor, not just a tool for solving problems.
  - **AI as a Mentor**: It guides you, answers questions, and helps debug your code through collaboration and conversation. The goal is to learn rather than just use AI to complete tasks.  
  - **Example**: Instead of just asking AI to do your homework, you ask it to help you understand concepts, write explanations, and debug your own code.
  - **AI as an Intern**: You delegate tasks like boilerplate code or UI design to AI. This allows you to focus on the interesting or challenging parts of your project, such as system design and integration. You still need to review and test AI-generated work to ensure it fits your project.
  - **Goal**: Use AI to accelerate your work, but always take responsibility for the final result. AI is an assistant that helps with routine tasks, but you should still understand and explain the work done.

## Lab Reflection
One challenge I encountered today was understanding the process of tokenization in the context of training AI models. The idea that text is broken down into tokens, which are then analyzed and predicted by the model, seemed complex. Also, the stochastic nature of AI predictions (where outputs can vary even for the same input) was initially hard to grasp. However, after reviewing how the model adjusts parameters based on tokens, it started to make more sense.

## Code Snippet
```
cd Documents/
cd labs
mkdir lab-markdown
cd lab-markdown
git init
git add .
git commit -m "commit"
gh repo create --public --source=. --push lab-markdown
```

## Helpful Links

https://tiktokenizer.vercel.app/?model=cl100k_base

