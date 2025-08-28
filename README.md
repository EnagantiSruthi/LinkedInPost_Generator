# LinkedIn Post Generator 🚀  

This project is a **Generative AI-powered tool** that helps LinkedIn influencers and professionals generate posts that **match their writing style**.  

---

## Project Overview  

Let's say **Mohan** is a LinkedIn influencer and he needs help in writing his future posts.  

- He can **feed his past LinkedIn posts** to this tool.  
- The tool will **extract key topics, length, and language**.  
- Mohan can then **select topic, length, and language** and click on the **Generate** button.  
- The tool will create a **new LinkedIn post** that matches **his own writing style**.  

---

## Example Outputs  

### Output 1  
<img src="resources/output1.jpg" width="600"/>  

---

### Output 2  
<img src="resources/output2.jpg" width="600"/>  

---

### Output 3  
<img src="resources/output3.jpg" width="600"/>  

---

### Workflow:  
1. **Stage 1**: Collect LinkedIn posts and extract **Topic, Language, Length** from them.  
2. **Stage 2**: Use the selected **topic, language, and length** to generate a new post.  
   - Some past posts related to that specific topic/language/length are used for **few-shot learning** to guide the LLM about writing style.  

---

## Set-up  

1. Get a **Groq API Key** from here: [https://console.groq.com/keys](https://console.groq.com/keys).  
   - Inside `.env`, update the value of `GROQ_API_KEY` with the API Key you created.  

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
