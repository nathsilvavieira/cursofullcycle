
ARG NODE_VERSION = v21.1.0

FROM node:${NODE_VERSION}

ENV PORT=3001
ENV MESSAGE="Hello Nathalia"

RUN useradd -m mynode
USER mynode

WORKDIR /app

COPY . .

CMD [ "node", "index.js" ]