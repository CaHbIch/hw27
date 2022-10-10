# Создание fixture и загрузка данных

Зайти в папку "ads/datasets" (там лежат файлы csv с данными)
Выполнить 'python3 load_csv_to_json.py' (получает данные из файлов csv, преобразует в json и помещает в папку с приборами)
Вернитесь в папку проекта и выполните «python3 manage.py loaddata ads.json».
Выполнить «python3 manage.py loaddata Categories.json»

# Доступные маршруты и методы

/ad/ - GET, POST
/ad/ - GET
/cat/ - GET, POST
/cat// - GET