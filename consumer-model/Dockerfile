FROM python:3.9-bullseye
COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

ENTRYPOINT [ "python", "-u", "consumer.py" ]

# docker run --rm --name model -v ${PWD}/testdir:/testdir model