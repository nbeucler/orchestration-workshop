FROM armhf/python
RUN pip install -U setuptools && pip install Flask
COPY rng.py /
CMD ["python", "rng.py"]
EXPOSE 80
