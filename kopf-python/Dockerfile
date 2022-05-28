FROM python:3.7
RUN pip install kopf pykube-ng==20.10.0
ADD operator.py /src/operator.py
CMD kopf run /src/operator.py --verbose
