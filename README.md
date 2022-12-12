## Команды:

1. Запустить базу данных в docker
```
docker-compose up -d
```
2. Запустить приложение
```
python main.py
```

## Домашнее задание к лекции «Asyncio»
## Получение из API персонажей Start Wars и загрузка в базу данных

### Реализовано:
- в таблицу выгружаются следующие поля:
'id', 'name', 'gender', 'height', 'mass', 'birth_year', 'skin_color', 'eye_color', 'hair_color', 'homeworld',
'films', 'species', 'starships', 'vehicles';

- поля 'films', 'species', 'starships', 'vehicles' переводятся в строковый формат (если непустые);
- асинхронность кода;