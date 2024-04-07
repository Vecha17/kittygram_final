#  Что такое Kittygram?

Kittygram - это приложение для размещения информации о своих котах, которой можно поделиться с другими

## Как запустить проект?

Чтобы запустить проект в терминале введите команду:
```
docker compose up
```

## Примеры использование api

```
https://kitty-practicum.hopto.org/api/cats
```

{
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "id": 1,
            "name": "Пузан",
            "color": "orange",
            "birth_year": 2020,
            "achievements": [
                {
                    "id": 1,
                    "achievement_name": "Съел деда"
                }
            ],
            "owner": 1,
            "age": 4,
            "image": "http://kitty-practicum.hopto.org/media/cats/images/temp.jpeg",
            "image_url": "/media/cats/images/temp.jpeg"
        }
    ]
}

```
https://kitty-practicum.hopto.org/api/cats/1
```

{
    "id": 1,
    "name": "Пузан",
    "color": "orange",
    "birth_year": 2020,
    "achievements": [
        {
            "id": 1,
            "achievement_name": "Съел деда"
        }
    ],
    "owner": 1,
    "age": 4,
    "image": "http://kitty-practicum.hopto.org/media/cats/images/temp.jpeg",
    "image_url": "/media/cats/images/temp.jpeg"
}

### Автор vechanka