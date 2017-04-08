FROM elviejokike/react-native-android

ARG NAME
ENV RN_APP ${NAME:-app}

RUN npm i -g yarn
RUN react-native init $RN_APP

RUN echo "Welcome to $RN_APP!"

VOLUME ["/"]
WORKDIR ["/"]
