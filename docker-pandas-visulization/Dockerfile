FROM python:3.7.3-slim


LABEL maintainer="Ibrahim Abu ALhaol"
LABEL version="0.1"
LABEL description="Noteboook and data (.csv file) to provide a summary \
                  of the total medals won by participating countries \
                  in the 2008 Summer Olympics."

WORKDIR /data

COPY . /data
RUN pip install --upgrade pip
RUN pip install numpy pandas
RUN pip install seaborn 
RUN pip install jupyter
RUN pip install jupyterlab

EXPOSE 8888

CMD ["jupyter","lab","--ip=0.0.0.0", "--port=8888", "--no-browser", "--allow-root"]
