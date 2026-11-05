![Vue Logo](https://st.timeweb.com/cloud-static/apps-logo/vue.svg)

# Vue на Deno

Пример приложения [Vue](https://vuejs.org/) на [Deno](https://deno.com/), которое можно развернуть в **Timeweb Cloud Apps**.

:tada: [Демо]

:rocket: [Создать свой Apps](https://timeweb.cloud/my/apps/create)

:books: [Документация Timeweb Cloud Apps](https://timeweb.cloud/docs/apps)

## Параметры деплоя

Выберите рантайм **Deno**, фреймворк **Vue** и тип приложения **frontend**. Для frontend будет опубликована статическая сборка.

| Параметр | Значение |
| --- | --- |
| Фреймворк | Vue |
| Версия Deno | 2.7.14 |
| Тип приложения | `frontend` |
| Команда сборки | `deno task build` |
| Директория сборки | `dist` |

## <a name="dev"></a>Локальный запуск проекта

```bash
# установка зависимостей
deno install --allow-scripts

# сборка для продакшн
deno task build
```
