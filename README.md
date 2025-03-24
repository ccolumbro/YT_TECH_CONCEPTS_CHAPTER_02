#BIT&CUBIT Tours - API Asíncrona

##Cómo probarlo

1. Instalar dependencias:
```bash
pip install -r requirements.txt
```

2. Ejecutar el servidor:
```bash
uvicorn app.main:app --reload
```

3. Ir a:
[http://localhost:8000/docs](http://localhost:8000/docs)

4. Probar el endpoint:
GET `/api/v1/destinos/info?lugar=tokyo`

##¿Qué tecnologías usa?

- FastAPI: framework web moderno, asíncrono por diseño
- httpx: cliente HTTP async para consumir APIs externas
- asyncio: simulación de operaciones internas con latencia

Ideal para explicar cómo el asincronismo permite manejar múltiples tareas concurrentes sin bloquear el servidor.