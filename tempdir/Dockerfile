FROM python
RUN pip install --progress-bar=off --root-user-action=ignore flask
COPY  ./static /home/myapp/static/
COPY  ./templates /home/myapp/templates/
COPY  sample_app.py /home/myapp/
EXPOSE 5050
CMD python3 /home/myapp/sample_app.py
