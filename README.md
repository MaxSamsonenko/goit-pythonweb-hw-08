# goit-pythonweb-hw-08

.venv\Scripts\Activate.ps1 - activate environment
uvicorn main:app --reload - start app from the main.py script with Uvicorn
fastapi dev main.py - start app with FastAPI in dev mode

Server started at http://127.0.0.1:8000
Documentation at http://127.0.0.1:8000/docs

# uvicorn main:app --host localhost --port 8000 --reload

Тут параметри команди мають наступне значення:

uvicorn — високопродуктивний вебсервер ASGI;
main — файл main.py;
app — об'єкт, повернений після запиту app = FastAPI();
-host — дозволяє прив'язати сокет до хоста. Значення за замовчуванням — 127.0.0.1;
-port — дозволяє прив'язати сокет до певного порту. За замовчуванням використовується значення 8000;
-reload — забезпечує гаряче перезавантаження сервера під час розробки.

http://127.0.0.1:8000/redoc
