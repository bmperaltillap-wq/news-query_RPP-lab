# News Query RPP Lab

**Task 1 – Retrieval de noticias de RPP**  
Pipeline end-to-end: RSS → tokenización (`tiktoken`) → embeddings (`all-MiniLM-L6-v2`) → vector store (ChromaDB) → retriever con LangChain → tabla de resultados.

---

## 📌 Objetivo
Ingerir las 50 últimas noticias de RPP (https://rpp.pe/rss) y construir un sistema de consulta por similitud (ejemplo: “Últimas noticias de economía”).

---

## 📂 Estructura
- `notebooks/rpp_retrieval.ipynb` — Notebook principal (modular: load → tokenize → embed → store → retrieve).
- `data/` — (opcional) snapshot de noticias (`rpp_sample.json`).
- `outputs/` — (opcional) capturas/tablas exportadas.

---

## ⚙️ Instalación
Clona el repositorio y luego:
```bash
pip install -r requirements.txt
