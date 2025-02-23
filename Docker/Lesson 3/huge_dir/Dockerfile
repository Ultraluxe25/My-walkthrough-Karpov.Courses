# FROM ubuntu:22.04
# RUN apt-get update && apt-get install -y cowsay
# ENTRYPOINT ["/usr/games/cowsay"]
# CMD ["Hi there"]

# FROM ubuntu:22.04
# WORKDIR /home
# RUN mkdir -p /home/user/app
# COPY script.sh /home/user/app/script.sh
# CMD ["bash", "/home/user/app/script.sh"]

FROM ubuntu:22.04
COPY script.sh script.sh
ENTRYPOINT ["bash", "script.sh"]
CMD ["world"]
