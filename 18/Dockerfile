FROM node:18.6.0-alpine3.16

RUN apk --update add --no-cache curl git openssh-client vim \
     && echo "alias ll='ls -l'" >> "$HOME/.profile" \
     && echo "export PS1='🐳 \[\033[1;36m\]\h \[\033[1;34m\]\w\[\033[0;35m\] \[\033[1;36m\]# \[\033[0m\]'" >> "$HOME/.profile"
