FROM zhangsheng377/stats_stock
ENTRYPOINT []

# RUN apt update && \
#     apt upgrade
WORKDIR /stats_stock
RUN git pull

CMD ["python3", "server.py"]
