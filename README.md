# 🧐 Company Brochure Generator using OpenAI

Generate professional brochures about any company using just its website URL and name — powered by OpenAI's GPT-4o-mini and Python.

---

## 📌 Overview

This project automatically creates a concise, Markdown-based brochure for a given company by:

* Scraping relevant links from the company website (e.g., About, Careers, News).
* Analyzing page structure and content.
* Using the OpenAI API to summarize key information about:

  * Company mission and services
  * Culture and values
  * Careers and hiring pages
  * News or announcements

---

## 🚀 Features

* 🌐 **Web scraping** using BeautifulSoup
* 🤖 **LLM-powered summarization** with GPT-4o-mini
* 📟 **Brochure generation** in clean Markdown format
* 🧠 **URL filtering** using intelligent prompt-based link selection

---

## 💠 Tech Stack

* Python
* Jupyter Notebook
* OpenAI API (GPT-4 / GPT-4o)
* BeautifulSoup (`bs4`)
* Requests
* dotenv

---

## 📁 Folder Structure

```
📆llm_brochure_generator/
 ├️ 📋 brochure_generator.ipynb       # Main notebook
 ├️ 📋 utils.py                        # Web scraping and helper functions (optional)
 ├️ 📄 .env                            # API key (not tracked)
 └️ 📄 README.md
```

---

## 🧪 How to Use

1. **Clone the repo:**

   ```bash
   git clone https://github.com/<your-username>/llm_brochure_generator.git
   cd llm_brochure_generator
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Add your OpenAI API key to ****************`.env`****************:**

   ```env
   OPENAI_API_KEY=sk-...
   ```

4. **Run the notebook:**

   Launch `brochure_generator.ipynb` and input:

   * Company name
   * Website URL

---

## 📌 Example Output

```markdown
# About Hugging Face

Hugging Face is a leading open-source AI company focused on democratizing machine learning tools and models. Their mission is to make machine learning accessible to all developers and researchers...

# Culture & Values

Hugging Face promotes an open, collaborative, and transparent work environment...

# Careers

Visit: https://huggingface.co/careers
```

---

## 🤝 Contributing

Pull requests are welcome! If you’d like to contribute improvements to scraping, LLM prompting, or formatting — feel free to fork and submit a PR.

---

## 🡩‍🎓 Credits

Created as part of the [llmengineering.dev](https://llmengineering.dev) course.
Built by [Your Name](https://github.com/your-github).

---

## 📄 License

MIT License
