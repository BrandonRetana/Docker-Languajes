FROM python:latest

WORKDIR /home/code

EXPOSE 8080

COPY requirements.txt ./

RUN pip install --no-cache-dir -r requirements.txt

COPY . .

CMD [ "python", "./your-daemon-or-script.py" ]