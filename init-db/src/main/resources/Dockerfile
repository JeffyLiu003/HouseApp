FROM swr.ap-southeast-1.myhuaweicloud.com/paas-poc/mysqlutf8:0.2
COPY ./init-db/target/sql /sql
COPY ./init-db/target/entrypoint.sh /
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["./entrypoint.sh"]
CMD ["--help"]
