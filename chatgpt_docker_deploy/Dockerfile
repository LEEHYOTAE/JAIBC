FROM python:3.10

EXPOSE 8501

WORKDIR /chathyo
ADD . /chathyo

RUN pip install -r requirements.txt

COPY app.py *.so /chathyo

CMD streamlit run app.py