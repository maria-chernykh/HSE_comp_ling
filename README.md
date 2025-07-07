# Промежуточный проект по программе ВШЭ ДПО 'Компьютерная лингвистика'  
*(English description is below)*
## "Как изменилась тематика фильмов за последние 20 лет"  
Этот NLP-проект создан для анализа изменений в тематике кинофильмов по двум периодам: 2020-2025 и 2000-2005гг.  
В качестве данных используются описания фильмов с [Кинопоиска](https://kinopoisk.ru). Данные загружаются через [API Кинопоиска](https://kinopoisk.dev).  
Для работы используются такие инструменты как: pandas, regex, nltk, mystem, pymorphy3, numpy, PIL, matplotlib, wordcloud. Тематические слова определяются с помощью метрики TF-IDF.
  
Этапы проекта:
1) парсинг, сбор корпусов
2) очистка и нормализация текстов
3) извлечение ключевых слов
4) визуализация ключевых слов
--------------  

## 'Movie topic drift over the recent 20 years'  
This NLP project is designed to analyze drift in movie topics across two time periods: 2020-2025 and 2000-2005 years.  
Movie descriptions from [Kinopoisk](https://kinopoisk.ru) are used as the data source. The data is loaded via [Kinopoisk API](https://kinopoisk.dev).  
Tools used in this project: pandas, regex, nltk, mystem, pymorphy3, numpy, PIL, matplotlib, wordcloud. Topic words are identified based on TF-IDF score.  
  
Project pipeline:
1) Data Parsing & Corpus Compilation
2) Text Preprocessing & Normalization
3) Keywords Extraction
4) Keywords Visualization
