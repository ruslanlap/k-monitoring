# K-Monitoring 📊

K-Monitoring є репозиторієм для тестування та експериментів з моніторингом. Використовуючи цей репозиторій, ви можете налаштувати та запустити різні механізми моніторингу для ваших додатків та систем.

## Огляд 👀

У цьому репозиторії ви знайдете стек інструментів для моніторингу:
* Prometheus 🗂️
* Open Telemetry 🌐
* Grafana 📈
* Loki 📜
* Fluent-bit 💬

## Встановлення та налаштування ⚙️

1. Склонуйте репозиторій до вашого локального середовища:

   ```bash
   git clone https://github.com/matvrus/k-monitoring.git
   cd k-monitoring
   ```

2. Найлегший спосіб запуску - використовуючи `docker-compose`.
   
   ```bash
   docker-compose up -d
   ```

3. Запустіть моніторинговий сервіс та сервіс сповіщень.

## Робота сервісів ⚙️

Кожен сервіс налаштований на окремому порті:
* Grafana: http://localhost:3002
* OpenTelemetry: http://localhost:4317
* Prometheus: http://localhost:9090

Перейдіть до сервісу Grafana та налаштуйте моніторинг до ваших потреб. Ви можете використовувати Loki для відстеження логів та Fluent-bit для обробки журналів.

🚀 Почніть експериментувати з моніторингом своїх додатків та систем за допомогою K-Monitoring!