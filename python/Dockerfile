FROM python:3
#COPY ./requirements.txt ./
WORKDIR /usr/src/app
#RUN pip install --no-cache-dir -r requirements.txt

#COPY ../../test-ecr/test.py .
COPY . .

CMD [ "python", "./test.py" ]
