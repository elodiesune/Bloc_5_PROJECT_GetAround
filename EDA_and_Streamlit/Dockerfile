FROM python:3.9

WORKDIR /home/app

COPY requirements.txt /dependencies/requirements.txt
RUN pip install -r /dependencies/requirements.txt

COPY . /home/app

CMD streamlit run --server.port $PORT app.py