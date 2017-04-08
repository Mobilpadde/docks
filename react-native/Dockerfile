FROM elviejokike/react-native-android

ENV NAME=app

RUN npm i -g yarn

RUN react-native init APP
RUN rm -Rf APP

RUN mkdir /apps
WORKDIR /apps
CMD react-native init $NAME

VOLUME /apps
