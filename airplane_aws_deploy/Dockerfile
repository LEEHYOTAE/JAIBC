FROM python:3.10

EXPOSE 8501

WORKDIR /airhyo
ADD . /airhyo

RUN pip install -r requirements.txt

COPY app_play.py *.so /airhyo

CMD streamlit run app_play.py