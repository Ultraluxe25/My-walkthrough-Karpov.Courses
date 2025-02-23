FROM ubuntu:22.04

WORKDIR /app

COPY script.sh script.sh

RUN apt-get update && apt-get install -y \
    vim \
    wget \
    curl \
    git
    
RUN touch hello.sh && echo "echo 'Hello from container'" > hello.sh

# Default powerline10k theme, no plugins installed
RUN sh -c "$(wget -O- https://github.com/deluan/zsh-in-docker/releases/download/v1.2.1/zsh-in-docker.sh)"

ENTRYPOINT ["zsh"]