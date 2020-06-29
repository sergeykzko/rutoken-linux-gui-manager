# Графическая утилита для работы с Рутокенами в Linux
Утилита предназначена для устройств семейства Рутокен ЭЦП. 
Её возможности:
1. Просмотр информации о Рутокене
2. Просмотр объектов, хранящихся на токене или смарт-карте
3. Генерация и удаление ключевых пар, импорт ключей и сертификатов в формате PKCS#12
4. Создание заявок на сертификат в формате PKCS#10
5. Форматирование устройств
6. Смена PIN-кодов Администратора и Пользователя
7. Разблокирование PIN-кода Пользователя

# Загрузка и запуск
git clone https://github.com/AktivCo/rutoken-linux-gui-manager --recursive

Утилита автоматически проверит наличие необходимых пакетов для работы, и при необходимости попросит их установить. **Установка требует наличия прав супер пользователя**, поэтому утилита спросит пароль администратора во время установки обновлений.

**Для пользователей Astra Linux, создан специальный настройщик**, создающий ярлык для запуска приложения без терминала. Просто запустите *token-assistent.installer* и ярлык автоматически появится. 

В остальных операционных системах запуск можно производить двойным щелчком по утилите *token-assistent.run*.
