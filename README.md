# Company Brochure Generator using OpenAI

Generate professional brochures about any company using just its website URL and name — powered by OpenAI's GPT-4o-mini and Python. The brochure is available in both **English and French**.

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

The brochure is generated in **English** and then automatically translated into **French**.

---

## 🚀 Features

* 🌐 **Web scraping** using BeautifulSoup
* 🤖 **LLM-powered summarization** with GPT-4o-mini
* 📟 **Brochure generation** in clean Markdown format
* 🧠 **URL filtering** using intelligent prompt-based link selection
* 🇫🇷 **Automatic translation** from English to French

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
📦 llm_brochure_generator/
 ├── README.md                                  # Project readme
 └── week1/
     └── community-contributions/
         └── day5_challenge_exercise/
             └── day5_translation_challenge.ipynb  # Main notebook
```

---

## 🧪 How to Use

1. **Clone the repo:**

   ```bash
   git clone https://github.com/RalphMaa/llm_brochure_generator.git
   cd llm_brochure_generator
   ```

2. **Set up your environment:**

   Create and activate a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # on Windows use `venv\Scripts\activate`
   ```

3. **Install required packages manually:**

   Since there's no `requirements.txt`, install dependencies manually:

   ```bash
   pip install openai python-dotenv beautifulsoup4 requests
   ```

4. **Create your `.env` file with your OpenAI API key:**

   ```bash
   touch .env
   ```

   Inside the `.env` file, add the following line:

   ```env
   OPENAI_API_KEY=your-api-key-here
   ```

5. **Run the notebook:**

   Open the following notebook in Jupyter:

   ```
   week1/community-contributions/day5_challenge_exercise/day5_translation_challenge.ipynb
   ```

   Inside the notebook, provide:

   * Company name
   * Website URL

   The notebook will generate:

   * A brochure in **English**
   * A translated version in **French**

---

## 📌 Example Output

Found links: {'links': [{'type': 'home page', 'url': 'https://huggingface.co/'}, {'type': 'models page', 'url': 'https://huggingface.co/models'}, {'type': 'datasets page', 'url': 'https://huggingface.co/datasets'}, {'type': 'spaces page', 'url': 'https://huggingface.co/spaces'}, {'type': 'enterprise page', 'url': 'https://huggingface.co/enterprise'}, {'type': 'pricing page', 'url': 'https://huggingface.co/pricing'}, {'type': 'docs page', 'url': 'https://huggingface.co/docs'}, {'type': 'blog page', 'url': 'https://huggingface.co/blog'}, {'type': 'careers page', 'url': 'https://apply.workable.com/huggingface/'}, {'type': 'about page', 'url': 'https://huggingface.co/huggingface'}, {'type': 'changelog page', 'url': 'https://huggingface.co/changelog'}, {'type': 'discussion page', 'url': 'https://discuss.huggingface.co'}, {'type': 'status page', 'url': 'https://status.huggingface.co'}, {'type': 'GitHub page', 'url': 'https://github.com/huggingface'}, {'type': 'Twitter page', 'url': 'https://twitter.com/huggingface'}, {'type': 'LinkedIn page', 'url': 'https://www.linkedin.com/company/huggingface/'}]}
# Hugging Face – The AI Community Building the Future

## About Us
Hugging Face is a platform where the machine learning community collaborates on models, datasets, and applications. We provide powerful tools and an extensive library to accelerate your AI projects.

## Our Offerings
- **Models**: Browse over 1 million models tailored for various applications.
- **Datasets**: Access and share a huge collection of datasets for any machine learning task.
- **Spaces**: Create and deploy applications with our user-friendly tools.
- **Enterprise Solutions**: Advanced AI solutions with enterprise-grade security and dedicated support.

## Trending Models This Week
- **moonshotai/Kimi-K2-Instruct**: 15.9k downloads (Updated 19 hours ago)
- **HuggingFaceTB/SmolLM3-3B**: 24.4k downloads (Updated 3 days ago)
- **THUDM/GLM-4.1V-9B-Thinking**: 34.9k downloads (Updated 5 days ago)
- **black-forest-labs/FLUX.1-Kontext-dev**: 239k downloads (Updated 16 days ago)
- **mistralai/Devstral-Small-2507**: 6.93k downloads (Updated 3 days ago)

## Key Features
- Collaborate and share unlimited public models, datasets, and applications.
- Accelerate your machine learning projects with paid compute and enterprise solutions starting at $0.60/hour for GPU.
- Join over 50,000 organizations leveraging our platform, including companies like Google, Microsoft, and Amazon.

## Get Started
Sign up today to build, discover, and collaborate in the evolving world of machine learning. 
Explore and utilize our community-driven open-source tools to enhance your workflow!

### [Sign Up](#) | [Log In](#)

---

# Hugging Face – La communauté IA qui construit l'avenir

## À Propos
Hugging Face est une plateforme où la communauté de l'apprentissage automatique collabore sur des modèles, des ensembles de données et des applications. Nous fournissons des outils puissants et une bibliothèque extensive pour accélérer vos projets IA.

## Nos Offres
- **Modèles** : Parcourez plus de 1 million de modèles adaptés à diverses applications.
- **Ensembles de données** : Accédez et partagez une vaste collection d'ensembles de données pour toute tâche d'apprentissage automatique.
- **Espaces** : Créez et déployez des applications avec nos outils conviviaux.
- **Solutions Entreprises** : Solutions IA avancées avec une sécurité de niveau entreprise et un support dédié.

## Modèles Tendance Cette Semaine
- **moonshotai/Kimi-K2-Instruct** : 15.9k téléchargements (mis à jour il y a 19 heures)
- **HuggingFaceTB/SmolLM3-3B** : 24.4k téléchargements (mis à jour il y a 3 jours)
- **THUDM/GLM-4.1V-9B-Thinking** : 34.9k téléchargements (mis à jour il y a 5 jours)
- **black-forest-labs/FLUX.1-Kontext-dev** : 239k téléchargements (mis à jour il y a 16 jours)
- **mistralai/Devstral-Small-2507** : 6.93k téléchargements (mis à jour il y a 3 jours)

## Caractéristiques Clés
- Collaborez et partagez des modèles, des ensembles de données et des applications publics illimités.
- Accélérez vos projets d'apprentissage automatique avec des solutions de calcul payantes et des solutions entreprises à partir de 0,60 $/heure pour un GPU.
- Rejoignez plus de 50 000 organisations utilisant notre plateforme, y compris des entreprises comme Google, Microsoft et Amazon.

## Commencez
Inscrivez-vous dès aujourd'hui pour construire, découvrir et collaborer dans le monde en évolution de l'apprentissage automatique. 
Explorez et utilisez nos outils open-source communautaires pour améliorer votre flux de travail !

### [S'inscrire](#) | [Se connecter](#)

---

## 🤝 Contributing

Pull requests are welcome! If you’d like to contribute improvements to scraping, LLM prompting, or formatting — feel free to fork and submit a PR.

---

## 🡩‍🎓 Credits

Created as part of the [llmengineering.dev](https://www.udemy.com/course/llm-engineering-master-ai-and-large-language-models/?couponCode=KEEPLEARNING) course.
Built by [Ralph Maalouf](https://github.com/RalphMaa).

---
