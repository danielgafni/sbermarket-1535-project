# Пример кода

В Jupyter-ноутбуке [Tips.ipynb](Tips.ipynb) находится пример работы с данными и описание некоторых полезных функций. Чтобы запустить этот ноутбук у себя на компьютере, нужно будет сделать следующие шаги:

# Установка окружения

Установите python с версией как минимум 3.7. Создайте при помощи [venv](https://docs.python.org/3/library/venv.html) виртуальное окружение, активируйте его и установите туда необходимые библиотеки при помощи `pip install -r requirements.txt`. Например, при помощи `venv` (рекомедуется использовать его ввиду простоты):

```bash
python -m venv venv

source ./venv/bin/activate  # На Mac OS / Linux
\venv\Scripts\activate.bat  # На Windows

pip install -r requirements.txt
```

# Jupyter

[Jupyter](https://jupyter.org/) - очень удобная среда для анализа данных (а иногда помогает и при написании обычного питоновского кода). Он включен в `requirements.txt`, поэтому его не надо отдельно устанавливать (но это легко сделать при помощи `pip install jupyter`). Активируйте виртуальное окружение. Запустите Jupyter командой:

```bash
jupyter notebook
```

Он откроется в браузере, где вы сможете выбрать [Tips.ipynb](Tips.ipynb) и позапускать в нем код. Не забудьте положить в папку проекта файл с данными!

Кстати, существует [Google Colab](https://colab.research.google.com/), который за вас запускает Jupyter на сервере Google, а вам остается только пользоваться им. Прямо как с гугл документами. Удобно!