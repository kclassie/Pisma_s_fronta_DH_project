# Pisma_s_fronta_DH_project

В репозитории содержатся материалы цифрового гуманитарного исследования "Анализ корпуса писем времен Великой Отечественной войны с использованием методов машинного обучения.

This repository describes my work on the digital humanities research about The Great Patriotic War

| Стек технологий        | |
| ------------- |:-------------:|
| Selenium WebDriver | Скрейпинг сайта с текстами писем                | 
| BeautifulSoup      | Синтаксический разбор HTML/XML                  |
| NLTK               | Символьная и статистическая обработка текста    |
| Pymorphy2          | Морфологический анализ текстов на русском языке |
| Gensim             | Тематическое моделирование                      |
| Scikit-learn       | Решение задач классического машинного обучения  |


# Содержание:

1)	PismaSFronta_scraping_Selenium.ipynb – программный код для скрейпинга сайта pismasfronta.com.
2)	PismaSFronta_url_sorting.ipynb – программный код для сортировки url-адресов страниц сайта.
3)	PismaSFronta_to_TEI.ipynb – программный код для форматирования данных html-кода в xml-документы по стандарту TEI.
4)	PismaSFronta_word_analysis.ipynb – программный код для статистического анализа текстов корпуса.
5)	PismaSFronta_W2V.ipynb – программный код для обучения модели Word2vec.
6)	PismaSFronta_clastering.ipynb – программный код для кластеризации текстов корпуса с применением алгорита k-mean.
7)	letters_model.model – файл с моделью Word2vec, обученной на текстах корпуса фронтовых писем: https://drive.google.com/open?id=1LEb-Qirzv7HqsOpsO3UkUfcjYoCQzXxr

## Корпус xml-файлов с текстами писем ## 
доступен в google-папке: https://drive.google.com/drive/folders/1FMNTBZF4GepY10VZyXySaWLralnOlqfY

Таблицы с частотностью слов и TF-IDF находятся здесь
https://drive.google.com/drive/folders/1rV-7-3O8IX-IvG0R53yvtfrJpBAQqXJo
