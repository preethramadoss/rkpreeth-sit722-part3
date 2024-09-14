# Your Solution

FROM python:bullseye

WORKDIR /app/

COPY book_catalog/requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

COPY /book_catalog/ .

CMD ["fastapi", "uvicorn", "pydantic", "sqlalchemy", "psycopg2-binary", "requests"]