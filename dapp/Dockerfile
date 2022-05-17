FROM node:6.17.0

WORKDIR /usr/src

RUN git clone https://github.com/softwarearchaeologist/Multisig.git ./

WORKDIR /usr/src/dapp

RUN npm install node-gyp \
&& npm install -g grunt-cli@1.3.0 \
&& npm install

EXPOSE 8080

CMD ["grunt"]

