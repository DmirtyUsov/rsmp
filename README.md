# rsmp
Парсинг единого реестра субъектов малого и среднего предпринимательства
https://www.nalog.ru/opendata/7707329152-rsmp/

1. Разбираем (парсим) каждый XML файл в архиве
2. Документы, у которых 'КодРегион' равен '14', сохраняем в базу MongoDB
3. Из базы MongoDB формируем нужный срез данных (юридические лица, индивидуальные предрприниматели) и сохрнаяем в xls файл для работы в Excel
