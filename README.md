## Описание
Данное ПО предназначено для ускорения проверки датасета от выбросов и ошибок. В программу загружается файл .csv с разметкой и id уникального ТС, вносимые правки применятся сразу ко всем кадрам с общим id.
## Установка
1. Клонируйте репозиторий:
    ```bash
    git clone https://github.com/Grenka054/Car-Brand-Model-Labeler.git
    cd Car-Brand-Model-Labeler
    ```

2. Создайте виртуальное окружение:
    ```bash
    python -m venv venv
    .venv\Scripts\activate # source venv/bin/activate  На Linux
    ```
Но удобнее всего это делать в VS Code с помощью расширения Python Environment Manager. Откройте репозиторий как папку.
3. Установите зависимости:
    ```bash
    pip install -r requirements.txt
    ```
## Использование

Для запуска используйте
```bash
python csv_editor.py
```
Горячие клавиши и другую информацию можно найти в разделе помощи.
