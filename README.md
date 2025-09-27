Лабораторная работа № 1: Nginx + Docker 👩‍💻 ФИО автора: Рыжкова Полина Андреевна Группа: 3МО-РБД

📌 Описание задания Создать веб-сервер в Docker с использованием Nginx и подключить HTML-страницу. Результат доступен по адресу http://localhost:8080.

⚙️ Как запустить проект Клонируйте репозиторий: git clone https://github.com/polinchik6/web_laba_1.git<--ссылка на репозиторий cd nginx-lab Запустите контейнеры:

docker-compose up -d --build Открыть в браузере: http://localhost:8080 📂 Содержимое проекта

docker-compose.yml — описание сервиса Nginx

code/index.html — главная HTML-страница

screenshots/ — все скриншоты

📸 Скриншоты работы

<img width="973" height="501" alt="Снимок экрана 2025-09-25 162222" src="https://github.com/user-attachments/assets/73663237-0b3b-451f-8405-23401b272590" />
<img width="955" height="251" alt="Снимок экрана 2025-09-25 162810" src="https://github.com/user-attachments/assets/b9f92db4-bc3e-4388-8ce5-8a56db7e5344" />
<img width="1036" height="332" alt="Снимок экрана 2025-09-25 163101" src="https://github.com/user-attachments/assets/8158b4a7-6ffd-44c7-bf76-990bb2f862bb" />
<img width="989" height="314" alt="Снимок экрана 2025-09-25 162933" src="https://github.com/user-attachments/assets/af982720-7caf-4a2d-b91e-23f9f1f1a926" />
<img width="636" height="259" alt="Снимок экрана 2025-09-25 163249" src="https://github.com/user-attachments/assets/4a9d0b3c-3b6f-4ea6-ab35-c1d2006773f1" />

✅ Результат Сервер в Docker успешно запущен, Nginx возвращает мою HTML-страницу.
