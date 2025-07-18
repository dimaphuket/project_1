# Анализ данных резюме — Проект 1

Этот проект представляет собой Jupyter Notebook для первичного анализа и очистки данных, собранных из резюме соискателей. Используется Python, библиотеки `pandas`, `plotly`, `numpy`, `matplotlib`.
Создано в рамках учебного проекта SkillFactory для демонстрации навыков первичного анализа и очистки данных.

## 📂 Содержимое

  - Project-1._Ноутбук-шаблон.ipynb` — основной Jupyter Notebook с анализом:
  - очистка данных (`dropna`, фильтрация по зарплате и возрасту),
  - визуализация распределений,
  - выявление выбросов по возрасту и опыту,
  - логарифмическое распределение признаков,
  - построение boxplot, scatter и тепловых карт,
  - сделаны основные выводы.

При запуске формируются копии составленных графиков в папке HTML. При их просмотре через GitHub вы можете посмотреть их в репозитории.
 
## 📊 Используемые библиотеки
pandas — для работы с табличными данными

numpy — для математических операций

plotly.express — интерактивные графики

matplotlib — статичная визуализация

## ⚙️ Установка

1. Клонируйте репозиторий: `git clone https://github.com/your-username/your-repo-name.git`
`cd your-repo-name`

3. Скачайте файл с данными на основе которых проводился анализ по ссылке https://drive.google.com/file/d/1Kb78mAWYKcYlellTGhIjPI-bCcKbGuTn/view?usp=sharing и поместите его в папку data

4. Установите необходимые библиотеки
`pip install pandas numpy matplotlib plotly`

## 📌 Заметки
Ноутбук можно использовать как шаблон для новых проектов.

Расчёты адаптированы под реальные резюме из CSV.
