FROM python:3.10-slim

WORKDIR /app

COPY Dashboard_Amostras_Agua/requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

COPY Dashboard_Amostras_Agua/ .

EXPOSE 8501

CMD ["streamlit", "run", "app.py", "--server.address=0.0.0.0"]
