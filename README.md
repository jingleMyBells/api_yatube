
# Yatube

Сервис для блоггинга (поддержаны: посты, комментарии, ленты подписок, группы)
Update 09.09.2022: Теперь доступен API v.1!

## Техстэк

**Client:** HTML

**Server:** Python 3.7.13, Django 2.2.16, DRF 3.12.4


## Деплой

Для развертки и запуска необходимо

Инсталлировать зависимости:

```bash
  pip install -r requirements.txt
```
Инициировать миграции:
```bash
  cd yatube && python3 manage migrate
```
Запустить сервер локально:
```bash
  python3 manage runserver
```

## API Endpoints:
(пути описаны для локального деплоя)
- [auth](https://127.0.0.1/api/v1/api-token-auth/)
- [posts](https://127.0.0.1/api/v1/posts/)
- - [posts: 1](https://127.0.0.1/api/v1/posts/1/)
- [groups](https://127.0.0.1/api/v1/groups/)
- - [groups: 1](https://127.0.0.1/api/v1/gourps/1/)
- [post:1:comments](https://127.0.0.1/api/v1/posts/1/comments/)
- - [post:1:comments:1](https://127.0.0.1/api/v1/posts/1/comments/1/ )

## Authors

- [@jinglemybells](https://www.github.com/jinglemybells)

