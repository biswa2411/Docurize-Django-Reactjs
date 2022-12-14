FROM node:lts

WORKDIR /usr/src/app

ENV HOST=0.0.0.0
ENV PORT=8002

RUN npm install -g react-scripts
RUN chown -Rh node:node /usr/src/app

USER node
EXPOSE 8002

CMD [ "sh", "-c", "npm install && npm run dev" ]
