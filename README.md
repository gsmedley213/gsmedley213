## 📚 Project Gutenberg Annotation Pipeline

I’ve developed a three-stage pipeline that uses a Large Language Model (LLM) to generate tooltip-like annotations for public domain books from Project Gutenberg.

---

### 🔗 The Pipeline at a Glance

1. **Content Extraction**  
   [`content-extractor`](https://github.com/gsmedley213/content-extractor)  
   Extracts content from a Project Gutenberg HTML eBook and saves a new HTML file with elements marked to associate them with extracted content.
   
3. **LLM Annotation**  
   [`llm-annotate`](https://github.com/gsmedley213/llm-annotate)  
   Uses an LLM (Google Gemini) to generate notes on book content, outputting to JSON.

4. **HTML Annotation Synthesis**  
   [`html-annotate`](https://github.com/gsmedley213/html-annotate)  
   Combines the marked HTML and the generated notes to produce a new file with notes presented like tooltips.

---

### 🛠️ Technologies Used

- Java 21+
- Spring Boot
- Gradle
- Google Gemini API

---

### 🚀 Try It Out

Each repository has a detailed README with setup instructions and usage examples.  

- [content-extractor](https://github.com/gsmedley213/content-extractor)
- [llm-annotate](https://github.com/gsmedley213/llm-annotate)
- [html-annotate](https://github.com/gsmedley213/html-annotate)
