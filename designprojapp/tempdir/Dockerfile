FROM python
COPY  ./static /home/myapp/static/
COPY  ./templates /home/myapp/templates/
COPY  design_app.py /home/myapp/
EXPOSE 5050
RUN python3 -m pip install flask
CMD python3 /home/myapp/design_app.py
