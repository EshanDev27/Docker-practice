FROM python

WORKDIR /mysqldir

COPY . .

RUN pip install pymysql
RUN pip install cryptography

CMD [ "python", "test.py" ]