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
<img width="1230" height="874" alt="Image" src="https://github.com/user-attachments/assets/f30f183c-fb67-447a-bc21-2da54d128145" />  

---

### Output 2  
<img width="1186" height="825" alt="Image" src="https://github.com/user-attachments/assets/01670091-e60a-41f8-97fc-086bb6da5adc" />

---

### Output 3  
<img width="1114" height="790" alt="Image" src="https://github.com/user-attachments/assets/6d21c396-95e6-431a-8073-70269aa93054" />
   

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

3. Run the streamlit app:
   ```commandline
   streamlit run main.py
   ```
