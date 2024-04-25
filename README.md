# vk.com_parser
# Парсер участников сообществ VK

Этот скрипт на Python позволяет пользователям собирать участников указанных сообществ VK.com и сохранять данные в файл Excel.

## Возможности
- Получение токена доступа от VK API.
- Преобразование коротких имен сообществ в числовые ID групп.
- Сбор ID участников каждого сообщества.
- Сохранение собранных данных в файл Excel, где участники каждого сообщества размещены на отдельных листах.

## Использование
1. Установите необходимые пакеты Python:
   ---
   pip install requests openpyxl
   ---
2. Заполните данные вашего приложения VK (`APP_ID` и `CLIENT_SECRET`) в скрипте.
3. Добавьте короткие имена сообществ VK, которые вы хотите спарсить, в список `GROUP_SCREEN_NAMES`.
4. Запустите скрипт
5. Следуйте инструкциям в скрипте для авторизации и получения токена доступа.
6. Скрипт соберет участников и сохранит их в файл Excel под названием `all_communities_members.xlsx`.

## Настройка
Замените следующие переменные на ваши реальные данные в скрипте:
- `APP_ID`: ID вашего приложения VK.
- `CLIENT_SECRET`: Секретный ключ вашего приложения VK.
- `GROUP_SCREEN_NAMES`: Список коротких имен сообществ VK, которые вы хотите спарсить.

## Отказ от ответственности
Используйте этот скрипт ответственно и в соответствии с условиями использования сервиса VK. Не используйте его для спама или любых несанкционированных действий. Убедитесь, что у вас есть разрешение на сбор и использование данных из сообществ, которые вы анализируете.
