Задание 0

<img width="658" height="138" alt="Screenshot from 2026-03-03 11-22-22" src="https://github.com/user-attachments/assets/e28d7c97-7bbf-4568-9c9a-22804a3ebb7b" />


<img width="453" height="45" alt="Screenshot from 2026-03-03 11-44-44" src="https://github.com/user-attachments/assets/e6a9b471-ea83-45cd-b041-cd2d2582346a" />


Задание 1 FastAPI приложение с MySQL

1. Создание Dockerfile.python Single stage:
   
<img width="673" height="235" alt="Screenshot from 2026-03-04 15-41-13" src="https://github.com/user-attachments/assets/635fdddd-651a-4320-8fd9-709b8123a9b3" />

Создаем Dockerfile.python с базовым образом python:3.12-slim и конструкцией COPY

2. Создание .dockerignore:

<img width="210" height="204" alt="Screenshot from 2026-03-04 15-37-58" src="https://github.com/user-attachments/assets/e8556482-73c8-4d6b-b30f-17f79755738f" />

Создание и наполнение.dockerignore для исключения лишних файлов

3. Сборка и тестирование образа single stage

<img width="1535" height="627" alt="Screenshot from 2026-03-04 15-44-58" src="https://github.com/user-attachments/assets/4dd8366d-24d2-480a-8b00-1f425223fe04" />

Сборка образа командой docker build -f Dockerfile.python -t homewk-app . Проверка работоспособности приложения через curl http://localhost:5000

4. Multistage сборка
   
<img width="664" height="508" alt="Screenshot from 2026-03-04 15-49-30" src="https://github.com/user-attachments/assets/db9a5d84-485a-4ffe-b4ec-9ece938cc5f7" />

Изменяем Dockerfile.python на multistage сборку

<img width="1548" height="531" alt="Screenshot from 2026-03-04 15-53-32" src="https://github.com/user-attachments/assets/b14c3111-2a6f-4ee4-baac-b535766f3b37" />

Собираем multistage образа homewk-multi

5. Запуск через docker compose

<img width="611" height="746" alt="Screenshot from 2026-03-04 17-11-45" src="https://github.com/user-attachments/assets/69089f60-12d6-4344-a6f1-a9626a3000c7" />

Файл compose.yaml для запуска MySQL и приложения


Задание 2

Задание 3

![photo_2026-03-05_13-42-59](https://github.com/user-attachments/assets/1071ce30-d526-493d-a53a-598ad5218d66)


<img width="710" height="834" alt="Screenshot from 2026-03-05 08-24-04" src="https://github.com/user-attachments/assets/570ed647-879e-4a72-9cbc-b07c2b376a09" />

Задание 4

![photo_2026-03-05_13-37-59](https://github.com/user-attachments/assets/292285b8-95f7-48f4-894e-249f9970a1eb)

![photo_2026-03-05_13-39-10](https://github.com/user-attachments/assets/f97f85f6-a048-4f0c-b060-818f07e7e7fc)

Скриншот sql запроса к БД приложения

https://github.com/Relekt71/shvirtd-example-python
