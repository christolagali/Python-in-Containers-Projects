From python
RUN mkdir -p /app
WORKDIR /app
COPY app.py .
COPY start-appy.sh .
RUN pip install Flask
CMD ["/bin/bash","start-appy.sh"]
