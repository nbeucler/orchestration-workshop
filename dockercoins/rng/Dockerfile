FROM armhf/python
RUN pip install --upgrade pip && pip install setuptools && pip install Flask
COPY rng.py /
CMD ["python", "rng.py"]
EXPOSE 80
