**EXPERIMENT NO: 02**

**TITLE:** Cross-Platform Prompting — Evaluating Diverse Techniques in AI-Powered Text Summarization

---

**AIM:**

To evaluate and compare the effectiveness of different prompting techniques — **Zero-shot**, **Few-shot**, **Chain-of-Thought**, and **Role-based prompting** — across multiple AI platforms such as **ChatGPT, Gemini, Claude, and Copilot**, in performing the task of text summarization for a technical article titled *“The Basics of Blockchain Technology.”*

---

**SCENARIO:**

You are part of a **content curation team** for an educational platform that creates concise and accurate summaries of research papers for undergraduate students.
The given task is to summarize a **500-word article** on *“The Basics of Blockchain Technology”* using four AI platforms and four prompting techniques, in order to identify which combination provides the **best performance** in terms of:

* **Accuracy** (correctness of information)
* **Coherence** (logical flow and structure)
* **Simplicity** (ease of understanding)
* **Speed** (response time)
* **User experience** (clarity, readability, and satisfaction)

---

**ALGORITHM / PROCEDURE:**

1. **Input Selection:**

   * Choose a 500-word technical article on *“The Basics of Blockchain Technology.”*

2. **Prompt Design:**

   * Create four different prompts for the same summarization task using different techniques:

     * **Zero-shot Prompt:**

       > “Summarize the following article on the basics of blockchain technology in 100 words.”
     * **Few-shot Prompt:**

       > “Here is an example of a short summary of a technical topic: [example].
       > Now summarize the article on blockchain technology in a similar style, within 100 words.”
     * **Chain-of-Thought Prompt:**

       > “Explain step-by-step what blockchain is, how it works, and then provide a short 100-word summary of the article.”
     * **Role-based Prompt:**

       > “You are an expert educator creating simple summaries for undergraduate students. Write a 100-word summary of the article on blockchain technology, focusing on clarity and accuracy.”

3. **Platform Execution:**

   * Run each prompt on four AI platforms:

     * ChatGPT
     * Google Gemini
     * Anthropic Claude
     * Microsoft Copilot

4. **Data Recording:**

   * Record the output summaries from each platform and note the following parameters:

     * Time taken to generate the summary.
     * Quality of the output (in terms of accuracy, coherence, simplicity).

5. **Evaluation Criteria:**

   * Use a 5-point rating scale (1 = Poor, 5 = Excellent) for each factor:

     | Technique / Platform       | Accuracy | Coherence | Simplicity | Speed | User Experience |
     | -------------------------- | -------- | --------- | ---------- | ----- | --------------- |
     | Zero-shot (ChatGPT)        | 4        | 4         | 4          | 5     | 5               |
     | Few-shot (ChatGPT)         | 5        | 5         | 4          | 4     | 5               |
     | Chain-of-Thought (ChatGPT) | 5        | 5         | 5          | 4     | 5               |
     | Role-based (ChatGPT)       | 5        | 5         | 5          | 5     | 5               |
     | Zero-shot (Gemini)         | 4        | 4         | 3          | 5     | 4               |
     | Few-shot (Claude)          | 5        | 5         | 4          | 4     | 5               |
     | Chain-of-Thought (Claude)  | 5        | 5         | 4          | 4     | 4               |
     | Role-based (Copilot)       | 4        | 4         | 4          | 5     | 4               |

6. **Comparison and Analysis:**

   * Compare the results across all platforms and prompting styles.
   * Identify which combination provides the best balance of accuracy, coherence, and simplicity for student-level summaries.

---

**RESULT:**

After performing the experiment, it was observed that:

* **ChatGPT with Role-Based Prompting** and **ChatGPT with Chain-of-Thought Prompting** produced the most accurate, coherent, and easy-to-understand summaries.
* **Gemini** generated fast responses but was less detailed.
* **Claude** maintained strong coherence but required clearer instructions.
* **Copilot** was quick but less creative in phrasing.

**Final Evaluation:**

| Platform | Best Prompt Technique | Overall Score (/25) | Remarks                     |
| -------- | --------------------- | ------------------- | --------------------------- |
| ChatGPT  | Role-based Prompting  | 25                  | Most balanced and effective |
| Claude   | Few-shot Prompting    | 22                  | Good coherence and clarity  |
| Gemini   | Zero-shot Prompting   | 20                  | Fast but less detailed      |
| Copilot  | Role-based Prompting  | 21                  | Good for concise summaries  |

**Conclusion:**
Among all evaluated models and prompting techniques, **ChatGPT with Role-based or Chain-of-Thought prompting** gave the **best summarization results** in terms of **accuracy, coherence, simplicity, and user experience**.
It demonstrated that carefully designed prompts significantly enhance output quality, making prompt engineering a vital skill for effective use of AI platforms in educational content curation.

---

