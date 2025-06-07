# Проект: Бинарная классификация для предиктивного обслуживания оборудования

## Описание проекта

Цель проекта — разработать модель машинного обучения, которая предсказывает, произойдет ли отказ оборудования (Target = 1) или нет (Target = 0).  
Проект реализован в виде многостраничного Streamlit-приложения.

---

## Используемый датасет

**AI4I 2020 Predictive Maintenance Dataset**  
Источник: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/601/predictive+maintenance+dataset)

Включает 10 000 записей, каждая из которых описывает работу оборудования с различными характеристиками и содержит бинарную метку "отказ".

---

## Установка и запуск

1. Клонируйте репозиторий:
```bash
git clone https://github.com/VolkovKiA/predictive_maintenance_project_demo.git
cd predictive_maintenance_project

2. Создайте и активируйте виртуальное окружение:
```bash
python -m venv venv
venv\Scripts\activate

3. Установите зависимости:
pip install -r requirements.txt

4. Запустите приложение:
streamlit run app.py

## Описание структуры проекта
predictive_maintenance_project/
├── app.py # Основной файл приложения Streamlit
├── analysis_and_model.py # Основная логика анализа и предсказаний
├── presentation.py # Презентация на слайдах
├── requirements.txt # Файл зависимостей
├── README.md # Документация проекта
├── data/ # Папка для CSV-файла
│ └── predictive_maintenance.csv
└── video/ # Папка с видео-демонстрацией
└── demo.mp4

5.  Видео-демо: ссылка или встроенное видео
https://disk.yandex.ru/d/E6AzNB8R-GJ9Aw# -
Проект: Бинарная классификация для предиктивного обслуживания оборудования
