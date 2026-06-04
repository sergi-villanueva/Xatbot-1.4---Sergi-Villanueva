# XatBot Talent 2026 - Sergi Villanueva

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![Google Gemini](https://img.shields.io/badge/Google%20Gemini-2.5%20Flash-orange.svg)](https://ai.google.dev/)
[![Flask](https://img.shields.io/badge/Flask-3.x-black.svg)](https://flask.palletsprojects.com/)

**XatBot dinàmic per WordPress** que extreu informació en temps real de la teva pàgina web i respon de forma intel·ligent utilitzant **Google Gemini**.

---

## ✨ Característiques

- **Scraping dinàmic** — Agafa la informació actual de la teva web cada vegada
- **Intel·ligència Artificial** — Alimentat per Google Gemini
- **Widget flotant** — Fàcil d'incrustar a WordPress
- **Ngrok** — Execució ràpida des de Google Colab
- **Totalment en català** — Respostes naturals i professionals

---

## 🚀 Com utilitzar

### 1. Google Colab
1. Obre el fitxer [`XatBot_talent_2026.ipynb`](XatBot_talent_2026.ipynb)
2. Configura els **Secrets** (`GEMINI_API_KEY` i `NGROK_AUTH_TOKEN`)
3. Executa les cel·les
4. Copia la URL de Ngrok

### 2. WordPress
1. Afegeix el contingut de [`Widget_talent.html`](Widget_talent.html) en un bloc **HTML personalitzat**
2. Actualitza la URL del Ngrok al widget

---

## 📁 Estructura del projecte
Xatbot-1.4---Sergi-Villanueva/
├── XatBot_talent_2026.ipynb      # Notebook principal (Colab)
├── Widget_talent.html            # Widget per WordPress
├── README.md
├── CHANGELOG.md
├── CONTRIBUTING.md


---

## 🛠 Tecnologies

- Python + Flask
- Google Gemini (gemini-2.5-flash)
- BeautifulSoup4 (scraping)
- Ngrok
- Google Colab
