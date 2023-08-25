Разработка интеллектуального консультанта для работников СПб ГКУ «МФЦ»
==============================

## Описание:
Участникам хакатона при помощи методов искусственного интеллекта и анализа больших данных, включающих базу данных описания услуг, перечня вопросов и ответов работников МФЦ, необходимо разработать расширение для LMS Joomla, совместимое с версией 3.0. В приложении должен быть предусмотрен интерфейс для ввода запроса пользователем, на которые генерируется ответ согласно сведениям, полученным из базы знаний и перечня вопросов и ответов.
### 🍀 Кейсодержатель:
Санкт-Петербургское государственное казенное учреждение «Многофункциональный центр предоставления государственных и муниципальных услуг». 
Организация предоставления государственных и муниципальных услуг по принципу «одного окна» в соответствии с соглашениями о взаимодействии с федеральными органами исполнительной власти, органами государственных внебюджетных фондов, исполнительными органами государственной власти Санкт-Петербурга, органами местного самоуправления.
### 🍀 Проблематика:
Повышение качества предоставления государственных услуг является одной из приоритетных
задач СПб ГКУ «МФЦ». На качество предоставление услуг влияют следующие факторы:
- Увеличение количества предоставляемых услуг в МФЦ;
- Отсутствие специализации работников МФЦ, осуществляющих приём документов;
- Высокая загруженность ведущих специалистов, осуществляющих консультирование
работников,
- Частое изменение законодательства и необходимость ориентироваться в большом
количестве информации в базе знаний.
### 🍀 Решение:
Внедрение чат-бота с искусственным интеллектом позволит повысить скорость и качество поиска информации в базе знаний. Работники смогут оперативно получать необходимую консультацию, а ведущие специалисты смогут сконцентрироваться на проверке принятых обращений, что позитивно скажется на скорости и качестве предоставления государственных услуг.




Installation:
------------
    pip install -r requirements.txt
------------


Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

