# Курочкина Анастасия - Начинающий Data Analyst

## 📌 Обо мне
Студентка 3 курса РХТУ им. Менделеева по специальности "Информационные компьютерные технологии". На данный момент у меня нет опыта работы аналитиком данных, но меня очень заинтересовала это направление, поэтому сейчас я активно осваиваю анализ данных и визуализацию информации. Мне нравится изучать новые инструменты и методы анализа данных. Независимо от того, работаю ли я в команде или самостоятельно, меня вдохновляет возможность открывать для себя что-то новое и получать удовольствие от использования данных для решения сложных задач. Ищу возможности для стажировки и практического применения навыков в реальных проектах, чтобы расширить свои знания и навыки.
Это репозиторий, где я буду демонстрировать свои навыки, делиться проектами и отслеживать свой прогресс в области анализа данных.

## 🎓 Образование
**РХТУ им. Д.И. Менделеева** (2022-2026)  
Факультет цифровых технологий и химического инжиниринга (ЦиТХИн)  
Кафедра информационных компьютерных технологий (ИКТ)

## 🧠 **Soft Skills**  
- Коммуникация  
- Тайм-менеджмент 
- Аналитическое мышление  
- Командная работа  

## 💻 **Hard Skills**  
- SQL
- Python (Pandas, NumPy, Matplotlib)  
- PowerBI  
- Excel / Google Sheets
- Английский: Intermediate (B1)  

## 📊 Проекты
### 1. Комплексный маркетинговый анализ с использованием SQL, Python и Power BI
#### Улучшение конверсии и вовлеченности: кейс розничного интернет-магазина

