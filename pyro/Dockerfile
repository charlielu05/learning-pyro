FROM python:3.8-slim-buster
RUN pip install torch==1.5.0+cpu torchvision==0.6.0+cpu -f https://download.pytorch.org/whl/torch_stable.html
RUN pip3 install pyro-ppl 
RUN pip3 install jupyter
RUN pip3 install pandas
RUN pip3 install matplotlib
WORKDIR "/home/jovyan"
CMD ["jupyter", "notebook", "--port=8888", "--no-browser", "--ip=0.0.0.0", "--allow-root"]
