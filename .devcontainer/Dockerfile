FROM node:12-stretch

RUN apt-get update

RUN apt-get install -y zsh

RUN npm install --global eslint prettier react-scripts typescript yarn

RUN wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | zsh || true

CMD ["zsh"]