- **SQL Server:** Запросы и очистка данных с помощью SQL для получения дополнительной информации.
  * Применение **CTE (Common Table Expressions)** для поиска дубликатов перед их удалением
  * Оконные функции (`ROW_NUMBER()`, `AVG() OVER`) для нумерации строк и расчета средних значений
  * Обработка пропусков: замена NULL на средние значения через `COALESCE`
  * Нормализация данных: приведение регистра (`UPPER`), удаление лишних пробелов (`REPLACE`)
  * Разделение составных полей (`CHARINDEX`, `LEFT`, `RIGHT`)
  * Категоризация цен через `CASE WHEN`
  * Объединение таблиц (`LEFT JOIN`)
  * Форматирование дат (`FORMAT`, `CONVERT`)
  
  *Code:* [`PortfolioProject_MarketingAnalytics.sql`](https://github.com/AAK30-23/PortfolioProject_MarketingAnalyticsShop/blob/main/PortfolioProject_MarketingAnalytics.sql)

- **Python:** Расширенный анализ настроений.
  * Подключение к SQL Server через `pyodbc`, выгрузка данных в `pandas`
  * Обработка пропусков и пустых значений в тексте
  * Анализ тональности отзывов с помощью **NLTK и VADER** 
  * Категоризация настроений с учетом рейтинга и тональности текста (Mixed Positive / Mixed Negative)
  * Группировка sentiment-оценок по диапазонам
  * Экспорт датасета в CSV
  
  *Code:* [`PortfolioProject_MarketingAnalytics.py`](https://github.com/AAK30-23/PortfolioProject_MarketingAnalyticsShop/blob/main/PortfolioProject_MarketingAnalytics.py)

- **Power BI:** Создание интерактивного дашборда.
  * Визуализация ключевых метрик: конверсия, вовлеченность клментов, рейтинг отзывов
  * Интерактивные фильтры по категориям товаров и датам
  * Анализ сезонности и эффективности маркетинговых кампаний

### 1. Комплексный маркетинговый анализ с использованием SQL, Python и Power BI
#### Улучшение конверсии и вовлеченности: кейс розничного интернет-магазина

[все твои SQL/Python навыки...]

- **Power BI:** Создание интерактивного дашборда.
  * Визуализация ключевых метрик: конверсия, вовлеченность клиентов, рейтинг отзывов
  * Интерактивные фильтры по категориям товаров и датам
  * Анализ сезонности и эффективности маркетинговых кампаний

<details>
<summary><b>📊 ПОСМОТРЕТЬ ДАШБОРДЫ </b></summary>
<br>

**Обзор ключевых метрик**
<img src="https://github.com/AAK30-23/PortfolioProject_MarketingAnalyticsShop/blob/main/PortfolioProject_MarketingAnalyticsShop_screens/PortfolioProject_MarketingAnalytics_pages-to-jpg-0001.jpg?raw=true" alt="Обзор KPI" style="width: 100%; border: 1px solid #ddd; border-radius: 4px; margin: 5px 0;">

**Анализ конверсии**
<img src="https://github.com/AAK30-23/PortfolioProject_MarketingAnalyticsShop/blob/main/PortfolioProject_MarketingAnalyticsShop_screens/PortfolioProject_MarketingAnalytics_pages-to-jpg-0002.jpg?raw=true" alt="Конверсия" style="width: 100%; border: 1px solid #ddd; border-radius: 4px; margin: 5px 0;">

**Анализ социальных сетей**
<img src="https://github.com/AAK30-23/PortfolioProject_MarketingAnalyticsShop/blob/main/PortfolioProject_MarketingAnalyticsShop_screens/PortfolioProject_MarketingAnalytics_pages-to-jpg-0003.jpg?raw=true" alt="Sentiment анализ" style="width: 100%; border: 1px solid #ddd; border-radius: 4px; margin: 5px 0;">

**Анализ оценок клиентов**
<img src="https://github.com/AAK30-23/PortfolioProject_MarketingAnalyticsShop/blob/main/PortfolioProject_MarketingAnalyticsShop_screens/PortfolioProject_MarketingAnalytics_pages-to-jpg-0004.jpg?raw=true" alt="Sentiment анализ" style="width: 100%; border: 1px solid #ddd; border-radius: 4px; margin: 5px 0;">

</details>

<details>
<summary><b>📋 ПОСМОТРЕТЬ ПРЕЗЕНТАЦИЮ ПО ПРОЕКТУ </b></summary>
 
<br>

<div style="display: flex; flex-wrap: wrap; justify-content: space-between;">
<img src="https://github.com/user-attachments/assets/2922f9d1-4db2-4458-bff5-d105e31b23e5" alt="Слайд1" style="width: 48%; margin: 5px 0; border: 1px solid #ddd; border-radius: 4px;">
<img src="https://github.com/user-attachments/assets/3de3b71f-3712-4885-a535-aa5e582adff1" alt="Слайд2" style="width: 48%; margin: 5px 0; border: 1px solid #ddd; border-radius: 4px;">
<img src="https://github.com/user-attachments/assets/a4d2f9fc-b895-4f47-ba9a-b673c76ac02d" alt="Слайд3" style="width: 48%; margin: 5px 0; border: 1px solid #ddd; border-radius: 4px;">
<img src="https://github.com/user-attachments/assets/5d9473af-7313-4012-862f-18b9820bbbee" alt="Слайд4" style="width: 48%; margin: 5px 0; border: 1px solid #ddd; border-radius: 4px;">
<img src="https://github.com/user-attachments/assets/f8ec92fa-8816-4a82-95d1-e48c9cc9fb90" alt="Слайд5" style="width: 48%; margin: 5px 0; border: 1px solid #ddd; border-radius: 4px;">
<img src="https://github.com/user-attachments/assets/17979fcc-fed5-45f7-a4a5-0310745cbd38" alt="Слайд6" style="width: 48%; margin: 5px 0; border: 1px solid #ddd; border-radius: 4px;">
<img src="https://github.com/user-attachments/assets/7a2a9047-f4e1-4616-a7a1-8d1b68198fb2" alt="Слайд7" style="width: 48%; margin: 5px 0; border: 1px solid #ddd; border-radius: 4px;">
<img src="https://github.com/user-attachments/assets/2336502f-2cef-451c-a462-f33c714a1a43" alt="Слайд8" style="width: 48%; margin: 5px 0; border: 1px solid #ddd; border-radius: 4px;">
<img src="https://github.com/user-attachments/assets/eb9e9fdb-20ff-4236-9de2-6b304afbf6e2" alt="Слайд9" style="width: 48%; margin: 5px 0; border: 1px solid #ddd; border-radius: 4px;">
<img src="https://github.com/user-attachments/assets/bb19a7ca-b9b7-4745-a308-a48c6a0acef1" alt="Слайд10" style="width: 48%; margin: 5px 0; border: 1px solid #ddd; border-radius: 4px;">
<img src="https://github.com/user-attachments/assets/04f23b75-cdf5-4425-89be-8dab45005441" alt="Слайд11" style="width: 48%; margin: 5px 0; border: 1px solid #ddd; border-radius: 4px;">
</div>

</details>

## 🏫 Дополнительная активность 
Курсы, которые я прошла/прохожу
- Курс [`Анализ данных просто и доступно`](https://stepik.org/course/73952/syllabus)
- Курс [`Анализ данных с Pandas`](https://stepik.org/course/187506/syllabus)
- Курс [`Теория вероятностей`](https://stepik.org/course/3089/syllabus)
- Курс [`Основы анализа данных в SQL, Python, Power BI, DataLens`](https://netology.ru/profile/program/spdata-1/schedule)
- Курс [`Интерактивный курс по SQL`](https://sql-academy.org/ru/guide)
- Упражнения по SQL [`Тренажер по SQL`](https://sql-academy.org/ru/trainer)
- Упражнения по SQL [`Упражнения по SQL`](https://sql-ex.ru/index.php?errno=3)
- Упражнения по SQL [`SQL & Data Interview Questions`](https://datalemur.com/questions)
- Плейлисты по SQL, Python для анализа данных, PowerBI на YouTube

## 📈 Что я сейчас изучаю
- Python (Pandas, NumPy, Matplotlib)  
- SQL
- PowerBI  
- Excel / Google Sheets
- Статистика для анализа данных 

## 📫 Контакты
[![Email](https://img.shields.io/badge/-Email-8B89CC?style=flat&logo=mail.ru&logoColor=white)](mailto:kurochkinaaanastasia@yandex.ru)  
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat&logo=github)](https://github.com/AAK30-23)  
