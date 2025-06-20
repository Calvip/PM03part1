<<<<<<< HEAD
<<<<<<< HEAD
=======

>>>>>>> d3780b3e4976f6680c93dc3de8ba0761ee1e533c
# PM03part1
=======
# Запуск
Для запуска нужно ввести последовательность команд
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
flask db upgrade
flask run --debug
```

## Обновление базы данных
```bash
flask db init
flask db migrate -m "Add table"
flask db upgrade
```
<<<<<<< HEAD
>>>>>>> b0cbca8 (first commit)
=======
>>>>>>> d3780b3e4976f6680c93dc3de8ba0761ee1e533c
