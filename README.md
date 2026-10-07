<div align="center">

# Андрей Мельнейчук

### **LLM Engineer / AI Backend Developer**

[![Telegram](https://img.shields.io/badge/Telegram-@melneichuk-2CA5E0?style=flat-square&logo=telegram&logoColor=white)](https://t.me/melneichuk)
[![Email](https://img.shields.io/badge/Email-andreimelneichuk@yandex.ru-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:andreimelneichuk@yandex.ru)
[![Location](https://img.shields.io/badge/Location-%D0%9F%D0%B5%D1%80%D0%BC%D1%8C%20%C2%B7%20%D1%80%D0%B5%D0%BB%D0%BE%D0%BA%D0%B0%D1%86%D0%B8%D1%8F%20%D0%B2%20%D0%A1%D0%B0%D0%BD%D0%BA%D1%82--%D0%9F%D0%B5%D1%82%D0%B5%D1%80%D0%B1%D1%83%D1%80%D0%B3%20%C2%B7%20Remote-blue?style=flat-square)](https://t.me/melneichuk)
[![Education](https://img.shields.io/badge/Education-PSNRU%20Computer%20Security-informational?style=flat-square)](https://psu.ru)

<p align="center">
  Разрабатываю и внедряю агентные архитектуры (<b>Model Context Protocol, Tool Calling</b>), поисковые RAG-контуры на базе <b>OpenSearch</b> и асинхронные бэкенд-сервисы на <b>Python, FastAPI и Apache Kafka</b>.
</p>

</div>

---

### 👨‍💻 Обо мне

- 🏢 **AI / LLM Developer в GreenData:** Разрабатываю AI-ассистента GreenBox — интеграция внешних API через **Model Context Protocol (MCP)**, прямой семантический и текстовый поиск в **OpenSearch**, асинхронная сервисная шина на **Apache Kafka**, оценка качества ответов (**LLM-as-a-Judge**, Langfuse) и пре-фильтрация трафика.
- 🧪 **Data & Model Evaluation в Яндекс Крауд (2023–2024):** Сравнительный аудит (Side-by-Side) качества ответов **YandexGPT** и поисковой выдачи, разметка галлюцинаций и формирование датасетов.
- 🎓 **Образование:** ПГНИУ (Институт компьютерных наук и технологий), специальность «Компьютерная безопасность» (Выпуск 2025).

---

### 🛠 Технологический стек

```
LLM & Агенты   :: MCP, Tool Calling, LangChain / LangGraph, OpenSearch (RAG), vLLM, Langfuse, MLflow, LLM-as-a-Judge
Модели & NLP   :: PyTorch, Transformers, BERT fine-tuning, Zero-Shot NLI, SpaCy, Label Studio
Бэкенд         :: Python (asyncio), FastAPI, Flask, Apache Kafka, PostgreSQL, SQLAlchemy, Redis, Pytest
Инфраструктура :: Docker, GitLab CI/CD, Linux, C++ (базовый)
```

---

### 🔬 Ключевые проекты и R&D

<table>
  <tr>
    <td width="50%">
      <h3>🔌 <a href="https://github.com/andreimelneichuk/mcp-secure-server">MCP Secure Server (RBAC & Auth)</a></h3>
      <p>Референсная реализация сервера <b>Model Context Protocol (MCP)</b> с ролевой моделью доступа (RBAC) и OAuth-аутентификацией для безопасного подключения инструментов к корпоративным источникам данных.</p>
      <p><code>Python</code> <code>MCP</code> <code>FastAPI</code> <code>OAuth</code> <code>Security</code></p>
    </td>
    <td width="50%">
      <h3>🔍 OpenSearch Agentic RAG</h3>
      <p><i>Коммерческий проект (код под NDA)</i></p>
      <p>Гибридный (полнотекстовый + семантический) поиск в OpenSearch, подключённый к AI-агенту как MCP-инструмент; фоновая периодическая индексация базы знаний через GitLab CI.</p>
      <p><code>OpenSearch</code> <code>MCP</code> <code>Python</code> <code>GitLab CI</code> <code>RAG</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>📑 <a href="https://github.com/andreimelneichuk/nlp-pipeline-bert">BERT Document Classifier</a></h3>
      <p>Fine-tuning <b>ruBERT</b> для многоклассовой классификации документов (балансировка классов через <code>WeightedRandomSampler</code>, <b>F1 ~0.95</b>) и динамическая <b>INT8-квантизация</b>: модель меньше ~4x, инференс на CPU быстрее в 2–3 раза практически без потери качества.</p>
      <p><code>PyTorch</code> <code>Transformers</code> <code>ruBERT</code> <code>INT8</code></p>
    </td>
    <td width="50%">
      <h3>🧪 <a href="https://github.com/andreimelneichuk/AgentLab">Tool Calling Stability Experiments</a></h3>
      <p>Бенчмарк архитектур агента с <b>MCP</b>: baseline-цикл (LLM → Tool → LLM) и 17 экспериментов — валидация и нормализация аргументов тулов, детерминированная маршрутизация, сжатие контекста, Graph-RAG, мультиагентная проверка ответов. Прогон на mock MCP-серверах, оценка через <b>LLM-as-a-Judge</b> (Solve Rate, Safety, latency).</p>
      <p><code>Python</code> <code>MCP</code> <code>Tool Calling</code> <code>LLM-as-a-Judge</code></p>
    </td>
  </tr>
</table>

---

### 📬 Контакты для связи

- **Telegram:** [@melneichuk](https://t.me/melneichuk)
- **Email:** [andreimelneichuk@yandex.ru](mailto:andreimelneichuk@yandex.ru)
- **Резюме:** [HeadHunter](https://perm.hh.ru/resume/6baf401fff0d4df01e0039ed1f63707073616c)
