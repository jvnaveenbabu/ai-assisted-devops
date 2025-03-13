# Day-02

### Tokens : 
- AI models read and generate text in tokens, not whole words. 
- **Tokens** are small piece of text. 
- A token can be a word or a part of a word. For Example **"Hello"** is one token, while **"unbelievable"** might split into **"un"**, **"believe"**, and "able" as seperate tokens. 

### Techniques in Prompt Engineering: 
1. **Zero-Shot Prompting** - Providing Prompt without examples. 
*Example:* "What is the capital of India?" 
<br>

2. **Few-Shot Prompting** – Providing examples to guide AI.
*Example:*
- Dog → Animal
- Apple → Fruit
- Car → ? (AI answers: Vehicle)"

3. **Muti-Shot Prompting** - Providing prompt with more no. of examples 
<br>
4. **Chain-of-Thought Prompting** – Encouraging step-by-step reasoning.
*Example:* "If a train leaves at 2 PM and takes 3 hours, what time does it arrive? Think step by step."

### Use Cases of Prompt Engineering DevOps -  
- Bash scripts
- Terraform 
- CI/CD configurations
- Kubernetes manifest files