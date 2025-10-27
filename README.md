🇫🇷 Description (Français)

Ce projet combine le web scraping avancé, l’analyse concurrentielle et les modèles de langage (LLMs) pour extraire, nettoyer et analyser des données de produits Amazon à grande échelle.
Grâce à l’API Oxylabs E-Commerce Scraper, le script collecte automatiquement les informations produits (titres, prix, évaluations, avis, vendeurs, catégories) et applique ensuite des LLMs (GPT, Claude, ou Gemini) pour générer des insights intelligents, comme des résumés de tendances ou des analyses de performances concurrentielles.

⸻

🚀 Fonctionnalités principales
	•	🌐 Extraction automatique des données :
Utilisation de l’API Oxylabs pour collecter de manière fiable et éthique les données produits Amazon.
	•	🧹 Nettoyage et structuration des données :
Transformation des réponses JSON en jeux de données propres et analysables avec Pandas.
	•	🤖 Analyse intelligente avec LLM :
Génération de résumés de tendances, analyse de sentiments dans les avis clients, et extraction automatique d’insights sur la concurrence.
	•	💡 Analyse concurrentielle :
Comparaison de prix, notes et volumes d’avis entre différents produits et vendeurs.
	•	📊 Exploration et visualisation :
Analyses statistiques et graphiques interactifs avec Matplotlib, Seaborn, et Plotly.
	•	⚙️ Exportation et automatisation :
Exportation des résultats en CSV, Excel ou base SQL, et intégration possible avec des tableaux de bord (Power BI / Tableau).

⸻

🛠️ Technologies utilisées
	•	Langage : Python
	•	APIs : Oxylabs Scraper API, OpenAI / Anthropic / Gemini (LLMs)
	•	Bibliothèques : Requests, Pandas, NumPy, Matplotlib, Seaborn, Plotly, LangChain
	•	Stockage : CSV, Excel, SQLite
	•	Environnement : Jupyter Notebook, VS Code

⸻

🧩 Pipeline du projet
	1.	Collecte des données via Oxylabs API
	2.	Nettoyage et parsing des données JSON
	3.	Analyse avec LLM pour extraire les insights pertinents
	4.	Visualisation et interprétation des résultats
	5.	Exportation vers formats exploitables

⸻

📈 Exemple de résultats générés

Résumé LLM :
“Les produits de la marque A affichent un prix moyen 12 % supérieur à ceux de la marque B, mais obtiennent une meilleure note moyenne (4.6/5 contre 4.2/5). Les avis clients soulignent la qualité et la durabilité comme principaux facteurs positifs.”

⸻

📚 Objectifs pédagogiques
	•	Appliquer des méthodes de scraping via API conformes et efficaces.
	•	Utiliser des LLMs pour interpréter et résumer des données non structurées.
	•	Mettre en œuvre un pipeline complet de collecte, traitement et analyse de données.
	•	Générer des insights exploitables pour l’intelligence économique et le marketing produit.

⸻

⚠️ Avertissement

Ce projet est réalisé à des fins éducatives et expérimentales.
Toutes les données sont collectées via l’API officielle d’Oxylabs, dans le respect des politiques d’utilisation et de la législation en vigueur.

⸻

🇬🇧 Description (English)

This project integrates advanced web scraping, competitive intelligence, and Large Language Models (LLMs) to extract, clean, and analyze Amazon product data at scale.
Using the Oxylabs E-Commerce Scraper API, it automatically gathers product details (titles, prices, ratings, reviews, sellers, categories) and applies LLM-powered analysis (GPT, Claude, Gemini) to generate smart insights and competitor summaries.

⸻

🚀 Key Features
	•	🌐 Automated Data Extraction:
Uses Oxylabs API to scrape Amazon product and seller data ethically and efficiently.
	•	🧹 Data Cleaning & Structuring:
Converts raw JSON data into clean, structured Pandas DataFrames.
	•	🤖 LLM-Powered Insights:
Summarizes trends, performs sentiment analysis on reviews, and extracts competitive intelligence automatically.
	•	💡 Competitor Benchmarking:
Compares prices, ratings, and review counts across competing brands and products.
	•	📊 Data Exploration & Visualization:
Provides EDA and visual insights using Matplotlib, Seaborn, and Plotly.
	•	⚙️ Data Export & Automation:
Exports data to CSV, Excel, or SQL and can integrate into dashboards (Power BI / Tableau).

⸻

🛠️ Tech Stack
	•	Languages: Python
	•	APIs: Oxylabs Scraper API, OpenAI / Anthropic / Gemini
	•	Libraries: Requests, Pandas, NumPy, Matplotlib, Seaborn, Plotly, LangChain
	•	Storage: CSV, Excel, SQLite
	•	Environment: Jupyter Notebook, VS Code

⸻

🧩 Workflow
	1.	Fetch data using Oxylabs API
	2.	Clean and parse JSON data
	3.	Run LLM-based summarization and sentiment analysis
	4.	Visualize and interpret results
	5.	Export structured insights

⸻

📈 Sample Output

LLM Summary Example:
“Brand A’s products are priced 12% higher on average than Brand B’s, but have better ratings (4.6 vs 4.2). Customer reviews highlight durability and packaging as key strengths.”

⸻

📚 Learning Objectives
	•	Learn how to perform API-based scraping responsibly.
	•	Use LLMs for automated insight generation and competitor benchmarking.
	•	Build end-to-end data pipelines from extraction to visualization.
	•	Derive business intelligence and actionable insights from unstructured data.

⸻

⚠️ Disclaimer

This project is for educational and research purposes only.
All data is collected via Oxylabs’ official API, respecting terms of service and applicable data regulations.
