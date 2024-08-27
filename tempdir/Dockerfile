FROM python
RUN pip install flask
COPY ./templates /home/myapp/templates/
COPY sample_app.py /home/myapp/
EXPOSE 5050
CMD python /home/myapp/sample_app.py
