# Применение ансамблевых методов для распознавания эмоций по речи

**Курсовая работа**  
Дисциплина: «Машинное обучение и анализ данных»  
Студент: Гумаров Рафаель  
Направление: Прикладная информатика (ИИ и анализ данных)

## Описание проекта

Данный проект посвящен решению задачи **Speech Emotion Recognition (SER)** — многоклассовой классификации эмоций по аудиозаписи речи с использованием **ансамблевых методов** машинного обучения.

### Основные цели:
- Извлечение акустических признаков из аудиофайлов
- Сравнение базовых моделей ML
- Построение и анализ ансамблевых моделей (Voting, Bagging, Boosting, Stacking)
- Оптимизация моделей и оценка их эффективности

## Используемый датасет

**RAVDESS** (Ryerson Audio-Visual Database of Emotional Speech and Song)  
- Количество файлов: 1440 аудиозаписей
- Количество эмоций: 8 (neutral, calm, happy, sad, angry, fearful, disgust, surprised)
- Актёры: 24

**Ссылка на датасет:** [Zenodo - Audio_Speech_Actors_01-24](https://zenodo.org/records/1188976)

## Структура проекта

├── Audio_Speech_Actors_01-24/     # Папка с аудиофайлами (Git LFS)
├── SER_Emotion_Recognition.ipynb  # Основной Jupyter Notebook
├── requirements.txt
├── README.md
└── .gitattributes


## Установка и запуск

### 1. Клонирование репозитория
```bash
git clone https://github.com/yourusername/ser-ensembles.git
cd ser-ensembles
git lfs pull

##Установка зависимостей

pip install -r requirements.txt

