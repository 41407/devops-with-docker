FROM ubuntu:18.04
COPY curler.sh .
RUN chmod +x curler.sh
CMD apt update && apt -y upgrade; apt -y install curl; ./curler.sh
