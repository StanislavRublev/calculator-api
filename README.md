\# API Calculator



API-калькулятор на Python с использованием FastAPI.



\## Операции

\- сложение

\- вычитание

\- умножение

\- деление

\- возведение в степень



\## Локальный запуск

py -3.13 -m uvicorn main:app --reload



Swagger:

http://127.0.0.1:8000/docs



\## Docker

Сборка:

docker build -t calculator-api .



Запуск:

docker run --name calculator-container -p 8000:8000 calculator-api

