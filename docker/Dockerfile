FROM public.ecr.aws/docker/library/python:latest
#FROM python
WORKDIR /app
COPY ./app/requirement.txt /app/
RUN pip install -r requirement.txt
COPY ./* /app/
CMD [ "python3", "/app/main.py" ]
#CMD [ "/bin/bash" ]