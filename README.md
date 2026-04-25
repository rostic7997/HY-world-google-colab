# HY-world-google-colab

# Обновляем пакеты и устанавливаем Python 3.10
``
sudo apt-get update
``
``
sudo apt-get install python3.10 python3.10-venv python3.10-dev -y
``
# Клонируем репозиторий (если еще нет)
``
git clone https://huggingface.co/spaces/prithivMLmods/HY-World-2.0-Demo
cd HY-World-2.0-Demo
``
# Создаем виртуальное окружение именно на базе Python 3.10
``
python3.10 -m venv venv310
``

# Активируем его
``
source venv310/bin/activate
``
# Теперь ваш терминал работает на Python 3.10. Проверьте:
``
python -V
``
