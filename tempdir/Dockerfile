FROM python
RUN pip install flask
COPY  ./static /home/myapp/static/
COPY  ./static /home/myapp/static/
COPY  ./templates /home/myapp/templates/
COPY  jonathan_website.py /home/myapp/
EXPOSE 8888
CMD python3 /home/myapp/jonathan_website.py
