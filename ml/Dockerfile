FROM ubuntu:latest
RUN apt update -y
RUN apt install -y python3-pip
RUN apt install -y python3-dev
RUN pip3 install numpy
RUN pip3 install pandas 
RUN pip3 install scikit-learn 
RUN pip3 install opencv-python 
RUN pip3 install matplotlib 

CMD python3 /code/train.py
