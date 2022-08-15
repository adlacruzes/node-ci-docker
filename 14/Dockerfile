FROM node:14.20.0-alpine3.16

RUN apk --update add --no-cache curl git openssh-client vim \
    && npm -g install npm@8 \
    && echo "alias ll='ls -la'" >> "$HOME/.profile" \
    && echo "export PS1='🐳 \[\033[1;36m\]\h \[\033[1;34m\]\w\[\033[0;35m\] \[\033[1;36m\]# \[\033[0m\]'" >> "$HOME/.profile"
