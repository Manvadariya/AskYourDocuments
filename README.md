# 🌟 AskYourDocuments: Elevate Your Document Interaction to an Art Form 🌟

**Step into the future of document intelligence.** AskYourDocuments is not just a tool; it's your **personal AI-powered concierge** for navigating complex information. Imagine effortlessly transforming static PDFs, DOCX files, images, and more into dynamic conversational partners. Uncover critical insights with unprecedented speed, extract knowledge with surgical precision, and immerse yourself in a **first-class document analysis experience**, meticulously crafted for discerning professionals who accept nothing less than excellence.

---

## 🔧 Engineered With a Symphony of Premium Technologies

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS"/>
  <img src="https://img.shields.io/badge/ChatGPT-10A37F?style=for-the-badge&logo=openai&logoColor=white" alt="ChatGPT"/>
  <img src="https://img.shields.io/badge/LangChain-000000?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain"/>
  <img src="https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" alt="Google Colab"/>
</p>

---

## ✨ Experience Unparalleled Premium Features
- **Sophisticated AI-Driven Analysis:** Delve deep into PDFs, DOCX, and even images, extracting nuanced insights with our advanced AI engine.
- **Intuitive Conversational Interface:** Engage with your documents as if consulting a subject matter expert, receiving articulate and context-aware responses.
- **Exquisite & Responsive Design:** Navigate a visually stunning UI, enhanced with fluid animations and a professional aesthetic that speaks to quality.
- **Universal Format Mastery:** Effortlessly manage and interrogate a diverse range of document types within a single, unified platform.
- **Elite, Enterprise-Grade Performance:** Rely on a robust backend powered by cutting-edge AI models and sophisticated document parsing for consistently superior results.

## ⚙️ A Glimpse into Our Advanced Technical Architecture
- **Frontend Elegance:** Crafted with responsive HTML5, styled with the utility-first power of Tailwind CSS, and brought to life with dynamic JavaScript animations for a seamless user experience.
- **Backend & AI Prowess:** A formidable Python ecosystem, integrating state-of-the-art Large Language Models (LLMs) and intelligent vector embeddings for profound contextual understanding.
- **Precision Document Processing:** Leveraging advanced parsing algorithms for meticulous extraction from PDF, DOCX, XLSX, PPTX, and various image formats.
- **Flexible Deployment Pathways:** Choose between convenient local Jupyter Notebook integration for rapid prototyping or robust enterprise server deployment for scalable solutions.

## 📦 Effortless & Seamless Onboarding Journey
1. **Acquire the Foundation:** Clone the repository to your preferred local or cloud environment.
2. **Ignite the Engine:** Launch the `AskYourDocuments.ipynb` notebook within your Jupyter environment (Google Colab recommended for ease of use and primary development environment).
3. **Automated Configuration:** Execute all cells sequentially; our intuitive setup process guides you effortlessly.
4. **Unlock the Power:** Begin uploading your documents and instantly experience the transformative power of AI-driven conversational intelligence.

---

## 🚀 Ascend to a New Realm of Document Experience Today!
Don't just manage your documents – **master them**. Unearth hidden intelligence, accelerate your workflows, and redefine your relationship with information. Join the vanguard of professionals who are leveraging the unparalleled power of conversational document analysis.

**AskYourDocuments** – Where your documents transcend their static form and become your most insightful, articulate, and indispensable partners. **Dare to experience the difference.**

## 🧪 Robust notebook environment setup (local Jupyter / VS Code)
1. Create and activate a fresh virtual environment.
2. Install Python dependencies:
   ```bash
   python -m pip install -r requirements.notebook.txt
   ```
3. Install optional OCR/system tools (Linux):
   ```bash
   sudo apt-get update
   sudo apt-get install -y tesseract-ocr tesseract-ocr-eng poppler-utils libreoffice unoconv
   ```
4. Export runtime secrets before running the notebook:
   ```bash
   export GITHUB_MODELS_ENDPOINT="https://models.github.ai/inference"
   export AZURE_INFERENCE_ENDPOINT="$GITHUB_MODELS_ENDPOINT"
   export GITHUB_TOKEN="<your_github_models_token>"
   export AZURE_EMBEDDING_API_KEY="$GITHUB_TOKEN"
   export AZURE_LLM_MODEL="openai/gpt-4o-mini"
   export AZURE_EMBEDDING_MODEL="openai/text-embedding-3-large"
   export HF_TOKEN="<your_huggingface_token>"
   export HF_VISION_MODEL="meta-llama/Llama-3.2-11B-Vision-Instruct"
   export NGROK_AUTHTOKEN="<optional_ngrok_token>"
   ```
5. Open `AskYourDocuments.ipynb` and run all cells.

> The notebook now reads environment variables directly and gracefully handles non-Colab environments.
