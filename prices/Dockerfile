FROM python
WORKDIR app
COPY requirements.txt .
RUN pip install -r requirements.txt
COPy . .
EXPOSE 80
CMD ["python", "app.py"]