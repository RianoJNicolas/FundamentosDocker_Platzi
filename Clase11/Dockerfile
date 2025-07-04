FROM python:3.12.-alpine3.17

WORKDIR /app

COPY requirments.txt requirments.txt

RUN pip install -r requirments.txt

COPY . .

CMD ["python", "-m", "flask", "run", "-host-0.0.0.0"]
